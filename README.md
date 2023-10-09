---- Minecraft Crash Report ----
// Hey, that tickles! Hehehe!

Time: 2023-10-09 20:35:41
Description: Unexpected error

java.lang.NullPointerException: Cannot invoke "net.minecraft.client.player.LocalPlayer.m_6117_()" because "this.f_91074_" is null
	at net.minecraft.client.Minecraft.m_91279_(Minecraft.java:1957) ~[client-1.20.1-20230612.114412-srg.jar%23344!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91398_(Minecraft.java:1795) ~[client-1.20.1-20230612.114412-srg.jar%23344!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91383_(Minecraft.java:1112) ~[client-1.20.1-20230612.114412-srg.jar%23344!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:718) ~[client-1.20.1-20230612.114412-srg.jar%23344!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:218) ~[forge-47.2.0.jar:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:smoothboot.mixins.json:client.MainMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.2.0.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.2.0.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$makeService$0(CommonClientLaunchHandler.java:25) ~[fmlloader-1.20.1-47.2.0.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Render thread
Stacktrace:
	at net.minecraft.client.Minecraft.m_91279_(Minecraft.java:1957) ~[client-1.20.1-20230612.114412-srg.jar%23344!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
-- Last reload --
Details:
	Reload number: 1
	Reload reason: initial
	Finished: No
	Packs: vanilla, mod_resources, file/FreshAnimations_v1.8.1.zip, cullleaves:smartleaves
Stacktrace:
	at net.minecraft.client.ResourceLoadStateTracker.m_168562_(ResourceLoadStateTracker.java:49) ~[client-1.20.1-20230612.114412-srg.jar%23344!/:?] {re:classloading}
	at net.minecraft.client.Minecraft.m_91354_(Minecraft.java:2326) ~[client-1.20.1-20230612.114412-srg.jar%23344!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:740) ~[client-1.20.1-20230612.114412-srg.jar%23344!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:218) ~[forge-47.2.0.jar:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:smoothboot.mixins.json:client.MainMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.2.0.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.2.0.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$makeService$0(CommonClientLaunchHandler.java:25) ~[fmlloader-1.20.1-47.2.0.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}


-- System Details --
Details:
	Minecraft Version: 1.20.1
	Minecraft Version ID: 1.20.1
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 17.0.8, Microsoft
	Java VM Version: OpenJDK 64-Bit Server VM (mixed mode), Microsoft
	Memory: 146777312 bytes (139 MiB) / 830472192 bytes (792 MiB) up to 8959033344 bytes (8544 MiB)
	CPUs: 2
	Processor Vendor: GenuineIntel
	Processor Name: Intel(R) Core(TM) i5-2400 CPU @ 3.10GHz
	Identifier: Intel64 Family 6 Model 42 Stepping 7
	Microarchitecture: Sandy Bridge (Client)
	Frequency (GHz): 3.09
	Number of physical packages: 1
	Number of physical CPUs: 4
	Number of logical CPUs: 4
	Graphics card #0 name: NVIDIA GeForce GTX 1650
	Graphics card #0 vendor: NVIDIA (0x10de)
	Graphics card #0 VRAM (MB): 4095.00
	Graphics card #0 deviceId: 0x1f82
	Graphics card #0 versionInfo: DriverVersion=31.0.15.3699
	Memory slot #0 capacity (MB): 4096.00
	Memory slot #0 clockSpeed (GHz): 1.07
	Memory slot #0 type: DDR3
	Memory slot #1 capacity (MB): 4096.00
	Memory slot #1 clockSpeed (GHz): 1.07
	Memory slot #1 type: DDR3
	Virtual memory max (MB): 22472.70
	Virtual memory used (MB): 11293.55
	Swap memory total (MB): 14322.25
	Swap memory used (MB): 822.44
	JVM Flags: 4 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xss1M -Xmx8544m -Xms256m
	Loaded Shaderpack: ComplementaryReimagined_r5.0.1.zip
		Profile: Custom (+19 options changed by user)
	Launched Version: forge-47.2.0
	Backend library: LWJGL version 3.3.1 build 7
	Backend API: NVIDIA GeForce GTX 1650/PCIe/SSE2 GL version 4.6.0 NVIDIA 536.99, NVIDIA Corporation
	Window size: 1024x768
	GL Caps: Using framebuffer using OpenGL 3.2
	GL debug messages: 
	Using VBOs: Yes
	Is Modded: Definitely; Client brand changed to 'forge'
	Type: Client (map_client.txt)
	Graphics mode: fast
	Resource Packs: vanilla, mod_resources, file/FreshAnimations_v1.8.1.zip (incompatible), cullleaves:smartleaves
	Current Language: en_us
	CPU: 4x Intel(R) Core(TM) i5-2400 CPU @ 3.10GHz
	ModLauncher: 10.0.9+10.0.9+main.dcd20f30
	ModLauncher launch target: forgeclient
	ModLauncher naming: srg
	ModLauncher services: 
		mixin-0.8.5.jar mixin PLUGINSERVICE 
		eventbus-6.0.5.jar eventbus PLUGINSERVICE 
		fmlloader-1.20.1-47.2.0.jar slf4jfixer PLUGINSERVICE 
		fmlloader-1.20.1-47.2.0.jar object_holder_definalize PLUGINSERVICE 
		fmlloader-1.20.1-47.2.0.jar runtime_enum_extender PLUGINSERVICE 
		fmlloader-1.20.1-47.2.0.jar capability_token_subclass PLUGINSERVICE 
		accesstransformers-8.0.4.jar accesstransformer PLUGINSERVICE 
		fmlloader-1.20.1-47.2.0.jar runtimedistcleaner PLUGINSERVICE 
		modlauncher-10.0.9.jar mixin TRANSFORMATIONSERVICE 
		modlauncher-10.0.9.jar fml TRANSFORMATIONSERVICE 
	FML Language Providers: 
		minecraft@1.0
		lowcodefml@null
		javafml@null
	Mod List: 
		dynamiclightsreforged-1.20.1_v1.6.0.jar           |Rubidium Dynamic Lights       |dynamiclightsreforged         |1.20.1_v1.6.0       |COMMON_SET|Manifest: NOSIGNATURE
		YungsBetterDungeons-1.20-Forge-4.0.3.jar          |YUNG's Better Dungeons        |betterdungeons                |1.20-Forge-4.0.3    |COMMON_SET|Manifest: NOSIGNATURE
		netherportalfix-forge-1.20-13.0.0.jar             |NetherPortalFix               |netherportalfix               |13.0.0              |COMMON_SET|Manifest: NOSIGNATURE
		YungsBetterOceanMonuments-1.20-Forge-3.0.3.jar    |YUNG's Better Ocean Monuments |betteroceanmonuments          |1.20-Forge-3.0.3    |COMMON_SET|Manifest: NOSIGNATURE
		connectivity-1.20.1-4.6.jar                       |Connectivity Mod              |connectivity                  |1.20.1-4.6          |COMMON_SET|Manifest: NOSIGNATURE
		sophisticatedcore-1.20.1-0.5.89.425.jar           |Sophisticated Core            |sophisticatedcore             |0.5.89.425          |COMMON_SET|Manifest: NOSIGNATURE
		rubidium-mc1.20.1-0.7.1.jar                       |Rubidium                      |rubidium                      |0.7.1               |COMMON_SET|Manifest: NOSIGNATURE
		gpumemleakfix-1.20.1-1.6.jar                      |Gpu memory leak fix           |gpumemleakfix                 |1.20.1-1.6          |COMMON_SET|Manifest: NOSIGNATURE
		Controlling-forge-1.20.1-12.0.2.jar               |Controlling                   |controlling                   |12.0.2              |COMMON_SET|Manifest: NOSIGNATURE
		Prism-1.20.1-forge-1.0.5.jar                      |Prism                         |prism                         |1.0.5               |COMMON_SET|Manifest: NOSIGNATURE
		Placebo-1.20.1-8.3.7.jar                          |Placebo                       |placebo                       |8.3.7               |COMMON_SET|Manifest: NOSIGNATURE
		modernfix-forge-5.7.5+mc1.20.1.jar                |ModernFix                     |modernfix                     |5.7.5+mc1.20.1      |COMMON_SET|Manifest: NOSIGNATURE
		YungsApi-1.20-Forge-4.0.2.jar                     |YUNG's API                    |yungsapi                      |1.20-Forge-4.0.2    |COMMON_SET|Manifest: NOSIGNATURE
		mixinextras-forge-0.2.0-beta.9.jar                |MixinExtras                   |mixinextras                   |0.2.0-beta.9        |COMMON_SET|Manifest: NOSIGNATURE
		Bookshelf-Forge-1.20.1-20.0.5.jar                 |Bookshelf                     |bookshelf                     |20.0.5              |COMMON_SET|Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		anti-xray-1.3.1-Forge-1.20.1.jar                  |AntiXray                      |antixray                      |1.3.1               |COMMON_SET|Manifest: NOSIGNATURE
		sophisticatedbackpacks-1.20.1-3.18.59.909.jar     |Sophisticated Backpacks       |sophisticatedbackpacks        |3.18.59.909         |COMMON_SET|Manifest: NOSIGNATURE
		balm-forge-1.20.1-7.1.4.jar                       |Balm                          |balm                          |7.1.4               |COMMON_SET|Manifest: NOSIGNATURE
		FpsReducer2-forge-1.20-2.5.jar                    |FPS Reducer                   |fpsreducer                    |1.20-2.5            |COMMON_SET|Manifest: NOSIGNATURE
		JustEnoughResources-1.20.1-1.4.0.238.jar          |Just Enough Resources         |jeresources                   |1.4.0.238           |COMMON_SET|Manifest: NOSIGNATURE
		chat_heads-0.10.22-forge-1.20.jar                 |Chat Heads                    |chat_heads                    |0.10.22             |COMMON_SET|Manifest: NOSIGNATURE
		cloth-config-11.1.106-forge.jar                   |Cloth Config v10 API          |cloth_config                  |11.1.106            |COMMON_SET|Manifest: NOSIGNATURE
		soundphysics-forge-1.20.1-1.1.2.jar               |Sound Physics Remastered      |sound_physics_remastered      |1.20.1-1.1.2        |COMMON_SET|Manifest: NOSIGNATURE
		SpelunkersCharm-3.4.4-1.20.1.jar                  |Spelunker's Charm             |spelunkers_charm              |1.0.0               |COMMON_SET|Manifest: NOSIGNATURE
		konkrete_forge_1.6.1-2_MC_1.20.jar                |Konkrete                      |konkrete                      |1.6.1               |COMMON_SET|Manifest: NOSIGNATURE
		AdvancementPlaques-1.20.1-forge-1.4.10.jar        |Advancement Plaques           |advancementplaques            |1.4.10              |COMMON_SET|Manifest: NOSIGNATURE
		entity_model_features_forge_1.20-1.0.2.jar        |Entity Model Features         |entity_model_features         |1.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		entity_texture_features_forge_1.20-4.5.1.jar      |Entity Texture Features       |entity_texture_features       |4.5.1               |COMMON_SET|Manifest: NOSIGNATURE
		Amplified_Nether_1.20.2_v1.2.3.jar                |Amplified Nether              |amplifiednether               |1.2.3               |COMMON_SET|Manifest: NOSIGNATURE
		repurposed_structures-7.1.7+1.20.1-forge.jar      |Repurposed Structures         |repurposed_structures         |7.1.7+1.20.1-forge  |COMMON_SET|Manifest: NOSIGNATURE
		BetterCompatibilityChecker-forge-4.0.8+mc1.20.1.ja|Better Compatibility Checker  |bcc                           |4.0.8               |COMMON_SET|Manifest: NOSIGNATURE
		AmbientSounds_FORGE_v5.2.22_mc1.20.1.jar          |AmbientSounds                 |ambientsounds                 |5.2.22              |COMMON_SET|Manifest: NOSIGNATURE
		TextruesRubidiumOptions-1.0.4+mc1.20.1.jar        |TexTrue's Rubidium Options    |reeses_sodium_options         |1.0.4+mc1.20.1      |COMMON_SET|Manifest: NOSIGNATURE
		spark-1.10.53-forge.jar                           |spark                         |spark                         |1.10.53             |COMMON_SET|Manifest: NOSIGNATURE
		modelfix-1.14.jar                                 |Model Gap Fix                 |modelfix                      |1.14                |COMMON_SET|Manifest: NOSIGNATURE
		memorysettings-1.20.1-5.4.jar                     |memorysettings mod            |memorysettings                |1.20.1-5.4          |COMMON_SET|Manifest: NOSIGNATURE
		curios-forge-5.3.5+1.20.1.jar                     |Curios API                    |curios                        |5.3.5+1.20.1        |COMMON_SET|Manifest: NOSIGNATURE
		oculus-mc1.20.1-1.6.9.jar                         |Oculus                        |oculus                        |1.6.9               |COMMON_SET|Manifest: NOSIGNATURE
		cullleaves-forge-3.2.0.jar                        |CullLeaves                    |cullleaves                    |3.2.0               |COMMON_SET|Manifest: NOSIGNATURE
		Searchables-forge-1.20.1-1.0.2.jar                |Searchables                   |searchables                   |1.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		YungsExtras-1.20-Forge-4.0.3.jar                  |YUNG's Extras                 |yungsextras                   |1.20-Forge-4.0.3    |COMMON_SET|Manifest: NOSIGNATURE
		BetterThirdPerson-Forge-1.20-1.9.0.jar            |Better Third Person           |betterthirdperson             |1.9.0               |COMMON_SET|Manifest: NOSIGNATURE
		YungsBetterStrongholds-1.20-Forge-4.0.3.jar       |YUNG's Better Strongholds     |betterstrongholds             |1.20-Forge-4.0.3    |COMMON_SET|Manifest: NOSIGNATURE
		Chunk Pregenerator-1.20-4.2.3.jar                 |Chunk Pregenerator            |chunkpregen                   |1.20-4.2.3          |COMMON_SET|Manifest: NOSIGNATURE
		YungsMenuTweaks-1.20.1-Forge-1.0.jar              |YUNG's Menu Tweaks            |yungsmenutweaks               |1.20.1-Forge-1.0    |COMMON_SET|Manifest: NOSIGNATURE
		deeperdarker-forge-1.20.1-1.2.0.jar               |Deeper and Darker             |deeperdarker                  |1.2.0               |COMMON_SET|Manifest: NOSIGNATURE
		AI-Improvements-1.20-0.5.2.jar                    |AI-Improvements               |aiimprovements                |0.5.2               |COMMON_SET|Manifest: NOSIGNATURE
		cupboard-1.20.1-2.0.jar                           |Cupboard utilities            |cupboard                      |1.20.1-2.0          |COMMON_SET|Manifest: NOSIGNATURE
		flib-1.20.1-0.0.11.jar                            |flib                          |flib                          |0.0.11              |COMMON_SET|Manifest: 1f:47:ac:b1:61:82:96:b8:47:19:16:d2:61:81:11:60:3a:06:4b:61:31:56:7d:44:31:1e:0c:6f:22:5b:4c:ed
		rubidium-extra-0.5.2+mc1.20.1-build.104.jar       |Rubidium Extra                |rubidium_extra                |0.5.2+mc1.20.1-build|COMMON_SET|Manifest: NOSIGNATURE
		KryptonReforged-0.2.3.jar                         |Krypton Reforged              |krypton                       |0.2.3               |COMMON_SET|Manifest: NOSIGNATURE
		YungsBetterMineshafts-1.20-Forge-4.0.4.jar        |YUNG's Better Mineshafts      |bettermineshafts              |1.20-Forge-4.0.4    |COMMON_SET|Manifest: NOSIGNATURE
		shulkerboxtooltip-forge-4.0.4+1.20.1.jar          |ShulkerBoxTooltip             |shulkerboxtooltip             |4.0.4+1.20.1        |COMMON_SET|Manifest: NOSIGNATURE
		gamemenumodoption-mc1.20.1-2.2.1.jar              |Game Menu Mod Option          |gamemenumodoption             |2.2.1               |COMMON_SET|Manifest: NOSIGNATURE
		YungsBetterJungleTemples-1.20-Forge-2.0.4.jar     |YUNG's Better Jungle Temples  |betterjungletemples           |1.20-Forge-2.0.4    |COMMON_SET|Manifest: NOSIGNATURE
		BetterAdvancements-1.20.1-0.3.2.161.jar           |Better Advancements           |betteradvancements            |0.3.2.161           |COMMON_SET|Manifest: NOSIGNATURE
		DripSounds-1.19.4-0.3.2.jar                       |Drip Sounds                   |waterdripsound                |0.3.2               |COMMON_SET|Manifest: NOSIGNATURE
		elytraslot-forge-6.3.0+1.20.1.jar                 |Elytra Slot                   |elytraslot                    |6.3.0+1.20.1        |COMMON_SET|Manifest: NOSIGNATURE
		Fastload-Reforged-mc1.20.1-3.4.0.jar              |Fastload-Reforged             |fastload                      |3.4.0               |COMMON_SET|Manifest: NOSIGNATURE
		jei-1.20.1-forge-15.2.0.27.jar                    |Just Enough Items             |jei                           |15.2.0.27           |COMMON_SET|Manifest: NOSIGNATURE
		AttributeFix-Forge-1.20.1-21.0.2.jar              |AttributeFix                  |attributefix                  |21.0.2              |COMMON_SET|Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		caelus-forge-3.1.0+1.20.jar                       |Caelus API                    |caelus                        |3.1.0+1.20          |COMMON_SET|Manifest: NOSIGNATURE
		waystones-forge-1.20-14.0.2.jar                   |Waystones                     |waystones                     |14.0.2              |COMMON_SET|Manifest: NOSIGNATURE
		Fallingleaves-1.20.1-2.1.0.jar                    |Falling Leaves                |fallingleaves                 |2.1.0               |COMMON_SET|Manifest: NOSIGNATURE
		FastSuite-1.20.1-5.0.1.jar                        |Fast Suite                    |fastsuite                     |5.0.1               |COMMON_SET|Manifest: NOSIGNATURE
		Clumps-forge-1.20.1-12.0.0.3.jar                  |Clumps                        |clumps                        |12.0.0.3            |COMMON_SET|Manifest: NOSIGNATURE
		make_bubbles_pop-0.2.0-forge-mc1.19.4+.jar        |Make Bubbles Pop              |make_bubbles_pop              |0.2.0-forge         |COMMON_SET|Manifest: NOSIGNATURE
		midnightlib-forge-1.4.1.jar                       |MidnightLib                   |midnightlib                   |1.4.1               |COMMON_SET|Manifest: NOSIGNATURE
		starlight-1.1.2+forge.1cda73c.jar                 |Starlight                     |starlight                     |1.1.2+forge.1cda73c |COMMON_SET|Manifest: NOSIGNATURE
		YungsBetterDesertTemples-1.20-Forge-3.0.3.jar     |YUNG's Better Desert Temples  |betterdeserttemples           |1.20-Forge-3.0.3    |COMMON_SET|Manifest: NOSIGNATURE
		farsight-1.20.1-3.5.jar                           |Farsight mod                  |farsight_view                 |1.20.1-3.5          |COMMON_SET|Manifest: NOSIGNATURE
		catalogue-forge-1.20.1-1.8.0.jar                  |Catalogue                     |catalogue                     |1.8.0               |COMMON_SET|Manifest: 0d:78:5f:44:c0:47:0c:8c:e2:63:a3:04:43:d4:12:7d:b0:7c:35:37:dc:40:b1:c1:98:ec:51:eb:3b:3c:45:99
		memoryleakfix-forge-1.17+-1.1.2.jar               |Memory Leak Fix               |memoryleakfix                 |1.1.2               |COMMON_SET|Manifest: NOSIGNATURE
		rubidium_extras-1.20.1_v1.4.3.jar                 |Rubidium Extras               |rubidium_extras               |1.20.1_v1.4.3       |COMMON_SET|Manifest: NOSIGNATURE
		forge-1.20.1-47.2.0-universal.jar                 |Forge                         |forge                         |47.2.0              |COMMON_SET|Manifest: 84:ce:76:e8:45:35:e4:0e:63:86:df:47:59:80:0f:67:6c:c1:5f:6e:5f:4d:b3:54:47:1a:9f:7f:ed:5e:f2:90
		Log-Begone-Forge-1.20.1-1.0.8.jar                 |Log Begone                    |logbegone                     |1.0.8               |COMMON_SET|Manifest: NOSIGNATURE
		client-1.20.1-20230612.114412-srg.jar             |Minecraft                     |minecraft                     |1.20.1              |COMMON_SET|Manifest: a1:d4:5e:04:4f:d3:d6:e0:7b:37:97:cf:77:b0:de:ad:4a:47:ce:8c:96:49:5f:0a:cf:8c:ae:b2:6d:4b:8a:3f
		smoothchunk-1.20.1-3.3.jar                        |Smoothchunk mod               |smoothchunk                   |1.20.1-3.3          |COMMON_SET|Manifest: NOSIGNATURE
		EnchantmentDescriptions-Forge-1.20.1-17.0.8.jar   |EnchantmentDescriptions       |enchdesc                      |17.0.8              |COMMON_SET|Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		BetterControls-Forge-1.20+v1.3.0.jar              |Better Controls               |bettercontrols                |1.3.0               |COMMON_SET|Manifest: NOSIGNATURE
		Jade-1.20.1-forge-11.6.1.jar                      |Jade                          |jade                          |11.6.1              |COMMON_SET|Manifest: NOSIGNATURE
		CreativeCore_FORGE_v2.11.2_mc1.20.1.jar           |CreativeCore                  |creativecore                  |2.11.2              |COMMON_SET|Manifest: NOSIGNATURE
		smoothboot-mc1.20.1-0.0.3.jar                     |Smooth Boot (Reloaded)        |smoothboot                    |0.0.3               |COMMON_SET|Manifest: NOSIGNATURE
		Ksyxis-Forge1.17-1.1.jar                          |Ksyxis                        |ksyxis                        |1.1                 |COMMON_SET|Manifest: NOSIGNATURE
		betterfpsdist-1.20.1-3.9.jar                      |betterfpsdist mod             |betterfpsdist                 |1.20.1-3.9          |COMMON_SET|Manifest: NOSIGNATURE
		Iceberg-1.20.1-forge-1.1.15.jar                   |Iceberg                       |iceberg                       |1.1.15              |COMMON_SET|Manifest: NOSIGNATURE
		Nullscape_1.20.2_v1.2.3.jar                       |Nullscape                     |nullscape                     |1.2.3               |COMMON_SET|Manifest: NOSIGNATURE
		entityculling-forge-1.6.2-mc1.20.1.jar            |EntityCulling                 |entityculling                 |1.6.2               |COMMON_SET|Manifest: NOSIGNATURE
		canary-mc1.20.1-0.2.7.jar                         |Canary                        |canary                        |0.2.7               |COMMON_SET|Manifest: NOSIGNATURE
		invhud.forge.1.20.1-3.4.18.jar                    |Inventory HUD+(Forge edition) |inventoryhud                  |3.4.18              |COMMON_SET|Manifest: NOSIGNATURE
		BetterTridents-v8.0.1-1.20.1-Forge.jar            |Better Tridents               |bettertridents                |8.0.1               |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		appleskin-forge-mc1.20.1-2.5.1.jar                |AppleSkin                     |appleskin                     |2.5.1+mc1.20.1      |COMMON_SET|Manifest: NOSIGNATURE
		ferritecore-6.0.0-forge.jar                       |Ferrite Core                  |ferritecore                   |6.0.0               |COMMON_SET|Manifest: 41:ce:50:66:d1:a0:05:ce:a1:0e:02:85:9b:46:64:e0:bf:2e:cf:60:30:9a:fe:0c:27:e0:63:66:9a:84:ce:8a
		PuzzlesLib-v8.0.24-1.20.1-Forge.jar               |Puzzles Lib                   |puzzleslib                    |8.0.24              |COMMON_SET|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		justzoom_forge_1.0.2_MC_1.20.1.jar                |Just Zoom                     |justzoom                      |1.0.2               |COMMON_SET|Manifest: NOSIGNATURE
		Rrls-3.2.0-1.20.1-forge.jar                       |Remove Reloading Screen       |rrls                          |3.2.0-1.20.1-forge  |COMMON_SET|Manifest: NOSIGNATURE
		deeper-oceans-mc1.20-v1.0.1a.jar                  |Deeper Oceans                 |deeper_oceans                 |1.0.1a              |COMMON_SET|Manifest: NOSIGNATURE
	Crash Report UUID: 1aa95f05-c762-43af-910b-cbaa7c8a160a
	FML: 47.2
	Forge: net.minecraftforge:47.2.0
