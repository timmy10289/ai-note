# 人工智慧

### 傳統 
 
* 搜尋(深度優先，廣度優先，最佳優先) + 優化 = 解空間搜尋(ex : Min-Max)  
### 機器學習  
* 統計  
* 神經網路 → 深度學習(模型: CNN , RNN , LSTM , BERT)  
### 應用  
* 影像  
  特徵  
  CNN  
  Yolo  
* 語言  
 規則  
 統計  
 RNN 
 BERT  
* 下棋  
 Min -Max  
 MCTS  
* 自動控制  
 機器人車
* 優化  
 數學(機率統計，微積分，代數(線性代數，三角函數)，幾何(微分幾何))  
 科學計算  
 
 # 爬山演算法  
 用 -(x^2+3*x+5)  
 ```
 def hillClimbing(f, x, dx=0.01):
    while (True):
        print('x={0:.5f} f(x)={1:.5f}'.format(x, f(x)))
        if f(x+dx)>f(x): 
            x = x + dx
        elif f(x-dx)>f(x): 
            x = x - dx
        else:
            break
    return x


def f(x):
    return -1*(x*x+3*x+5)
    

hillClimbing(f, 0) 
```  
# 結果  
```
x=-1.38000 f(x)=-2.76440
x=-1.39000 f(x)=-2.76210
x=-1.40000 f(x)=-2.76000
x=-1.41000 f(x)=-2.75810
x=-1.42000 f(x)=-2.75640
x=-1.43000 f(x)=-2.75490
x=-1.44000 f(x)=-2.75360
x=-1.45000 f(x)=-2.75250
x=-1.46000 f(x)=-2.75160
x=-1.47000 f(x)=-2.75090
x=-1.48000 f(x)=-2.75040
x=-1.49000 f(x)=-2.75010
x=-1.50000 f(x)=-2.75000
```  
算出最高點x為-1.5 但這個解只會是區域性的解  
![image](https://github.com/timmy10289/pic/blob/main/a.jpg)  
 
 
