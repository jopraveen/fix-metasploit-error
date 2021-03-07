# fix-metasploit-error
If you get errors after updating your metasploit... then I hope this helps you :D

Add this to your /etc/hosts

```151.101.192.70 rubygems.org```

then install following stuffs

```sudo gem install bundler -v 2.2.5```

```bundle install```

```sudo gem update --system```

It will take few minutes to run so wait :)

Then run ```msfconsole``` 

Now your problem will be fixed :)
