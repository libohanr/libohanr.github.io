---
layout: default
---
arXiv: <a href="placeholder">placeholder</a>

Text can be **bold**, _italic_, or ~~strikethrough~~.

## Abstract

Streaming accent translation is the task of translating speech between different accents in real-time but keep the speaker's voice identity and prosodic attributes. Previous accent translation approaches are mostly focus on non-streaming translation, which are limited to practical situations, such as live streaming, real-time communication. In this paper, we propose an accent translation system, which translates source accent speech to target accent intermediate bottleneck features (IBFs) and then feeds the IBFs into a TTS decoder for target accent speech synthesis. Then we train a full stream model with teacher guidance from the non-streaming model. Furthermore, the proposed system is able to scale to other audio conversion tasks, such as voice conversion. Experiments show that our proposed streaming system achieves naturalness of , accent accuracy , timbre similarity of on accent translation task, and naturalness of , timbre similarity of on voice conversion task. Both subjective and objective evaluations show our streaming system achieves on parity quality with non-streaming system.

## Audio Samples
<div class="table-wrapper">
  <table>
  <thead>
  <tr>
      <th>Source Speech (non-native accent)</th>
      <th>Converted Speech (native enUS accent)</th>
  </tr>
  </thead>
  <tbody>
  <tr>
      <td style="text-align: center" rowspan="1"><audio width="100px" controls="controls"><source src="assets/wav/ref_audio1.wav" autoplay="">Your browser does not support the audio element.</audio></td>
      <td style="text-align: center" rowspan="1"><audio width="100px" controls="controls"><source src="assets/wav/ref_audio1.wav" autoplay="">Your browser does not support the audio element.</audio></td>
  </tr>
  
  <tr>
      <td style="text-align: center" rowspan="1"><audio controls="controls"><source src="assets/wav/ref_audio1.wav" autoplay="">Your browser does not support the audio element.</audio></td>
      <td style="text-align: center" rowspan="1"><audio controls="controls"><source src="assets/wav/ref_audio1.wav" autoplay="">Your browser does not support the audio element.</audio></td>
  </tr>
    
  <tr>
      <td style="text-align: center" rowspan="1"><audio controls="controls"><source src="assets/wav/ref_audio1.wav" autoplay="">Your browser does not support the audio element.</audio></td>
      <td style="text-align: center" rowspan="1"><audio controls="controls"><source src="assets/wav/ref_audio1.wav" autoplay="">Your browser does not support the audio element.</audio></td>
  </tr>
    </tbody></table></div>

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

<div class="table-wrapper">
  <table>
  <thead>
  <tr>
      <th>Source Speech</th>
      <th>Target Speech</th>
      <th></th>
      <th>Conversion Speech</th>
  </tr>
  </thead>
  <tbody>
  <tr>
      <td style="text-align: center" rowspan="8"><audio controls="controls"><source src="assets/wav/ref_audio1.wav" autoplay="">Your browser does not support the audio element.</audio></td>
      <td style="text-align: center" rowspan="4"><audio controls="controls"><source src="assets/wav/ref_audio1.wav" autoplay="">Your browser does not support the audio element.</audio></td>
      <td style="text-align: center">Baseline</td>
      <td style="text-align: center"><audio controls="controls"><source src="assets/wav/ref_audio1.wav" autoplay="">Your browser does not support the audio element.</audio></td>
  </tr>
  <tr>
      <td style="text-align: center">Proposed</td>
      <td style="text-align: center"><audio controls="controls"><source src="wav/daily/1/proposed_f.wav" autoplay="">Your browser does not support the audio element.</audio></td>
      
  </tr>
  <tr>
    <td style="text-align: center">Proposed<font color="#FF0000"> w/o IBFs </font></td>
    <td style="text-align: center"><audio controls="controls"><source src="wav/daily/1/wo_ibf_f.wav" autoplay="">Your browser does not support the audio element.</audio></td>
    
  </tr>
  <tr>
    <td style="text-align: center">Proposed<font color="#FF0000"> w/o TG </font> </td>
    <td style="text-align: center"><audio controls="controls"><source src="wav/daily/1/wo_tg_f.wav" autoplay="">Your browser does not support the audio element.</audio></td>
    
  </tr>
  <tr>
      <td style="text-align: center" rowspan="4"><audio controls="controls"><source src="wav/target_m.wav" autoplay="">Your browser does not support the audio element.</audio></td>
      <td style="text-align: center">Baseline</td>
      <td style="text-align: center"><audio controls="controls"><source src="wav/daily/1/bl_m.wav" autoplay="">Your browser does not support the audio element.</audio></td>
      
  </tr>
<tr>
    <td style="text-align: center">Proposed</td>
    <td style="text-align: center"><audio controls="controls"><source src="wav/daily/1/proposed_m.wav" autoplay="">Your browser does not support the audio element.</audio></td>
    
</tr>
<tr>
  <td style="text-align: center">Proposed <font color="#FF0000">w/o IBFs</font> </td>
  <td style="text-align: center"><audio controls="controls"><source src="wav/daily/1/wo_ibf_m.wav" autoplay="">Your browser does not support the audio element.</audio></td>
  
</tr>
<tr>
  <td style="text-align: center">Proposed <font color="#FF0000">w/o TG</font> </td>
  <td style="text-align: center"><audio controls="controls"><source src="wav/daily/1/wo_tg_m.wav" autoplay="">Your browser does not support the audio element.</audio></td>
  
</tr>
  </tbody>
  </table></div>

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
