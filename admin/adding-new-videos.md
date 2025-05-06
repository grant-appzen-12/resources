# Adding New Videos

This guide explains the process for adding new videos to the catalog while maintaining our ID stability policy.

## Step 1: Assign the Next Sequential ID

The next available ID is **V013**.

Always use the next available sequential ID regardless of which category the video belongs to. IDs are global across all categories.

## Step 2: Name the Video File

Format: `V[ID]-[descriptive-name].mp4`

Example: `V013-supplier-onboarding.mp4`

Place the file in: `/resources/videos/current/new/`

## Step 3: Update the GitBook

1. Add the video to the appropriate section in the SUMMARY.md file
2. Create a new markdown file for the video
3. Add the video to the category overview page

## Step 4: Create the Video Detail Page

Create a new markdown file with the following information:
- ID and title
- Duration
- File path
- Description
- Key features demonstrated
- Related videos

## Example Addition

```markdown
# V013: Supplier Onboarding

**Duration:** 4:22  
**Path:** `/resources/videos/current/new/V013-supplier-onboarding.mp4`  
**Category:** Accounts Payable Solutions - Autonomous AP

## Description
This video demonstrates the supplier onboarding workflow...

...
```
