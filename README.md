# Program_class

### 程式語言觀念
  + 作業系統(OS): https://zh.wikipedia.org/wiki/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F 
    + 命令列(Command Line)模式。互動式的操作方式:鍵盤打字。
    + 圖形化使用者介面(GUI)或稱視窗程式。互動式的操作方式:鍵盤+滑鼠。

  + 直譯式語言 (MATLAB、Python、PHP、JavaScript)
    + MATLAB.exe script.m
  + 編譯式語言 (C/C++、Fortran、C#)
    + xxx.c -> xxx.exe  , 使用Windows執行xxx.exe 

```Matlab
%--------------------------------------------------------------------------
% 把所有不限數量空格分開的字串取出
Target_String=['   56   74   29    0 LOGE'];
% 將目標字串依序匹配所有連續非空格的字符並輸出。等效於把所有空格分開的字串取出。
% 「\S」指空白符號，後面接著「+」就是1~Inf個。
Output_cell=regexp(Target_String,'\S+','match');
%--------------------------------------------------------------------------
```
