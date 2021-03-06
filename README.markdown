Colorize
========

Colorize add color to $stdout output.

Install Renv:

    sudo gem install fnando-colorize --source=http://gems.github.com

Or

    git clone git://github.com/fnando/colorize.git
    cd colorize
    rake gem:install

Usage:

    require "rubygems"
    require "colorize"
    
    puts Colorize.apply "test", :color => :red
    puts Colorize.apply "test", :color => :red, :bgcolor => :blue
    puts Colorize.apply "test", :style => %w(highlight blink underscore)
    
    Colorize.puts "test", :style => %w(highlight blink underscore)

Disable Colorize by adding the following to your `~/.bash_profile`:

    export COLORIZE=0

MAINTAINER
----------

* Nando Vieira (<http://simplesideias.com.br>)

LICENSE:
--------

(The MIT License)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.