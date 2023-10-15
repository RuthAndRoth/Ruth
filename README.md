# Ruth2 and Roth2 Mesh Avatar Project

Ruth2 and Roth2 are low-poly mesh bodies, specifically designed for OpenSimulator.
They are built to use standard Second Life(TM) UV maps using scratch-built open
source mesh bodies by Shin Ingen with other open source contributions from the
OpenSimulator Community.

This repo has been split into 4 new repos to clarify where things belong:

* Ruth2: https://github.com/RuthAndRoth/Ruth2
* Roth2: https://github.com/RuthAndRoth/Roth2
* Reference: https://github.com/RuthAndRoth/Reference
* Extras: https://github.com/RuthAndRoth/Extras

The files that were moved have been deleted from the master branch of this repo,
however they remain in the archived branches.  The 'archive-repo-split' branch
contains the last state of the Ruth repository before the split occurred.

* Github Repository: https://github.com/RuthAndRoth/Ruth
* Discord Discussion Forum: https://discordapp.com/channels/619919380154810380/619919380691550240
* Discord Discussion Forum Invitation (open to all): https://discord.gg/UMyaZkc
* MeWe Community Page: https://mewe.com/group/5bbe0189a5f4e57c73569fb9
* Second Life Groups: "RuthAndRoth" and "Ruth and Roth Community"
* OpenSim Group: OSGrid RuthAndRoth
* OpenSim Region: OSGrid RuthAndRoth hop://login.osgrid.org/RuthAndRoth/128/128/26

## Previous Contents

The contents of this repo prior to the split have been archived into a branch
named 'archive-repo-split'.  There are also tags added that mark the last commit
that was present when the splits were performed to simplify matching up the
old and new repos if required:

* extras-split
* reference-split
* roth-split
* ruth-split

## Previous Release

The Ruth 2.0 RC#2 (also known as Ruth2 v2) release files have been archived into a git branch named 'archive-ruth-rc2' and the directories renamed 'Release' in that branch.

The Ruth 2.0 RC#3 (also known as Ruth2 v3) release files have been archived into a git branch named 'archive-ruth-rc3' and the directories renamed 'Release' in that branch.

## Licenses

Ruth2 and Roth2 are AGPL licensed, other contents of this repository are also
AGPL licensed unless otherwise indicated.  See Licenses.txt for specific details.

# Relocated Files

The migration of content from this repository to its new home:

## Roth2

* Contrib/Shin Ingen/Roth/Uploads -> Artifacts/Collada
  * Artifacts/Collada/osRoth2.0_9k_RC\#1.dae -> Artifacts/Collada/ro2_9k_v1.dae
  * Artifacts/Collada/osRoth2.0_9k_RC\#1_Boxers.dae Artifacts/Collada/ro2_9k_v1_Boxers.dae
  * Artifacts/IAR/R2-Roth-RC1.iar -> Artifacts/IAR/Roth2-v1.iar
* Contrib/Shin\ Ingen/Roth/osRoth2.0_9k_RC#1.blend -> Mesh/ro2_9k_v1.blend
* Licenses.txt -> LICENSE.md
* Mesh/Avatar Roth -> Mesh
  * Mesh/osRoth2_CurrentRelease_DevKit_RC#1.blend -> Mesh/ro2_DevKit_v1.blend
  * Mesh/osRoth2_CurrentRelease_Source_RC#1.blend -> Mesh/ro2_Source_v1.blend
* Mesh/Avatar Roth/IARs -> Artifacts/IAR
* Mesh/Avatar Roth/Scripts -> Scripts
* Mesh/Avatar Roth/Textures -> Textures

## Ruth2

* Animations -> Accessories/Animations
* Clothing -> Accessories/Clothing
* Contrib/Shin Ingen/Ruth/Uploads -> Artifacts/Collada
* Licenses.txt -> LICENSE.md
* Mesh/Avatar Ruth -> Mesh
  * Mesh/OSRuth2_CurrentRelease_DevKit_RC3.blend -> Mesh/ru2_DevKit_v3.blend
  * Mesh/OSRuth2_CurrentRelease_Source_RC3.blend -> Mesh/ru2_Source_v3.blend
* Mesh/Avatar Ruth/IARs -> Artifacts/IAR
  * Artifacts/IAR/R2-Ruth-RC3.iar -> Artifacts/IAR/Ruth2-v3.iar
* Mesh/Avatar Ruth/Scripts -> Scripts
* Mesh/Avatar Ruth/Textures -> Textures
* Mesh/Avatar Ruth/Uploads -> Artifacts/Collada
* Shapes -> Accessories/Shapes
* Skins -> Accessories/Skins

## Reference

* Contrib/Ada Radius/SecondLifeAvatar -> Linden Lab
* Contrib/Ada Radius/ccccybernetics avatar_databank -> Avatar Databank
* Skins/CMFF Templates -> CMFF Templates
* Skins/Robin Wood Templates -> Robin Wood Templates

## Extras

* Attachments/ElfEars -> Accessories/ElfEars
* Clothing -> Clothing
* Contrib/Sundance Haiku/Fingernail Project -> HUDs/Fingernail Project
* Contrib/Sundance Haiku/Hand Pose Library & HUD -> HUDs/Hand Pose Library
* LSLScripts/Parts Renamer by Fritigern Gothly -> Scripts/Parts Renamer
* Photos -> Textures
* Skins/Ada Radius-Skin and Eyelash Helpers -> Textures/Skin and Eyelash Helpers
