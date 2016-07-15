---
layout: page
---
[:smile:](http://www.emoji-cheat-sheet.com/)

## 组件云服务 ##
1. [用户认证 (https://iam.imaicloud.com)停止](/iam/)
2. [在线客服 (http://ocs.imaicloud.com)停止](http://ocs.imaicloud.com)

## 管理控制台 ##
1. [容器管理 (https://dockerui.imaicloud.com)](https://dockerui.imaicloud.com)            
2. [docker镜像库 (https://registry.imaicloud.com)](https://registry.imaicloud.com)

## 基础云服务 ##
1. [文档数据库(https://couchdb.imaicloud.com)](https://couchdb.imaicloud.com/_utils)

## 工具云服务 ##
1. [etcd-viewer (https://etcd.imaicloud.com)](https://etcd.imaicloud.com)
2. [在线excel (https://ethercalc.imaicloud.com)](https://ethercalc.imaicloud.com)
3. [用户行为分析 (https://uba.imaicloud.com)](https://uba.imaicloud.com)

## 文档中心 ##
1. [平台概述](/doc/plat)
2. [免费https证书](/doc/letsencrypt-https)
3. [css的例子(容器管理2)](http://dockerui2.imaiclouid.com)

<div class="adm-block">
    <div class="col-md-12">
        <div class="portlet">
            <div class="portlet-title">
                <div class="caption pull-left" style="width:50%;">用户信息</div>
                <div class="pull-right" style="width:50%;text-align:right;">
                    <a onclick="forAdmConsole()" style="cursor:pointer;">控制台</a>
                    <script type="text/javascript">
                        function forAdmConsole(){
                            window.open('https://dev.imaicloud.com/adm/console/forConsole?user_id=adm','_blank');
                        }
                    </script>
                </div>
            </div>
            <div class="portlet-body">
                <label class="caption">二级域名：<em id="adm-subdomain"></em></label>
                <label class="caption">github账号：<em id="adm-github"></em></label>
            </div>
        </div>
    </div>
</div>
