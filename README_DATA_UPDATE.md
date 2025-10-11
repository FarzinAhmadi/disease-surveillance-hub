# Dynamic Surveillance Dashboards - Data Update Guide

## 🔄 How to Update Data

Your dashboards are configured to **automatically read data from CSV files**. You only need to update the data files—the HTML dashboards never need to be regenerated!

### Step-by-Step Update Process

#### 1. Prepare Your New Data
- Get the latest NNDSS weekly data CSV file
- Name it exactly: `nndss_data.csv`
- Ensure it has the same column structure as the original

#### 2. Upload to GitHub
```bash
# Option A: Via GitHub Website
1. Go to your repository on GitHub.com
2. Navigate to the `dynamic_surveillance` folder
3. Click "Add file" → "Upload files"
4. Upload the new `nndss_data.csv` file
5. Commit changes

# Option B: Via Git Command Line
git add dynamic_surveillance/nndss_data.csv
git commit -m "Update surveillance data - Week XX"
git push origin main
```

#### 3. Done!
- Your dashboards will **automatically load the new data**
- No need to regenerate HTML files
- Changes appear within 1-2 minutes

## 📊 File Structure

```
dynamic_surveillance/
├── index.html                    # Hub page (never needs updating)
├── pertussis.html                # Disease dashboards (never need updating)
├── measles_total.html           
├── nndss_data.csv                # ← UPDATE THIS FILE
└── states_data.csv               # Only update if population changes
```

## ⚡ Benefits of Dynamic Loading

✅ **No HTML regeneration** needed
✅ **Instant updates** when data changes
✅ **One file to update** (nndss_data.csv)
✅ **No coding required** for updates
✅ **Automatic calculation** of rates and statistics

## 🎯 What Gets Updated Automatically

When you upload new data, the dashboards automatically recalculate:
- All case counts (weekly and cumulative)
- Incidence rates per 100,000 population
- State rankings and top states
- Timeline visualizations
- Geographic distribution maps
- Summary statistics

## ⚠️ Important Notes

1. **File name must be exact**: `nndss_data.csv`
2. **Column structure must match** the original format
3. **GitHub Pages** may take 1-2 minutes to update after upload
4. **Clear browser cache** if you don't see changes immediately

## 🔍 Troubleshooting

**Dashboard shows "Loading..." indefinitely:**
- Check that `nndss_data.csv` exists in the correct folder
- Verify the file name is exactly `nndss_data.csv`
- Check browser console for error messages

**Data looks wrong:**
- Verify CSV column names match original structure
- Check for proper formatting (no extra quotes, correct delimiters)
- Ensure numeric fields don't have commas or special characters

## 📞 Support

For questions or issues, check the repository issues page or contact the dashboard administrator.

---

**Last Updated**: Generated dynamically from surveillance data
**Data Source**: National Notifiable Diseases Surveillance System (NNDSS)
