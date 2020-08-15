# 通信

ARQ(Automatic Repeat Request)：再送制御．再送による遅延が生じるためリアルタイム性が要求されないデータ通信などのサービスで利用．  
Stop and Wait ARQ：もっとも単純なARQ．往復時間が大きなシステム(衛星通信など)では伝送効率が大きく低下するため不向き．  
Go Back N ARQ：Stop and Wait ARQに比べて効率的．  
Selective Repeat ARQ：最も効率が良いARQ受信データを一時的に蓄積するためにバッファが必要．出力側ではデータの正しい順序への並び替えが必要．  
インターリーブ：バースト誤りの対処法．バースト誤りをランダム誤りに変換する．  