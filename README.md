# Vivino-Beta
Vivino-Beta
1) cucumber-appium-ruby- This framework to run automated BDD tests for Android and iOS.

2) Prerequisites
* Mac
* Android SDK
* Xcode installed
* Ruby 2.1.1
* Appium

3) Install appium and dependecies
This will install the command line version of appium.
    *brew install node
    *npm install -g appium@1.4.0
    *npm install wd
    
 4)Install bundler and the gems the framework is dependent on
    *gem install bundler
    *bundle install
    
 5) Running tests
    The Appium server should be running, either from terminal or GUI.
    *appium

6) Use Cucumber to run the tests.
    bundle exec cucumber -r features -p {CUCUMBER_PROFILE_HERE}

7) Cucumber profiles are listed in `cucumber.yml`.
