# jenkins-jobs-template

Jenkins Job パイプライン(Jenkinsfile)のテンプレート。  
　  
　  
``随時更新中``  



---

:book: 参考：  

* [Jenkins](https://www.jenkins.io/)  
* [Jenkins User Documentation](https://www.jenkins.io/doc/)  
* [Using a Jenkinsfile](https://www.jenkins.io/doc/book/pipeline/jenkinsfile/)    

## 1. Setup

### 1.1 Jenkins master

[こちら](setup-master) の手順で Jenkins master を Dcoker で構築します。

### 1.2 Jenkinsfile エディター

テキストエディタなら何でも良いですが、Visual Studio Code を推奨します。  
　  
* [Visual Studio Code – コード エディター | Microsoft Azure](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)
* [JenkinsFile Support - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=ivory-lab.jenkinsfile-support)  Jenkinsfile をサポート、比較的更新が多いものを選択。


## 2. Template


基本的なパイプラインジョブ作成手順は[こちら](blob/master/tree/master/template/master-node-only)を参照してください。

### 2.1 master node only

master ノードのみで動作するテンプレートです。

| Title | Node | Keyword | Jenkinsfile | Description 
| ----- | ---- | ---- | :---------: |----------- 
| hello world | master | [node](https://www.jenkins.io/doc/book/pipeline/#node), [sh](https://www.jenkins.io/doc/pipeline/steps/workflow-durable-task-step/#sh-shell-script)  | [:page_facing_up:](tree/master/template/master-node-only/hello-world.Jenkinsfile) | master ノードのシェルスクリプトで echo します。 

　  
　  
　  
　  
　  
　  

* * *

###### :copyright: 商標について

<sup>当ドキュメントに記載されている会社名、システム名、製品名は一般に各社の登録商標または商標です。</sup>  
<sup>なお、本文および図表中では、「™」、「®」は明記しておりません。</sup>  

###### 免責事項  
<sup>当ドキュメント上の掲載内容については細心の注意を払っていますが、その情報に関する信頼性、正確性、完全性について保証するものではありません。</sup>  
<sup>掲載された内容の誤り、および掲載された情報に基づいて行われたことによって生じた直接的、また間接的トラブル、損失、損害については、筆者は一切の責任を負いません。</sup>  
<sup>また当ドキュメント、およびドキュメントに含まれる情報、コンテンツは、通知なしに随時変更されます。</sup>  


