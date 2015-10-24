task :deploy do
  puts "Deploying to s3"
  system("bundle exec jekyll build")
  system "s3cmd put --recursive _site/* s3://mlop.es"
end