
##

## :wrench: インストール方法(Linux環境で行います。)

- 端末を開きます。

- gitコマンドでこのリポジトリをクローンします。

    ```
    git clone https://github.com/ftmmchan/GRUB-Template.git
    ```

- ホームディレクトリにGRUB-Templateというフォルダがあると思うので中にあるbackground.pngなどの画像を適当に差し替えます。
    
   テーマは右寄りと左寄りの2種類用意しています。 
    
 - テーマをインストールします。以下例

    ```
    cd GRUB-Template/Template_1
    #作業ディレクトリに移動
    ```
    ```
    sudo ./install.sh                
    #エラーが出る場合 
    sudo bash ./install.sh
    ```

- PCを再起動すれば反映されます。

 - アンインストールする場合。

    ```
    sudo ./uninstall.sh                
    #エラーが出る場合 
    sudo bash ./uninstall.sh
    ```

元の製作者：13atm01
