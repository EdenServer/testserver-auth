# What is this repo for?

The official test server is for public use now. But we want users to make a reasonable effort to test things that are good for the public, not just collect and hoard information for their personal gain. Therefore, we currently have a simple system setup where any activity on the issues in the [community repo](https://github.com/EdenServer/community) will extend time that your machine is an active tester. All new users to the test server will have a fresh extension. Once you've authenticated your character you will need to occasionally perform an action (ex. create, comment on) an issue in the community repo so that your account stays considered an active tester. This system is designed to be balanced enough to encourage contribution at your own pace but ensure you're working on something for everyone's benefit.

# Setup Instructions

1. Create a character on the test server.
2. Use the `!testauth` command with your GitHub username like `!testauth godmode`. When you first log in you won't be able to zone, interact with NPCs or players.
3. The command will output a sequence of letters and numbers.
4. Visit the [Issues page](https://github.com/EdenServer/testauth/issues). Make sure you are signed in and comment on an existing issue with the code output by the `!testauth` command.
5. Within 30 seconds your character should receive a message in game that your account has been authorized.

# Troubleshooting

**My character was authorized but now it stopped working. What happened?**
Most likely, the system has determined you to be an inactive tester. Make sure that you are logged into the GitHub account you authenticated on. If you forget what account that was, you can `!testauth` without a username. It will output the name of the account you are authenticated on.

**I'm trying to authenticate but it's not working.**
Make sure that you are typing the right GitHub username with the `!testauth` command and the right authentication code on the [Issues page](https://github.com/EdenServer/testauth/issues).
