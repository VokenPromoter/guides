# voken到底是做什么的之二：CDN内容分发

各位voken社区的家人们，大家晚上好。上一回我们讲解了“voken到底是做什么的”之第一层的服务，就是国际流量共享服务。
很多社区成员纷纷表示对项目有了真正意义上的了解。

> 注明：不论是线上课程，还是线下沙龙，都只使用**国际流量共享**这样的描述，避开敏感的表达方法。

那么，今天我们进一步来了解一下它的第二层业务，就是CDN内容加速分发，什么是CDN内容分发呢？
CDN的全称是Content Delivery Network，即内容分发网络，（大家可以在百度百科查索到详细的介绍）。

CDN的关键技术主要是内容的存储和分发，什么意思呢，举例，我们平时都有去优酷或者爱奇异看视频吧，
你可能是在上海，也可能是在西安，或者在深圳等全国各个地方的用户，
这些全国各地的用户是访问了优酷在不同地区的服务器的，
大家都在这上面看视频，优酷这家公司是需要向机房支付费用的，这是传统的CDN服务，
由一家机构或组织集中提供服务，大量的用户透过这个中心化的机构得到服务，
这种传统中心化的 CDN 服务，依赖于 IDC 机房或云服务商，节点数量有限，资源昂贵而且容易形成访问服务压力，
而现在我们要做的就是分布式的CDN服务，什么意思呢，
我原来在上海，我在优酷上看视频，内容是从优酷华东服务器分出来的吧，因为存储也在优酷这个网站啊，
我原来是在深圳，我在优酷上看视频，也要由优酷的可能是华南服务器上分出来，
那分布式CDN怎么做呢，是通过在网络各处设置节点服务器，
使用户可就近取得所需内容，使内容传输更快、更高效，
解决 Internet网络拥挤的状况，提高用户获取内容的响应速度。

举例：我想看一集《新白娘子传奇》的电视剧，
不用从优酷的服务器出来了，从哪来呢，可以从我家邻居的节点来，因为他近期看过，
内容就直接从他那里传给我，大大提高了速度，效率非常高，
这个时候，优酷也不用向机房或云服务商付费了，直接付给我邻居就好了，
付什么的呢，按量支付 voken，
也就是说分布式CDN它完全不同于传统的集中化的存储和分发了，
而是利用散落在各地的闲置终端和闲置的带宽来提供服务，
它可以是你家的电视盒子，也可能是电脑，或者路由器、手机等，
这样做的直接好处是降低了B端也就是企业或组织的成本，
所有关于视频、直播、网游等提供内容服务的行业企业都将大幅度降低CDN成本，
而提供服务节点让闲置的带宽分享出来，成为CDN供应商，收取回报，
这又是一门天经地意的生意，供需非常明确，
这就是voken的第二层业务，它主要是为企业、机构、组织、或个人网站等提供服务的，业内简称2B业务（To B业务）。
这也是voken这个项目的独有优势，因为前一节我们已说过，
经过第一层业务的开展，voken在全球已经拥有大量的节点，
不论是原来的服务节点还是使用节点，都可以参与到CDN业务中来，将自己家里或办公室的闲置和闲时带宽贡献出来赚取收入。

好，那接下来，我们来了解一下传统CDN服务的收费方式和计价方式。
这一点大家也可以动动手指在网上自己查一下，都是行业公开的数据，报价非常清晰，
还是前面提倡的观点，很多事情自己查一下就心里有数了，
你听身边的人说，凭所谓的感觉去判断是不理性的，也是不科学的，
不如去了解这个行业的真实情况，只是动动手指头百度一下而已嘛，又能麻烦和复杂到哪里去呢？

你认真去做功课了，你会发现voken项目白皮书里面所有提到的专业以及内容是多么的真实和客观，
这是目前为止，能了解到的行业内人的一致好评，也是我们V5社区越来越坚定跟随项目方一直做这个项目的主要原因。

好，那现在讲收费，目前，国际主要是采用流量计费方式，
举例亚马逊云和谷歌云，国际主流的计费标准是每1个G价格8到8.5美分，按每100G算就是8到8.5美金，
然后，亚洲的计价标准每100G是14到20美金，南美和非洲的流量更贵。
那么，现在voken的发行价是从0.001到0.601大家记得，每一个voken锚定的是100G的流量，
那么，我们又可以算一下这里机的利润空间了吧，就算你是在0.601的价格阶段投资voken的，你也同样拥有巨大的利润空间，
所以为什么我们从上周的培训课程后，大家有没有发现，
在已上市voken的交易所看不到有什么大量的出售voken的卖盘了吧，
随着了解，越来越多的人都选择持有voken了，而且，大部分的人都不懂，以为项目方无所作为，
其实大家恰恰说错了，或者说是误解了，因为据我们所知，项目方正在大量做关于服务节点的工作展开，
这其实是目前整个项目当中最有价值的一环，我们说的是目前，它比任何的做市或是操控价格都来得实际，这才是项目方目前最应该做的事。

好的，那么还是那句话，认知是投资的变现，在公开的项目上，
每个人怎么看项目是没有人能强加说服的，我们也很认同项目方提出来的寻找合格投资者理念，
所谓的合格投资者就是你要明白，并且是主动去搞明白这是一件什么样的事情，
而你参与进来又是为了得到什么，你愿意付出什么，愿意承担什么样的风险，
这才是一个合格的投资者，无论你投什么样的项目，都是这样的。
所以，我们会全力配和项目稳稳推动市场销售以及社区的建设、服务及管理，
在此，欢迎越来越多的社区爱好者共同加入V5社区联盟，我们一起实现梦想。

今晚的课程就先到这里，下一节课程是讲第三层的DDoS安全防御服务，下次再见各位家人。
