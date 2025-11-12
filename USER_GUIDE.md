# Personal Financial Calendar - User Guide

## 🎉 New Features Added!

### 1. 📤 Export Profile
**Location:** Menu Bar → "Export Profile"

**What it does:**
- Downloads your current profile as a `.json` file
- Creates a backup you can save anywhere
- Allows sharing profiles between devices

**How to use:**
1. Open the profile you want to export
2. Click "Export Profile" in the menu
3. Save the downloaded JSON file somewhere safe
4. Use this file to restore your profile later or use on another device

---

### 2. 📥 Import Profile
**Location:** Menu Bar → "Import Profile"

**What it does:**
- Loads a previously exported profile JSON file
- Creates a new profile from the imported data
- Automatically renames if a profile with that name already exists

**How to use:**
1. Click "Import Profile" in the menu
2. Click "Choose File" and select your `.json` profile file
3. The profile will be imported and appear in your profile list
4. If the name conflicts, it will add "(1)", "(2)", etc.

---

### 3. 👥 Combined Finances Mode
**Location:** Menu Bar → "Combined Finances"

**What it does:**
- Merges 2 or more individual profiles into a household budget
- Smart detection of shared expenses (rent, utilities, etc.)
- Allows you to choose which items to merge vs keep separate
- Creates a new combined profile you can save and reload

**Perfect for:**
- Couples managing shared finances
- Roommates splitting rent and utilities
- Family budgets combining multiple income sources
- "What-if" scenarios comparing different living arrangements

---

## 🏠 How to Use Combined Finances Mode

### Step 1: Select Profiles to Combine

1. Click **"Combined Finances"** in the menu bar
2. You'll see cards for all your profiles
3. Click on 2 or more profiles you want to combine
   - Selected profiles will be highlighted in blue
4. Click **"Next: Review Items →"**

### Step 2: Review & Merge Items

The interface will show all income, expenses, and assets from the selected profiles, organized into groups.

**🔍 Smart Grouping:**
- Items with similar names or categories are grouped together
- Each group is highlighted with a colored box
- These are **suggested merges** - items that might be shared

**✅ Merging Items:**
- **Check the box** next to items you want to merge together
  - Example: Both you and your partner have "Rent" expenses → Check both to combine into one
- **Leave unchecked** for separate expenses
  - Example: Each person has their own car payment → Leave unchecked to keep separate

**Examples:**

**Merge These (Check Both):**
- Rent/Mortgage (if you live together)
- Internet/Utilities (if shared)
- Groceries (if from shared budget)
- Joint savings accounts

**Keep Separate (Leave Unchecked):**
- Individual car payments
- Personal credit cards
- Individual subscriptions (Netflix on Person A, Spotify on Person B)
- Separate bank accounts

### Step 3: Name & Create

1. Enter a name for your combined profile
   - Default: "Profile A + Profile B"
   - Suggestion: "Our Household Budget" or "Jane & John Combined"
2. Click **"Create Combined Profile"**
3. The system will create the new profile with:
   - Merged items shown as "Item Name (Combined)"
   - Separate items shown as "Item Name (Person's Name)"

### Step 4: Save Your Combined Profile

After creating, you'll be prompted to download a backup:
- Click **Yes** to save the combined profile as a JSON file
- Store this file safely - you can reload it anytime
- You can also export it later using "Export Profile"

---

## 💡 Example Scenarios

### Scenario 1: Couple Moving In Together

**Individual Profiles:**
- "Sarah's Budget" - $3000 income, $1800 rent, $200 utilities
- "Mike's Budget" - $3500 income, $1500 rent, $150 utilities

**Combined:**
1. Select both profiles
2. Merge: Rent → Creates one "$3300 Rent (Combined)"
3. Merge: Utilities → Creates one "$350 Utilities (Combined)"
4. Keep separate: Each person's car payment, credit cards
5. Result: "Sarah & Mike's Home" shows accurate shared + individual expenses

### Scenario 2: Roommate Situation

**Individual Profiles:**
- "Alex" - Pays full rent, splits utilities
- "Jordan" - Pays half utilities, own expenses
- "Taylor" - Pays half utilities, own expenses

**Combined:**
1. Select all three profiles
2. Merge: Utilities from all three → Split cost shown
3. Keep separate: Alex's full rent (only in Alex's name)
4. Keep separate: Everyone's individual expenses
5. Result: "Apartment 4B" shows total household costs

### Scenario 3: What-If Planning

**Testing Marriage:**
1. Export your current "Single" profile as backup
2. Create "Partner's Budget" profile with their income/expenses
3. Use Combined Mode to see merged finances
4. Review the calendar to see future cash flow
5. Make decisions based on the projection
6. Keep or discard the combined profile

---

## 🔄 Loading Existing Combined Profiles

If you previously created and exported a combined profile:

1. Click **"Combined Finances"** in menu
2. At the bottom, you'll see **"Load Existing Combined Profile"**
3. Click **"Import Combined Profile"**
4. Select your previously saved `.json` file
5. The combined profile loads with all your merged items intact

The system remembers:
- Which profiles were combined
- Which items were merged
- All the merged amounts and names

---

## 📊 Viewing Combined Profile Data

When viewing a combined profile:
- The subtitle shows **"COMBINED MODE"** badge
- Item names show "(Combined)" for merged items
- Item names show "(Person Name)" for individual items
- The calendar shows all transactions from both/all profiles
- Net worth includes all assets and liabilities

---

## 💾 Data Management Best Practices

1. **Export Regularly**
   - Export your main profiles weekly/monthly
   - Export combined profiles after creation
   - Store backups in cloud storage (Dropbox, Google Drive, etc.)

2. **Name Clearly**
   - Use descriptive names: "2025 Budget" not "Budget1"
   - Combined profiles: "Our Budget" or "Household 2025"
   - Date your backups: "Sarah_Budget_2025-11-11.json"

3. **Test Before Deleting**
   - Create combined profile
   - Review it thoroughly
   - Export it as backup
   - Only then consider deleting old individual profiles

4. **Update Combined Profiles**
   - If individual budgets change, recreate the combined profile
   - Or manually edit the combined profile directly
   - Export the new version

---

## ⚠️ Important Notes

1. **Combined Mode is Additive**
   - Merged items add amounts together
   - Checking "Rent $1500" + "Rent $1500" = "$3000 Rent (Combined)"
   - This is correct for shared expenses paid by both people

2. **Browser Storage**
   - All data is in browser localStorage
   - Clearing browser data = losing profiles
   - Always keep exported JSON backups!

3. **No Auto-Sync**
   - This is a single-device app
   - To use on multiple devices: Export → Transfer → Import
   - Consider keeping files in cloud storage for easy access

4. **Profile Independence**
   - Creating a combined profile doesn't modify originals
   - Original individual profiles remain unchanged
   - You can create multiple different combined versions

---

## 🎯 Quick Tips

- **Split Rent 50/50?** Each person's profile has half the rent, then merge both = full rent shown
- **One Person Pays Rent?** Only that person has it, leave unchecked, shows as "(Name)'s Rent"
- **Testing Scenarios?** Duplicate profiles, modify one, create combined, compare forecasts
- **Lost Profile?** If you have the JSON export, just import it back
- **Multiple Combined Profiles?** Create as many as you want - test different living arrangements!

---

## 🆘 Troubleshooting

**Q: My combined profile shows double rent**
A: You checked both rent items to merge. They added together. Uncheck one if only one person pays.

**Q: Can I edit a combined profile?**
A: Yes! It's just a regular profile. Use the Data Management tab to modify items.

**Q: Can I "uncombine" profiles?**
A: No automatic split. But you still have your original individual profiles. The combined is separate.

**Q: Import failed**
A: Make sure it's a valid JSON file exported from this app. Check the file isn't corrupted.

**Q: Where's my exported file?**
A: Check your browser's default download folder (usually ~/Downloads).

---

## 🚀 Advanced Use Cases

### Multi-Property Management
- Profile for each property
- Combine to see total real estate expenses
- Compare profitability

### Business + Personal
- Separate "Business" and "Personal" profiles  
- Combined view shows total cash flow
- Keep taxes separate

### Future Planning
- Current situation profile
- Future goal profile (higher income, paid off debt)
- Compare forecasts side-by-side

### College Roommates
- Each roommate creates their profile
- Share JSON files with each other
- Everyone can import and create combined household view
- Each person sees their portion + shared costs

---

Enjoy your enhanced Personal Financial Calendar! 🎉