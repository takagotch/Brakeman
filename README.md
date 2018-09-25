### Brakeman
---
https://github.com/presidentbeef/brakeman


```
gem install brakeman

group :development do
  gem 'brakeman'
end

docker pull presidentbeef/brakeman

git clone https://github.com/presidentbeef/brakeman.git
cd brakeman
docker build . -t brakeman

brakeman

brakeman /path/to/rails/application

docker run -v "$(pwd)":/code brakeman
docker run

brakeman -o output_file
brakeman -p output.html -o output.json
brakeman -q
brakeman -d
brakeman -x DefaultRoutes
brakeman -x DefaultRoutes,Redirect
brakeman -t SQL,ValidationRegex
brakeman --faster
brakeman --no-exit-on-warn --no-exit-on-error
brakeman --skip-files file1,/path1/,path2/
brakeman --compare old_report.json
brakeman -I

brakeman -w3

git clone git://github.com/presidentbeef/brakeman.git
cd brakeman
gem build brakeman.gemspec
gem install brakeman*.gem



```

