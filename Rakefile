# Rakefile for sass stuff

desc 'Start watching the zen.scss file'
task :watch do
	sh 'sass --watch public/styles/zen.scss:public/styles/zen.css'
end

desc 'Onetime compile scss into css'
task :scss do
	sh 'sass --force --update public/styles/zen.scss:public/styles/zen.css'
end

desc 'Open ZenGarden page'
task :open do
	sh 'open http://zengarden.dev/zen.html'
end