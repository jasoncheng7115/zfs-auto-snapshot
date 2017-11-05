# zfs-auto-snapshot-tzPatch / zfs 自動快照工具時區問題更新檔

&nbsp;&nbsp;
## 套件說明
  
本專案為分支版本，主要修復快照產生的時區錯誤問題，並加入說補充裝說明。
這個套件可以全自動化的建立、倒回以及銷毀 ZFS 快照。

&nbsp;&nbsp;
&nbsp;&nbsp;

透過這支工具可以很容易的建立出四種不同排程的快照，名稱格式為 
- (刻) @zfs-auto-snap_frequent 
- (時) @zfs-auto-snap_hourly 
- (日) @zfs-auto-snap_daily 
- (週) @zfs-auto-snap_weekly 
- (月) @zfs-auto-snap_monthly 


本程式是以 Shell Script 形式撰寫，可以設定在 cron 排程裡，也可以直接在命令模式下執行它。

&nbsp;&nbsp;
&nbsp;&nbsp;


#### 安裝說明下載方式說明

    wget https://github.com/jasoncheng7115/zfs-auto-snapshot/archive/master.zip
    unzip master.zip
    cd zfs-auto-snapshot-master
    make install
