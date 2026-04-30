# Personal Development Build Changes

This is a personal-use modification of Fincept Terminal for private learning and development.

## What changed

1. **Top navigation simplified for personal use**
   - Added direct `WATCHLIST` tab.
   - Added direct `JOURNAL` tab.
   - Removed heavy/less-needed tabs from the visible top bar: `NODES`, `CODE`, `QUANTLIB`, `FORUM`.
   - The screens are still registered internally; only the main top navigation was simplified.

2. **Personal trading journal improvements**
   - Added note categories:
     - `TRADING JOURNAL`
     - `DAILY PLAN`
     - `TRADE REVIEW`
     - `RISK NOTES`
     - `LESSONS`
   - Added `+ TRADE` button to create a pre-filled trade journal template.
   - Added `+ PLAN` button to create a pre-filled daily trading plan template.

3. **Starter watchlist adjusted**
   - New installations create a `Personal Watchlist` instead of `Default`.
   - Added `SPY` and `QQQ` to the starter symbols.

4. **Personal visible branding**
   - Window title changed to `AM-Trading`.
   - Top brand changed to `AM TRADING DESK`.
   - First-time setup title changed to `AM-Trading`.

## Files modified

- `fincept-qt/src/ui/navigation/FKeyBar.cpp`
- `fincept-qt/src/ui/navigation/NavigationBar.cpp`
- `fincept-qt/src/screens/notes/NotesScreen.cpp`
- `fincept-qt/src/screens/notes/NotesScreen.h`
- `fincept-qt/src/screens/watchlist/WatchlistScreen.cpp`
- `fincept-qt/src/app/MainWindow.cpp`
- `fincept-qt/src/app/main.cpp`
- `fincept-qt/src/screens/setup/SetupScreen.cpp`

## Important

This is still based on Fincept Terminal source code. Use it privately unless you obtain the correct license for commercial use or redistribution.

