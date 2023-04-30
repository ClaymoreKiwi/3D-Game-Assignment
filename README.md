# 3D-Game-Assignment
3D Game Development and Game assets Pipeline module repo - versions and updates

Note: Resize this window until a single line seperates key information for the best visual representation
----------------------------------------------------------------------------------------------------------------------------------------
# HOW TO PLAY

keyboard controls:
use WASD to move character
mouse movement to rotate the player and aim
left click to shoot
right click to aim -> (NOTE: player is NOT supposed to move when they aim)

Controller Controls:
right trigger to shoot
left trigger to aim
left analogue to move
right analogue to aim

killing enemies grants 10 points each
Reach 200 points to complete the first level
Reach 600 points to complete the second level

Enemies do damage and push the player pack when they collide
Enemies drop some ammunition for the player to collect (they dissapear after a timer)
----------------------------------------------------------------------------------------------------------------------------------------
Folder Structure Key:
Indicates folder --> -Folder_Name
Indicates multiple Files of the same type--> **File_Name** x(n)
indication of external refernces --> (referances)
External Asset used in 1 or more levels --> !! 
folders/files on the same indentation inicate file hierarchy
----------------------------------------------------------------------------------------------------------------------------------------
# FOLDER STRUCTURE

Content Structure:
	-Collections
		**Empty**
	-Developers
		-tingl
			-Collections
				**Empty**
	-Enemies
		-Animations
			**Animation Files**
		-Mesh
			-Blueprints
				-Spawner
					-Materials
						**Material Files**
					-Textures
						**Texture Files**
					**SpawnerBP**
				**EnemyBP**
			-Textures
	-External_assets
		-Kobo_Nature (Studio Kobo - Environments - Epic Games Assets Store - Accessed 02/03/2023)
			-Blueprints
				**Crystal Blueprints**
			-Materials
				-M-Instances
					-MI-Grass
						**GrassMaterials**
					-MI-Leaves
						**LeafMaterials**
					-MI-Particles
						**ParticleMaterials**
					-MI-Plants
						**PlantsMaterials**
					-MI-Rocks
						**RocksMaterials**
					-MI-Trunk
						**TrunksMaterials**
					-MI-Water
						**WaterMaterials**
					**MI-Asstes**
				-M-LayerInfo
					**LandscapeMaterials**
				-M-Master
					**MasterMaterials**
				-M-PostProcess
					**PostProcessMaterials**
			-Meshes
				-SM-Bamboo !!
					**MeshAssets**
				-SM-Birch
					**MeshAssets**
				-SM-Grass  !!
					**MeshAssets**
				-SM-Palm  !!
					**MeshAssets**
				-SM-Particles
					**MeshAssets**
				-SM-Pine  !!
					**MeshAssets**
				-SM-Plants  !!
					**MeshAssets**
				-SM-Rocks  !!
					**MeshAssets**
				**MeshAssets**
			-ParticleEffects
				**Particles**
			-Textures
				-T-Albedo
					**TextureFiles**
				-T-Alpha
					**TextureFiles**
				-T-Normal
					**TextureFiles**
		-StarterContent
			-Architecture
				**MeshAssets**
			-Audio
				**AudioFiles**
			-Blueprints
				-Assets
					**BlueprintAssets**
				**BlueprintAssets**
			-HDRI
				**HDRIAsset**
			-Maps
				**UnrealLevelAssets**
			-Materials
				**MaterialAssets**
			-Particles
				-Materials
					**MaterialAssets**
				**ParticleAsset**
			-Props
				-Materials
					**MaterialAssets**
				**MeshAsset**
			-Shapes
				**PrimitiveMeshAssets**
			-Textures
				**TextureAssets**
	-Levels
		-Blueprints
			**BlueprintsAssets** x3
		-Level1_Beach_Sharedassets
			**LayerInfo** x2
		**UnrealLevelAssets** x4
	-Main_Menu_Assets
		-Blueprints
			**BlueprintsAssets** x3
		-Fonts
			**FontsAssets** x2
		-Images
			**Images** x8
		-Sounds
			**SoundFiles**x2
		**UnrealLevelAssets** x1
	-Materials
		-Materials_BP
			**LandscapeAssets** x1
		-Skydome
			**MaterialAsset** x3
		-Textures
			**TextureAssets** x4
	-Player
		-Animations
			**AnimAssets** x28
		-HUD_Items
			**Images** x3
		-Mesh
			-Blueprints
				**BlueprintAssets** x4
			-Mesh_text
				**TextureAssets** x18
		-Sound
			**AudioAssets** x2
	-Props
		-Chair
			**MayaAssets** x15
		-Dock
			**MayaAssets** x5
		-Umbrella
			**MayaAssets** x4
		-Weapons
			-Blueprints
				**BlueprintAsset** x1
			-Mesh
				-KA_Val (FPS Weapon Bundle - Epic Games Asset pack - Deadghost Interactive - Weapons - Accessed 04/03/23)
					**WeaponAsset** x12
			-SFX
				**AudioAssets** x8
	Sounds_and_Music
		-SFX
			**AudioAssets** x2
		**AudioAssets** x5