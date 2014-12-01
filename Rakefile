desc "Publish blog"
task :publish do
  puts "Building blog"
  system "bundle exec middleman build"
  puts "Pushing the blog"
  system "cd build; git add -A; git commit -m \"A new blog post.\"; git push origin master"
  puts "Pushing the code"
  system "git add -A; git commit -m \"A new blog post.\";git push origin master"
end
