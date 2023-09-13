```bash
    00:52:50.000 --> 00:52:55.000
    ^^
SyntaxError: illegal target for annotation
>>> 寮€鍙戞蹇靛拰璇█鏇村ソ鐨勪簡锛屽畠浠�
  File "<stdin>", line 1
    寮€鍙戞蹇靛拰璇█鏇村ソ鐨勪簡锛屽畠浠�
     ^
SyntaxError: invalid character '€' (U+20AC)
>>> 
>>> 00:52:55.000 --> 00:53:00.000
  File "<stdin>", line 1
    00:52:55.000 --> 00:53:00.000
    ^^
SyntaxError: illegal target for annotation
>>> 姘歌繙涓嶄細璁╀綘璺宠繃涓€椤点€�
  File "<stdin>", line 1
    姘歌繙涓嶄細璁╀綘璺宠繃涓€椤点€�
           ^
SyntaxError: invalid character '╀' (U+2540)
>>> 
>>> 00:53:00.000 --> 00:53:05.000
  File "<stdin>", line 1
    00:53:00.000 --> 00:53:05.000
    ^^
SyntaxError: illegal target for annotation
>>> 浣犵煡閬擄紝鍦ㄦ垜鐨勬暀瀹ら噷濂藉儚涓嶆垚涓鸿鑰呬笉鏄竴绉嶉€夋嫨銆�
  File "<stdin>", line 1
    浣犵煡閬擄紝鍦ㄦ垜鐨勬暀瀹ら噷濂藉儚涓嶆垚涓鸿鑰呬笉鏄竴绉嶉€夋嫨銆�
                           ^
SyntaxError: invalid non-printable character U+E1F0
>>> 
>>> 00:53:05.000 --> 00:53:10.000
  File "<stdin>", line 1
    00:53:05.000 --> 00:53:10.000
    ^^
SyntaxError: illegal target for annotation
>>> 褰撶劧锛岃繖鎰忓懗鐫€鎴戝繀椤诲拰 13 宀佺殑瀛╁瓙浜夎寰堝褰撶劧杩欐剰鍛崇潃鏈変簺浜�
  File "<stdin>", line 1
    褰撶劧锛岃繖鎰忓懗鐫€鎴戝繀椤诲拰 13 宀佺殑瀛╁瓙浜夎寰堝褰撶劧杩欐剰鍛崇潃鏈変簺浜�
              ^
SyntaxError: invalid character '€' (U+20AC)
>>> 
>>> 00:53:10.000 --> 00:53:15.000
  File "<stdin>", line 1
    00:53:10.000 --> 00:53:15.000
    ^^
SyntaxError: illegal target for annotation
>>> 缁欐垜閭伓鐨勮〃鎯呮槸鍥犱负鎴戣浠栦滑璇讳功浣嗘槸濡傛灉鎴戞湁涓€闂�
  File "<stdin>", line 1
    缁欐垜閭伓鐨勮〃鎯呮槸鍥犱负鎴戣浠栦滑璇讳功浣嗘槸濡傛灉鎴戞湁涓€闂�
        ^
SyntaxError: invalid non-printable character U+E045
>>> 
>>> 00:53:15.000 --> 00:53:20.000
  File "<stdin>", line 1
    00:53:15.000 --> 00:53:20.000
    ^^
SyntaxError: illegal target for annotation
>>> 鏁欏鍏佽浜轰滑涓嶈涔﹀氨閫冭劚閭ｅ氨鍦ㄦ垜韬笂锛岄偅涓嶅湪浠栬韩涓娿€�
  File "<stdin>", line 1
    鏁欏鍏佽浜轰滑涓嶈涔﹀氨閫冭劚閭ｅ氨鍦ㄦ垜韬笂锛岄偅涓嶅湪浠栬韩涓娿€�
      ^
SyntaxError: invalid non-printable character U+E17B
>>> 
>>> 00:53:20.000 --> 00:53:25.000
  File "<stdin>", line 1
    00:53:20.000 --> 00:53:25.000
    ^^
SyntaxError: illegal target for annotation
>>> 鏄殑銆�
  File "<stdin>", line 1
    鏄殑銆�
     ^
SyntaxError: invalid non-printable character U+E21C
>>> 
>>> 00:54:40.000 --> 00:54:45.000
  File "<stdin>", line 1
    00:54:40.000 --> 00:54:45.000
    ^^
SyntaxError: illegal target for annotation
>>> 濡傛灉浣犺娉曠悊瑙ｆ墍鏈夎繖浜涘鎴戞潵璇村皢鏄濂囩殑-Of褰撶劧銆備絾瀹冧細寰堟劅婵€鐨勩€�
  File "<stdin>", line 1
    濡傛灉浣犺娉曠悊瑙ｆ墍鏈夎繖浜涘鎴戞潵璇村皢鏄濂囩殑-Of褰撶劧銆備絾瀹冧細寰堟劅婵€鐨勩€�
         ^
SyntaxError: invalid non-printable character U+E195
>>> .encode('ENCODING_A').decode('ENCODING_B')
  File "<stdin>", line 1
    .encode('ENCODING_A').decode('ENCODING_B')
    ^
SyntaxError: invalid syntax
>>> "浣犺蛋杩涘埆浜虹殑鎴垮瓙锛屼綔涓轰竴涓湁璇嗗瓧鐨勪汉锛屼綘棣栧厛瑕佺湅鐨勬槸浠€涔堬紵浣犵湅鐪嬩粬浠殑".encode('UTF-8').decode('GBK')
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
UnicodeDecodeError: 'gbk' codec can't decode byte 0xae in position 32: illegal multibyte sequence
>>> "浣犺蛋杩涘埆浜虹殑鎴垮瓙锛屼綔涓轰竴涓湁璇嗗瓧鐨勪汉锛屼綘棣栧厛瑕佺湅鐨勬槸浠€涔堬紵浣犵湅鐪嬩粬浠殑".encode('UTF-8', errors='ignore').decode('GBK', errors='ignore')
'娴ｇ姾铔嬫潻娑樺焼娴滆櫣娈戦幋鍨鐡欓敍灞肩稊娑撹桨绔存稉顏呮箒鐠囧棗鐡ч惃鍕姹夐敍灞肩稑妫ｆ牕鍘涚憰浣烘箙閻ㄥ嫭妲告禒鈧娑斿牞绱垫担鐘垫箙閻瀣╃铂娴狀剛娈'
>>> "浣犺蛋杩涘埆浜虹殑鎴垮瓙锛屼綔涓轰竴涓湁璇嗗瓧鐨勪汉锛屼綘棣栧厛瑕佺湅鐨勬槸浠€涔堬紵浣犵湅鐪嬩粬浠殑".encode('GBK', errors='ignore').decode('UTF-8', errors='ignore')
'你走进别人的房子，作为一东识字的人，你首先要看的是么？你看看他仚'
>>> 
 *  还原的历史记录 

(base) sakuratsuki@Mahoumori EECS1720 % 
 *  还原的历史记录 

(base) sakuratsuki@Mahoumori EECS1720 % 
 *  还原的历史记录 

(base) sakuratsuki@Mahoumori EECS1720 % 
 *  还原的历史记录 

(base) sakuratsuki@Mahoumori EECS1720 % 
```
