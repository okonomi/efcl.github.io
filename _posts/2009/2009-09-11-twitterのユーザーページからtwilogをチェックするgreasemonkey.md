---
title: TwitterのユーザーページからTwilogをチェックするGreasemonkey
author: azu
layout: post
permalink: /2009/0911/res1303/
SBM_count:
  - '00002<>1355286071<>0<>0<>1<>1<>0'
dsq_thread_id:
  - 300802277
categories:
  - その他
tags:
  - Greasemonkey
  - twitter
---
[Twilog][1]というTwitterのつぶやきを日付毎に記録してくれるサービスが便利なので、  
twitterのユーザーページ(https://twitter.com/azu_re )とかからそのユーザーがTwilogを利用してるかをチェックするGreasemonkeyを書きました。<figure id="attachment_1304" style="width: 300px;" class="wp-caption alignnone">

[<img class="size-medium wp-image-1304" title="large" src="https://efcl.info/wp-content/uploads/2009/09/large-300x109.png" alt="large" width="300" height="109" />][2]<figcaption class="wp-caption-text">ユーザー名の横にアイコンがでる</figcaption></figure> 
Twilogに登録していると、ユーザー名の隣にアイコンを表示します。

*   [Twilog checker][3]

<br class="spacer_" />

登録してるかを判定するAPIがないかなーって[つぶやいた][4]ら[作ってくれた][5]みたいなので、それを使わしてもらっています。  
*  
ユーザーが登録済みかを判定  
true : 1   
false: 0   
e.g)<http://twilog.org/user-exist.cgi?id=azu_re> // 1*

 [1]: http://twilog.org/
 [2]: https://efcl.info/wp-content/uploads/2009/09/large.png
 [3]: http://userscripts.org/scripts/show/57387
 [4]: http://twitter.com/azu_re/status/3864502565
 [5]: http://twitter.com/ropross/statuses/3886731176
