# Search & Trade Artifacts AGOT Compatibility

This is a [Search & Trade Artifacts](https://steamcommunity.com/sharedfiles/filedetails/?id=2962238514) compatibility patch for [A Game of Thrones](https://steamcommunity.com/sharedfiles/filedetails/?id=2962333032). For an overview of features and other changes, see the [Search & Trade Artifacts README](https://github.com/pharaox/artifact_trade/blob/main/README.md).

The latest version is compatible with CK3 1.17.x, STA 0.15.x and AGOT 0.4.13+.

Load order:

* AGOT
* Search & Trade Artifacts
* Search & Trade Artifacts AGOT Compatibility

## Overview

Search & Trade Artifacts is already largely compatible with most mods due to its design, however there are a few minor things that don't work quite as expected with conversion mods without a compatch. This submod is making it fully compatible with AGOT. It introduces the following changes:

* Enables proper filtering by modifier for historical artifacts added by AGOT (such as Valyrian steel blades)
* Eliminates errors due to vanilla artifact modifiers and religions that don't exist in AGOT.
* Adds an AGOT-specific **Special** filter option for Valyrian steel blades.
* Ensures that the **Buy Artifact** and **Sell Artifact** interactions abide by certain AGOT restrictions, such as:
  * Non-humans can't be interacted with.
  * Wildlings can only interact with wildlings, and vice versa.
* Ensures that the **Visit Holding** decision improvements properly take into account changes made by AGOT.

## AGOT Artifact Trading

AGOT has recently introduced its own artifact trading system. It enables both players and AI to buy artifacts from or sell artifacts to a special character known as the *Treasure Keeper* via the **Peruse Artifacts Market** decision. The artifact prices, AI willingness to buy or sell, and other core aspects of this trading system have been contributed by me (**@pharaox**) and are based on STA logic, so this system is fully compatible with STA even without this submod. In addition, this submod ensures that the *Treasure Keeper* can't be targeted by the **Buy Artifact** and **Sell Artifact** interactions.

AGOT artifact trading is subject to certain restrictions that also apply to STA interactions and the vanilla **Destroy Artifact** interaction if STA is enabled. These are:

* The AI can't trade special AGOT artifacts such as historical unique artifacts, Valyrian steel blades, and dragon eggs.
* Both players and AI can't trade special thrones (e.g. *The Iron Throne*).
* Both players and AI can't destroy special AGOT artifacts of all 4 kinds listed above.

## Links

* [GitHub Repository](https://github.com/pharaox/artifact_trade_agot)
