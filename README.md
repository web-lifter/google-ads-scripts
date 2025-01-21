
# Google Ads Scripts

Welcome to the Google Ads Scripts repository! This repository contains a collection of scripts designed to automate and enhance various aspects of managing Google Ads campaigns.

## Table of Contents

1. [Overview](#overview)
2. [Scripts](#scripts)
   - [404 Checking](#404-checking)
   - [A/B Split Test](#ab-split-test)
   - [Ad Scheduling Script](#ad-scheduling-script)
   - [Automated Alerts](#automated-alerts)
   - [Automated Bidding Script](#automated-bidding-script)
   - [Broken Link Checker Script](#broken-link-checker-script)
   - [Budget Management Script](#budget-management-script)
   - [Keyword Management Script](#keyword-management-script)
   - [Location-Based Bidding Script](#location-based-bidding-script)
   - [Negative Keyword Script](#negative-keyword-script)
   - [Performance Reporting](#performance-reporting)
   - [Stock Management Script](#stock-management-script)
   - [Targeting Based on Distance Script](#targeting-based-on-distance-script)
   - [Weather-Based Bidding Script](#weather-based-bidding-script)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributing](#contributing)
6. [License](#license)
7. [Contact](#contact)

## Overview

This repository contains a variety of scripts intended to assist with managing Google Ads campaigns. Each script serves a unique purpose, from checking for 404 errors on landing pages to adjusting bids based on weather conditions.

## Scripts

### 404 Checking

**Path:** `google-ads-scripts/404-checking`

This script checks for 404 errors on your landing pages and alerts you if any are found.

### A/B Split Test

**Path:** `google-ads-scripts/ab-split-test`

This script facilitates A/B split testing by rotating ads and tracking performance metrics to determine the best-performing ads.

### Ad Scheduling Script

**Path:** `google-ads-scripts/ad-scheduling-script`

This script automates the scheduling of ads to ensure they are shown at optimal times.

### Automated Alerts

**Path:** `google-ads-scripts/automated-alerts`

This script sends automated alerts based on predefined conditions, such as sudden drops in impressions or clicks.

### Automated Bidding Script

**Path:** `google-ads-scripts/automated-bidding-script`

This script automates bidding strategies based on performance data to maximise ROI.

### Broken Link Checker Script

**Path:** `google-ads-scripts/broken-link-checker-script`

This script checks for broken links in your ads and alerts you to any issues.

### Budget Management Script

**Path:** `google-ads-scripts/budget-management-script`

This script helps manage your advertising budget by adjusting bids and budgets based on performance and spending limits.

### Keyword Management Script

**Path:** `google-ads-scripts/keyword-management-script`

This script automates the management of keywords, including adding, removing, and adjusting bids based on performance.

### Location-Based Bidding Script

**Path:** `google-ads-scripts/location-based-bidding-script`

This script adjusts bids based on the location of the user, allowing for more targeted advertising.

### Negative Keyword Script

**Path:** `google-ads-scripts/negative-keyword-script`

This script helps manage negative keywords to ensure your ads are not shown for irrelevant searches.

### Performance Reporting

**Path:** `google-ads-scripts/performance-reporting`

This script generates performance reports for your campaigns, providing insights into key metrics and trends.

### Stock Management Script

**Path:** `google-ads-scripts/stock-management-script`

This script adjusts ads based on stock levels, ensuring that ads are only shown for products that are in stock.

### Targeting Based on Distance Script

**Path:** `google-ads-scripts/targeting-based-on-distance-script`

This script adjusts targeting and bids based on the distance of the user from a specified location.

### Weather-Based Bidding Script

**Path:** `google-ads-scripts/weather-based-bidding-script`

This script adjusts bids based on weather conditions, allowing for more effective targeting based on external factors.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/web-lifter/google-ads-scripts.git
   ```
2. Navigate to the script directory you wish to use:
   ```bash
   cd google-ads-scripts/script-directory
   ```

## How to Upload a Script to Google Ads

### Prerequisites
1. Ensure you have a **Google Ads account** with admin-level access.
2. Locate the desired script in the repository and review its purpose and requirements.

### Steps to Upload a Script

1. **Access Google Ads Scripts**:
   - Log in to your Google Ads account.
   - Navigate to **Tools & Settings** (wrench icon) in the top-right corner.
   - Under "Bulk Actions," click on **Scripts**.

2. **Create a New Script**:
   - Click the **+ Script** button.
   - Assign a descriptive name to your script.

3. **Copy the Script Code**:
   - Open the desired script file in the repository (e.g., `google-ads-scripts/404-checking/404-checking.js`).
   - Copy the entire script code.

4. **Paste the Code into Google Ads**:
   - In the script editor within Google Ads, paste the copied code.

5. **Authorize the Script**:
   - Click the **Authorize** button above the script editor.
   - Grant the necessary permissions for the script to access and manage your Google Ads data.

6. **Preview the Script**:
   - Click **Preview** to simulate the script's functionality without making changes to your campaigns.
   - Review the log for any errors or warnings.

7. **Run the Script**:
   - If the preview runs successfully, click **Run** to execute the script.
   - You can also schedule the script to run automatically:
     - Click on the **Create Schedule** button.
     - Set the desired frequency and save.

### Best Practices
- **Test Thoroughly**: Always test scripts in preview mode before running them live.
- **Monitor Changes**: Review campaign performance after running scripts to ensure they produce the desired results.
- **Document Updates**: If you modify scripts for customization, document the changes for future reference.

## Contributing

We welcome contributions! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`
3. Make your changes and commit them: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature-branch-name`
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact

For any questions or inquiries, please contact [open-source@weblifter.com.au](mailto:open-source@weblifter.com.au).
