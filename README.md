node-tweetbot
-------------

Your own markov-chain-based twitter buddy.

Idea
====

Attach a bot to your twitter account, and have it synthesize and post tweets on
a semi-regular interval based on your timeline.

Install
=======

```bash
$ npm install -g tweetbot
```

Configuration
=============

<<<<<<< HEAD
- Create a new app on [https://dev.twitter.com/apps/new](dev.twitter.com), and
=======
- Create a new app on [dev.twitter.com](https://dev.twitter.com/apps/new), and
>>>>>>> 42f630938ba0f4ebe73f0df01b8c4683d05b87a7
  then set **Access** to **Read and Write** on the **Settings** page.
- Request an **Access token** on the **Details** page of your app.
- Find a writable folder on your computer, change to it, and run:

    ```bash
    $ tweetbot-init
    ```
- Enter the credentials when prompted.
- Edit `tweetbot.json` to tweak defaults, if desired.

Usage
=====

```bash
$ tweetbot --conf=[path to tweetbot.json]
```

License
=======

MIT