## lkk122.py
param xml數據轉換器  
手動輸入xml值可轉換成跑跑內的數值，
反之亦可以。

可自行新增數據，需填入數據名稱、該數據的兩個xml值、該數據的兩個內部值，  
程式會假設數據為線性變化，自行計算出公式。  
> 請注意相同的數據名稱不可輸入第二遍，若要修改公式請自行打開data.data進行修改

>>請注意data.data的公式中的所有運算元與運算子中間皆需要有空格，否則會有問題發生。

有些數據名稱只能查看公式，  
原因為該數據為布林值/公式特殊/所有車子的數據皆相同等情況。  
請自行根據公式給的提示進行轉換。
> 公式 " Y = X ? 1 : 0 " 表示該數據為布林值

## lkk123.py
可將param.xml內部數據自行轉換為跑跑內部所需數據。
### 使用方式
* 第一種 : 請將xml檔案直接拉到lkk123.exe上，使用debug方法的請設法將傳入參數的第一格設為xml的相對位置或絕對位置。程式會生成param.xml，**請注意是以文字檔格式輸出**
* 第二種 : 請新創一個文字檔案(.txt)，內部輸入xml的檔名或絕對位置之後，再以","隔開後輸入1或0。
>ex:  
param@tw.xml,0

  將該文字檔拉到lkk123.exe上。程式會產生param.xml，若","後輸入0會 **以xml格式輸出**，若輸入1則一樣是以文字檔格式輸出。

若程式無法正確運作，會將原因寫於param.xml，若有問題可詢問。

## lkk126.py
轉換跑跑內部數據格式。xml <---> txt
### 使用方式
* 請將檔案直接拉到lkk126.exe上，程式會判斷文檔格式為何，進而生成Kartspec.xml/.txt。
