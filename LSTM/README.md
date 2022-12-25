目前功能：

data_process：把資料格式調成以月為單位的（大概要跑半小時，不過檔案應該有小很多，我放在 https://drive.google.com/drive/folders/1hm-Kq3tEjpw9mFThDX4AuKNBnUPUCLC3?usp=share_link 和 https://drive.google.com/drive/folders/1rSA6F5fZ0a2NqHT6YSjbDPAdpSMXKnMQ?usp=share_link）。

LSTM：拿V_cred來train，拿V_cred_public來測試。



TODO:

1.把五個V_的資料做適當合併，一起丟進LSTM來train。

2.oversampling。