# kaggle_IEEE

link: https://www.kaggle.com/c/sp-society-camera-model-identification

# summary

* densenet 会优秀许多，224 CROP 是足够的，但应该产生更多数据，这里每张图片只生成了16张图片

* 先把图片分成 train, valid 再去生成 CROP 图片

* gleb dataset 应该帮助不小 (keypoint)

# rank

时间不是很足，最后2天才找到正确的方法。 排名 （219/591, top 38%）

```
xgb_3fold : public score 0.833, private score 0.816

xgb_5fold : public score 0.832, private score 0.821
```
