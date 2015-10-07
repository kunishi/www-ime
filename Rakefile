source_dir = File.expand_path "./_site"
deploy_user = "www-ime"
deploy_host = "www-ime.c.oka-pu.ac.jp"
deploy_dir = "public_html"

desc "Deploy web contents"
task :deploy do
  sh "rsync -avz #{source_dir}/ #{deploy_user}@#{deploy_host}:#{deploy_dir}/"
end
