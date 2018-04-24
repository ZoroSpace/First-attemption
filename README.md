# IJCAI-18 阿里妈妈搜索广告转化预测 初赛心得

之前在天池上参加了那个o2o优惠券的新人赛，跟着大神的代码和思路学到了很多以前完全不了解的东西，
这次阿里妈妈搜索广告转化预测的题的类型和那个新人赛是非常相似的，所以划分数据；特征提取以及后面的模型训练都是跟着他们之前做o2o那个思路做的

数据的划分是用的划窗法
提取特征主要是从
user_id,item_id,shop_id,item_brand_id 来提取如打开次数，购买次数，购买频率之类的特征，
另外还有利用一些分类变量来提取类似的特征，比如item_sales_level;item_price_level；item_category_list之类提取各自类别的这些特征
当然还有最重要的就是判断用户是否是当日最后/第一次打开这个广告，这个提出来对模型的提升还是很大的

不过我这个成绩也就只是混过了初赛而已，作为一个天池新人还有很多要学的，比如我这次各种各样花式提特征提了两百个，不知道到底哪些是需要的，
哪些又是不需要的，对于特征选择我还一窍不通，希望复赛完能帮我解决这些问题。
