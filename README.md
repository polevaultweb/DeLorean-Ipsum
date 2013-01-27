DeLorean-Ipsum
==============

The Back To The Future Lorem Ipsum Generator
http://www.deloreanipsum.com/

Copyright (c) 2013 Polevaultweb http://www.polevaultweb.com/

## Example Usage
```html
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js"></script>
<script src="jquery.delorean.ipsum.min.js"></script>
<script>
  $('#demo-output').delorean({ type: 'paragraphs', amount: 5, character: '', tag:  'p' });
</script>
```

## Options
- Type: paragraphs, sentences, words, letters. Default - paragraphs.
- Amount: number of the above type. Default - 3
- Tag: HTML tag to wrap around the output. Default - 'p'
- Character: Marty, Doc, Biff etc. Leave blank for all characters. Default - 'all'.
- perPara: Number of sentences per paragraphs. Default - 5.