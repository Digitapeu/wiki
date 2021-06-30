# WAM QA Testing

### What is WAM

**WAM** is a mobile (and web) app where people of all ages come and enjoy many hyper-casual games in a social, competitive environment.

You can find and install the app at the following URLs:
> iOS: https://apps.apple.com/gh/app/wam-for-hyper-casual-gamers/id1555705917

> Android: https://play.google.com/store/apps/details?id=com.digitap.wam

### What is the goal of QA

Our main goal with the manual QA testing is to ensure that people from different countries, with different internet connections/speeds and with different types of devices (high end or low end) have the same great experience when playing on WAM.

This being said, your role will be to make 1 or 2 bug reports per month (each in the limit of 2 hours per report). The report can be made on either one device type (Android/iOS), or even better, on both. 

### What are the deliverables

Your bug report needs to contain the following pieces:

- a detailed description of the bugs found;
- steps to reproduce;
- screenshots/video recordings of the bug;
- a full-lenght video recording of the whole testing session;
- device medium info (device type, OS version, app version, internet connection type, etc);

Also, try to:

- use Google Docs / Sheets in order to create the bug report (don't send txt files);
- upload the videos / screenshots on some file sharing service (google drive, dropbox, wetransfer);

### What you need to test

In general you will need to go through the following "test cases":

1. **Install** the app (iOS/Android)

2. **Registration**
When you open the app you will get on “the feed” which is something similar to TikTok. Here you can scroll up/down to see what tournaments are active right now on the platform. You won’t be able to play any of them if you don’t login / register. So go ahead and press a “LOG IN” button. Select your preferred method (you will need to test all of them):
    1. with email + pass
    2. with facebook
    3. with apple (if iOS)

3. **Onboarding** 
After you are logged in for the first time, you will see the terms and conditions where you need to click the “ACCEPT” button. Then the onboarding starts. You have some steps where we present you the app and you need to press "NEXT" and then“ENTER". Then you will need to“ENABLE" notifications, and you will arrive back on “the feed". 

	Feel free to explore the app at this moment, see all the tabs and sections, etc.

4. **Join your first tournament**
On “the feed” scroll and find a game tournament you’d like. To join a tournament, you’ll have to pay a small amount of “tapcoins” (which is our official in-app currency). You receive “tapcoins” when you register, when you win a tournament, invite a friend or when you buy a package.

	Press “Play for X coins” on a tournament, agree on paying the “tapcoins” 	amount by clicking “YES” in the popup and you should be redirected inside the game.

5. **Playing the first tournament/game**
When you get in the first game, you will see a quick tour of the buttons and functions: how can you access your “wallet” and the “rankings” for that tournament. After you get pass them, you can start playing.

	When you lose in the game, you will see a popup that allows you to “Continue for 50 tapcoins”,  “Continue with an Ad” or “Start from 0”. If you choose to continue by paying or watching an Ad, you will be able to continue the game from the last score. By getting a bigger score, you can get higher in the rankings and you will win a bigger prize at the end of the tournament.

	Play as much as you want, and try to enjoy it. Repeat all the steps on other tournaments as well. When you want to exit this game, press the little X in the right corner.

	**!! IMPORTANT: The focus of our testing is NOT to find bugs inside the games. So don’t look for that too much. Let us know if a game is unplayable or has some big issues – but don’t focus too much of your time on testing the games itself.**

6. **Check the tournament leaderboard**
For a tournament you entered and played, press on the ranking icon (inside the game, at the bottom right) or on “the feed” by pressing the “Rankings” icon/button. See if you are on the right position and you have the exact points you made in the game.

7. **Verify your email address** (only for accounts made with email/pass)
If you registered the account using an email address, go to your email and check if you received our verification email. If received, click on the link to verify your account. You will receive an extra 1000 tapcoins for doing this.

8. **Check your wallet and get the daily reward**
From “the feed”, press on the top where you see the current “tapcoins” amount. A new screen should open and you should see the current balance, a history button at the top left, and a list of packages you can purchase.

	Try to click on the “Collect 500 TapCoins” and you should receive a daily reward.

9. **Play a game / join a tournament from the “discovery”**
From the bottom menu of the app, press the search icon. You will get in our “Discovery” section where you can find all the games we have on the platform. Try to look for a game, open it and play it.

10. **Update profile**
Go to your profile by pressing the avatar icon from the bottom menu (the right side). The first time you go in the account screen, you will see a walkthrough that will present you the basic features. 

	Try to change your username, add a profile picture, change your name, add a social network profile, update your status.

	Browse the “tournaments” you are in.

	Feel free to test whatever else you find useful.

11. **Create private tournament**
From the bottom menu, press the big “+” button. Select a game from our list, give your private tournament a simple name, select the duration and the entry fee. Finish the creation of the tournament, and click “Invite Friends” to invite some friends on your private tournaments.

	After the tournament was created, you will be redirected in the tournament page and you can start playing. Submit a new score.

12. **Logout, Close app, Login again**
Test the flow of logging out, closing the app, reopening and login again with an account which already is created.

	Also test closing the app while logged in, and reopening the app to see if the session is persisted.

13. **Other mentions**
Feel free to test any other feature of the app (like chat, adding friends, see other user profiles, etc).

	Also try to let the app in background for a while then reopen it and start doing things.

------------

### Other info

We will send you a message every time we need a new bug report. Sometimes we’ll ask you to test a certain area of the app more than others.

As stated before any other input from you is welcomed. You should try to enjoy the app and at the end tell us what you think about it.

If you have any other question, please let us know.
