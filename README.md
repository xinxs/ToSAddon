## Recent updates (最近の更新内容)

Last Updated : November 5, 2019

* **Map Mate Ver. 0.90**
  * 10/30に行われたIToSのアップデートに対応しました。<br>Added support for IToS update on October 30.

March 16, 2019

* **Map Mate Ver. 0.89**
  * 3/13に行われたIToSのアップデートに対応しました。<br>Added support for IToS update on March 13.

## About Re: Build patch (Update in Mar 2, 2019) (Re:Buildパッチへの対応について)
I have confirmed that the following add-on is affected by Re: Build patch.  
Re:Buildパッチにより次のアドオンに影響が出ていることを確認しています。

* **Better Pick Queue**
  * There is a problem that operation stops when equipment items are picked up.<br>装備アイテムを拾うと動作が停止します。
    * Support completed in Ver.1.14.<br>Ver.1.14で対応完了しました。
* **BuffCounter**
  * Since the ID number of the buff and the acquisition method have been changed, the buffing enhancement value can not be displayed correctly.<br>バフの番号と取得方法が変更され、バフの強化値が正しく表示できない問題が発生しています。
    * Support completed in Ver.1.19.<br>Ver.1.19で対応完了しました。
* **Dur notice Mini**
  * Since the method of obtaining the item endurance value was changed, there was a problem that display of durability was not done at all.<br>アイテム耐久値の取得方法が変更され、耐久度の表示が全くされない問題が発生していました。
    * Support completed in Ver.1.23.<br>Ver.1.23で対応完了しました。
* **Equip Marker**
  * It does not work.<br>動作しません。
    * Although it was provisionally supported by Ver. 1.03, the following functions can not be used.<br>Ver.1.03で暫定対応しましたが次の機能が使用できません。
      * Display does not apply to item decomposition window.<br>アイテム分解ウィンドウに表示が適用されません。
      * The display does not apply to the item column being equipped.<br>装備中アイテム欄に表示が適用されません。
* **Remaining Counter**
  * There is a problem that the skill icon is not displayed.<br>スキルアイコンが表示されない不具合があります。
    * Support completed in Ver.1.04.<br>Ver.1.04で対応完了しました。
* **Shop Helper**
  * The skill level is not displayed at buff shops.<br>バフ商店でスキルレベルの表示がされません。
    * Because the actual skill level differs from the displayed skill level, we are considering abolishing this function.<br>実際のスキルレベルと表示されるスキルレベルが異なるため、この機能は廃止することを検討中です。
  * The endurance value will not be displayed until repaired at the repair shop.<br>修理商店で修理するまで耐久値の表示がされません。
    * It occurred when it was involved in the problem of EquipMarker.<br> Please update EquipMarker.<br>EquipMarkerの不具合に巻き込まれて発生しているものでした。EquipMarkerをアップデートしてください。

## Notice:
<span style="color:#FF0000;">The author is not currently working in ToS.  
Therefore, I am planning to fix fatal things. However, basically it only updates as a whim.  
現在、作者はToSを引退しています。そのため、致命的なものの修正は行うつもりですが、基本的には気まぐれで更新しかしません。</span>

# Add-ons for Tree of Savior - Tree of Saviorアドオン集
「あったらちょっと便利だな」と思う小道具を気まぐれに作成しています。    
**Please**:
I am not good at English. I frequently translate English into different nuances.  
So, I would appreciate it if you could told me the correct translation when you see an unnatural English translation  


## [Better Pick Queue Ver. 1.14 ( JP / EN )](https://github.com/Toukibi/ToSAddon/tree/master/BetterPickQueue)
画面の右下で拾ったアイテムを表示する機能を強化します。  
This add-on enhances the ability to display the items picked up.  
![Image of main image of Better-Pick-Queue](https://github.com/Toukibi/ToSAddon/blob/ForImage/BetterPickQueue/img/topimage2_ja.jpg?raw=true)    

## [BuffCounter Ver. 1.19 ( JP / EN / KR )](https://github.com/Toukibi/ToSAddon/tree/master/BuffCounter)
上段バフの残り枠数を教えてくれます。  
さらに、トークンの残り日数やバフのレベル・効果などを追加表示します。  
This add-on will tell you the remaining number of upper buffs.  
(In addition, the remaining time of the token is displayed in the buff field)  
!["Image of main image of Buff-Counter"](https://github.com/Toukibi/ToSAddon/raw/ForImage/BuffCounter/img/topimage.png?raw=true)  

## [Clover Finder Ver. 2.01 ( JP / EN )](https://github.com/Toukibi/ToSAddon/tree/master/Do-It-Yourself/With_ipf/CloverFinder)
訳ありのあの有名なアドオンです。  
ランク9実装の時に動かなくなった物を組み直して再び動くようにしました。  
しかし、物が物だけに**取り扱いは自己責任で**お願いします。  
That is a famous add-on that has certain circumstances.  
It stopped working due to the patch of December 2017. However, I reorganized it so that it moves again.  
However, for **this add-on is the elimination target**, handling is **at your own risk**.  

## [Don't Decompose Me Ver. 1.02 ( JP / EN )](https://github.com/Toukibi/ToSAddon/tree/master/DontDecomposeMe)
アイテム分解時に大事なアイテムを分解しないようにアイテムの見分けをしやすくしてくれます。  
(**誤って分解することを阻止することはできません**)   
It makes it easier to distinguish items so as not to disassemble important items at the time of item disassembly.  
(**It will not be able to prevent the decomposition by mistake**)  
!["Image of main image of Don't-Decompose-Me"](https://github.com/Toukibi/ToSAddon/blob/ForImage/DontDecomposeMe/img/topimage_ja.png?raw=true)  

## [Dur notice Mini Ver. 1.23 ( JP / EN )](https://github.com/Toukibi/ToSAddon/tree/master/DurNoticeMini)
装備の耐久で最も低い武器と防具の数値をリアルタイムに表示してくれます。  
This add-on will tell you the minimum durability value of your equipment.  
!["Image of main image of Dur-Notice-Mini"](https://github.com/Toukibi/ToSAddon/blob/ForImage/DurNoticeMini/Main/img/topimage.png?raw=true)  

## [Equip Marker Ver. 1.03 ](https://github.com/Toukibi/ToSAddon/tree/master/EquipMarker)
アイテム表示に強化値とランクと未鑑定の情報を追加します。  
This add-on adds enhancement value, item rank and unidentified icon to the item display.    
![Image of main image of Equip-Marker](https://github.com/Toukibi/ToSAddon/blob/ForImage/EquipMarker/img/topimage_ja.jpg?raw=true)    

## [Experience Viewer Ex Ver. 1.02](https://github.com/Toukibi/ToSAddon/tree/master/ExpViewer_Ex)
経験値に関する情報と、獲得シルバーの情報を表示します。  
This add-on will display all sorts of information about your character's experience and information on acquired silver.  
![ExpViewerの外観](https://github.com/Toukibi/ToSAddon/blob/ForImage/ExpViewer_Ex/img/topimage_ja.jpg?raw=true)

## [Item Drops 2 Ver. 2.01 ( JP / EN )](https://github.com/Toukibi/ToSAddon/tree/master/ItemDrops2)
ItemDropsが2になって帰ってきました。ドロップしたアイテムを**色濃く**強調表示してくれます。  
ItemDrops is back. It highlights the dropped item **more strongly**.    
![Image of main image of ItemDrops2](https://github.com/Toukibi/ToSAddon/blob/ForImage/ItemDrops2/img/topimage_ja.jpg?raw=true)    

## [Map Mate Ver. 0.90 ( JP / EN )](https://github.com/Toukibi/ToSAddon/tree/master/MapMate)
マップ表示を色々便利にしてくれます。  
This add-on makes map display a lot convenient.   
!["Image of main image of Map-Mate"](https://github.com/Toukibi/ToSAddon/blob/ForImage/MapMate/image/MapMate_MiniMap.png?raw=true)  

## [Shop Helper Ver. 0.90 ( JP / EN / KR / BR )](https://github.com/Toukibi/ToSAddon/tree/master/ShopHelper)
街などで開かれている露店の表示を少しだけ使いやすくしてくれます。  
This add-on will make the display of the stalls opened in towns etc. a little easier to use.  
!["Image of main image of ShopHelper"](https://github.com/Toukibi/ToSAddon/blob/forImageStrage/ShopHelper/img/ShopHelperImage.jpg?raw=true)
!["Image of setting image of ShopHelper"](https://github.com/Toukibi/ToSAddon/blob/forImageStrage/ShopHelper/img/option_jp.jpg?raw=true)  

## [Tooltip Helper Ver. 1.04 (Rebuild by Toukibi)( JP / EN )](https://github.com/Toukibi/ToSAddon/tree/master/TooltipHelper_Rebuild)
Tooltip Helperはツールチップに追加の情報を表示するためのアドオンです。  
冒険日誌の変更パッチで動かなくなった原作を再構築したものです。
Tooltip Helper is an add-on for displaying additional information on tooltips.  
It is the one which reconstructed original version which stopped working with change patch of Journal.
![Tooltip Helperのイメージ](https://github.com/Toukibi/ToSAddon/raw/ForImage/TooltipHelper_Rebuild/img/topimage_s_ja.jpg?raw=true)
