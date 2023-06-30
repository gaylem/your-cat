# Tell me about your cat.

I built this form for Codesmith workshop assignment using basic HTML and CSS. I've deployed it using Surge and am collecting the data via SheetDB.

https://tell-me-about-your-cat.surge.sh/

The assignment instructions are below.

# Build With Code - Webforms, Persistent Storage, and Deployment Workshop

**Note**: _At the top right of this window, select “Open Preview” to see the formatted version of this README._

## Overview:

_Time to start solidifying our knowledge by actually getting our hands dirty in the code. These challenges will start off a bit more simplistic (covering basic pieces that we have discussed in the Build with Code workshop), then we will move into some more complex things by going into some more intricate web form techniques that were not explicitly covered in the workshop 😎_

## Challenge 1: Fork This Repo

Before we get started, we’ll need to “Fork” this repository/project. The act of forking a repository essentially copies the repo into your own account to begin working on it.

**Note:** if you are working in pairs only one of you needs to do this as you will both be working on the same repository.

1. Click on the blue button that says “Fork”
2. You may be prompted to log in or create a Repl account - follow the instructions on your screen.
3. A dialog box should popup, where you can name the repository and add a description. Rename it to include your own name, and then click “Fork Repl”

You’ll notice your repo’s name and your username will be displayed on the top left:

![Repl Image](./assets/repl_img.png)

## Challenge 2: Build Your HTML Form

1. Using the provided _index.html_ file, create 3 text `input` elements.
   - Note: you can view your rendered HTML by clicking the “play” button at the top of your screen. A web view of that file should display. Also, feel free to copy the url at the top of that web view tab and open a dedicated browser window to view your webpage in (this often works smoother than using the repl webview)
1. Search online for some documentation for input HTML elements. Explore the different “types” of inputs that exist (e.g. text, date, color, etc). Experiment 🧪 with them in your code.

1. Once you are finished exploring the different types of inputs, remove all existing inputs from your html.

1. Create 4 new text `input` elements to track the following:

   - First Name
   - Last Name
   - Email
   - Favorite Snack

1. Create a form element that will allow you to submit all the previous information to the `codesmith.io` server. What HTML elements do you need to add to make this possible?
   - **Note:** Check the “network” tab in your browser's developer tools to ensure the information is being sent successfully

## Challenge 3: Get Started with SheetDB

You have a form! You can take a user’s input!... but where can we store the information that the user submits? That’s where SheetDB comes in!

SheetDB can take our Form Inputs and store them in a Google Sheet (similar to Excel Spreadsheets), thus giving us a place to store our user’s inputs in the cloud. Let’s setup a SheetDB account:

1. Navigate to https://www.sheetdb.io/
2. Select “Log In Using Google Account”
   ![Login Image](./assets/sheetdb_login.png)
3. After completing log-in, select “Create new API”
   ![New API Image](./assets/sheetdb_new_api.png)
4. On the pop-up, select “Create new spreadsheet” and enter a name for your spreadsheet, then click “Create”.
   ![New Sheet Image](./assets/sheetdb_create_new_sheet.png)
5. On the next screen, enter the names of the inputs from your HTML Form(first_name, last_name, message) as columns in your spreadsheet. Then click “Create”
   ![Columns Image](./assets/sheetdb_columns.png)

## Challenge 4: Connect to SheetDB

Once you’ve set up your account following the steps above, you should see your Spreadsheet dashboard. Note the API Endpoint URL for sending data, as well as the Google Docs URL so that you can view the data in your spreadsheet.

- Modify your HTML Form to send data to SheetDB. Feel free to use the W3Schools documentation referenced above to guide you through the process.

![API Image](./assets/sheetdb_api.png)

After you’ve successfully connected to your sheet, you should see the Form inputs appearing in the Google Sheet after each submission.

## Challenge 5: Deploy Your App with Surge.sh

We have a form! We’re sending the input data to our own Google Sheet! Let’s share this with the world!

1. To do this, we’ll need to deploy our application online. There are many popular platforms to do this such as AWS (Amazon Web Services) or Google Cloud. For today, we’ll use Surge.sh which simplifies this process.
1. Check out the [Surge.sh Documentation](https://surge.sh/help/getting-started-with-surge), and follow the steps using the Shell in your Repl to deploy your app on the web!
1. Once completed post your deployed url in the #Build-with-Code [CSX Slack channel](https://join.slack.com/t/codesmithx/shared_invite/zt-1y42rf02e-QUoBemecgVaL7O6pnG85ig) to see if others can access! 🔥

## Bonus Challenges

- Adjust your form:

  - Rather than having your “Favorite Snack” input be a `text` input, create some preloaded options for snacks using radio buttons (i.e. use radio buttons for Favorite Snacks input so that the only options are “gummy bears”, twin snakes, Takis)
  - Add a favorite color option to your form that uses the input of type `color`
  - Add a birthday option to your form that uses the input of type `date`
  - Update your Email in a way that your form will not submit unless it is a valid email address (i.e. has an “@” symbol)

- Make your from more unique by adding CSS 🤯
- How can you augment your code so that when you successfully submit the form to Surge.sh you see something nicer than the default response? I.e. maybe a “success” page 🤔

### Once you’ve completed the challenge (or whenever you really feel like it lol), deploy once again through Surge.sh to see your changes live on the web!
