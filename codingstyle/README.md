# codingstyle

## 分號
- 不要用分號作為一行的結束且不要用分號作為兩行之間的分隔。

## 分行
- 一行不要超過80個字，除非其中有包含長URL的註解和很長的引入敘述。
- 不要使用反斜線來接續兩行。
- 確保隱行被放在括弧(大、中、小)中，如有必要可以在表達式外額外新增括弧。
 
 ```python
 foo_bar(self, width, height, color='black', design=None, x='foo',
   emphasis=None, highlight=0) 
 ```
 
 ```python
 if(width==0 and height ==0 and
   color=='red' and emphasis=='strong')
 ```
 
- 當字串長度大於一行時，將其分行並使用括弧將整個字串包起來。
  
  ```python
  x=('This will build a very long long'
  'long long long long long long string')
 ```
 
- 放在註解中的URL連結盡量避免分行，如有需要，連結可以放在獨立的一行
  
  ```python
  正確: 
  # See details at
  # http://www.example.com/us/developer/documentation/api/content/v2.0/csv_file_name_extension_full_specification.html
  ```
  
  ```python
  錯誤: 
  # See details 
  # http://www.example.com/us/developer/documentation/api/content/\
  # v2.0/csv_file_name_extension_full_specification.html
  ```
  
  注意以上案例的縮排情形。
  
## 括弧

