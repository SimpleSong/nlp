# location_nlp
最近在做地理位置的数据清洗，分享一些数据和代码

# 1.全国省市级联数据
1. 数据内容包含，全国省、市、区划、街道，字段有行政区划code，经纬度
2. 数据格式有json和sql
3. 数据来源amap(高德地图)，也有代码可以更新数据哦，不过要配置一下高德地图的开发key，和对应的mysql数据配置，看一下data/__init__.py就懂啦，很简单的
