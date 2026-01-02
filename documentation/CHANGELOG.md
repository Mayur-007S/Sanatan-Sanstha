# 📝 Changelog - Swabhav Dosh Sarni

All notable changes to this project will be documented in this file.

---

## [Version 1.8.5] - 2025-12-30
### 🎨 Branding
- **New Header:** Added "Om" logo and "Swabhav Dosh Sarni" text to the secondary navigation bar for better branding visibility.

## [Version 1.8.4] - 2025-12-30
### ✨ New Features
- **Global Search:** Added search bars to "History Log", "Decision History", and "Transformation Log" to quickly find specific entries.
- **Smart Sorting:** All history lists now automatically sort by latest date first, ensuring you always see recent activity at the top.

## [Version 1.8.3] - 2025-12-30
### 🐛 Bug Fixes
- **Improved Comparison Selector:** Replaced "Select Wrong Thing" dropdown with a custom searchable dropdown that wraps long text, allowing you to read the full mistake description easily.

## [Version 1.8.2] - 2025-12-30
### 🐛 Bug Fixes
- **Full Text Visibility:** Fixed issue where text in "Select Wrong Thing" and "Select Decision" dropdowns was truncated. Now shows the full description.

## [Version 1.8.1] - 2025-12-30
### 🎨 UI UX Improvements
- **Searchable Multi-Select:** Replaced the standard dropdown with a user-friendly searchable list for Defects
- **Better Selection:** Checkboxes for easier selection of multiple items
- **Interactive Badges:** Selected defects appear as badges inside the input field that can be removed with a click

## [Version 1.8.0] - 2025-12-30

### ✨ New Features

#### **Multiple Personality Defects Selection**
- **What's New:** You can now select **multiple personality defects** for a single wrong thing!
- **Why It Matters:** Often a single mistake involves more than one defect. For example, shouting at someone might involve both "Anger" and "Arrogance"
- **How to Use:** 
  - Hold **Ctrl** (Windows) or **Cmd** (Mac) while clicking to select multiple defects
  - Selected defects appear as colorful badges in the history log
  - All selected defects are exported to Excel

### 🎨 UI Improvements
- **Badge Display:** Multiple defects now show as individual colored badges for better visibility
- **Helper Text:** Added instruction below the defect selector: "💡 Hold Ctrl (Windows) or Cmd (Mac) to select multiple defects"
- **Multi-Select Box:** Increased height to show 8 options at once for easier selection

### 🔧 Technical Improvements
- **Backward Compatibility:** Old entries with single defects still work perfectly
- **Data Format:** Defects are now stored as arrays internally
- **Excel Export:** Multiple defects are exported as comma-separated values (e.g., "Anger, Arrogance")
- **Edit Functionality:** When editing an entry, all previously selected defects are automatically highlighted

### 📊 Example Use Case

**Before (Version 1.7.0):**
- You could only select ONE defect per mistake
- If a mistake involved anger AND ego, you had to choose just one

**After (Version 1.8.0):**
- Select both "Anger (Krodha)" AND "Egoistic"
- Both appear as badges: `[Anger] [Egoistic]`
- More accurate tracking of complex behaviors!

---

## [Version 1.7.0] - 2025-12-29

### 🆘 Enhanced Bug Reporting

#### **Bilingual Instructions**
- Added Hindi/Marathi translations for bug reporting instructions
- Clearer guidance: "काय अडचण आली?" (What went wrong?)

#### **Dual Email Options**
- **Option 1:** Open in Mail App (for mobile users)
- **Option 2:** Open in Chrome/Browser (for desktop users)
- Pre-filled email templates for both options

### 🎨 UI Fixes
- Fixed "Save Mistake" button visibility issue
- Improved sticky positioning for better mobile experience
- Enhanced feedback section styling

---

## [Version 1.6.0] - 2025-12-20

### 🌍 Multi-Language Support

#### **6 Languages Added**
- English (en)
- Hindi (हिन्दी)
- Marathi (मराठी)
- Gujarati (ગુજરાતી)
- Kannada (ಕನ್ನಡ)
- Tamil (தமிழ்)

#### **Features**
- Instant translation via Google Translate
- Language preference saved in browser
- Bilingual defect names (e.g., "Anger (क्रोध)")

---

## [Version 1.5.0] - 2025-12-15

### 💾 Excel Export Functionality

#### **Export All Data**
- **4 Excel Sheets:**
  1. Master Journey Log (consolidated view)
  2. All Mistakes History
  3. All Decisions Taken
  4. All Transformation Results

#### **Features**
- One-click export
- Lazy-loading of XLSX library (faster initial load)
- Comprehensive data backup

---

## [Version 1.4.0] - 2025-12-10

### 🌟 Results Tracking Feature

#### **New "Results" Tab**
- Document transformation after implementing decisions
- Link results to specific decisions
- Track internal and external changes

#### **Benefits**
- See tangible evidence of spiritual growth
- Motivates continued practice
- Complete the three-step cycle

---

## [Version 1.3.0] - 2025-12-05

### 💡 Decision Logging Feature

#### **New "Right Decision" Tab**
- Link corrective actions to specific mistakes
- Build a knowledge base of right responses
- Prepare mentally for future situations

#### **Features**
- Dropdown populated from logged mistakes
- Linked data structure
- Edit and delete functionality

---

## [Version 1.2.0] - 2025-11-28

### 🎨 UI/UX Improvements

#### **Design Enhancements**
- Modern gradient backgrounds
- Improved form styling
- Better mobile responsiveness
- Smooth animations and transitions

#### **Performance**
- Optimized rendering (show 50 entries, load more on demand)
- Faster sorting algorithm
- Reduced initial load time

---

## [Version 1.1.0] - 2025-11-20

### 📋 Enhanced Personality Defects

#### **Expanded Defect List**
- Added 30+ specific defects
- Organized into 4 categories:
  1. Shadripu (The Six Foes)
  2. Defects Affecting Others
  3. Defects Affecting Self
  4. Operational & Behavioral

#### **Better Categorization**
- Optgroups for easier navigation
- Bilingual names (English + Marathi/Hindi)
- "Others" option for unlisted defects

---

## [Version 1.0.0] - 2025-11-15

### 🎉 Initial Release

#### **Core Features**
- **Wrong Things Log:** Record mistakes with date, time, defect, and description
- **Local Storage:** All data stored on device
- **Privacy:** 100% offline capability
- **Edit & Delete:** Modify or remove entries
- **Responsive Design:** Works on all devices

#### **Basic Functionality**
- Form validation
- Toast notifications
- Chronological sorting
- Simple, clean interface

---

## 🔮 Upcoming Features (Roadmap)

### Version 1.9.0 (Planned)
- 📊 **Analytics Dashboard:** Visual charts showing defect patterns over time
- 🔍 **Search Functionality:** Find specific entries quickly
- 🏷️ **Tags/Labels:** Add custom tags to entries

### Version 2.0.0 (Planned)
- 🔔 **Daily Reminders:** Optional notifications to log entries
- 🌙 **Dark Mode:** Eye-friendly theme for night use
- 📱 **Progressive Web App (PWA):** Install as mobile app

### Version 2.1.0 (Planned)
- ☁️ **Optional Cloud Sync:** Backup to cloud (encrypted)
- 👥 **Mentor Sharing:** Securely share data with spiritual guide
- 📚 **Resource Library:** Articles on each defect

---

## 📊 Version Comparison

| Feature | v1.0 | v1.3 | v1.5 | v1.7 | v1.8 |
|---------|------|------|------|------|------|
| Log Mistakes | ✅ | ✅ | ✅ | ✅ | ✅ |
| Log Decisions | ❌ | ✅ | ✅ | ✅ | ✅ |
| Log Results | ❌ | ❌ | ✅ | ✅ | ✅ |
| Excel Export | ❌ | ❌ | ✅ | ✅ | ✅ |
| Multi-Language | ❌ | ❌ | ❌ | ✅ | ✅ |
| Bug Reporting | ❌ | ❌ | ❌ | ✅ | ✅ |
| **Multiple Defects** | ❌ | ❌ | ❌ | ❌ | **✅** |

---

## 🙏 Acknowledgments

### Contributors
- **Mayur Myana** - Developer & Maintainer
- **Beta Testers** - Early users who provided valuable feedback
- **Community** - Feature requests and bug reports

### Special Thanks
- **Sanatan Sanstha** - For the foundational teachings
- **Users** - For choosing this tool on their spiritual journey

---

## 📞 Report Issues or Suggest Features

**Email:** mayurmyana111@gmail.com  
**Subject:** "Feature Request" or "Bug Report"

We read every email and consider every suggestion!

---

## 📝 Notes

### Versioning Scheme
- **Major (X.0.0):** Breaking changes or major new features
- **Minor (1.X.0):** New features, backward compatible
- **Patch (1.0.X):** Bug fixes and minor improvements

### Update Frequency
- **Bug Fixes:** As soon as reported and verified
- **New Features:** Every 2-4 weeks
- **Major Versions:** Every 3-6 months

---

**🕉️ Stay Updated! 🕉️**

Check the version number in the app menu (⋮) to see if you have the latest version.

**Current Version:** 1.8.0  
**Last Updated:** December 30, 2025

