# switch-kpm-ips-patches
IPS patches for the Nintendo Switch version of Kotor 1 &amp; 2, adapted from LaneDibello's [Kotor-Patch-Manager](https://github.com/LaneDibello/Kotor-Patch-Manager) patches.

Many of the patches don't need to be ported to the Switch because the Switch version already fixes the problem, such as the 4GBPatch, or because the patch just isn't applicable to the Switch, such as ExpandedKeyboardControl. I'm also not porting things like Snake, although it's funny, I don't think it's necessary to have.

I also include Switch-specific fixes. Most notably the AnimatedTextureFix for both games. This bug has to do with mipmaps, where the highest quality map wouldnt' appear animated. See an example [here](https://youtu.be/CmlEmN5rivw). The patches fix this for each game, so animated textures work perfectly.

### Installation
**You must have custom firmware running on your Switch, or be using an emulator.**

Move the patches you want to install into /atmosphere/exefs_patches/ on your Switch or emulator. Move the folder with the .ips file in it, not just the .ips file. 
To uninstall, delete the folder.

## Patch Status

#### Status key
| Symbol | Meaning |
|:---:|:---|
| ✅ | Ported and working |
| 🚧 | In progress |
| ❌ | Planning to port |
| ⬜ | Not planning to port |

### Kotor 1
| Status | Patch Name | Notes |
|:---:|:---|:---|
| ⬜ | 4GBPatch | |
| ⬜ | AdditionalConsoleCommands | |
| ⬜ | Alt Tab Patch | |
| ✅ | Animated Texture Fix | Switch-specific patch |
| ❌ | AppearanceBodyVariations | |
| ⬜ | BorderlessFullscreen | |
| ⬜ | CubeMapFix | |
| ❌ | DialogueRepliesPast9 | |
| ❌ | EnableScriptAurPostString | |
| ⬜ | ExpandedKeyboardControl | |
| ❌ | ExpandedVanillaOptions | |
| ❌ | FairPazaakTurnOrder | |
| ⬜ | FrameLimiter | |
| ❌ | GrassMemorySafety | |
| ❌ | GrassRenderFix | |
| ⬜ | K1GUITests | |
| ❌ | K1K2PartyTransitionRule | |
| ❌ | K1MarkedEmptyContainers | |
| ❌ | K1PazaakK2Speed | |
| ❌ | K1SecurityDemolitionsXP | |
| ❌ | K1SecuritySpikes | |
| ❌ | K1SkillPointsIntModFix | |
| ❌ | K1StrayBugFixes | |
| ⬜ | K1WidescreenPatch | |
| ❌ | LevelUpLimit | |
| ❌ | Map Texture Patch | |
| ⬜ | ModOptions | |
| ⬜ | MorePlaceablesIn2DA | |
| ⬜ | Movie Patch | |
| ❌ | PartyRosterLimit32K1 | |
| ⬜ | PlanetsLimit | |
| ⬜ | Post-Combat Movement Fix | |
| ❌ | Referenced Model Stealth Fix | |
| ❌ | SaberThrowSFX | |
| ❌ | SaveGameMemoryLeak | |
| ⬜ | ScriptExtender | |
| ❌ | SemiTransparentLetterbox | |
| ⬜ | ShaderDebug | |
| ⬜ | ShipBuildFalse | |
| ⬜ | Snake | |
| ⬜ | SoftShadowsFix | |
| ❌ | StoreConfirmThreshold2500 | |
| ❌ | StoreNoConfirmThreshold | |
| ❌ | TextureBucketSafety | |

### Kotor 2
| Status | Patch Name | Notes |
|:---:|:---|:---|
| ⬜ | 4GBPatch | |
| ⬜ | AdditionalConsoleCommands | |
| ✅ | Animated Texture Fix | Switch-specific patch |
| ❌ | AuroraAnimationBank | |
| ⬜ | BorderlessFullscreen | |
| ⬜ | DeSteamify | |
| ⬜ | EnableCheats | |
| ⬜ | ExpandedKeyboardControl | |
| ❌ | FullPartySelect | |
| ❌ | GoodAlignmentHeads | |
| ❌ | K2AntiSkipPatch | |
| ❌ | K2AspyrColorCorrection | |
| ⬜ | K2AspyrControllerFixes | |
| ❌ | K2AspyrFogReflectionFix | |
| ❌ | K2AspyrLoadingScreenLineFix | |
| ❌ | K2AspyrMapAspectFix | |
| ✅ | K2AspyrMusicFix | |
| ❌ | K2AspyrNormalMapsFix | |
| ❌ | K2AspyrSaberTextureFix | |
| 🚧 | K2AspyrShaderFixes | |
| ⬜ | K2AspyrVisibleConsole | |
| ⬜ | K2AspyrWindowingFixes | |
| ⬜ | K2ClassMenuClothes | |
| ✅ | K2FinesseMeleeFix | |
| ❌ | K2GrassFogFix | |
| ⬜ | K2MP3PlaybackFix | |
| ❌ | Max Lights | |
| ⬜ | Movie Patch | |
| ❌ | PartyRosterLimit32K2 | |
| ⬜ | Post-Combat Movement Fix | |
| ❌ | Referenced Model Stealth Fix | |
| ❌ | SaberThrowSFX | |
| 🚧 | SemiTransparentLetterbox | |
| ⬜ | ShaderDebug | |
| ✅ | StoreConfirmThreshold2500 | |
| ❌ | StoreNoConfirmThreshold | |
