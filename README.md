# Create web crawler using puppeteer

## Workflow

The crawler will perform the following operation:

1. Go to https://lattice.is/dashboard
2. Go to Login Screen
3. Fill in your username / password
4. Click login button
5. Upon successful login, click on the user menu (upper right part of the page)
6. Click on sign out.
7. Browser close.

## Running your application

You application should be able to run using cli

`
node index.js`

## Completion details

1. Create your lattice account if you don't have one
2. Use your credentials to perform the worflow above
3. Do not hard code your credential in your js files, use dotenv and read your credentials from the env file.
4. We will use our own credentials when we test your work
5. We should be able to run your crawler through cli >> `node index.js`
6. When you are done, delete the node_modules folder, and your env file, then zip your project folder.
7. Please email your work to DJ.

## Other Details

1. Use puppeteer as your chromium library (https://www.npmjs.com/package/puppeteer)
2. For your helper packages or functions i.e lodash etc, feel free to use whichever your want
