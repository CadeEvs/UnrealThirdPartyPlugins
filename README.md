# Unreal Third Party Plugins
A list of recommended third party plugins for Unreal Engine.

## Game Systems
| Name                                                                                         | Description                                                                                                 | Source | Notes            |
| -------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- | ------ | ---------------- |
| [GameItemsPlugin](https://github.com/bohdon/GameItemsPlugin)                                 | Provides classes and tools for creating gameplay items, inventories and equipment.                          | Open   |                  |
| [ExtendedGameplayAbilitiesPlugin](https://github.com/bohdon/ExtendedGameplayAbilitiesPlugin) | Three plugins for extending and working with Unreal's builtin Gameplay Abilities.                           | Open   |                  |
| [GameExperiencesPlugin](https://github.com/bohdon/GameExperiencesPlugin)                     | Defining modular extensions to game modes that leverage the GameFeatures plugin. Based on Lyra experiences. | Open   |                  |
| [SPUD](https://github.com/sinbad/SPUD)                                                       | A save game and streaming level persistence solution for Unreal Engine 5.                                   | Open   |                  |
| [SUDS](https://github.com/sinbad/SUDS)                                                       | Allows you to run dialogues in your game based on a script that you write in a text file.                   | Open   | Has paid version |

## Core
| Name                                                 | Description                                                                                                                                             | Source | Notes |
| ---------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ | ----- |
| [FlowGraph](https://github.com/MothCocoon/FlowGraph) | A design-agnostic event node editor. It provides a graph editor tailored for scripting flow of events in virtual worlds.                                | Open   |       |
| [ue5coro](https://github.com/landelare/ue5coro)      | Implements C++20 coroutine support for Unreal Engine 5 with a focus on gameplay logic, convenience, and providing seamless integration with the engine. | Open   |       |
| [VoxelCore](http://voxelcore/)                       | It's essentially a layer on top Unreal to make it easier to write high-performance code & customize the editor.                                         | Open   |       |

## Tools
| Name                                                                                  | Description                                                                                                                         | Source | Notes |
| ------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- | ------ | ----- |
| [Blueprint Assist](https://www.fab.com/listings/14d7ba87-a587-406d-9369-ed75fa0a55ed) | Provides automatic formatting and mouse-free node editing when working with blueprints.                                             | Paid   |       |
| [MDMetaDataEditor](https://github.com/DoubleDeez/MDMetaDataEditor)                    | Enables editing the meta data of Blueprint-created variables, function parameters, functions, events, macros, and collapsed graphs. | Open   |       |
| [Get Relief!](https://www.fab.com/listings/5f5db94e-852a-4bbb-9bb0-c3757834c3a0)      | Aims to simplify and demystify different Relief Mapping techniques for materials.                                                   | Open   |       |
| [Quick Actions](https://github.com/outoftheboxplugins/QuickActions)                   |                                                                                                                                     | Open   |       |
| [Slate Icon Browser](https://github.com/sirjofri/SlateIconBrowser)                    | Lets you browse Unreal Engine's Editor icons/brushes easily, search for specific ones and copy slate code for the selected icon.    | Open   |       |

## Debugging
| Name                                                                  | Description                                                                                     | Source | Notes |
| --------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ------ | ----- |
| [UnrealImGui](https://github.com/IDI-Systems/UnrealImGui)             | Integrates Dear ImGui developed by Omar Cornut.                                                 | Free   |       |
| [Cog](https://github.com/arnaud-jamin/Cog)                            | A set of debug tools for Unreal Engine built on top of Dear ImGui                               | Free   |       |
| [Property Watcher](https://github.com/aquanox/SubsystemBrowserPlugin) | A runtime variable watch window for Unreal Engine using ImGui.                                  | Free   |       |
| [Subsystem Browser](https://github.com/guitarfreak/PropertyWatcher)   | Provides a dedicated Subsystem Browser panel to display active subsystems with property editor. | Free   |       |

## UI
| Name                                                             | Description                                                                                                                                                                                                                                      | Source | Notes |
| ---------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------ | ----- |
| [MDViewModel](https://github.com/DoubleDeez/MDViewModel)         | An Unreal-ified implementation of the Model-View-ViewModel pattern, supporting UMG Widgets and Actor Blueprints as Views with the goal of automating the most common binding patterns.                                                           | Free   |       |
| [MDFastBinding](https://github.com/DoubleDeez/MDFastBinding)     | A versatile and performant alternative to UMG property bindings for designer-friendly workflows. The goal was to build a tool that allows mutating raw data into a form that can drive visuals, all within the editor, while staying performant. | Free   |       |
| [UIDataSource](https://github.com/Sharundaar/UIDatasource)       | A light MVVM plugin that aims to provide a performant, simple, and easy to integrate middle layer that helps with developping UI alongside an ever changing game.                                                                                | Free   |       |
| [DeferredPainter](https://github.com/Sharundaar/DeferredPainter) | An UMG exposed deferred paint container for Unreal.                                                                                                                                                                                              | Free   |       |

## Online
| Name                                                                                      | Description | Source | Notes                        |
| ----------------------------------------------------------------------------------------- | ----------- | ------ | ---------------------------- |
| [EOS Online Subsystem](https://www.fab.com/listings/b900b244-0ff6-49e3-8562-5fc630ba9515) |             | Paid   | Offers limited free version  |
| [EOSIntegrationKit](https://github.com/betidestudio/EOSIntegrationKit)                    |             | Open   | Optional marketplace payment |

## Languages
| Name                                                                 | Description                                                                                                        | Source | Notes                       |
| -------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ | ------ | --------------------------- |
| [AngelScript](https://github.com/Hazelight/UnrealEngine-Angelscript) | A set of engine modifications and a plugin for Unreal Engine 5 that integrates a full-featured scripting language. | Open   | Requires custom engine fork |
| [UnrealSharp](https://github.com/UnrealSharp/UnrealSharp)            | Allows game developers to use C# in their projects with the power of .NET 9.                                       | Open   |                             |

## Source Control
| Name                                                          | Description                                                                                                                                                                                                      | Source | Notes |
| ------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------ | ----- |
| [UEGitPlugin](https://github.com/ProjectBorealis/UEGitPlugin) | Refactor of the Git LFS 2 plugin by SRombauts, with lessons learned from production that include performance optimizations, new features and workflow improvements.                                              | Open   |       |
| [rugs](https://github.com/jorgenpt/rugs)                      | An efficient, easy-to-deploy alternative to Epic's official metadata server for Unreal Game Sync. It is designed to work seamlessly with Unreal Game Sync, and adds support for basic authentication if desired. | Open   |       |
| [Friendshipper](https://github.com/believer-oss/ethos)        | Desktop application for viewing and downloading builds of an Unreal project. It can be used in one of two modes:                                                                                                 | Open   |       |
| [p4transfer](https://github.com/perforce/p4transfer)          | Utility for transferring a subset of files (with complete history of all changelists) from one Helix Core repository to another, only requiring read access to the source repository.                            | Open   |       |
