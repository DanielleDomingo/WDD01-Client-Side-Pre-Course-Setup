# Set up your git config

Let git know what your user name and email address are.

1. Open your terminal. You can do this by typing `cmd-space`, then typing `Terminal` and pushing enter
2. In your terminal, copy and paste the below code snippet. Replace `"[YOUR NAME]"` and `user@developersinstitute.co.nz` with your name and email. Note that the name has quotes, and the email does not.

   ```bash
   git config --global user.name "Bill Murray"
   ```

   and then

   ```bash
   git config --global user.email user@developersinstitute.co.nz
   ```
3. To verify you have set up your config correctly, type the following into your Terminal and check the values returned match what you typed above:

   ```bash
   git config --global user.name
   ```

   You should see your name printed to the Terminal window. Now type:

   ```bash
   git config --global user.email
   ```

   You should see your email printed to the Terminal window.