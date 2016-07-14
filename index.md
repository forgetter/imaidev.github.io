---
layout: page
---
[:smile:](http://www.emoji-cheat-sheet.com/)                                                          

## 组件云服务 ##
1. [用户认证（缺）](/iam/)
2. [在线客服](http://ocs.imaicloud.com)

## 基础云服务 ##
1. [CouchDB](http://couch.imaicloud.com/_utils)

## 工具云服务 ##
1. [etcd-viewer](http://etcd.imaicloud.com)
2. [在线excel](http://ethercalc.imaicloud.com)
3. [用户行为分析](http://uba.imaicloud.com)

## 文档中心 ##
1. [平台概述](/doc/plat)
2. [免费https证书](/doc/letsencrypt-https)

<div class="adm-block">
    <div class="col-md-12">
        <div class="portlet">
            <div class="portlet-title">
                <div class="caption pull-left" style="width:50%;">用户信息</div>
                <div class="pull-right" style="width:50%;">
                    <a onclick="forAdmConsole()"><small>控制台</small></a>
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
