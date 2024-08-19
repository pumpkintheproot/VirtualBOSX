<p align="center">
  <img width="40%" height="40%" src="docs/assets/logo.png">
</p>


<h3 align="center">A very simple guide for running early versions of Mac OS X in VirtualBox</h3>

<h1 align="center">Contributing to the Documentation</h1>

<h4 align="center">If you have any changes or improvements you'd like to contribute for review and merge, to update misinformation or outdated information, as well as maybe even adding whole new pages, you can follow the general outline below to get a local copy of the documentation running.</h4>
<h6 align="center">Instructions written for Mac OS X hosts but is adoptable to other OS's.</h6>

</br>

1. Install/Update ``brew`` 
   - Visit https://brew.sh/ for instructions and information.

2. Install/Update ``ruby``
   - Once ``brew`` is installed, you can run ``brew install ruby`` in your terminal.
   - If using ZSH (any recent versions of macOS) Be sure to read the post install text as it suggest you should run the following command to export to PATH:
      - ``echo 'export PATH="/usr/local/opt/ruby/bin:$PATH"' >> ~/.zshrc``
      - Restart Terminal for changes to apply.

3. Install/Update ``gem`` and ``bundler``
   - Run ``gem update`` in your terminal window.
   - Run ``gem install bundler`` in your terminal window.

4. Fork DarwinKVM, git clone your fork, navigate to Docs directory.
   - ``git clone --recursive git@github.com:yourusername/DarwinKVM.git``
   - ``cd DarwinKVM/docs``

5. Installing Docs dependencies, and running the server.
   - Run ``bundle install`` in your terminal window.
   - Running ``bundle exec jekyll serve`` will build and run a live copy of the DarwinKVM docs on port 4000 by default.
   - To change the port, you can specify the IP address and port to run on, allowing local mobile devices to also connect and preview DKVM Docs.
      - ``bundle exec jekyll serve --host YOUR_IP_ADDRESS --port PORT``

<h4 align="center">You'll now be able to see the changes you make update live so you can work quickly and preview the final look of your Markdown files easily. Once you are done making your changes you can then proceed to submit a Pull Request for review, and eventual merge to Main.</h4>
<h6 align="center">A big thanks to all future contributors! ꩓</h6>
