# Data_hw1
## hw1_1
* 程式說明
  * 輸入(n r)，輸出(n(n-1)...(n-r+1))/r!。
  * 使用遞迴，遞迴的終止條件為r==1時。
* 程式設計
  * 我希望可以從小乘(除)到大，例如:(n r)=(6 3)時，可以先4/1<(n-2)/(r-2)>再乘以5/2<(n-1)/(r-1)>最後再乘以6/3<n/r>。
  * 若還未到終止條件，則return func(n-1,r-1)n/r，每次呼叫的function中的參數n和r皆須減一，直到達終止條件。
  * 達終止條件時，回傳n/r。
* 程式架構
  * if (達終止條件) 回傳數值。
  </enter>else call function。(n--;r--;)
