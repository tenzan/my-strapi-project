1. An app created with following options selected.

npx create-strapi-app@latest                                                                                                                                              pwsh   100  16:28:08 
Need to install the following packages:
create-strapi-app@5.5.0
Ok to proceed? (y)


 Strapi   v5.5.0 🚀 Let's create your new project

? What is the name of your project? (my-strapi-project)
? What is the name of your project? my-strapi-project

We can't find any auth credentials in your Strapi config.

Create a free account on Strapi Cloud and benefit from:

- ✦ Blazing-fast ✦ deployment for your projects
- ✦ Exclusive ✦ access to resources to make your project successful
- An ✦ Awesome ✦ community and full enjoyment of Strapi's ecosystem

Start your 14-day free trial now!


? Please log in or sign up.
? Please log in or sign up. Skip
? Do you want to use the default database (sqlite) ? (Y/n)
? Do you want to use the default database (sqlite) ? Yes
? Start with an example structure & data? (y/N)
? Start with an example structure & data? No
? Start with Typescript? (Y/n)
? Start with Typescript? Yes
? Install dependencies with npm? (Y/n)
? Install dependencies with npm? Yes
? Initialize a git repository? (Y/n)
? Initialize a git repository? Yes


2. Created 4 customer roles under `Users & Permissions plugin>Roles`:
    - custom-role-1 (with some random permissions on `Organization`)
    - custom-role-2 (with some random permissions on `Organization`)
    - custom-role-3 (with some random permissions on `Organization`)
    - custom-role-4 (with some random permissions on `Organization`)

4. Go to Content Manager

5. Click on `Create an entry` on User

6. Click on drop-down list

# Result

Only the 1st 4 roles displayed:
  - Authenticated
  - Public
  - custom-role-1
  - custom-role-2

# Expected result
  - drop-down list should show all available roles or provide a scroll bar
