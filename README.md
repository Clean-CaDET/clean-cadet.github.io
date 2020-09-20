<h1 align="center">
  <br>
  <img src="/images/ccadet_text.png" alt="Clean CaDET"/>
</h1>

Repository for the Clean CaDET website, alive at [https://clean-cadet.github.io/](https://clean-cadet.github.io/). 

Website is based on the [Reverie](https://github.com/amitmerchant1990/reverie), an elegant [Jekyll](https://jekyllrb.com/) theme.

## Local development setup

1. Install Ruby and Jekyll:  
```shell script
$ sudo apt-get update

$ sudo apt-get install ruby ruby-dev make gcc build-essential nodejs  

$ sudo gem install jekyll bundler
```

2. Clone `clean-cadet.github.io` repository

3. Position into folder and install dependencies:  
```shell script
$ cd clean-cadet.github.io/

$ bundle install
```

4. Start Jekyll server:
```shell script
$ bundle exec jekyll serve
```

Website is alive at [http://127.0.0.1:4000/](http://127.0.0.1:4000/).

