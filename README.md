# 🔥 Features

Better ChatGPT comes with a bundle of amazing features! Here are some of them:

- Proxy to bypass ChatGPT regional restrictions
- Prompt library
- Organize chats into folders
- Token count and pricing
- ShareGPT integration
- Custom model parameters (e.g. presence_penalty)
- Chat as user / assistant / system
- Edit, reorder and insert any messages, anywhere
- Chat title generator
- Save chat automatically to local storage
- Import / Export chat
- Download chat (markdown / image / json)
- Multiple language support (i18n)

# 🛠️ Usage

To get started, simply visit our website at <https://bettergpt.chat/>. There are 3 ways for you to start using Better ChatGPT.

1. Enter into the API menu your OpenAI API Key obtained from [OpenAI API Keys](https://platform.openai.com/account/api-keys).
2. Utilise the api endpoint proxy provided by [ayaka14732/ChatGPTAPIFree](https://github.com/ayaka14732/ChatGPTAPIFree) (if you are in a region with no access to ChatGPT)
3. Host your own API endpoint by following the instructions provided here: <https://github.com/ayaka14732/ChatGPTAPIFree>. Subsequently, enter the API endpoint into the API menu.

## Desktop App

Download the desktop app [here](https://github.com/christophercelaya/better-gpt/releases)

| OS      | Download  |
| ------- | --------- |
| Windows | .exe      |
| MacOS   | .dmg      |
| Linux   | .AppImage |

### Features:

- Unlimited local storage
- Runs locally (access Better ChatGPT even if the website is not accessible)

# 🛫 Host your own Instance

If you'd like to run your own instance of Better ChatGPT, you can easily do so by following these steps:

## Vercel
todo

## GitHub Pages

### Steps

1. Create a GitHub account (if you don't have one already)
1. Star this [repository](https://github.com/ztjhz/BetterChatGPT) ⭐️
1. Fork this [repository](https://github.com/ztjhz/BetterChatGPT)
1. In your forked repository, navigate to the `Settings` tab
   ![image](https://user-images.githubusercontent.com/59118459/223753577-9b6f8266-26e8-471b-8f45-a1a02fbab232.png)
1. In the left sidebar, click on `Pages` and in the right section, select `GitHub Actions` for `source`.
   ![image](https://user-images.githubusercontent.com/59118459/227568881-d8fb7baa-f890-4dee-8fc2-b6b429ba2098.png)
1. Now, click on `Actions`
   ![image](https://user-images.githubusercontent.com/59118459/223751928-cf2b91b9-4663-4a36-97de-5eb751b32c7e.png)
1. In the left sidebar, click on `Deploy to GitHub Pages`
   ![image](https://user-images.githubusercontent.com/59118459/223752459-183ec23f-72f5-436e-a088-e3386492b8cb.png)
1. Above the list of workflow runs, select `Run workflow`.
   ![image](https://user-images.githubusercontent.com/59118459/223753340-1270e038-d213-4d6f-938c-66a30dad7c88.png)
1. Navigate back to the `Settings` tab
   ![image](https://user-images.githubusercontent.com/59118459/223753577-9b6f8266-26e8-471b-8f45-a1a02fbab232.png)
1. In the left sidebar, click on `Pages` and in the right section. Then at the top section, you can see that "Your site is live at `XXX`".
   ![image](https://user-images.githubusercontent.com/59118459/227568881-d8fb7baa-f890-4dee-8fc2-b6b429ba2098.png)

### Running it locally

1. Ensure that you have the following installed:

   - [node.js](https://nodejs.org/en/)
   - [yarn](https://yarnpkg.com/) or [npm](https://www.npmjs.com/)

2. Clone this [repository](https://github.com/ztjhz/BetterChatGPT) by running `git clone https://github.com/ztjhz/BetterChatGPT.git`
3. Navigate into the directory by running `cd BetterChatGPT`
4. Run `yarn` or `npm install`, depending on whether you have yarn or npm installed.
5. Launch the app by running `yarn dev` or `npm run dev`
