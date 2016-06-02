# faye-server
for rails app https://github.com/imnithin/gossip-girl using private pub


  run in background
  RAILS_ENV=production bundle exec rackup private_pub.ru -s thin -E production &

  ps -aux | grep rack & kill it to stop  or use foreman or http://stackoverflow.com/a/6431006/2231236


private_pub.yml configs to remain same with apps
