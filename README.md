# County Lines Manager - "Skills" Update

## 🎯 Major Features

### Skill Tree System
After each game over, invest your earnings into permanent upgrades across four skill trees:
- **Operations**: Margins, Money, Banking
- **Logistics**: Transport, Evasion, Territory
- **The Network**: Personnel, Legal, Influence
- **Intelligence & Heat**: Counter-investigation tactics

**Grind Skills** (Max Level 10):
- Cost £300k per level
- Stack for powerful cumulative effects

**Elite Upgrades** (One-time unlocks):
- Require category investment thresholds
- Game-changing abilities like starting with a vehicle or keeping 50% cash on death

---

## 🆕 New Mechanics

### Investigation System Overhaul
- **Safe House**: Daily chance to pause investigation for 24h (1% per level)
- **Fixers Network**: Auto-reduce investigation by 1 point/level/day
- **Legal Retainer**: -2% investigation fill rate per level
- **Witness Control**: -1% global heat growth rate per level
- **Cover Story**: -0.5% heat during active laundering per level

### Economy Balance
- Bank interest reduced to **0.01% per day** (from 1%)
- Laundering now supports **custom amounts** with input field
- Better Equipment boosts processing AND sales speed

### Crew & Operations
- **Gang Leader**: -1% crew wages per level (floors at 50%)
- **Northampton Connection**: +2 Loyal Workers (wage-free crew)
- Operations now track sold units for statistics

### Travel Improvements
- **Route Master**: -1.5% travel time per level (all modes)
- **Heat Dodger**: -1% heat gain during travel per level
- **Street Racer**: -2% pull over risk per level
- **Mechanic**: +2% vehicle escape chance per level (caps at 95%)

### Laundering Upgrades
- **Cleaner**: -5% laundering time per level (50% floor, 1h min)
- **Accountant**: +2% laundering payout per level
- Dynamic UI shows adjusted completion time

---

## 🎨 UI/UX Improvements

### Tooltips System
Hover over UI elements for detailed explanations:
- Travel mode buttons (Train/Coach/Car/Bump)
- Heat action cards
- Ops risk indicators
- Vehicle escape chances

### Tutorial System
- First-run banner with 5-step guidance
- Auto-completes after step 5 with 3-second display
- Persists with localStorage flag

### Stats Panel
- Comprehensive list of all active permanent upgrades
- Shows current levels and effects
- Quick reference for skill benefits

### Quality of Life
- Backpack and House inventory panels
- Operation stock breakdown by product type
- Laundering pending transactions display
- Custom amount input for laundering with "Max" button

---

## 🔧 Under the Hood

### Persistence
- Custom events (Admin tab) save/load from localStorage
- All skill states, vehicle ownership, action cooldowns persist
- Investigation pause state survives sessions

### Admin Tools
- Event editor with custom triggers and chances
- Product config adjustments with live price refresh
- Debug cheats for testing

---

## 🐛 Bug Fixes
- Fixed tooltip component parse errors
- Added all missing icon definitions
- Safe fallback for skill checks when state is unavailable
- Laundering time now reflects Cleaner skill consistently
- Bank interest label matches implemented rate

---

## 📊 Skill Reference

### Operations Skills
| Skill | Effect | Max Level | Cost |
|-------|--------|-----------|------|
| Sweet Talker | -1% Buy Price | 10 | £300k/lvl |
| Pressure the Trap | +1% Sell Price | 10 | £300k/lvl |
| Gang Leader | -1% Crew Wages | 10 | £300k/lvl |
| Better Equipment | +2% Crew Speed | 10 | £300k/lvl |
| **Crooked Accountant** | Keep 50% Cash on Death | 1 | £2m + £1.5m invested |

### Logistics Skills
| Skill | Effect | Max Level | Cost |
|-------|--------|-----------|------|
| Street Racer | -2% Pull Over Risk | 10 | £300k/lvl |
| Local Influence | -2% Raid Risk | 10 | £300k/lvl |
| Mechanic | +2% Vehicle Escape | 10 | £300k/lvl |
| Route Master | -1.5% Travel Time | 10 | £300k/lvl |
| Heat Dodger | -1% Heat on Travel | 10 | £300k/lvl |
| **Grannies Gift** | Start with Ford Mondeo | 1 | £1m + £1.5m invested |

### Network Skills
| Skill | Effect | Max Level | Cost |
|-------|--------|-----------|------|
| Trap Training | -1.5% Raid Risk | 10 | £300k/lvl |
| Police Bribery | -2% Investigation Fill | 10 | £300k/lvl |
| Cleaner | -5% Laundry Time | 10 | £300k/lvl |
| Accountant | +2% Laundry Payout | 10 | £300k/lvl |
| Cover Story | -0.5% Heat During Laundry | 10 | £300k/lvl |
| **Northampton Connection** | +2 Loyal Workers | 1 | £1.8m + £1.5m invested |
| **The Fall Guy** | Second Chance When Caught | 1 | £5m + £5m invested |

### Intelligence Skills
| Skill | Effect | Max Level | Cost |
|-------|--------|-----------|------|
| Safe House | +1% Daily Pause Chance | 10 | £300k/lvl |
| Witness Control | -1% Heat Gain Rate | 10 | £300k/lvl |
| Fixers Network | -1 Heat Point Daily | 10 | £300k/lvl |
| **Insurance** | Survive One Raid | 1 | £5m + £5m invested |

---

## 🎮 Strategy Tips

1. **Early Game**: Focus on Grind skills that improve margins (Sweet Talker, Pressure the Trap)
2. **Mid Game**: Invest in travel efficiency and crew management (Route Master, Gang Leader)
3. **Late Game**: Stack heat management (Safe House, Fixers, Witness Control) to extend runs
4. **Elite Priority**: Northampton Connection gives free labor, Crooked Accountant preserves capital

---

## 📝 Changelog Summary

**v1.0 "Skills" Update**
- Added: Full skill tree system with 4 categories and 20+ upgrades
- Added: Custom laundering amount input
- Added: Update notification popup
- Improved: All skill effects now integrated into game logic
- Improved: Tutorial auto-completes at step 5
- Improved: Tooltips on Travel and Heat actions
- Improved: Stats panel shows all active upgrades
- Balanced: Bank interest to 0.01%/day
- Balanced: Safe House to daily pause chance mechanic
- Fixed: Multiple icon definition errors
- Fixed: Tooltip component parse issues
- Fixed: Laundering time display consistency

---

**Thank you for playing!** Report bugs or suggest features via GitHub.
