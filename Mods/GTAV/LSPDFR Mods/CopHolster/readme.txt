Cop Holster 3.2.0.0 ReadMe

------Requirements------
RAGEPluginHook 0.23 or higher.

------Installation------
Place CopHolster.dll and CopHolster.xml in your Plugins folder.
When ingame, open the RPH console (default F4) and type LoadPlugin CopHolster.dll.

--------Controls--------
Cop Holster will automatically kick-in when unholstering your pistol with a supported model.
Intimidation mode (hand on holster) can be toggled with the Right Shift Key (keyboard) or the Right DPad (controller).

----------FAQ-----------
Does this come with RDE support?
-> The RDE Cop Holster config file is in the RDE 3.1 download.

Does this come with EUP support?
-> Yes. Cop Holster comes with support for EUP 7.5.

The plugin crashed/I found a bug/I have a suggestion.
-> Post in the comment section of the download page. I'll reply as quick as possible.

How does Cop Holster work?
-> All ped models in GTA have what are called drawables. They are pieces of clothing or equipment that can vary between instances of that model.
   Many of the default cop models have two holster drawables. One is empty, and one has a pistol. Cop Holster simply changes between those
   two drawables depending on if you have your pistol drawn or not to give the illusion that you are taking the pistol out of the holster.

I'm a ped model developer and would like to make my model work with Cop Holster. How would I go about doing that?
-> First you need to make sure your ped has 2 holster models for the holster you'd like to make dynamic -- one that's empty and one that isn't.
   Then you need to figure out the component ID for the models. Based upon the model's prefix, you can easily figure that out using this table:
		0 - HEAD
		1 - BERD
		2 - HAIR
		3 - UPPR
		4 - LOWR
		5 - HAND
		6 - FEET
		7 - TEEF
		8 - ACCS
		9 - TASK
		10 - DECL
		11 - JBIB
	Now you need the drawable ID. This is the number you see in the model's name.
	So for example, if your model has the name task_002_u, your component ID would be 9 and your drawable ID would be 2.
	Now, fill in the information below and place it after the <Peds> tag in CopHolster.xml.
	
	<Item FuncHolster="true" FuncIntim="true">
		<Model>put your ped's name here</Model>
		<FuncIntimMeshes>
			<Item>
				<Component>put empty holster component ID</Component>
				<Drawable>put empty holster drawable ID</Drawable>
			</Item>
			<Item>
				<Component>put occupied holster component ID</Component>
				<Drawable>put occupied holster drawable ID</Drawable>
			</Item>				
		</FuncIntimMeshes>
		<Weapons>
			<Item WeaponSet="Pistols">
				<Component>put holster component ID</Component>
				<Holstered>put empty holster drawable ID</Holstered>
				<Unholstered>put occupied holster drawable ID</Unholstered>
			</Item>				
		</Weapons>
	</Item>

	And you're done!
	
	Cop Holster also comes with some more sophisticated features, like defining a dynamic holster for groups of weapons.
	You can define new weapon groups under the <WeaponSets> element.
	You can then choose what weapon group you'd like to make the holster dynamic for by changing the WeaponSet attribute.
	
--------Changelog-------
3.2.0.0
- Updated RPH dependency to 0.55 (minimum 0.23 required).
- Config file is now in XML format with support for weapon-specific drawable switching. Big thanks to @Yard1 for implementing this!
- Default intimidation mode keyboard toggle changed to Right Shift Key.
- Default intimidation mode gamepad toggle changed to DPad Right.
- Added support for EUP 7.5.