# lib-crud-api
lib-crud-api library create-read-update-delete action with schema from core system (api)

{File Structure}
1.Create
2.Read
3.Update
4.Delete

core interpreter acction between user and server processing


Command 'goenv' not found, did you mean:

  command 'gbenv' from deb gbutils (5.7.1-1)

Try: sudo apt install <deb name>

sa@DESKTOP-SQLE148:~$ ls -la
total 52
drwxr-xr-x 1 sa   sa    4096 Dec 21 22:06 .
drwxr-xr-x 1 root root  4096 Dec  9 22:38 ..
-rw------- 1 sa   sa    6499 Dec 20 23:44 .bash_history
-rw-r--r-- 1 sa   sa     220 Oct 18 14:12 .bash_logout
-rw-r--r-- 1 sa   sa      23 Dec 13 14:36 .bash_profile
-rw-r--r-- 1 sa   sa    3947 Dec 12 23:37 .bashrc
drwxr-xr-x 1 sa   sa    4096 Dec 11 21:52 .bundle
drwxr-xr-x 1 sa   sa    4096 Dec 10 08:58 .cache
drwxr-xr-x 1 sa   sa    4096 Nov 14 16:47 .gem
-rw-r--r-- 1 sa   sa      86 Dec 13 02:05 .gitconfig
drwx------ 1 sa   sa    4096 Dec 20 23:26 .gnupg
-rw------- 1 sa   sa       4 Dec 20 23:27 .irb_history
drwxr-xr-x 1 sa   sa    4096 Oct 18 14:13 .landscape
-rw------- 1 sa   sa      20 Dec 13 16:05 .lesshst
-rw-r--r-- 1 sa   sa       0 Dec 21 21:46 .motd_shown
-rw------- 1 sa   sa       9 Nov 14 16:07 .node_repl_history
-rw-r--r-- 1 sa   sa     807 Oct 18 14:12 .profile
drwxr-xr-x 1 sa   sa    4096 Nov 14 16:08 .rbenv
drwxr-xr-x 1 sa   sa    4096 Dec 20 23:26 .rvm
drwx------ 1 sa   sa    4096 Nov 14 16:54 .ssh
-rw-r--r-- 1 sa   sa       0 Oct 18 14:44 .sudo_as_admin_successful
-rw------- 1 sa   sa   17027 Dec 21 22:06 .viminfo
-rw-r--r-- 1 sa   sa     116 Dec 13 15:00 .yarnrc
-rw-r--r-- 1 sa   sa      52 Dec 11 20:26 Gemfile
-rw-r--r-- 1 sa   sa     223 Dec 11 21:37 Gemfile.lock
drwxr-xr-x 1 sa   sa    4096 Dec 13 08:59 appname
-rw------- 1 sa   sa    3454 Dec 10 08:25 id_rsa.pub
-rw-r--r-- 1 sa   sa     753 Dec 10 08:25 id_rsa.pub.pub
drwxr-xr-x 1 sa   sa    4096 Dec 10 08:58 myapp
drwxr-xr-x 1 sa   sa    4096 Dec 10 09:41 myapp2
drwxr-xr-x 1 sa   sa    4096 Dec 20 22:24 myapp3
drwxr-xr-x 1 sa   sa    4096 Dec 21 22:06 myapp4
drwxr-xr-x 1 sa   sa    4096 Dec 11 21:42 postfix
drwxr-xr-x 1 sa   sa    4096 Dec 11 22:06 rails-web-api
drwxr-xr-x 1 sa   sa    4096 Dec 13 22:03 rails_graphql
drwxr-xr-x 1 sa   sa    4096 Dec 20 00:19 rails_react_recipe
-rw------- 1 sa   sa    3434 Nov 14 16:53 sa
-rw-r--r-- 1 sa   sa     746 Nov 14 16:53 sa.pub
drwxr-xr-x 1 sa   sa    4096 Dec 20 22:39 super-awesome-app
-rwxr-xr-x 1 sa   sa       0 Dec 11 21:30 testcron.sh
sa@DESKTOP-SQLE148:~$ vim Gemfile
sa@DESKTOP-SQLE148:~$ gem install rails
ERROR:  While executing gem ... (Gem::FilePermissionError)
    You don't have write permissions for the /var/lib/gems/2.7.0 directory.
sa@DESKTOP-SQLE148:~$ cd myapp4
sa@DESKTOP-SQLE148:~/myapp4$ ls -la
total 8
drwxr-xr-x 1 sa sa 4096 Dec 21 22:06 .
drwxr-xr-x 1 sa sa 4096 Dec 21 22:10 ..
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 .git
-rw-r--r-- 1 sa sa  695 Dec 21 22:02 .gitignore
-rw-r--r-- 1 sa sa   10 Dec 21 22:02 .ruby-version
-rw-r--r-- 1 sa sa 2261 Dec 21 22:06 Gemfile
-rw-r--r-- 1 sa sa  374 Dec 21 22:02 README.md
-rw-r--r-- 1 sa sa  227 Dec 21 22:02 Rakefile
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 app
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 bin
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 config
-rw-r--r-- 1 sa sa  130 Dec 21 22:02 config.ru
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 db
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 lib
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 log
-rw-r--r-- 1 sa sa   64 Dec 21 22:02 package.json
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 public
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 storage
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 test
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 tmp
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 vendor
sa@DESKTOP-SQLE148:~/myapp4$ rails server
Could not find gem 'rails (~> 7.0.0)' in any of the gem sources listed in your Gemfile.
Run `bundle install` to install missing gems.
sa@DESKTOP-SQLE148:~/myapp4$ cat Gemfile
source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
#gem 'rails', '~> 5.2.3'
# old
# gem "rails", "~> 6.1.4"
# # new
gem "rails", "~> 7.0.0"
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
sa@DESKTOP-SQLE148:~/myapp4$ vim Gemdfile
sa@DESKTOP-SQLE148:~/myapp4$ vim Gemfile
sa@DESKTOP-SQLE148:~/myapp4$ bundle update
Fetching gem metadata from https://rubygems.org/...........
Resolving dependencies..........
Using rake 13.0.6
Following files may not be writable, so sudo is needed:
  /usr/local/bin
  /var/lib/gems/2.7.0
  /var/lib/gems/2.7.0/build_info
  /var/lib/gems/2.7.0/cache
  /var/lib/gems/2.7.0/doc
  /var/lib/gems/2.7.0/extensions
  /var/lib/gems/2.7.0/gems
  /var/lib/gems/2.7.0/specifications
Using concurrent-ruby 1.1.10
Using minitest 5.16.3
Using erubi 1.11.0
Using builder 3.2.4
Using racc 1.6.1
Using rack 2.2.4
Using nio4r 2.5.8
Using websocket-extensions 0.1.5
Using marcel 1.0.2
Using mini_mime 1.1.2
Using date 3.3.3
Using crass 1.0.6
Using timeout 0.3.1
Using io-like 0.3.1
Using public_suffix 5.0.1
Using msgpack 1.6.0
Using bundler 2.3.26
Using byebug 11.1.3
Using matrix 0.4.2
Using regexp_parser 2.6.1
Using coffee-script-source 1.12.2
Using execjs 2.8.1
Using method_source 1.0.0
Using thor 1.2.1
Using bindex 0.8.1
Using ffi 1.15.5
Using rb-fsevent 0.11.2
Using ruby_dep 1.5.0
Using puma 3.12.6
Using rexml 3.2.5
Using rubyzip 2.3.2
Using tilt 2.0.11
Using websocket 1.2.9
Using spring 2.1.1
Using sqlite3 1.5.4 (x86_64-linux)
Using turbolinks-source 5.2.0
Using i18n 1.12.0
Using tzinfo 2.0.5
Using nokogiri 1.13.10 (x86_64-linux)
Using rack-test 2.0.2
Using sprockets 3.7.2
Using websocket-driver 0.7.5
Using net-protocol 0.2.1
Using archive-zip 0.12.0
Using addressable 2.8.1
Using bootsnap 1.15.0
Using coffee-script 2.4.1
Using uglifier 4.2.0
Using rb-inotify 0.10.1
Using selenium-webdriver 4.7.1
Using turbolinks 5.2.1
Using activesupport 7.0.4
Using loofah 2.19.1
Fetching xpath 3.2.0
Installing zeitwerk 2.6.6


Your user account isn't allowed to install to the system RubyGems.
  You can cancel this installation and run:

      bundle config set --local path 'vendor/bundle'
      bundle install

  to install the gems into ./vendor/bundle/, or you can enter your password
  and install the bundled gems to RubyGems using sudo.

  Password:


Your user account isn't allowed to install to the system RubyGems.
  You can cancel this installation and run:

      bundle config set --local path 'vendor/bundle'
      bundle install

  to install the gems into ./vendor/bundle/, or you can enter your password
  and install the bundled gems to RubyGems using sudo.

  Password:
Sorry, try again.


Your user account isn't allowed to install to the system RubyGems.
  You can cancel this installation and run:

      bundle config set --local path 'vendor/bundle'
      bundle install

  to install the gems into ./vendor/bundle/, or you can enter your password
  and install the bundled gems to RubyGems using sudo.

  Password:
Sorry, try again.


Your user account isn't allowed to install to the system RubyGems.
  You can cancel this installation and run:

      bundle config set --local path 'vendor/bundle'
      bundle install

  to install the gems into ./vendor/bundle/, or you can enter your password
  and install the bundled gems to RubyGems using sudo.

  Password:
sudo: 3 incorrect password attempts
Fetching net-imap 0.3.3


Your user account isn't allowed to install to the system RubyGems.
  You can cancel this installation and run:

      bundle config set --local path 'vendor/bundle'
      bundle install

  to install the gems into ./vendor/bundle/, or you can enter your password
  and install the bundled gems to RubyGems using sudo.

  Password:
Sorry, try again.


Your user account isn't allowed to install to the system RubyGems.
  You can cancel this installation and run:

      bundle config set --local path 'vendor/bundle'
      bundle install

  to install the gems into ./vendor/bundle/, or you can enter your password
  and install the bundled gems to RubyGems using sudo.

  Password:
Sorry, try again.


Your user account isn't allowed to install to the system RubyGems.
  You can cancel this installation and run:

      bundle config set --local path 'vendor/bundle'
      bundle install

  to install the gems into ./vendor/bundle/, or you can enter your password
  and install the bundled gems to RubyGems using sudo.

  Password:
Installing net-imap 0.3.3
Fetching net-pop 0.1.2
Installing net-pop 0.1.2
Fetching net-smtp 0.3.3
Fetching chromedriver-helper 2.1.1
Installing net-smtp 0.3.3
Installing chromedriver-helper 2.1.1
Fetching listen 3.1.5
Fetching sass-listen 4.0.0
Installing listen 3.1.5
Installing sass-listen 4.0.0
Installing rails-dom-testing 2.0.3
Using globalid 1.0.0
Using activemodel 7.0.4
Fetching rails-html-sanitizer 1.4.4
Installing rails-html-sanitizer 1.4.4
--- ERROR REPORT TEMPLATE -------------------------------------------------------

```
Gem::Package::FormatError: No such file or directory @ rb_sysopen - /var/lib/gems/2.7.0/cache/xpath-3.2.0.gem
  /usr/lib/ruby/2.7.0/rubygems/package.rb:637:in `rescue in verify'
  /usr/lib/ruby/2.7.0/rubygems/package.rb:614:in `verify'
  /usr/lib/ruby/2.7.0/rubygems/package.rb:599:in `spec'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/rubygems_gem_installer.rb:95:in `spec'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/source/rubygems.rb:190:in `install'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/installer/gem_installer.rb:54:in `install'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/installer/gem_installer.rb:16:in `install_from_spec'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/installer/parallel_installer.rb:186:in `do_install'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/installer/parallel_installer.rb:177:in `block in worker_pool'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/worker.rb:62:in `apply_func'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/worker.rb:57:in `block in process_queue'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/worker.rb:54:in `loop'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/worker.rb:54:in `process_queue'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/worker.rb:91:in `block (2 levels) in create_threads'
Errno::ENOENT: No such file or directory @ rb_sysopen - /var/lib/gems/2.7.0/cache/xpath-3.2.0.gem
  /usr/lib/ruby/2.7.0/rubygems/package/file_source.rb:30:in `initialize'
  /usr/lib/ruby/2.7.0/rubygems/package/file_source.rb:30:in `open'
  /usr/lib/ruby/2.7.0/rubygems/package/file_source.rb:30:in `with_read_io'
  /usr/lib/ruby/2.7.0/rubygems/package.rb:618:in `verify'
  /usr/lib/ruby/2.7.0/rubygems/package.rb:599:in `spec'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/rubygems_gem_installer.rb:95:in `spec'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/source/rubygems.rb:190:in `install'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/installer/gem_installer.rb:54:in `install'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/installer/gem_installer.rb:16:in `install_from_spec'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/installer/parallel_installer.rb:186:in `do_install'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/installer/parallel_installer.rb:177:in `block in worker_pool'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/worker.rb:62:in `apply_func'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/worker.rb:57:in `block in process_queue'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/worker.rb:54:in `loop'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/worker.rb:54:in `process_queue'
  /var/lib/gems/2.7.0/gems/bundler-2.3.26/lib/bundler/worker.rb:91:in `block (2 levels) in create_threads'

```

## Environment

```
Bundler       2.3.26
  Platforms   ruby, x86_64-linux
Ruby          2.7.0p0 (2019-12-25 revision 647ee6f091eafcce70ffb75ddf7e121e192ab217) [x86_64-linux]
  Full Path   /usr/bin/ruby2.7
  Config Dir  /etc
RubyGems      3.1.2
  Gem Home    /var/lib/gems/2.7.0
  Gem Path    /home/sa/.gem/ruby/2.7.0:/var/lib/gems/2.7.0:/usr/lib/ruby/gems/2.7.0:/usr/share/rubygems-integration/2.7.0:/usr/share/rubygems-integration/all:/usr/lib/x86_64-linux-gnu/rubygems-integration/2.7.0
  User Home   /home/sa
  User Path   /home/sa/.gem/ruby/2.7.0
  Bin Dir     /usr/local/bin
OpenSSL
  Compiled    OpenSSL 1.1.1f  31 Mar 2020
  Loaded      OpenSSL 1.1.1f  31 Mar 2020
  Cert File   /usr/lib/ssl/cert.pem
  Cert Dir    /usr/lib/ssl/certs
Tools
  Git         2.25.1
  RVM         not installed
  rbenv       rbenv 1.1.1
  chruby      not installed
```

## Bundler Build Metadata

```
Built At          2022-11-17
Git SHA           23ec5b8501
Released Version  true
```

## Gemfile

### Gemfile

```ruby
source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
#gem 'rails', '~> 5.2.3'
# old
# gem "rails", "~> 6.1.4"
# # new
gem 'rails', '~> 7.0.0'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
```

### Gemfile.lock

```
<No /home/sa/myapp4/Gemfile.lock found>
```

--- TEMPLATE END ----------------------------------------------------------------

Unfortunately, an unexpected error occurred, and Bundler cannot continue.

First, try this link to see if there are any existing issue reports for this error:
https://github.com/rubygems/rubygems/search?q=No+such+file+or+directory+%40+rb_sysopen+-+%2Fvar%2Flib%2Fgems%2F2.7.0%2Fcache%2Fxpath-3.2.0.gem&type=Issues

If there aren't any reports for this error yet, please fill in the new issue form located at https://github.com/rubygems/rubygems/issues/new?labels=Bundler&template=bundler-related-issue.md, and copy and paste the report template above in there.
sa@DESKTOP-SQLE148:~/myapp4$ bundle install
Fetching gem metadata from https://rubygems.org/...........
Resolving dependencies.........
Using rake 13.0.6
Following files may not be writable, so sudo is needed:
  /usr/local/bin
  /var/lib/gems/2.7.0
  /var/lib/gems/2.7.0/build_info
  /var/lib/gems/2.7.0/cache
  /var/lib/gems/2.7.0/doc
  /var/lib/gems/2.7.0/extensions
  /var/lib/gems/2.7.0/gems
  /var/lib/gems/2.7.0/specifications
Using concurrent-ruby 1.1.10
Using minitest 5.16.3
Using erubi 1.11.0
Using builder 3.2.4
Using racc 1.6.1
Using crass 1.0.6
Using nio4r 2.5.8
Using rack 2.2.4
Using websocket-extensions 0.1.5
Using marcel 1.0.2
Using mini_mime 1.1.2
Using date 3.3.3
Using public_suffix 5.0.1
Using io-like 0.3.1
Using timeout 0.3.1
Using msgpack 1.6.0
Using bundler 2.3.26
Using byebug 11.1.3
Using matrix 0.4.2
Using regexp_parser 2.6.1
Using coffee-script-source 1.12.2
Using execjs 2.8.1
Using method_source 1.0.0
Using thor 1.2.1
Using bindex 0.8.1
Using zeitwerk 2.6.6
Using ffi 1.15.5
Using ruby_dep 1.5.0
Using puma 3.12.6
Using rb-fsevent 0.11.2
Using rexml 3.2.5
Using tilt 2.0.11
Using websocket 1.2.9
Using spring 2.1.1
Using sqlite3 1.5.4 (x86_64-linux)
Using turbolinks-source 5.2.0
Using i18n 1.12.0
Using tzinfo 2.0.5
Using nokogiri 1.13.10 (x86_64-linux)
Using rack-test 2.0.2
Using sprockets 3.7.2
Using websocket-driver 0.7.5
Using addressable 2.8.1
Using archive-zip 0.12.0
Using net-protocol 0.2.1
Using bootsnap 1.15.0
Using coffee-script 2.4.1
Using uglifier 4.2.0
Using rubyzip 2.3.2
Using turbolinks 5.2.1
Using activesupport 7.0.4
Using loofah 2.19.1
Using rb-inotify 0.10.1
Using chromedriver-helper 2.1.1
Using net-imap 0.3.3
Using net-pop 0.1.2
Using net-smtp 0.3.3
Using selenium-webdriver 4.7.1
Using rails-dom-testing 2.0.3
Using globalid 1.0.0
Using activemodel 7.0.4
Using rails-html-sanitizer 1.4.4
Using listen 3.1.5
Fetching xpath 3.2.0
Using sass-listen 4.0.0
Using mail 2.8.0
Using activejob 7.0.4
Using activerecord 7.0.4
Using actionview 7.0.4
Fetching spring-watcher-listen 2.0.1


Your user account isn't allowed to install to the system RubyGems.
  You can cancel this installation and run:

      bundle config set --local path 'vendor/bundle'
      bundle install

  to install the gems into ./vendor/bundle/, or you can enter your password
  and install the bundled gems to RubyGems using sudo.

  Password:
Installing spring-watcher-listen 2.0.1
Installing xpath 3.2.0
Fetching sass 3.7.4
Using actionpack 7.0.4
Fetching jbuilder 2.11.5
Installing sass 3.7.4
Installing jbuilder 2.11.5
Fetching capybara 3.38.0
Installing capybara 3.38.0
Installing actioncable 7.0.4
Installing activestorage 7.0.4
Using actionmailer 7.0.4
Installing railties 7.0.4
Fetching sprockets-rails 3.4.2
Installing sprockets-rails 3.4.2
Installing actionmailbox 7.0.4
Installing actiontext 7.0.4
Fetching coffee-rails 4.2.2
Installing coffee-rails 4.2.2
Fetching sass-rails 5.1.0
Fetching web-console 4.2.0
Installing sass-rails 5.1.0
Installing web-console 4.2.0
Installing rails 7.0.4
Bundle complete! 18 Gemfile dependencies, 86 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
Post-install message from sass:

Ruby Sass has reached end-of-life and should no longer be used.

* If you use Sass as a command-line tool, we recommend using Dart Sass, the new
  primary implementation: https://sass-lang.com/install

* If you use Sass as a plug-in for a Ruby web framework, we recommend using the
  sassc gem: https://github.com/sass/sassc-ruby#readme

* For more details, please refer to the Sass blog:
  https://sass-lang.com/blog/posts/7828841

sa@DESKTOP-SQLE148:~/myapp4$ cd bin
sa@DESKTOP-SQLE148:~/myapp4/bin$ ls -la
total 8
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 .
drwxr-xr-x 1 sa sa 4096 Dec 21 22:17 ..
-rwxr-xr-x 1 sa sa  125 Dec 21 22:02 bundle
-rwxr-xr-x 1 sa sa  141 Dec 21 22:02 rails
-rwxr-xr-x 1 sa sa   90 Dec 21 22:02 rake
-rwxr-xr-x 1 sa sa  957 Dec 21 22:02 setup
-rwxr-xr-x 1 sa sa  819 Dec 21 22:02 update
-rwxr-xr-x 1 sa sa  303 Dec 21 22:02 yarn
sa@DESKTOP-SQLE148:~/myapp4/bin$ cd ..
sa@DESKTOP-SQLE148:~/myapp4$ bin/rails app:update
    conflict  config/boot.rb
Overwrite /home/sa/myapp4/config/boot.rb? (enter "h" for help) [Ynaqdhm] h
        Y - yes, overwrite
        n - no, do not overwrite
        a - all, overwrite this and all others
        q - quit, abort
        d - diff, show the differences between the old and the new
        h - help, show this help
        m - merge, run merge tool
Overwrite /home/sa/myapp4/config/boot.rb? (enter "h" for help) [Ynaqdhm] a
       force  config/boot.rb
       exist  config
    conflict  config/application.rb
       force  config/application.rb
    conflict  config/environment.rb
       force  config/environment.rb
       exist  config/environments
    conflict  config/environments/development.rb
       force  config/environments/development.rb
    conflict  config/environments/production.rb
       force  config/environments/production.rb
    conflict  config/environments/test.rb
       force  config/environments/test.rb
       exist  config/initializers
    conflict  config/initializers/assets.rb
       force  config/initializers/assets.rb
    conflict  config/initializers/content_security_policy.rb
       force  config/initializers/content_security_policy.rb
      create  config/initializers/cors.rb
    conflict  config/initializers/filter_parameter_logging.rb
       force  config/initializers/filter_parameter_logging.rb
    conflict  config/initializers/inflections.rb
       force  config/initializers/inflections.rb
      create  config/initializers/new_framework_defaults_7_0.rb
      create  config/initializers/permissions_policy.rb
      remove  config/initializers/cors.rb
File unchanged! The supplied flag value not found!  config/application.rb
       exist  bin
    conflict  bin/rails
       force  bin/rails
    conflict  bin/rake
       force  bin/rake
    conflict  bin/setup
       force  bin/setup
       rails  active_storage:update
Copied migration 20221221152520_add_service_name_to_active_storage_blobs.active_storage.rb from active_storage
Copied migration 20221221152521_create_active_storage_variant_records.active_storage.rb from active_storage
Copied migration 20221221152522_remove_not_null_on_active_storage_blobs_checksum.active_storage.rb from active_storage

After this, check Rails upgrade guide at https://guides.rubyonrails.org/upgrading_ruby_on_rails.html for more details about upgrading your app.
sa@DESKTOP-SQLE148:~/myapp4$ rails db:migrate
== 20221221152520 AddServiceNameToActiveStorageBlobs: migrating ===============
-- table_exists?(:active_storage_blobs)
   -> 0.0041s
== 20221221152520 AddServiceNameToActiveStorageBlobs: migrated (0.0051s) ======

== 20221221152521 CreateActiveStorageVariantRecords: migrating ================
-- table_exists?(:active_storage_blobs)
   -> 0.0041s
== 20221221152521 CreateActiveStorageVariantRecords: migrated (0.0096s) =======

== 20221221152522 RemoveNotNullOnActiveStorageBlobsChecksum: migrating ========
-- table_exists?(:active_storage_blobs)
   -> 0.0050s
== 20221221152522 RemoveNotNullOnActiveStorageBlobsChecksum: migrated (0.0068s)

sa@DESKTOP-SQLE148:~/myapp4$ cd config
sa@DESKTOP-SQLE148:~/myapp4/config$ cat initiallizers
cat: initiallizers: No such file or directory
sa@DESKTOP-SQLE148:~/myapp4/config$ ls -la
total 12
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 .
drwxr-xr-x 1 sa sa 4096 Dec 21 22:17 ..
-rw-r--r-- 1 sa sa 1080 Dec 21 22:24 application.rb
-rw-r--r-- 1 sa sa  207 Dec 21 22:24 boot.rb
-rw-r--r-- 1 sa sa  188 Dec 21 22:02 cable.yml
-rw-r--r-- 1 sa sa  464 Dec 21 22:02 credentials.yml.enc
-rw-r--r-- 1 sa sa  594 Dec 21 22:02 database.yml
-rw-r--r-- 1 sa sa  128 Dec 21 22:24 environment.rb
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 environments
drwxr-xr-x 1 sa sa 4096 Dec 21 22:24 initializers
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 locales
-rw------- 1 sa sa   32 Dec 21 22:02 master.key
-rw-r--r-- 1 sa sa 1397 Dec 21 22:02 puma.rb
-rw-r--r-- 1 sa sa  139 Dec 21 22:02 routes.rb
-rw-r--r-- 1 sa sa  111 Dec 21 22:02 spring.rb
-rw-r--r-- 1 sa sa 1093 Dec 21 22:02 storage.yml
sa@DESKTOP-SQLE148:~/myapp4/config$ cd initializers
sa@DESKTOP-SQLE148:~/myapp4/config/initializers$ dir
application_controller_renderer.rb  inflections.rb
assets.rb                           mime_types.rb
backtrace_silencers.rb              new_framework_defaults_7_0.rb
content_security_policy.rb          permissions_policy.rb
cookies_serializer.rb               wrap_parameters.rb
filter_parameter_logging.rb
sa@DESKTOP-SQLE148:~/myapp4/config/initializers$ ls -la
total 24
drwxr-xr-x 1 sa sa 4096 Dec 21 22:24 .
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 ..
-rw-r--r-- 1 sa sa  216 Dec 21 22:02 application_controller_renderer.rb
-rw-r--r-- 1 sa sa  502 Dec 21 22:24 assets.rb
-rw-r--r-- 1 sa sa  404 Dec 21 22:02 backtrace_silencers.rb
-rw-r--r-- 1 sa sa 1044 Dec 21 22:24 content_security_policy.rb
-rw-r--r-- 1 sa sa  244 Dec 21 22:02 cookies_serializer.rb
-rw-r--r-- 1 sa sa  396 Dec 21 22:24 filter_parameter_logging.rb
-rw-r--r-- 1 sa sa  649 Dec 21 22:24 inflections.rb
-rw-r--r-- 1 sa sa  156 Dec 21 22:02 mime_types.rb
-rw-r--r-- 1 sa sa 6757 Dec 21 22:24 new_framework_defaults_7_0.rb
-rw-r--r-- 1 sa sa  384 Dec 21 22:24 permissions_policy.rb
-rw-r--r-- 1 sa sa  485 Dec 21 22:02 wrap_parameters.rb
sa@DESKTOP-SQLE148:~/myapp4/config/initializers$ cat application_controller_renderer.rb
# Be sure to restart your server when you modify this file.

# ActiveSupport::Reloader.to_prepare do
#   ApplicationController.renderer.defaults.merge!(
#     http_host: 'example.org',
#     https: false
#   )
# end
sa@DESKTOP-SQLE148:~/myapp4/config/initializers$ cat new_framework_defaults_7_0.rb
# Be sure to restart your server when you modify this file.
#
# This file eases your Rails 7.0 framework defaults upgrade.
#
# Uncomment each configuration one by one to switch to the new default.
# Once your application is ready to run with all new defaults, you can remove
# this file and set the `config.load_defaults` to `7.0`.
#
# Read the Guide for Upgrading Ruby on Rails for more info on each option.
# https://guides.rubyonrails.org/upgrading_ruby_on_rails.html

# `button_to` view helper will render `<button>` element, regardless of whether
# or not the content is passed as the first argument or as a block.
# Rails.application.config.action_view.button_to_generates_button_tag = true

# `stylesheet_link_tag` view helper will not render the media attribute by default.
# Rails.application.config.action_view.apply_stylesheet_media_default = false

# Change the digest class for the key generators to `OpenSSL::Digest::SHA256`.
# Changing this default means invalidate all encrypted messages generated by
# your application and, all the encrypted cookies. Only change this after you
# rotated all the messages using the key rotator.
#
# See upgrading guide for more information on how to build a rotator.
# https://guides.rubyonrails.org/v7.0/upgrading_ruby_on_rails.html
# Rails.application.config.active_support.key_generator_hash_digest_class = OpenSSL::Digest::SHA256

# Change the digest class for ActiveSupport::Digest.
# Changing this default means that for example Etags change and
# various cache keys leading to cache invalidation.
# Rails.application.config.active_support.hash_digest_class = OpenSSL::Digest::SHA256

# Don't override ActiveSupport::TimeWithZone.name and use the default Ruby
# implementation.
# Rails.application.config.active_support.remove_deprecated_time_with_zone_name = true

# Calls `Rails.application.executor.wrap` around test cases.
# This makes test cases behave closer to an actual request or job.
# Several features that are normally disabled in test, such as Active Record query cache
# and asynchronous queries will then be enabled.
# Rails.application.config.active_support.executor_around_test_case = true

# Define the isolation level of most of Rails internal state.
# If you use a fiber based server or job processor, you should set it to `:fiber`.
# Otherwise the default of `:thread` if preferable.
# Rails.application.config.active_support.isolation_level = :thread

# Set both the `:open_timeout` and `:read_timeout` values for `:smtp` delivery method.
# Rails.application.config.action_mailer.smtp_timeout = 5

# The ActiveStorage video previewer will now use scene change detection to generate
# better preview images (rather than the previous default of using the first frame
# of the video).
# Rails.application.config.active_storage.video_preview_arguments =
#   "-vf 'select=eq(n\\,0)+eq(key\\,1)+gt(scene\\,0.015),loop=loop=-1:size=2,trim=start_frame=1' -frames:v 1 -f image2"

# Automatically infer `inverse_of` for associations with a scope.
# Rails.application.config.active_record.automatic_scope_inversing = true

# Raise when running tests if fixtures contained foreign key violations
# Rails.application.config.active_record.verify_foreign_keys_for_fixtures = true

# Disable partial inserts.
# This default means that all columns will be referenced in INSERT queries
# regardless of whether they have a default or not.
# Rails.application.config.active_record.partial_inserts = false

# Protect from open redirect attacks in `redirect_back_or_to` and `redirect_to`.
# Rails.application.config.action_controller.raise_on_open_redirects = true

# Change the variant processor for Active Storage.
# Changing this default means updating all places in your code that
# generate variants to use image processing macros and ruby-vips
# operations. See the upgrading guide for detail on the changes required.
# The `:mini_magick` option is not deprecated; it's fine to keep using it.
# Rails.application.config.active_storage.variant_processor = :vips

# Enable parameter wrapping for JSON.
# Previously this was set in an initializer. It's fine to keep using that initializer if you've customized it.
# To disable parameter wrapping entirely, set this config to `false`.
# Rails.application.config.action_controller.wrap_parameters_by_default = true

# Specifies whether generated namespaced UUIDs follow the RFC 4122 standard for namespace IDs provided as a
# `String` to `Digest::UUID.uuid_v3` or `Digest::UUID.uuid_v5` method calls.
#
# See https://guides.rubyonrails.org/configuring.html#config-active-support-use-rfc4122-namespaced-uuids for
# more information.
# Rails.application.config.active_support.use_rfc4122_namespaced_uuids = true

# Change the default headers to disable browsers' flawed legacy XSS protection.
# Rails.application.config.action_dispatch.default_headers = {
#   "X-Frame-Options" => "SAMEORIGIN",
#   "X-XSS-Protection" => "0",
#   "X-Content-Type-Options" => "nosniff",
#   "X-Download-Options" => "noopen",
#   "X-Permitted-Cross-Domain-Policies" => "none",
#   "Referrer-Policy" => "strict-origin-when-cross-origin"
# }


# ** Please read carefully, this must be configured in config/application.rb **
# Change the format of the cache entry.
# Changing this default means that all new cache entries added to the cache
# will have a different format that is not supported by Rails 6.1 applications.
# Only change this value after your application is fully deployed to Rails 7.0
# and you have no plans to rollback.
# When you're ready to change format, add this to `config/application.rb` (NOT this file):
#  config.active_support.cache_format_version = 7.0


# Cookie serializer: 2 options
#
# If you're upgrading and haven't set `cookies_serializer` previously, your cookie serializer
# is `:marshal`. The default for new apps is `:json`.
#
# Rails.application.config.action_dispatch.cookies_serializer = :json
#
#
# To migrate an existing application to the `:json` serializer, use the `:hybrid` option.
#
# Rails transparently deserializes existing (Marshal-serialized) cookies on read and
# re-writes them in the JSON format.
#
# It is fine to use `:hybrid` long term; you should do that until you're confident *all* your cookies
# have been converted to JSON. To keep using `:hybrid` long term, move this config to its own
# initializer or to `config/application.rb`.
#
# Rails.application.config.action_dispatch.cookies_serializer = :hybrid
#
#
# If your cookies can't yet be serialized to JSON, keep using `:marshal` for backward-compatibility.
#
# If you have configured the serializer elsewhere, you can remove this section of the file.
#
# See https://guides.rubyonrails.org/action_controller_overview.html#cookies for more information.
sa@DESKTOP-SQLE148:~/myapp4/config/initializers$ vim new_framework_defaults_7.0.rb
sa@DESKTOP-SQLE148:~/myapp4/config/initializers$ ls -la
total 24
drwxr-xr-x 1 sa sa 4096 Dec 21 22:30 .
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 ..
-rw-r--r-- 1 sa sa  216 Dec 21 22:02 application_controller_renderer.rb
-rw-r--r-- 1 sa sa  502 Dec 21 22:24 assets.rb
-rw-r--r-- 1 sa sa  404 Dec 21 22:02 backtrace_silencers.rb
-rw-r--r-- 1 sa sa 1044 Dec 21 22:24 content_security_policy.rb
-rw-r--r-- 1 sa sa  244 Dec 21 22:02 cookies_serializer.rb
-rw-r--r-- 1 sa sa  396 Dec 21 22:24 filter_parameter_logging.rb
-rw-r--r-- 1 sa sa  649 Dec 21 22:24 inflections.rb
-rw-r--r-- 1 sa sa  156 Dec 21 22:02 mime_types.rb
-rw-r--r-- 1 sa sa 6757 Dec 21 22:24 new_framework_defaults_7_0.rb
-rw-r--r-- 1 sa sa  384 Dec 21 22:24 permissions_policy.rb
-rw-r--r-- 1 sa sa  485 Dec 21 22:02 wrap_parameters.rb
sa@DESKTOP-SQLE148:~/myapp4/config/initializers$ vim new_framework_defaults_7_0.rb
sa@DESKTOP-SQLE148:~/myapp4/config/initializers$ cd ..
sa@DESKTOP-SQLE148:~/myapp4/config$ ls ..
Gemfile       README.md  app  config     db   log           public   test  vendor
Gemfile.lock  Rakefile   bin  config.ru  lib  package.json  storage  tmp
sa@DESKTOP-SQLE148:~/myapp4/config$ cd ..
sa@DESKTOP-SQLE148:~/myapp4$ cd bin
sa@DESKTOP-SQLE148:~/myapp4/bin$ ls -la
total 8
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 .
drwxr-xr-x 1 sa sa 4096 Dec 21 22:17 ..
-rwxr-xr-x 1 sa sa  125 Dec 21 22:02 bundle
-rwxr-xr-x 1 sa sa  141 Dec 21 22:24 rails
-rwxr-xr-x 1 sa sa   90 Dec 21 22:24 rake
-rwxr-xr-x 1 sa sa 1010 Dec 21 22:24 setup
-rwxr-xr-x 1 sa sa  819 Dec 21 22:02 update
-rwxr-xr-x 1 sa sa  303 Dec 21 22:02 yarn
sa@DESKTOP-SQLE148:~/myapp4/bin$ rails server
=> Booting Puma
=> Rails 7.0.4 application starting in development
=> Run `bin/rails server --help` for more startup options
Puma starting in single mode...
* Version 3.12.6 (ruby 2.7.0-p0), codename: Llamas in Pajamas
* Min threads: 5, max threads: 5
* Environment: development
* Listening on tcp://localhost:3000
Use Ctrl-C to stop
DEPRECATION WARNING: Non-URL-safe CSRF tokens are deprecated. Use 6.1 defaults or above. (called from block (3 levels) in <class:Railtie> at /var/lib/gems/2.7.0/gems/actionpack-7.0.4/lib/action_controller/railtie.rb:80)
DEPRECATION WARNING: Using legacy connection handling is deprecated. Please set
`legacy_connection_handling` to `false` in your application.

The new connection handling does not support `connection_handlers`
getter and setter.

Read more about how to migrate at: https://guides.rubyonrails.org/active_record_multiple_databases.html#migrate-to-the-new-connection-handling
 (called from block (2 levels) in <class:Railtie> at /var/lib/gems/2.7.0/gems/activerecord-7.0.4/lib/active_record/railtie.rb:264)
Started GET "/" for ::1 at 2022-12-21 22:46:42 +0700
  ActiveRecord::SchemaMigration Pluck (0.8ms)  SELECT "schema_migrations"."version" FROM "schema_migrations" ORDER BY "schema_migrations"."version" ASC
Processing by Rails::WelcomeController#index as HTML
  Rendering /var/lib/gems/2.7.0/gems/railties-7.0.4/lib/rails/templates/rails/welcome/index.html.erb
  Rendered /var/lib/gems/2.7.0/gems/railties-7.0.4/lib/rails/templates/rails/welcome/index.html.erb (Duration: 3256.4ms | Allocations: 483)
Completed 200 OK in 5006ms (Views: 3881.7ms | ActiveRecord: 0.0ms | Allocations: 4113)


^C^C
- Gracefully stopping, waiting for requests to finish
=== puma shutdown: 2022-12-21 23:29:17 +0700 ===
- Goodbye!
Exiting
sa@DESKTOP-SQLE148:~/myapp4/bin$
sa@DESKTOP-SQLE148:~/myapp4/bin$ git
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone             Clone a repository into a new directory
   init              Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add               Add file contents to the index
   mv                Move or rename a file, a directory, or a symlink
   restore           Restore working tree files
   rm                Remove files from the working tree and from the index
   sparse-checkout   Initialize and modify the sparse-checkout

examine the history and state (see also: git help revisions)
   bisect            Use binary search to find the commit that introduced a bug
   diff              Show changes between commits, commit and working tree, etc
   grep              Print lines matching a pattern
   log               Show commit logs
   show              Show various types of objects
   status            Show the working tree status

grow, mark and tweak your common history
   branch            List, create, or delete branches
   commit            Record changes to the repository
   merge             Join two or more development histories together
   rebase            Reapply commits on top of another base tip
   reset             Reset current HEAD to the specified state
   switch            Switch branches
   tag               Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch             Download objects and refs from another repository
   pull              Fetch from and integrate with another repository or a local branch
   push              Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.
sa@DESKTOP-SQLE148:~/myapp4/bin$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ../.gitignore
        ../.ruby-version
        ../Gemfile
        ../Gemfile.lock
        ../README.md
        ../Rakefile
        ../app/
        ./
        ../config.ru
        ../config/
        ../db/
        ../lib/
        ../log/
        ../package.json
        ../public/
        ../storage/
        ../test/
        ../tmp/
        ../vendor/


It took 5.10 seconds to enumerate untracked files. 'status -uno'
may speed it up, but you have to be careful not to forget to add
new files yourself (see 'git help status').
nothing added to commit but untracked files present (use "git add" to track)
sa@DESKTOP-SQLE148:~/myapp4/bin$ git --version
git version 2.25.1
sa@DESKTOP-SQLE148:~/myapp4/bin$ git config --list
color.ui=true
user.name=term
user.email=apannavich@gmail.com
user.password=term
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
sa@DESKTOP-SQLE148:~/myapp4/bin$ ls -la
total 8
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 .
drwxr-xr-x 1 sa sa 4096 Dec 21 22:17 ..
-rwxr-xr-x 1 sa sa  125 Dec 21 22:02 bundle
-rwxr-xr-x 1 sa sa  141 Dec 21 22:24 rails
-rwxr-xr-x 1 sa sa   90 Dec 21 22:24 rake
-rwxr-xr-x 1 sa sa 1010 Dec 21 22:24 setup
-rwxr-xr-x 1 sa sa  819 Dec 21 22:02 update
-rwxr-xr-x 1 sa sa  303 Dec 21 22:02 yarn
sa@DESKTOP-SQLE148:~/myapp4/bin$ cd ..
sa@DESKTOP-SQLE148:~/myapp4$ dir
Gemfile       README.md  app  config     db   log           public   test  vendor
Gemfile.lock  Rakefile   bin  config.ru  lib  package.json  storage  tmp
sa@DESKTOP-SQLE148:~/myapp4$ ls -ls
total 12
4 -rw-r--r-- 1 sa sa 2261 Dec 21 22:13 Gemfile
8 -rw-r--r-- 1 sa sa 6190 Dec 21 22:18 Gemfile.lock
0 -rw-r--r-- 1 sa sa  374 Dec 21 22:02 README.md
0 -rw-r--r-- 1 sa sa  227 Dec 21 22:02 Rakefile
0 drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 app
0 drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 bin
0 drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 config
0 -rw-r--r-- 1 sa sa  130 Dec 21 22:02 config.ru
0 drwxr-xr-x 1 sa sa 4096 Dec 21 22:26 db
0 drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 lib
0 drwxr-xr-x 1 sa sa 4096 Dec 21 22:24 log
0 -rw-r--r-- 1 sa sa   64 Dec 21 22:02 package.json
0 drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 public
0 drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 storage
0 drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 test
0 drwxr-xr-x 1 sa sa 4096 Dec 21 22:43 tmp
0 drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 vendor
sa@DESKTOP-SQLE148:~/myapp4$ cd ..
sa@DESKTOP-SQLE148:~$ ls -ls
total 16
0 -rw-r--r-- 1 sa sa   54 Dec 21 22:10 Gemfile
0 -rw-r--r-- 1 sa sa  223 Dec 11 21:37 Gemfile.lock
0 drwxr-xr-x 1 sa sa 4096 Dec 13 08:59 appname
4 -rw------- 1 sa sa 3454 Dec 10 08:25 id_rsa.pub
4 -rw-r--r-- 1 sa sa  753 Dec 10 08:25 id_rsa.pub.pub
0 drwxr-xr-x 1 sa sa 4096 Dec 10 08:58 myapp
0 drwxr-xr-x 1 sa sa 4096 Dec 10 09:41 myapp2
0 drwxr-xr-x 1 sa sa 4096 Dec 20 22:24 myapp3
0 drwxr-xr-x 1 sa sa 4096 Dec 21 22:17 myapp4
0 drwxr-xr-x 1 sa sa 4096 Dec 11 21:42 postfix
0 drwxr-xr-x 1 sa sa 4096 Dec 11 22:06 rails-web-api
0 drwxr-xr-x 1 sa sa 4096 Dec 13 22:03 rails_graphql
0 drwxr-xr-x 1 sa sa 4096 Dec 20 00:19 rails_react_recipe
4 -rw------- 1 sa sa 3434 Nov 14 16:53 sa
4 -rw-r--r-- 1 sa sa  746 Nov 14 16:53 sa.pub
0 drwxr-xr-x 1 sa sa 4096 Dec 20 22:39 super-awesome-app
0 -rwxr-xr-x 1 sa sa    0 Dec 11 21:30 testcron.sh
sa@DESKTOP-SQLE148:~$ cat id_ras.pub
cat: id_ras.pub: No such file or directory
sa@DESKTOP-SQLE148:~$ cat id_rsa.pub
-----BEGIN OPENSSH PRIVATE KEY-----
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
-----END OPENSSH PRIVATE KEY-----
sa@DESKTOP-SQLE148:~$ cat id_rsa.pub.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQDGKnIb73iSw9R9q56xrUS5O0det3rTpkegaZ1f2b3JaAbvc+Qu8ZJ2kg1dloBvHHjBf53s0Tm5LonIHGVVPSBkdbZ43yaXu6kJ7elccUut46Tu3XRy9XbqfDn7oIPtYvKN4JDjZUv3au5ezViJjtDOCfG0NpBCkzOJHuZ/FPG8wb0TU251efnAuKNYN3amG2ts87TcWJGNdMFxi4zBVInkIIYCTqWuyRDY8x1m1r6gdWY55r91D04aTXn3j5bGc7/o3i4c1mvAK2RZZxutRM25vnYNN5o5+52POTBYgPowHJ8pGhAMLdT+UtYqortU8LaMqn59btFNhPxWiVPYJUUYKp0FS8aCHr9qL1zJeteRtnQShDLxBn2/GTJkMb2mBDPHlnmDMeaxvKhw6I3HXlgeF9LbBIEwhDWZBtQT+ZCq8QPxsTV25+evCkrUJyN6CozFclwn2PCGZiKgKiT20zWohEIMLUOWvh7YIiNEdLe/VaHRpzVyXHSyCROOvgTEgAon5eYcK3S7CXU0Cwe5mYJo12Bb51HNK46ltFkmDq/vfnUOyuRDjkp53O9sn5WvGZgvjzaJUgNoVN++BZayKijBdzVJiNTIqvsfkKVDZg3sox3hH3rHedwiMWEqxBgzrc/zs2jNivZEOcGQhmQGFQl5YLAlnZQs51LtDJs0gQ9JCQ== leothai.pannavich@gmail.com
sa@DESKTOP-SQLE148:~$ ls -la
total 64
drwxr-xr-x 1 sa   sa    4096 Dec 21 22:35 .
drwxr-xr-x 1 root root  4096 Dec  9 22:38 ..
-rw------- 1 sa   sa    6499 Dec 20 23:44 .bash_history
-rw-r--r-- 1 sa   sa     220 Oct 18 14:12 .bash_logout
-rw-r--r-- 1 sa   sa      23 Dec 13 14:36 .bash_profile
-rw-r--r-- 1 sa   sa    3947 Dec 12 23:37 .bashrc
drwxr-xr-x 1 sa   sa    4096 Dec 11 21:52 .bundle
drwxr-xr-x 1 sa   sa    4096 Dec 10 08:58 .cache
drwxr-xr-x 1 sa   sa    4096 Nov 14 16:47 .gem
-rw-r--r-- 1 sa   sa      86 Dec 13 02:05 .gitconfig
drwx------ 1 sa   sa    4096 Dec 20 23:26 .gnupg
-rw------- 1 sa   sa       4 Dec 20 23:27 .irb_history
drwxr-xr-x 1 sa   sa    4096 Oct 18 14:13 .landscape
-rw------- 1 sa   sa      20 Dec 13 16:05 .lesshst
-rw-r--r-- 1 sa   sa       0 Dec 21 21:46 .motd_shown
-rw------- 1 sa   sa       9 Nov 14 16:07 .node_repl_history
-rw-r--r-- 1 sa   sa     807 Oct 18 14:12 .profile
drwxr-xr-x 1 sa   sa    4096 Nov 14 16:08 .rbenv
drwxr-xr-x 1 sa   sa    4096 Dec 20 23:26 .rvm
drwx------ 1 sa   sa    4096 Nov 14 16:54 .ssh
-rw-r--r-- 1 sa   sa       0 Oct 18 14:44 .sudo_as_admin_successful
-rw------- 1 sa   sa   11461 Dec 21 22:35 .viminfo
-rw-r--r-- 1 sa   sa     116 Dec 13 15:00 .yarnrc
-rw-r--r-- 1 sa   sa      54 Dec 21 22:10 Gemfile
-rw-r--r-- 1 sa   sa     223 Dec 11 21:37 Gemfile.lock
drwxr-xr-x 1 sa   sa    4096 Dec 13 08:59 appname
-rw------- 1 sa   sa    3454 Dec 10 08:25 id_rsa.pub
-rw-r--r-- 1 sa   sa     753 Dec 10 08:25 id_rsa.pub.pub
drwxr-xr-x 1 sa   sa    4096 Dec 10 08:58 myapp
drwxr-xr-x 1 sa   sa    4096 Dec 10 09:41 myapp2
drwxr-xr-x 1 sa   sa    4096 Dec 20 22:24 myapp3
drwxr-xr-x 1 sa   sa    4096 Dec 21 22:17 myapp4
drwxr-xr-x 1 sa   sa    4096 Dec 11 21:42 postfix
drwxr-xr-x 1 sa   sa    4096 Dec 11 22:06 rails-web-api
drwxr-xr-x 1 sa   sa    4096 Dec 13 22:03 rails_graphql
drwxr-xr-x 1 sa   sa    4096 Dec 20 00:19 rails_react_recipe
-rw------- 1 sa   sa    3434 Nov 14 16:53 sa
-rw-r--r-- 1 sa   sa     746 Nov 14 16:53 sa.pub
drwxr-xr-x 1 sa   sa    4096 Dec 20 22:39 super-awesome-app
-rwxr-xr-x 1 sa   sa       0 Dec 11 21:30 testcron.sh
sa@DESKTOP-SQLE148:~$ cd myapp4
sa@DESKTOP-SQLE148:~/myapp4$ ls -la
total 16
drwxr-xr-x 1 sa sa 4096 Dec 21 22:17 .
drwxr-xr-x 1 sa sa 4096 Dec 21 22:35 ..
drwxr-xr-x 1 sa sa 4096 Dec 21 23:35 .git
-rw-r--r-- 1 sa sa  695 Dec 21 22:02 .gitignore
-rw-r--r-- 1 sa sa   10 Dec 21 22:02 .ruby-version
-rw-r--r-- 1 sa sa 2261 Dec 21 22:13 Gemfile
-rw-r--r-- 1 sa sa 6190 Dec 21 22:18 Gemfile.lock
-rw-r--r-- 1 sa sa  374 Dec 21 22:02 README.md
-rw-r--r-- 1 sa sa  227 Dec 21 22:02 Rakefile
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 app
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 bin
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 config
-rw-r--r-- 1 sa sa  130 Dec 21 22:02 config.ru
drwxr-xr-x 1 sa sa 4096 Dec 21 22:26 db
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 lib
drwxr-xr-x 1 sa sa 4096 Dec 21 22:24 log
-rw-r--r-- 1 sa sa   64 Dec 21 22:02 package.json
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 public
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 storage
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 test
drwxr-xr-x 1 sa sa 4096 Dec 21 22:43 tmp
drwxr-xr-x 1 sa sa 4096 Dec 21 22:02 vendor
sa@DESKTOP-SQLE148:~/myapp4$ snap install altair
Interacting with snapd is not yet supported on Windows Subsystem for Linux.
This command has been left available for documentation purposes only.
sa@DESKTOP-SQLE148:~/myapp4$ install altair-graphql
install: missing destination file operand after 'altair-graphql'
Try 'install --help' for more information.
sa@DESKTOP-SQLE148:~/myapp4$ install --help
Usage: install [OPTION]... [-T] SOURCE DEST
  or:  install [OPTION]... SOURCE... DIRECTORY
  or:  install [OPTION]... -t DIRECTORY SOURCE...
  or:  install [OPTION]... -d DIRECTORY...

This install program copies files (often just compiled) into destination
locations you choose.  If you want to download and install a ready-to-use
package on a GNU/Linux system, you should instead be using a package manager
like yum(1) or apt-get(1).

In the first three forms, copy SOURCE to DEST or multiple SOURCE(s) to
the existing DIRECTORY, while setting permission modes and owner/group.
In the 4th form, create all components of the given DIRECTORY(ies).

Mandatory arguments to long options are mandatory for short options too.
      --backup[=CONTROL]  make a backup of each existing destination file
  -b                  like --backup but does not accept an argument
  -c                  (ignored)
  -C, --compare       compare each pair of source and destination files, and
                        in some cases, do not modify the destination at all
  -d, --directory     treat all arguments as directory names; create all
                        components of the specified directories
  -D                  create all leading components of DEST except the last,
                        or all components of --target-directory,
                        then copy SOURCE to DEST
  -g, --group=GROUP   set group ownership, instead of process' current group
  -m, --mode=MODE     set permission mode (as in chmod), instead of rwxr-xr-x
  -o, --owner=OWNER   set ownership (super-user only)
  -p, --preserve-timestamps   apply access/modification times of SOURCE files
                        to corresponding destination files
  -s, --strip         strip symbol tables
      --strip-program=PROGRAM  program used to strip binaries
  -S, --suffix=SUFFIX  override the usual backup suffix
  -t, --target-directory=DIRECTORY  copy all SOURCE arguments into DIRECTORY
  -T, --no-target-directory  treat DEST as a normal file
  -v, --verbose       print the name of each directory as it is created
      --preserve-context  preserve SELinux security context
  -Z                      set SELinux security context of destination
                            file and each created directory to default type
      --context[=CTX]     like -Z, or if CTX is specified then set the
                            SELinux or SMACK security context to CTX
      --help     display this help and exit
      --version  output version information and exit

The backup suffix is '~', unless set with --suffix or SIMPLE_BACKUP_SUFFIX.
The version control method may be selected via the --backup option or through
the VERSION_CONTROL environment variable.  Here are the values:

  none, off       never make backups (even if --backup is given)
  numbered, t     make numbered backups
  existing, nil   numbered if numbered backups exist, simple otherwise
  simple, never   always make simple backups

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report install translation bugs to <https://translationproject.org/team/>
Full documentation at: <https://www.gnu.org/software/coreutils/install>
or available locally via: info '(coreutils) install invocation'
sa@DESKTOP-SQLE148:~/myapp4$ git init
Reinitialized existing Git repository in /home/sa/myapp4/.git/
sa@DESKTOP-SQLE148:~/myapp4$ git remote add origin https://github.com/pannavicb/lib-crud-api.git
sa@DESKTOP-SQLE148:~/myapp4$ git add *
sa@DESKTOP-SQLE148:~/myapp4$ git commit -m 'file ruby api'
[master (root-commit) d570ebc] file ruby api
 83 files changed, 1499 insertions(+)
 create mode 100644 Gemfile
 create mode 100644 Gemfile.lock
 create mode 100644 README.md
 create mode 100644 Rakefile
 create mode 100644 app/assets/config/manifest.js
 create mode 100644 app/assets/images/.keep
 create mode 100644 app/assets/javascripts/application.js
 create mode 100644 app/assets/javascripts/cable.js
 create mode 100644 app/assets/javascripts/channels/.keep
 create mode 100644 app/assets/stylesheets/application.css
 create mode 100644 app/channels/application_cable/channel.rb
 create mode 100644 app/channels/application_cable/connection.rb
 create mode 100644 app/controllers/application_controller.rb
 create mode 100644 app/controllers/concerns/.keep
 create mode 100644 app/helpers/application_helper.rb
 create mode 100644 app/jobs/application_job.rb
 create mode 100644 app/mailers/application_mailer.rb
 create mode 100644 app/models/application_record.rb
 create mode 100644 app/models/concerns/.keep
 create mode 100644 app/views/layouts/application.html.erb
 create mode 100644 app/views/layouts/mailer.html.erb
 create mode 100644 app/views/layouts/mailer.text.erb
 create mode 100755 bin/bundle
 create mode 100755 bin/rails
 create mode 100755 bin/rake
 create mode 100755 bin/setup
 create mode 100755 bin/update
 create mode 100755 bin/yarn
 create mode 100644 config.ru
 create mode 100644 config/application.rb
 create mode 100644 config/boot.rb
 create mode 100644 config/cable.yml
 create mode 100644 config/credentials.yml.enc
 create mode 100644 config/database.yml
 create mode 100644 config/environment.rb
 create mode 100644 config/environments/development.rb
 create mode 100644 config/environments/production.rb
 create mode 100644 config/environments/test.rb
 create mode 100644 config/initializers/application_controller_renderer.rb
 create mode 100644 config/initializers/assets.rb
 create mode 100644 config/initializers/backtrace_silencers.rb
 create mode 100644 config/initializers/content_security_policy.rb
 create mode 100644 config/initializers/cookies_serializer.rb
 create mode 100644 config/initializers/filter_parameter_logging.rb
 create mode 100644 config/initializers/inflections.rb
 create mode 100644 config/initializers/mime_types.rb
 create mode 100644 config/initializers/new_framework_defaults_7_0.rb
 create mode 100644 config/initializers/permissions_policy.rb
 create mode 100644 config/initializers/wrap_parameters.rb
 create mode 100644 config/locales/en.yml
 create mode 100644 config/puma.rb
 create mode 100644 config/routes.rb
 create mode 100644 config/spring.rb
 create mode 100644 config/storage.yml
 create mode 100644 db/migrate/20221221152520_add_service_name_to_active_storage_blobs.active_storage.rb
 create mode 100644 db/migrate/20221221152521_create_active_storage_variant_records.active_storage.rb
 create mode 100644 db/migrate/20221221152522_remove_not_null_on_active_storage_blobs_checksum.active_storage.rb
 create mode 100644 db/schema.rb
 create mode 100644 db/seeds.rb
 create mode 100644 lib/assets/.keep
 create mode 100644 lib/tasks/.keep
 create mode 100644 log/.keep
 create mode 100644 package.json
 create mode 100644 public/404.html
 create mode 100644 public/422.html
 create mode 100644 public/500.html
 create mode 100644 public/apple-touch-icon-precomposed.png
 create mode 100644 public/apple-touch-icon.png
 create mode 100644 public/favicon.ico
 create mode 100644 public/robots.txt
 create mode 100644 storage/.keep
 create mode 100644 test/application_system_test_case.rb
 create mode 100644 test/controllers/.keep
 create mode 100644 test/fixtures/.keep
 create mode 100644 test/fixtures/files/.keep
 create mode 100644 test/helpers/.keep
 create mode 100644 test/integration/.keep
 create mode 100644 test/mailers/.keep
 create mode 100644 test/models/.keep
 create mode 100644 test/system/.keep
 create mode 100644 test/test_helper.rb
 create mode 100644 tmp/.keep
 create mode 100644 vendor/.keep
sa@DESKTOP-SQLE148:~/myapp4$ git push -u origin master
Username for 'https://github.com': apannavich@gmail.com
Password for 'https://apannavich@gmail.com@github.com':
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/pannavicb/lib-crud-api.git/'
sa@DESKTOP-SQLE148:~/myapp4$ git push -u origin master
Username for 'https://github.com': apannavich@gmail.com
Password for 'https://apannavich@gmail.com@github.com':
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/pannavicb/lib-crud-api.git/'
sa@DESKTOP-SQLE148:~/myapp4$ git push -u origin master
Username for 'https://github.com': apannavich@gmail.com
Password for 'https://apannavich@gmail.com@github.com':
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/pannavicb/lib-crud-api.git/'
sa@DESKTOP-SQLE148:~/myapp4$ git push -u origin master
Username for 'https://github.com': term
Password for 'https://term@github.com':
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/pannavicb/lib-crud-api.git/'
sa@DESKTOP-SQLE148:~/myapp4$ git push -u origin master
Username for 'https://github.com': term
Password for 'https://term@github.com':
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/pannavicb/lib-crud-api.git/'
sa@DESKTOP-SQLE148:~/myapp4$ git push -u origin master
Username for 'https://github.com': term
Password for 'https://term@github.com':
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/pannavicb/lib-crud-api.git/'
sa@DESKTOP-SQLE148:~/myapp4$ git push -u origin master
Username for 'https://github.com': siracha2022
Password for 'https://siracha2022@github.com':
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/pannavicb/lib-crud-api.git/'
sa@DESKTOP-SQLE148:~/myapp4$ git push -u origin master
Username for 'https://github.com': pannavicb
Password for 'https://pannavicb@github.com':
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/pannavicb/lib-crud-api.git/'
sa@DESKTOP-SQLE148:~/myapp4$ git push -u origin master
Username for 'https://github.com':
