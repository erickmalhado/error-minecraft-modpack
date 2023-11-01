# error-minecraft-modpack
help me, I created a modpack in 1.18.2 but an error is appearing: The game crashed whilst rendering overlay Error: java.lang.IllegalArgumentException: Failed to create player model for default
and this appears:
---- Minecraft Crash Report ----
// Hey, that tickles! Hehehe!

Time: 31/10/2023 21:17
Description: Rendering overlay

java.lang.IllegalArgumentException: Failed to create player model for default
	at net.minecraft.client.renderer.entity.EntityRenderers.lambda$createPlayerRenderers$3(EntityRenderers.java:71) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at com.google.common.collect.RegularImmutableMap.forEach(RegularImmutableMap.java:196) ~[guava-31.0.1-jre.jar%2330!/:?] {}
	at net.minecraft.client.renderer.entity.EntityRenderers.m_174051_(EntityRenderers.java:64) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.client.renderer.entity.EntityRenderDispatcher.m_6213_(EntityRenderDispatcher.java:467) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default,pl:mixin:APP:playerAnimator-common.mixins.json:firstPerson.EntityRenderDispatcherMixin,pl:mixin:APP:soulfired.mixins.json:client.EntityRenderDispatcherMixin,pl:mixin:A}
	at net.minecraft.server.packs.resources.ResourceManagerReloadListener.m_10759_(ResourceManagerReloadListener.java:15) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:computing_frames,re:mixin,re:classloading}
	at java.util.concurrent.CompletableFuture$UniRun.tryFire(CompletableFuture.java:787) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniRun.tryFire(CompletableFuture.java:784) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniRun.tryFire(CompletableFuture.java:795) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniRun.tryFire(CompletableFuture.java:784) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniRun.tryFire(CompletableFuture.java:795) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniRun.tryFire(CompletableFuture.java:784) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniRun.tryFire(CompletableFuture.java:795) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniRun.tryFire(CompletableFuture.java:784) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:726) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:714) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:726) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:714) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:726) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:714) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:726) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:714) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:726) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:714) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:726) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:714) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:726) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at com.mojang.blaze3d.systems.RenderSystem.m_69884_(RenderSystem.java:212) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,xf:OptiFine:default,re:classloading,xf:OptiFine:default,pl:mixin:APP:fpsreducer.mixins.json:RenderSystemMixin,pl:mixin:A}
	at com.mojang.blaze3d.systems.RenderSystem.m_69495_(RenderSystem.java:199) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,xf:OptiFine:default,re:classloading,xf:OptiFine:default,pl:mixin:APP:fpsreducer.mixins.json:RenderSystemMixin,pl:mixin:A}
	at com.mojang.blaze3d.platform.Window.m_85435_(Window.java:442) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,xf:OptiFine:default,re:classloading,xf:OptiFine:default}
	at net.minecraft.client.Minecraft.m_91383_(Minecraft.java:1068) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:bookshelf.common.mixins.json:client.AccessorMinecraft,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:botania_xplat.mixins.json:client.AccessorMinecraft,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:blueprint.mixins.json:client.MinecraftMixin,pl:mixin:APP:ars_nouveau.mixins.json:light.ClientMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:665) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:bookshelf.common.mixins.json:client.AccessorMinecraft,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:botania_xplat.mixins.json:client.AccessorMinecraft,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:blueprint.mixins.json:client.MinecraftMixin,pl:mixin:APP:ars_nouveau.mixins.json:light.ClientMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:205) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$launchService$0(CommonClientLaunchHandler.java:31) ~[fmlloader-1.18.2-40.2.7.jar%2318!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:37) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:106) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:77) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:149) [bootstraplauncher-1.0.0.jar:?] {}
Caused by: java.lang.NullPointerException: Cannot invoke "com.google.common.collect.ImmutableMap.entrySet()" because "ladysnake.illuminations.client.Illuminations.OVERHEADS_DATA" is null
	at ladysnake.illuminations.client.render.entity.feature.OverheadFeatureRenderer.<init>(OverheadFeatureRenderer.java:25) ~[illuminations-forge-1.18.2-1.10.2.19.jar%23140!/:1.18.2-1.10.2.19] {re:mixin,re:classloading}
	at net.minecraft.client.renderer.entity.player.PlayerRenderer.handler$bda000$addLayer(PlayerRenderer.java:3026) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:playerAnimator-common.mixins.json:PlayerRendererMixin,pl:mixin:APP:upgradednetherite.mixins.json:MixinPlayerRenderer,pl:mixin:APP:do-a-barrel-roll.mixins.json:PlayerEntityRendererMixin,pl:mixin:APP:blueprint.mixins.json:client.PlayerRendererMixin,pl:mixin:APP:3dskinlayers.mixins.json:PlayerRendererMixin,pl:mixin:APP:illuminations.mixins.json:forge.PlayerEntityRendererMixin,pl:mixin:APP:expandability.mixins.json:swimming.client.PlayerRendererMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.entity.player.PlayerRenderer.<init>(PlayerRenderer.java:57) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:playerAnimator-common.mixins.json:PlayerRendererMixin,pl:mixin:APP:upgradednetherite.mixins.json:MixinPlayerRenderer,pl:mixin:APP:do-a-barrel-roll.mixins.json:PlayerEntityRendererMixin,pl:mixin:APP:blueprint.mixins.json:client.PlayerRendererMixin,pl:mixin:APP:3dskinlayers.mixins.json:PlayerRendererMixin,pl:mixin:APP:illuminations.mixins.json:forge.PlayerEntityRendererMixin,pl:mixin:APP:expandability.mixins.json:swimming.client.PlayerRendererMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.entity.EntityRenderers.lambda$static$0(EntityRenderers.java:27) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.client.renderer.entity.EntityRenderers.lambda$createPlayerRenderers$3(EntityRenderers.java:67) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	... 115 more


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Render thread
Stacktrace:
	at net.minecraft.client.renderer.entity.EntityRenderers.lambda$createPlayerRenderers$3(EntityRenderers.java:71) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at com.google.common.collect.RegularImmutableMap.forEach(RegularImmutableMap.java:196) ~[guava-31.0.1-jre.jar%2330!/:?] {}
	at net.minecraft.client.renderer.entity.EntityRenderers.m_174051_(EntityRenderers.java:64) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.client.renderer.entity.EntityRenderDispatcher.m_6213_(EntityRenderDispatcher.java:467) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default,pl:mixin:APP:playerAnimator-common.mixins.json:firstPerson.EntityRenderDispatcherMixin,pl:mixin:APP:soulfired.mixins.json:client.EntityRenderDispatcherMixin,pl:mixin:A}
	at net.minecraft.server.packs.resources.ResourceManagerReloadListener.m_10759_(ResourceManagerReloadListener.java:15) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:computing_frames,re:mixin,re:classloading}
	at java.util.concurrent.CompletableFuture$UniRun.tryFire(CompletableFuture.java:787) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniRun.tryFire(CompletableFuture.java:784) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniRun.tryFire(CompletableFuture.java:795) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniRun.tryFire(CompletableFuture.java:784) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniRun.tryFire(CompletableFuture.java:795) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniRun.tryFire(CompletableFuture.java:784) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniRun.tryFire(CompletableFuture.java:795) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniRun.tryFire(CompletableFuture.java:784) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:726) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:714) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:726) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:714) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:726) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:714) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:726) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:714) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:726) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:714) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:726) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_143940_(SimpleReloadInstance.java:69) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at net.minecraft.util.thread.BlockableEventLoop.execute(BlockableEventLoop.java:118) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:computing_frames,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default}
	at net.minecraft.server.packs.resources.SimpleReloadInstance.m_10834_(SimpleReloadInstance.java:68) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading}
	at java.util.concurrent.CompletableFuture$UniCompletion.claim(CompletableFuture.java:572) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:714) ~[?:?] {}
	at java.util.concurrent.CompletableFuture.postComplete(CompletableFuture.java:510) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture.postFire(CompletableFuture.java:614) ~[?:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$UniAccept.tryFire(CompletableFuture.java:726) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$Completion.run(CompletableFuture.java:482) ~[?:?] {}
	at com.mojang.blaze3d.systems.RenderSystem.m_69884_(RenderSystem.java:212) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,xf:OptiFine:default,re:classloading,xf:OptiFine:default,pl:mixin:APP:fpsreducer.mixins.json:RenderSystemMixin,pl:mixin:A}
	at com.mojang.blaze3d.systems.RenderSystem.m_69495_(RenderSystem.java:199) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,xf:OptiFine:default,re:classloading,xf:OptiFine:default,pl:mixin:APP:fpsreducer.mixins.json:RenderSystemMixin,pl:mixin:A}
-- Overlay render details --
Details:
	Overlay name: net.minecraft.client.gui.screens.LoadingOverlay
Stacktrace:
	at net.minecraft.client.renderer.GameRenderer.m_109093_(GameRenderer.java:1261) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,xf:OptiFine:default,re:classloading,pl:accesstransformer:B,xf:OptiFine:default,pl:mixin:APP:do-a-barrel-roll.mixins.json:GameRendererMixin,pl:mixin:APP:shouldersurfing.mixins.json:MixinGameRenderer,pl:mixin:A}
	at net.minecraft.client.Minecraft.m_91383_(Minecraft.java:1046) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:bookshelf.common.mixins.json:client.AccessorMinecraft,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:botania_xplat.mixins.json:client.AccessorMinecraft,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:blueprint.mixins.json:client.MinecraftMixin,pl:mixin:APP:ars_nouveau.mixins.json:light.ClientMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:665) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:bookshelf.common.mixins.json:client.AccessorMinecraft,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:botania_xplat.mixins.json:client.AccessorMinecraft,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:blueprint.mixins.json:client.MinecraftMixin,pl:mixin:APP:ars_nouveau.mixins.json:light.ClientMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:205) ~[client-1.18.2-20220404.173914-srg.jar%23225!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$launchService$0(CommonClientLaunchHandler.java:31) ~[fmlloader-1.18.2-40.2.7.jar%2318!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:37) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:106) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:77) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:149) [bootstraplauncher-1.0.0.jar:?] {}


-- Last reload --
Details:
	Reload number: 1
	Reload reason: initial
	Finished: No
	Packs: Default

-- System Details --
Details:
	Minecraft Version: 1.18.2
	Minecraft Version ID: 1.18.2
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 17.0.1, Microsoft
	Java VM Version: OpenJDK 64-Bit Server VM (mixed mode), Microsoft
	Memory: 1271816856 bytes (1212 MiB) / 3254779904 bytes (3104 MiB) up to 8589934592 bytes (8192 MiB)
	CPUs: 8
	Processor Vendor: GenuineIntel
	Processor Name: Intel(R) Core(TM) i7-7700HQ CPU @ 2.80GHz
	Identifier: Intel64 Family 6 Model 158 Stepping 9
	Microarchitecture: Kaby Lake
	Frequency (GHz): 2,81
	Number of physical packages: 1
	Number of physical CPUs: 4
	Number of logical CPUs: 8
	Graphics card #0 name: Intel(R) HD Graphics 630
	Graphics card #0 vendor: Intel Corporation (0x8086)
	Graphics card #0 VRAM (MB): 1024,00
	Graphics card #0 deviceId: 0x591b
	Graphics card #0 versionInfo: DriverVersion=27.20.100.9664
	Graphics card #1 name: NVIDIA GeForce GTX 1050 Ti
	Graphics card #1 vendor: NVIDIA (0x10de)
	Graphics card #1 VRAM (MB): 4095,00
	Graphics card #1 deviceId: 0x1c8c
	Graphics card #1 versionInfo: DriverVersion=31.0.15.4592
	Memory slot #0 capacity (MB): 8192,00
	Memory slot #0 clockSpeed (GHz): 2,40
	Memory slot #0 type: DDR4
	Memory slot #1 capacity (MB): 8192,00
	Memory slot #1 clockSpeed (GHz): 2,40
	Memory slot #1 type: DDR4
	Virtual memory max (MB): 24215,86
	Virtual memory used (MB): 14369,06
	Swap memory total (MB): 8192,00
	Swap memory used (MB): 269,84
	JVM Flags: 9 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xss1M -Xmx8G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
	Launched Version: 1.18.2-forge-40.2.7
	Backend library: LWJGL version 3.2.2 SNAPSHOT
	Backend API: Intel(R) HD Graphics 630 GL version 3.2.0 - Build 27.20.100.9664, Intel
	Window size: 854x480
	GL Caps: Using framebuffer using OpenGL 3.2
	GL debug messages: 
	Using VBOs: Yes
	Is Modded: Definitely; Client brand changed to 'forge'
	Type: Client (map_client.txt)
	Graphics mode: fancy
	Resource Packs: 
	Current Language: Português (Brasil)
	CPU: 8x Intel(R) Core(TM) i7-7700HQ CPU @ 2.80GHz
	OptiFine Version: OptiFine_1.18.2_HD_U_H6
	OptiFine Build: 20220313-160847
	Render Distance Chunks: 12
	Mipmaps: 4
	Anisotropic Filtering: 1
	Antialiasing: 0
	Multitexture: false
	Shaders: null
	OpenGlVersion: 3.2.0 - Build 27.20.100.9664
	OpenGlRenderer: Intel(R) HD Graphics 630
	OpenGlVendor: Intel
	CpuCount: 8
	ModLauncher: 9.1.3+9.1.3+main.9b69c82a
	ModLauncher launch target: forgeclient
	ModLauncher naming: srg
	ModLauncher services: 
		 mixin PLUGINSERVICE 
		 eventbus PLUGINSERVICE 
		 slf4jfixer PLUGINSERVICE 
		 object_holder_definalize PLUGINSERVICE 
		 runtime_enum_extender PLUGINSERVICE 
		 capability_token_subclass PLUGINSERVICE 
		 accesstransformer PLUGINSERVICE 
		 runtimedistcleaner PLUGINSERVICE 
		 mixin TRANSFORMATIONSERVICE 
		 OptiFine TRANSFORMATIONSERVICE 
		 fml TRANSFORMATIONSERVICE 
	FML Language Providers: 
		minecraft@1.0
		lowcodefml@null
		javafml@null
	Mod List: 
		client-1.18.2-20220404.173914-srg.jar             |Minecraft                     |minecraft                     |1.18.2              |NONE      |Manifest: a1:d4:5e:04:4f:d3:d6:e0:7b:37:97:cf:77:b0:de:ad:4a:47:ce:8c:96:49:5f:0a:cf:8c:ae:b2:6d:4b:8a:3f
		forge-1.18.2-40.2.7-universal.jar                 |Forge                         |forge                         |40.2.7              |NONE      |Manifest: 84:ce:76:e8:45:35:e4:0e:63:86:df:47:59:80:0f:67:6c:c1:5f:6e:5f:4d:b3:54:47:1a:9f:7f:ed:5e:f2:90
