[22:23:36.997] [Main Thread/INFO] [tML]: Starting tModLoader client 1.4.4.9+2023.11.3.3|2023.11|stable|Stable|de3f637ae9b4d6d70a4a0133ac97c6d5917b0fc1|5250083680267361047 built 02/01/2024 01:23
[22:23:37.008] [Main Thread/INFO] [tML]: Log date: 28/01/2024
[22:23:37.009] [Main Thread/INFO] [tML]: Running on Windows (v10.0.19045.0) X64 NetCore 6.0.14
[22:23:37.011] [Main Thread/INFO] [tML]: FrameworkDescription: .NET 6.0.14
[22:23:37.011] [Main Thread/INFO] [tML]: Executable: C:\Program Files (x86)\Steam\steamapps\common\tModLoader\tModLoader.dll
[22:23:37.011] [Main Thread/INFO] [tML]: Working Directory: C:\Program Files (x86)\Steam\steamapps\common\tModLoader
[22:23:37.832] [Main Thread/WARN] [tML]: tModLoader.RuntimeErrorSilentlyCaughtException
System.ArgumentException: An item with the same key has already been added. Key: client.log
   at System.Collections.Generic.Dictionary`2.TryInsert(TKey key, TValue value, InsertionBehavior behavior)
   at System.Collections.Generic.Dictionary`2.Add(TKey key, TValue value)
   at Ionic.Zip.ZipFile.InternalAddEntry(String name, ZipEntry entry)
   at Ionic.Zip.ZipFile._InternalAddEntry(ZipEntry ze)
   at Ionic.Zip.ZipFile.AddEntry(String entryName, Stream stream)
   at Terraria.ModLoader.Engine.LogArchiver.Archive() in tModLoader\Terraria\ModLoader\Engine\LogArchiver.cs:line 131
   at Terraria.ModLoader.Engine.LogArchiver.ArchiveLogs() in tModLoader\Terraria\ModLoader\Engine\LogArchiver.cs:line 34
   at Terraria.ModLoader.Logging.LogStartup(Boolean dedServ) in tModLoader\Terraria\ModLoader\Logging.cs:line 94
   at Terraria.Program.StartupSequenceTml(Boolean isServer) in tModLoader\Terraria\Program.TML.cs:line 284
   at Terraria.Program.LaunchGame(String[] args, Boolean monoArgs) in tModLoader\Terraria\Program.cs:line 211
   at Terraria.MonoLaunch.Main_End(String[] args) in tModLoader\Terraria\MonoLaunch.cs:line 78
   at Terraria.MonoLaunch.<>c__DisplayClass1_0.<Main>b__1() in tModLoader\Terraria\MonoLaunch.cs:line 64
   at System.Threading.Thread.StartCallback()

[22:23:37.834] [Main Thread/ERROR] [tML]: System.ArgumentException: An item with the same key has already been added. Key: client.log
   at System.Collections.Generic.Dictionary`2.TryInsert(TKey key, TValue value, InsertionBehavior behavior)
   at System.Collections.Generic.Dictionary`2.Add(TKey key, TValue value)
   at Ionic.Zip.ZipFile.InternalAddEntry(String name, ZipEntry entry)
   at Ionic.Zip.ZipFile._InternalAddEntry(ZipEntry ze)
   at Ionic.Zip.ZipFile.AddEntry(String entryName, Stream stream)
   at Terraria.ModLoader.Engine.LogArchiver.Archive() in tModLoader\Terraria\ModLoader\Engine\LogArchiver.cs:line 131
[22:23:37.849] [Main Thread/INFO] [tML]: Saves Are Located At: C:\Users\XmasH\Documents\My Games\Terraria\tModLoader
[22:23:37.851] [Main Thread/INFO] [tML]: Developer mode enabled
[22:23:37.861] [Main Thread/INFO] [tML]: Display DPI: Diagonal DPI is 96. Vertical DPI is 96. Horizontal DPI is 96
[22:23:37.862] [Main Thread/INFO] [tML]: High DPI Display detected: setting FNA to highdpi mode
[22:23:37.866] [Main Thread/DEBUG] [FNA]: Querying linked library versions...
[22:23:37.867] [Main Thread/DEBUG] [FNA]: SDL v2.28.2
[22:23:37.868] [Main Thread/DEBUG] [FNA]: FNA3D v23.10.0
[22:23:37.870] [Main Thread/DEBUG] [FNA]: FAudio v22.9.1
[22:23:38.334] [Main Thread/INFO] [tML]: Distribution Platform: Steam. Detection method: CWD is /steamapps/
[22:23:38.345] [Main Thread/DEBUG] [tML]: Process.Start (UseShellExecute = False): "C:\Program Files (x86)\Steam\steamapps\common\tModLoader\dotnet\6.0.14\dotnet.exe" tModLoader.dll -terrariasteamclient 1672
[22:23:38.841] [Main Thread/DEBUG] [TerrariaSteamClient]: Recv: init_success
[22:23:38.842] [Main Thread/DEBUG] [TerrariaSteamClient]: Send: acknowledged
[22:23:39.727] [Main Thread/INFO] [Terraria]: Steam Cloud Quota: 811.8 MB available
[22:23:39.727] [Main Thread/INFO] [tML]: Steam beta branch: None
[22:23:39.728] [Main Thread/INFO] [tML]: SteamBackend: Running standard Steam Desktop Client API
[22:23:39.728] [Main Thread/INFO] [tML]: Current 1281930 Workshop Folder Directory: C:\Program Files (x86)\Steam\steamapps\common\tModLoader\..\..\workshop
[22:23:39.818] [Main Thread/INFO] [FNA]: SDL Video Diver: windows
[22:23:39.818] [Main Thread/INFO] [FNA]: FNA3D Driver: D3D11
[22:23:39.818] [Main Thread/INFO] [FNA]: D3D11 Adapter: NVIDIA GeForce GT 730
[22:23:39.822] [Main Thread/INFO] [FNA]: SetStringMarker not supported!
[22:23:39.837] [Main Thread/INFO] [tML]: Terraria Steam Install Location assumed to be: C:\Program Files (x86)\Steam\steamapps\common\Terraria
[22:23:40.556] [Main Thread/INFO] [tML]: Maximum Resolution is 1920 x 1200
[22:23:40.567] [Main Thread/DEBUG] [Terraria]: Device Created, Adapter: S22B300, DisplayMode: {{Width:1600 Height:900 Format:Color}}, Profile: HiDef, Width: 1279, Height: 768, Fullscreen: False, Display: \\.\DISPLAY1
[22:23:40.799] [Main Thread/INFO] [FNA]: SDL Audio Diver: 
[22:23:41.312] [Main Thread/DEBUG] [tML]: Native Resolve: tModLoader, Version=1.4.4.9, Culture=neutral, PublicKeyToken=null -> RzChromaSDK64.dll
[22:23:41.313] [Main Thread/DEBUG] [tML]: 	not found
[22:23:46.052] [9/DEBUG] [tML]: SSDP search line separator: CRLF
[22:23:58.977] [Main Thread/WARN] [tML]: Silently Caught Exception: 
ReLogic.Content.AssetLoadException: Asset could not be found: "Images\DSTNoise"
   at ReLogic.Content.AssetRepository.LoadAssetWithPotentialAsync[T](Asset`1 asset, AssetRequestMode mode) in D:\a\tModLoader\tModLoader\src\tModLoader\ReLogic\Content\AssetRepository.cs:line 268
   at System.Runtime.CompilerServices.AsyncMethodBuilderCore.Start[TStateMachine](TStateMachine& stateMachine)
   at ReLogic.Content.AssetRepository.LoadAssetWithPotentialAsync[T](Asset`1 asset, AssetRequestMode mode)
   at ReLogic.Content.AssetRepository.LoadAsset[T](Asset`1 asset, AssetRequestMode mode) in D:\a\tModLoader\tModLoader\src\tModLoader\ReLogic\Content\AssetRepository.cs:line 206
   at ReLogic.Content.AssetRepository.Request[T](String assetName, AssetRequestMode mode) in D:\a\tModLoader\tModLoader\src\tModLoader\ReLogic\Content\AssetRepository.cs:line 157
   at ReLogic.Content.IAssetRepository.Request[T](String assetName) in D:\a\tModLoader\tModLoader\src\tModLoader\ReLogic\Content\IAssetRepository.cs:line 30
   at Terraria.Graphics.Shaders.ScreenShaderData.UseImage(String path, Int32 index, SamplerState samplerState) in tModLoader\Terraria\Graphics\Shaders\ScreenShaderData.cs:line 124
   at Terraria.Initializers.ScreenEffectInitializer.Load() in tModLoader\Terraria\Initializers\ScreenEffectInitializer.cs:line 27
   at Terraria.Main.PostContentLoadInitialize() in tModLoader\Terraria\Main.cs:line 9674
   at Terraria.Main.DrawSplash(GameTime gameTime) in tModLoader\Terraria\Main.cs:line 45070
   at Terraria.Main.DoDraw(GameTime gameTime) in tModLoader\Terraria\Main.cs:line 52860
   at Terraria.Main.Draw_Inner(GameTime gameTime) in tModLoader\Terraria\Main.cs:line 52843
   at Terraria.Main.Draw(GameTime gameTime) in tModLoader\Terraria\Main.cs:line 52830
   at Microsoft.Xna.Framework.Game.Tick() in D:\a\tModLoader\tModLoader\FNA\src\Game.cs:line 562
   at Microsoft.Xna.Framework.Game.RunLoop() in D:\a\tModLoader\tModLoader\FNA\src\Game.cs:line 878
   at Microsoft.Xna.Framework.Game.Run() in D:\a\tModLoader\tModLoader\FNA\src\Game.cs:line 419
   at Terraria.Program.RunGame() in tModLoader\Terraria\Program.cs:line 266
   at Terraria.Program.LaunchGame_(Boolean isServer) in tModLoader\Terraria\Program.cs:line 240
   at Terraria.Program.LaunchGame(String[] args, Boolean monoArgs) in tModLoader\Terraria\Program.cs:line 213
   at Terraria.MonoLaunch.Main_End(String[] args) in tModLoader\Terraria\MonoLaunch.cs:line 78
   at Terraria.MonoLaunch.<>c__DisplayClass1_0.<Main>b__1() in tModLoader\Terraria\MonoLaunch.cs:line 64
   at System.Threading.Thread.StartCallback()

[22:23:58.980] [Main Thread/ERROR] [Terraria]: Failed to load asset: "Images\DSTNoise"
ReLogic.Content.AssetLoadException: Asset could not be found: "Images\DSTNoise"
   at ReLogic.Content.AssetRepository.LoadAssetWithPotentialAsync[T](Asset`1 asset, AssetRequestMode mode) in D:\a\tModLoader\tModLoader\src\tModLoader\ReLogic\Content\AssetRepository.cs:line 268
[22:24:09.213] [Main Thread/ERROR] [Terraria]: ReLogic.Content.AssetLoadException: Asset could not be found: "Images\DSTNoise"
   at ReLogic.Content.AssetRepository.LoadAssetWithPotentialAsync[T](Asset`1 asset, AssetRequestMode mode) in D:\a\tModLoader\tModLoader\src\tModLoader\ReLogic\Content\AssetRepository.cs:line 268
   at ReLogic.Content.AssetRepository.SafelyWaitForLoad[T](Asset`1 asset, Task loadTask, Boolean tracked) in D:\a\tModLoader\tModLoader\src\tModLoader\ReLogic\Content\AssetRepository.cs:line 314
   at ReLogic.Content.AssetRepository.<>c__DisplayClass44_0`1.<LoadAsset>b__0() in D:\a\tModLoader\tModLoader\src\tModLoader\ReLogic\Content\AssetRepository.cs:line 207
   at ReLogic.Content.AssetRepository.Request[T](String assetName, AssetRequestMode mode) in D:\a\tModLoader\tModLoader\src\tModLoader\ReLogic\Content\AssetRepository.cs:line 164
   at ReLogic.Content.IAssetRepository.Request[T](String assetName) in D:\a\tModLoader\tModLoader\src\tModLoader\ReLogic\Content\IAssetRepository.cs:line 30
   at Terraria.Graphics.Shaders.ScreenShaderData.UseImage(String path, Int32 index, SamplerState samplerState) in tModLoader\Terraria\Graphics\Shaders\ScreenShaderData.cs:line 124
   at Terraria.Initializers.ScreenEffectInitializer.Load() in tModLoader\Terraria\Initializers\ScreenEffectInitializer.cs:line 27
   at Terraria.Main.PostContentLoadInitialize() in tModLoader\Terraria\Main.cs:line 9674
   at Terraria.Main.DrawSplash(GameTime gameTime) in tModLoader\Terraria\Main.cs:line 45008
   at Terraria.Main.DoDraw(GameTime gameTime) in tModLoader\Terraria\Main.cs:line 52860
   at Terraria.Main.Draw_Inner(GameTime gameTime) in tModLoader\Terraria\Main.cs:line 52853
   at Terraria.Main.Draw(GameTime gameTime) in tModLoader\Terraria\Main.cs:line 52834
[22:24:09.495] [Main Thread/FATAL] [tML]: Main engine crash

ReLogic.Content.AssetLoadException: Asset could not be found: "Images\DSTNoise"
   at ReLogic.Content.AssetRepository.LoadAssetWithPotentialAsync[T](Asset`1 asset, AssetRequestMode mode) in D:\a\tModLoader\tModLoader\src\tModLoader\ReLogic\Content\AssetRepository.cs:line 268
   at ReLogic.Content.AssetRepository.SafelyWaitForLoad[T](Asset`1 asset, Task loadTask, Boolean tracked) in D:\a\tModLoader\tModLoader\src\tModLoader\ReLogic\Content\AssetRepository.cs:line 314
   at ReLogic.Content.AssetRepository.<>c__DisplayClass44_0`1.<LoadAsset>b__0() in D:\a\tModLoader\tModLoader\src\tModLoader\ReLogic\Content\AssetRepository.cs:line 207
   at ReLogic.Content.AssetRepository.Request[T](String assetName, AssetRequestMode mode) in D:\a\tModLoader\tModLoader\src\tModLoader\ReLogic\Content\AssetRepository.cs:line 164
   at ReLogic.Content.IAssetRepository.Request[T](String assetName) in D:\a\tModLoader\tModLoader\src\tModLoader\ReLogic\Content\IAssetRepository.cs:line 30
   at Terraria.Graphics.Shaders.ScreenShaderData.UseImage(String path, Int32 index, SamplerState samplerState) in tModLoader\Terraria\Graphics\Shaders\ScreenShaderData.cs:line 124
   at Terraria.Initializers.ScreenEffectInitializer.Load() in tModLoader\Terraria\Initializers\ScreenEffectInitializer.cs:line 27
   at Terraria.Main.PostContentLoadInitialize() in tModLoader\Terraria\Main.cs:line 9674
   at Terraria.Main.DrawSplash(GameTime gameTime) in tModLoader\Terraria\Main.cs:line 45008
   at Terraria.Main.DoDraw(GameTime gameTime) in tModLoader\Terraria\Main.cs:line 52860
   at Terraria.Main.Draw_Inner(GameTime gameTime) in tModLoader\Terraria\Main.cs:line 52853
   at Terraria.Main.Draw(GameTime gameTime) in tModLoader\Terraria\Main.cs:line 52834
   at Microsoft.Xna.Framework.Game.Tick() in D:\a\tModLoader\tModLoader\FNA\src\Game.cs:line 562
   at Microsoft.Xna.Framework.Game.RunLoop() in D:\a\tModLoader\tModLoader\FNA\src\Game.cs:line 878
   at Microsoft.Xna.Framework.Game.Run() in D:\a\tModLoader\tModLoader\FNA\src\Game.cs:line 419
   at Terraria.Program.RunGame() in tModLoader\Terraria\Program.cs:line 266
[22:24:09.498] [Main Thread/DEBUG] [TerrariaSteamClient]: Send: shutdown




This erro in my Tmod someone help me?
