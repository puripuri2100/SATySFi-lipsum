version 0.2.0

A SATySFi package of dummy text.


# install

You can install `lipsum` package with [Satyrographos](https://github.com/na4zagin3/satyrographos).

```
opam install satysfi-lipsum

satyrographos install
```

After installation, you can import this package by writing the code in preamble.

```
@require lipsum/lipsum
```

# Usage

Block Command can not use on text-mode.

"quick-brown-fox", "iroha", "jugemu" and "jugemuP" don't take a argument.

"lipsum", "wagahai" and "preamble" take a argument of paragraph number.
`+lipsum`, `+wagahai` and `+preamble` take an optional argument of paragraph range.


## quick-brown-fox

  The quick brown fox jumps over the lazy dog.

  - `val quick-brown-fox-string : string`
  - `val quick-brown-fox-text : inline-text`
  - `direct \quick-brown-fox : [] inline-cmd`
  - `direct +quick-brown-fox : [] block-cmd`

## Lorem ipsum

20 paragraphs.

  - `val lipsum-string : int -> string`
  - `val lipsum-text : int -> inline-text`
  - `direct \lipsum : [int] inline-cmd`
  - `direct +lipsum : [int?; int] block-cmd`

## The iroha sequence（いろはにほへと……）.

1 paragraph.

  - `val iroha-string : string`
  - `val iroha-text : inline-text`
  - `direct \iroha : [] inline-cmd`
  - `direct +iroha : [] block-cmd`

## The "jugemu" name （寿限無寿限無……）.

1 paragraph.

  - `val jugemu-string : string`
  - `val jugemu-text : inline-text`
  - `direct \jugemu : [] inline-cmd`
  - `direct +jugemu : [] block-cmd`

## The "jugemu" name, with some punctuation added in ad hoc manner （寿限無・寿限無、……）.

1 paragraph.

  - `val jugemuP-string : string`
  - `val jugemuP-text : inline-text`
  - `direct \jugemuP : [] inline-cmd`
  - `direct +jugemuP : [] block-cmd`

## The first chapter from the novel "吾輩は猫である" written by Natsume Soseki.

33 paragraphs.

  - `val wagahai-string : int -> string`
  - `val wagahai-text : int -> inline-text`
  - `direct \wagahai : [int] inline-cmd`
  - `direct +wagahai : [int?; int] block-cmd`

## The preamble of the Constitution of Japan.

4 paragraphs.

  - `val preamble-string : int -> string`
  - `val preamble-text : int -> inline-text`
  - `direct \preamble : [int] inline-cmd`
  - `direct +preamble : [int?; int] block-cmd`

# License

This package released under [the MIT license](https://github.com/puripuri2100/SATySFi-lipsum/blob/master/LICENSE).

---

(c) Naoki Kaneko 2020
