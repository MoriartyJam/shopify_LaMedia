1.Project's Title

Create custome theme for shopify store.

2.Project Description

Work with the standard Shopify theme to enhance product options functionality, display relevant photos and price.

3.How to Install and Run the Project

To start project with Theme Kit:

Step 1: Install Theme Kit curl -s https://shopify.dev/themekit.py | sudo python3 Step 2: Get a Theme password Steps:

Ask the store owner or a staff member with the appropriate permissions to create a Theme password for you using the Theme Access app.
Go to your email inbox and open the invitation containing your Theme password.
In the invitation, click Get Theme password.
Copy the password. You’ll use it in the next step.

Step 3: Connect to an existing theme theme get --list --password=[your-password] --store="[your-store.myshopify.com]"

Step 4: Need to make clone repo from git https://github.com/MoriartyJam/shopify.store_unilime

Step 5: Set up your config file

mkdir [your-theme-name]

cd [your-theme-name]

theme get --password=[your-password] --store="[your-store.myshopify.com]" --themeid=[your-theme-id]

Step 6: Create a new theme

theme new --password=[your-password] --store="[your-store.myshopify.com]" --name=[theme name]

Step 7: Push updates to your theme

theme watch
