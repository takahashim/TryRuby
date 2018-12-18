---
title: "ウェブエディタ"
description: Play around with Ruby programs
---

<div class="row">
  <div class="col-md-4">
    <div id="tryruby-explanation">
      <h2 id="tryruby-title">Ruby playground</h2>
      <div id="ryruby-content">
        <select name="sample_code" id="sample_code">
          <option value="list1_1_1">1.1 リスト1</option>
          <option value="list1_1_2">1.1 リスト2</option>
          <option value="list1_2_3">1.2 リスト3</option>
          <option value="list1_2_4">1.2 リスト4</option>
          <option value="list1_3_5">1.3 リスト5</option>
        </select>
      </div>

      <p>このPlaygroundの画面では、Rubyのサンプルコードを試しに実行してみることができます。<br/>リストを選択して、「実行する」ボタンを教えてみてください。</p>
    </div>
  </div>

  <div class="col-md-8">

    <div class="row" id="wrapper">

      <div id="editor_wrapper" class="col-md-12">
        <h4>エディタ</h4>
        <div id="editor" class="well" style="padding:0"></div>

        <div class="row">
          <div class="col-md-12">
            <button type="button" id="btn_run" class="btn btn-primary btn-block">実行する<span class="glyphicon glyphicon-play" aria-hidden="true"></span></button>
          </div>
        </div>
      </div>

      <div class="col-md-6">
        <h4>実行結果</h4>
        <div id="output" class="well" style="padding:0">
        </div>
      </div>

      <div class="col-md-6">
        <h4>見本</h4>
        <div id="example" class="well" style="padding:0">
        </div>
      </div>

    </div>
  </div>
</div>

<script>Opal.load('try_ruby');</script>
