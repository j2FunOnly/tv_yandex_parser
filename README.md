# TvYandexParser

Simple Web Parser. Gets tv schedule from https://tv.yandex.ru an saves to pdf.

## Usage

```ruby
  require 'tv_yandex_parser'

  parser = TvYandexParser::Parser.new(
    Time.now, 7, TvYandexParser::Channels::HUNT_AND_FISHING
  )
  parser.to_pdf('tv_schedule.pdf')
```

## Development

To install this gem onto your local machine, run `bundle exec rake install`.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/j2FunOnly/tv_yandex_parser.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).


This gem uses (c) 2009, ParaType Ltd fonts with Original Name: PT Sans.

Copyright (c) 2009, ParaType Ltd. All Rights Reserved.

LICENSING AGREEMENT
for the fonts with Original Name: PT Sans, PT Serif
Version 1.2 - December 23, 2010

GRANT OF LICENSE
ParaType Ltd grants you the right to use, copy, modify the fonts and distribute
modified and unmodified copies of the fonts by any means, including placing
on Web servers for free downloading, embedding in documents and Web pages,
bundling with commercial and non commercial products, if it does not conflict
with the conditions listed below:

- You may bundle the font with commercial software, but you may not sell the
fonts by themselves. They are free.

- You may distribute the fonts in modified or unmodified version only together
with this Licensing Agreement and with above copyright notice. You have no
right to modify the text of Licensing Agreement. It can be placed in a separate
text file or inserted into the font file, but it must be easily viewed by users.

- You may not distribute modified version of the font under the Original name
or à combination of Original name with any other words without explicit written
permission from ParaType.

TERMINATION & TERRITORY
This license has no limits on time and territory, but it becomes null and void
if any of the above conditions are not met.

DISCLAIMER
THE FONT SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF
ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY
WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR
PURPOSE AND NONINFRINGEMENT OF COPYRIGHT, PATENT, TRADEMARK,
OR OTHER RIGHT. IN NO EVENT SHALL PARATYPE BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, INCLUDING ANY GENERAL, SPECIAL,
INDIRECT, INCIDENTAL, OR CONSEQUENTIAL DAMAGES, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT
OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM OTHER
DEALINGS IN THE FONT SOFTWARE.

[ParaType Ltd](http://www.paratype.ru)
