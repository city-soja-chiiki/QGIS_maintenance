# 総社市道路・水路台帳閲覧システム賃貸用　掲示板  
**[【GEOソリューションズ】](https://geo-sol.co.jp/)**   
　契約期間　令和3年9月1日～令和8年8月31日  
　保守点検回数　　定期40回（1回／月）　令和5年5月より   
　　　　　　　　　不定期26回  
### 運用ルール  
　ISSUES の　CLOSE　は，OPEN　した者が行うこと。  
### 保守詳細は下記のとおり
#### [　2.QGIS本体の保守](https://github.com/city-soja-chiiki/QGIS/blob/main/2.QGIS%E6%9C%AC%E4%BD%93%E3%81%AE%E4%BF%9D%E5%AE%88.md)  
#### [　4.その他台帳用QGISの保守](https://github.com/city-soja-chiiki/QGIS/blob/main/4.%E3%81%9D%E3%81%AE%E4%BB%96%E5%8F%B0%E5%B8%B3%E7%94%A8QGIS%E3%81%AE%E4%BF%9D%E5%AE%88.md)  　
### 今後の引継ぎ段取り概要　2023/05/19初版作成
1. LGWANとクラウドのプロジェクトファイル統合  
　　・プロジェクトファイルの保存先を統合  
2. LGWANとクラウドのデータベース統合  
　　・LGWANとクラウドのIPアドレス統合（クラウド側は２IP運用）  
　　・PostGISのデータ構造を統一
　　　　soja_lgwan,soja_cloudに統合
3. LGWANとクラウドのデータ統合   
4. QGISランチャ  
　　・コンフィグファイルのランチャー内移行  
　　・プラグインファイルのランチャー内移行  
　　・プラグイン　コンフィグファイルのバージョン管理追加  
　　・ランチャーのオブジェクト化  
1. LIZMAP
1. 保守点検チェック表の作成  
#### 追加機能の検討
　ログインの再構築  
　検索プラグインの再構築    
