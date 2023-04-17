<kbd>
<a href="https://github.com/jge162">
  <img src="https://www.springboard.com/blog/wp-content/uploads/2019/07/sb-blog-programming.png" alt="3D Animation Banner" width="1000">
</a>
</kbd>

<h1 align="center">Hello, my name is Jeremy Escobar</h1>
<h3 align="center">Computer Engineer </> </h3>

<div style="display: flex;">
<p align="left"> 
  <img src="https://komarev.com/ghpvc/?username=jge162&label=Profile%20views&color=0e75b6&style=flat" alt="jge162" /> 
</p><img src="https://img.shields.io/github/stars/jge162?style=social" alt="GitHub User's stars">
  <a href="https://github.com/jge162?tab=followers"><img src="https://img.shields.io/github/followers/jge162?label=Followers&style=social" alt="GitHub Badge"></a>
</div>

| Github Stats | GitHub Community |
| -------- | -------- |
| ![Streaks](https://github-readme-streak-stats.herokuapp.com/?user=jge162&stroke=ffffff&background=1c1917&ring=0891b2&fire=0891b2&currStreakNum=ffffff&currStreakLabel=0891b2&sideNums=ffffff&sideLabels=ffffff&dates=ffffff&hide_border=true) <br> <img width="491" alt="Screenshot 2023-01-28 at 1 31 13 AM" src="https://user-images.githubusercontent.com/31228460/215258739-6ac0360c-db14-439f-8675-f4dcd7ea8e0e.png"> | [<img width="300" alt="Screenshot 2023-02-13 at 5 26 06 PM" src="https://user-images.githubusercontent.com/31228460/219539977-8fc444a5-08d7-4bb6-8a33-ac388789bcf1.png">](https://github.com/orgs/community/discussions?discussions_q=is%3Aunanswered) |

<h3 align="left">"Link to GitHub Marketplace Actions I have created" 
<a href="https://github.com/marketplace/actions/python-action" align="left">Python-workflows,</a>
<a href="https://github.com/marketplace/actions/create-release-on-close" align="left"> create-release,</a>
<a href="https://github.com/marketplace/actions/verilog-compiler" align="left"> verilog-compiler</a>
</h3>

```yaml
name: Python Action, create-release, verilog-compiler

on:
  schedule:
  - cron: '0 0 * * 6' 
  # action will run once a week on Saturday at 12:00 am 
  workflow_dispatch:

jobs:
  Python-analyze:
    runs-on: ubuntu-latest

    steps:
    - name: Python Action
      uses: jge162/Action-workflows@2.1.0
      # Multi-purpose GitHub Action

    - name: create-release-on-close
      uses: jge162/create-release@v2.2.1
      # This actions was created to help streamline
      # releases through GitHub Action.
      
    - name: Verilog Compiler
      uses: jge162/verilog_compiler@1.0.0
      # I created this because I have experience with Verilog and
      # found nothing useful in the Github marketplace for it.

#!/bin/bash

thanks = "Thanks for visiting my GitHub"
echo " $thanks "
