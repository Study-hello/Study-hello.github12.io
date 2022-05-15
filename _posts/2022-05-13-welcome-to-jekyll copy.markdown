---
layout: post
title:  "我的第二篇文章!"
date:   2022-05-13 13:08:20 +0000
categories: jekyll update
---
我的第一个递归程序:

{% highlight ruby %}
#include <bits/stdc++.h>
using namespace std;

int fact(int n){
  if(n<=1) return 1;
  return n*fact(n-1);
}

int main(){
  cout<<"请输入数字n（计算n!）:";
  cin>>n;
  cout<<fact(n);
}

{% endhighlight %}


