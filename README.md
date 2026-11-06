# switch-kpm-ips-patches
IPS patches for the Nintendo Switch version of Kotor 1 &amp; 2, adapted from LaneDibello's [Kotor-Patch-Manager](https://github.com/LaneDibello/Kotor-Patch-Manager) patches.

Many of the patches don't need to be ported to the Switch because the Switch version already fixes the problem, such as the 4GBPatch, or because the patch just isn't applicable to the Switch, such as ExpandedKeyboardControl. I'm also not porting things like Snake because although it's funny, I don't think it's necessary to have.

I also include Switch-specific fixes, for problems unique to the Switch versions of the games.

### Installation
**You must have custom firmware running on your Switch, or be using an emulator.**
**The patches are made for the latest versions of the games, 1.0.4 for both. They will not work on any other version of the game**

Move the patches you want to install into /atmosphere/exefs_patches/ on your Switch or emulator. Move the entire folder with the .ips file in it, not just the .ips file. 
To uninstall, delete the folder.

## Patch Status

#### Status key
| Symbol | Meaning |
|:---:|:---|
| ✅ | Patched and working |
| 🚧 | In progress |
| ❌ | Planning to port |
| ⬜ | Not planning to port |

### Kotor 1
| Status | Patch Name | Notes |
|:---:|:---|:---|
| ⬜ | 4GBPatch | The Switch has 4GB of unified memory, and the game already uses all of it that it can |
| ⬜ | AdditionalConsoleCommands | You can access console commands on the Switch, however I don't see the need for implementing this patch as of now |
| ⬜ | Alt Tab Patch |  |
| ✅ | Animated Texture Fix | Switch-specific patch. Fixes a bug where the highest quality mipmap of animated textures wouldn't actually be animated. [Example](https://youtu.be/CmlEmN5rivw) |
| ❌ | AppearanceBodyVariations | |
| ⬜ | BorderlessFullscreen |  |
| ⬜ | CubeMapFix |  |
| ❌ | DialogueRepliesPast9 | TODO: Confirm Switch logic matches PC for this patch |
| ❌ | EnableScriptAurPostString | |
| ⬜ | ExpandedKeyboardControl |  |
| ❌ | ExpandedVanillaOptions | I'd like to be able to use this to give the Switch access to the PC options that are hidden |
| ❌ | FairPazaakTurnOrder | |
| ⬜ | FrameLimiter | The Switch currently caps the framerate at 30fps. I'm planning on developing a 60fps patch, but I don't know if the Switch can actually achieve stable 60fps |
| ❌ | GrassMemorySafety | TODO: Confirm Switch logic matches PC for this patch |
| ❌ | GrassRenderFix | As far as I can tell, this bug doesn't exist on the Switch |
| ⬜ | K1GUITests | |
| ❌ | K1K2PartyTransitionRule | |
| ❌ | K1MarkedEmptyContainers | |
| ❌ | K1PazaakK2Speed | |
| ❌ | K1SecurityDemolitionsXP | |
| ❌ | K1SecuritySpikes | |
| ❌ | K1SkillPointsIntModFix | |
| ❌ | K1StrayBugFixes | TODO: Compare Switch &amp; PC logic for each of these fixes |
| ⬜ | K1WidescreenPatch | |
| ❌ | LevelUpLimit | |
| ❌ | Map Texture Patch | |
| ⬜ | ModOptions | |
| ⬜ | MorePlaceablesIn2DA | |
| ⬜ | Movie Patch | |
| ⬜ | PartyRosterLimit32K1 | |
| ⬜ | PlanetsLimit | |
| ⬜ | Post-Combat Movement Fix | |
| ❌ | Referenced Model Stealth Fix | TODO: Figure out what this patch does |
| ❌ | SaberThrowSFX | TODO: Confirm Switch logic matches PC for this patch |
| ❌ | SaveGameMemoryLeak | TODO: Confirm Switch logic matches PC for this patch |
| ⬜ | ScriptExtender | |
| ❌ | SemiTransparentLetterbox | |
| ⬜ | ShaderDebug | |
| ⬜ | ShipBuildFalse | |
| ⬜ | Snake | |
| ⬜ | SoftShadowsFix | |
| ❌ | StoreConfirmThreshold2500 | |
| ❌ | StoreNoConfirmThreshold | |
| ⬜ | TextureBucketSafety | |

### Kotor 2
| Status | Patch Name | Notes |
|:---:|:---|:---|
| ⬜ | 4GBPatch | The Switch has 4GB of unified memory, and the game already uses all of it that it can |
| ⬜ | AdditionalConsoleCommands | You can access console commands on the Switch, however I don't see the need for implementing this patch as of now |
| ✅ | Animated Texture Fix | Switch-specific patch. Fixes a bug where the highest quality mipmap of animated textures wouldn't actually be animated. [Example](https://youtu.be/CmlEmN5rivw)|
| ❌ | AuroraAnimationBank | |
| ⬜ | BorderlessFullscreen | |
| ⬜ | DeSteamify | |
| ⬜ | EnableCheats | |
| ⬜ | ExpandedKeyboardControl | |
| ❌ | FullPartySelect | TODO: Create Switch version of partyselect_p.gui for this patch |
| ✅ | GoodAlignmentHeads | |
| ⬜ | K2AntiSkipPatch | |
| ❌ | K2AspyrColorCorrection | |
| ⬜ | K2AspyrControllerFixes | |
| ❌ | K2AspyrFogReflectionFix | Fog is already enabled on the Switch version TODO: Confirm if reflection logic matches PC and needs patch |
| ❌ | K2AspyrLoadingScreenLineFix | TODO: Confirm Switch logic matches PC for this patch |
| ❌ | K2AspyrMapAspectFix | TODO: Confirm Switch logic matches PC for this patch |
| ✅ | K2AspyrMusicFix | |
| ⬜ | K2AspyrNormalMapsFix | |
| ❌ | K2AspyrSaberTextureFix | TODO: Confirm Switch logic matches PC for this patch |
| 🚧 | K2AspyrShaderFixes | |
| ⬜ | K2AspyrVisibleConsole | |
| ⬜ | K2AspyrWindowingFixes | |
| ⬜ | K2ClassMenuClothes | |
| ✅ | K2FinesseMeleeFix | |
| ✅ | K2GrassFogFix | |
| ⬜ | K2MP3PlaybackFix | |
| ❌ | Max Lights | |
| ⬜ | Movie Patch | |
| ⬜ | PartyRosterLimit32K2 | |
| ⬜ | Post-Combat Movement Fix | |
| ❌ | Referenced Model Stealth Fix | TODO: Figure out what this patch does |
| ❌ | SaberThrowSFX | TODO: Confirm Switch logic matches PC for this patch |
| 🚧 | SemiTransparentLetterbox | |
| ⬜ | ShaderDebug | |
| ✅ | StoreConfirmThreshold2500 | |
| ❌ | StoreNoConfirmThreshold | |
