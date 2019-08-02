# Ruby
- Ruby version 2.4.0 or above, including all development headers (ruby version can be checked by running ruby -v)
   <code> 
    brew install ruby |
    export PATH=/usr/local/opt/ruby/bin:$PATH |
    which ruby |
    ruby -v 
   </code>
- RubyGems (which you can check by running gem -v)
- GCC and Make (in case your system doesn’t have them installed, which you can check by running gcc -v,g++ -v and make -v in your system’s command line interface)

# Jekyll
- Install a full Ruby development environment
- Install Jekyll and bundler gems
  <code> sudo gem install bundler | sudo gem install -n /usr/local/bin/ jekyll</code>
- Create a new Jekyll site at ./myblog
  <code> jekyll new myblog </code>
- Change into your new directory
  <code> cd myblog </code>
- Build the site and make it available on a local server
  <code> bundle exec jekyll serve </code>
- Now browse to http://localhost:4000

# jekyll-admin
- cd /blog
- gem 'jekyll-admin', '~> 0.8.1'
- bundle install
- bundle exec jekyll serve
