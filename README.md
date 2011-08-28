===
string-irc

Port of http://search.cpan.org/~hirose/String-IRC-0.04/ from Perl to Ruby.

Add color codes for mIRC compatible client.

Compatibility
---

Tested under Ruby 1.9.2.

Ruby 1.8.7 is not supported yet.

Usage
---

    $ gem install string-irc

    require 'string-irc'

    si1 = StringIrc.new('hello')
    si1.red.underline
    si2 = StringIrc.new('world').yellow('green').bold
    msg = "#{si1.to_s} #{si2.to_s}"

Copyright
---

MIT License