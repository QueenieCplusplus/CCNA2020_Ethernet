# CCNA2020_Ethernet
相對於 WAN 而言是小範圍地理的區域網路，想對 WLAN 的無線，Ethernet 是有線的。
乙太網至今發展了 40 年。

因為有線網路是有線的，有賴線路和連結器（如 AUI ）接收器的媒介，任何一處細節都會造成網路的不穩定。

# MAC 的數據傳輸協定，一種匯流排傳輸技術

CSMA, Carrier Sense Multiple Access / CD 即（影格）載波偵測多重（媒體）存取/碰撞偵測。

如上的載波體即無線電波，此技術提供了讓多台主機共享一條通道！



                  @1

                線路空閒 | 線路忙碌

                   |         |

                開始傳輸     等待（隔一段時間）

                   |         |

                傳輸成功      @1（重新嘗試連線, 計算連續次數）
 
                             |

                       斷開傳輸連線的嘗試 （一旦超過最大嘗試重新連線次數）
