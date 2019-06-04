## 生成package.json文件  
  npm init
  npm init --yes

## 查看各命令的简单用法  
npm -l            display full usage info
npm <command> -h  quick help on <command>
npm help <term>   search for help on <term>
npm help npm      involved overview

## 安装包  
  npm install --save -dev 开发依赖
  npm install -D

  npm install --save  生产依赖

  npm install -g 全局安装

  npm help install   获取install命令的详细信息

## 更新包  
  npm outdated  检查包是否有更新

## 淘宝镜像  
  npm i -g cnpm

## 配置  
  npm config -h
  npm config ls

  prefix:全局包安装地址
  npmrc文件
