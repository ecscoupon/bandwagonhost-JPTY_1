# 搬瓦工日本东京(JPTY_1机房)VPS多维度测评 | 硬件质量、三网回程、国际测速、流媒体解锁全套测试数据，综合来看比较适合移动用户

搬瓦工（BandwagonHost）提供日本东京（JPTY_1）机房VPS，官方的表述为AMD+NVMe, Equinix IX, Google, Cloudflare, NTT, Softbank, China Direct，可以看出到中国方向是直连线路。

那么，搬瓦工日本东京（JPTY_1）机房VPS究竟怎么样？本文通过常见Linux命令对搬瓦工日本东京（JPTY_1）机器进行测评，包括硬件质量、带宽速度、路由延迟、网络质量、IP质量等几个方面数据，测评结果仅供参考，具体请以实际使用为准。

## 为什么选择日本东京VPS

东京 VPS 最大优势是**亚太低延迟**，相比美西机房，国内访问延迟更低，网络抖动更小，适合面向中日韩、东南亚的站点与轻量业务。原生东京 IP 对日本本土流媒体、本土平台适配更好，IP 纯净度高，做日本跨境独立站、社媒运营时，风控通过率更高。东京机房基建成熟，带宽资源充足，线路可选软银、IIJ 等优质骨干网，无需备案，建站上线快。但短板也很明显：带宽单价高于美国机房，晚高峰部分普通线路会出现拥堵，IP同样存在流媒体风控风险。

## 关于搬瓦工BandwagonHost

搬瓦工是加拿大 IT7 旗下老牌海外 VPS 服务商，中文主机圈知名度很高，采用 KVM 虚拟化架构，主打 SSD 云主机，支持支付宝、PayPal 等多种支付，对国内用户友好。机房遍布洛杉矶、香港、日本、荷兰、新加坡等地，热门套餐支持 KiwiVM 面板一键切换机房，CN2 GIA 直连线路国内访问延迟低、稳定性强。

搬瓦工套餐选择丰富，带宽多为 1Gbps，自带简单快照备份，适合搭建博客、小型站点与网络测试。需要注意，工单响应速度一般，商家不承诺流媒体解锁，IP 存在风控风险，禁止用于违规用途，选购时优先关注线路与机房库存。

**<a href="https://bwh89.net/aff.php?aff=71768" target="_blank" rel="nofollow noopener noreferrer">搬瓦工官网：点此直达</a>**

<img width="688" height="536" src="https://github.com/ecscoupon/pictures/blob/main/tyvps.png" alt="搬瓦工官网">

## 测试机器方案配置 

本次记录的套餐为 VPS - Self-managed - SPECIAL 20G KVM PROMO V5 - CN2 GIA ECOMMERCE ，参数配置如下：

SSD: 20 GB RAID-10

RAM: 1GB

CPU: 2x AMD EPYC

Transfer: 1000 GB/mo

Link speed: 2.5 Gigabit

搬瓦工日本东京（JPTY_1）基于KVM虚拟化，宿主机为AMD EPYC-Genoa，RAID-10 SSD阵列，最高10Gbps带宽，自带快照和备份功能，自带1个IPv4和IPv6，支持常见Linux发行版，$49.99/季起：
<ul>
 	<li><span style="color: #ff9900;">记得选择“JP - Equinix TY8 Tokyo (JPTY_1)”机房</span></li>
 	<li><span style="color: #ff9900;">该系列可以在16个机房之间一键切换（不包括日本、新加坡、香港CN2 GIA）</span></li>
</ul>
<table>
<tbody>
<tr>
<td style="text-align: center;"><strong>内存</strong></td>
<td style="text-align: center;"><strong>CPU</strong></td>
<td style="text-align: center;"><strong>硬盘</strong></td>
<td style="text-align: center;"><strong>流量</strong></td>
<td style="text-align: center;"><strong>带宽</strong></td>
<td style="text-align: center;"><strong>租用价格</strong></td>
<td style="text-align: center;"><strong>购买地址</strong></td>
</tr>
<tr>
<td style="text-align: center;">1GB</td>
<td style="text-align: center;">2核</td>
<td style="text-align: center;">20GB SSD</td>
<td style="text-align: center;">1TB/月</td>
<td style="text-align: center;">2.5Gbps</td>
<td style="text-align: center;"><span style="color: #ff0000;">49.99美元/季</span></td>
<td style="text-align: center;"><a href="https://bwh89.net/aff.php?aff=71768&pid=87" target="_blank" rel="noopener">官网购买</a></td>
</tr>
<tr>
<td style="text-align: center;">2GB</td>
<td style="text-align: center;">3核</td>
<td style="text-align: center;">40GB SSD</td>
<td style="text-align: center;">2TB/月</td>
<td style="text-align: center;">2.5Gbps</td>
<td style="text-align: center;"><span style="color: #ff0000;">89.99美元/季</span></td>
<td style="text-align: center;"><a href="https://bwh89.net/aff.php?aff=71768&pid=88" target="_blank" rel="noopener">官网购买</a></td>
</tr>
<tr>
<td style="text-align: center;">4GB</td>
<td style="text-align: center;">4核</td>
<td style="text-align: center;">80GB SSD</td>
<td style="text-align: center;">3TB/月</td>
<td style="text-align: center;">2.5Gbps</td>
<td style="text-align: center;"><span style="color: #ff0000;">56.99美元/月</span></td>
<td style="text-align: center;"><a href="https://bwh89.net/aff.php?aff=71768&pid=89" target="_blank" rel="noopener">官网购买</a></td>
</tr>
<tr>
<td style="text-align: center;">8GB</td>
<td style="text-align: center;">6核</td>
<td style="text-align: center;">160GB SSD</td>
<td style="text-align: center;">5TB/月</td>
<td style="text-align: center;">5Gbps</td>
<td style="text-align: center;"><span style="color: #ff0000;">86.99美元/月</span></td>
<td style="text-align: center;"><a href="https://bwh89.net/aff.php?aff=71768&pid=90" target="_blank" rel="noopener">官网购买</a></td>
</tr>
<tr>
<td style="text-align: center;">16GB</td>
<td style="text-align: center;">8核</td>
<td style="text-align: center;">320GB SSD</td>
<td style="text-align: center;">8TB/月</td>
<td style="text-align: center;">5Gbps</td>
<td style="text-align: center;"><span style="color: #ff0000;">159.99美元/月</span></td>
<td style="text-align: center;"><a href="https://bwh89.net/aff.php?aff=71768&pid=91" target="_blank" rel="noopener">官网购买</a></td>
</tr>
<tr>
<td style="text-align: center;">32GB</td>
<td style="text-align: center;">10核</td>
<td style="text-align: center;">640GB SSD</td>
<td style="text-align: center;">10TB/月</td>
<td style="text-align: center;">10Gbps</td>
<td style="text-align: center;"><span style="color: #ff0000;">289.99美元/月</span></td>
<td style="text-align: center;"><a href="https://bwh89.net/aff.php?aff=71768&pid=92" target="_blank" rel="noopener">官网购买</a></td>
</tr>
<tr>
<td style="text-align: center;">64GB</td>
<td style="text-align: center;">12核</td>
<td style="text-align: center;">1280GB SSD</td>
<td style="text-align: center;">12TB/月</td>
<td style="text-align: center;">10Gbps</td>
<td style="text-align: center;"><span style="color: #ff0000;">549.99美元/月</span></td>
<td style="text-align: center;"><a href="https://bwh89.net/aff.php?aff=71768&pid=93" target="_blank" rel="noopener">官网购买</a></td>
</tr>
</tbody>
</table>
<ul>
 	<li>默认支持1个IPv4和IPv6</li>
 	<li>自带免费备份+免费快照</li>
</ul>

### 综合测评数据分享如下

**硬件质量检测报告：** AMD Genoa EPYC，2 核 2 线程，主频约 2445MHz，支持 AES-NI、AVX2，**不支持 VT-x**。内存 1G，开启气球回收与 KSM 复用；硬盘 19G，NVMe 磁盘读写性能不错，顺序读 1222MB/s、写 2016MB/s，随机 IOPS 表现尚可。
综合 HQ 硬件得分 28063。机器已稳定运行 3 天多，负载很低。适合轻量建站、代理测试；但内存偏小，不适合跑大型程序。

<img src="https://github.com/ecscoupon/pictures/blob/main/tyvpscepingdata.png" alt="硬件质量检测报告">

**IPv4大包回程路由测试：** 电信分 163 普通线路与 CMI，国内多地延迟大多 47–80ms，少数地区 20% 丢包且部分节点测试失败，联通主要走 4837 骨干网，延迟普遍 62–126ms、整体零丢包，部分区域是 CMI→4837 混合线路，联通表现最稳，移动全为 CMI 线路，延迟大多 43–103ms、少量地区小幅丢包；整体大包回程零重传 54 个，1~20% 重传 39 个，无大于 20% 严重丢包，联通质量最优，电信部分省份轻微丢包、个别节点不通，移动整体尚可。

<img src="https://github.com/ecscoupon/pictures/blob/main/tyvpscepingdat.png" alt="IPv4大包回程路由测试">

**教育网回程路由延迟测试结果：** IPv4 走 NTT、Cogent 等线路，大部分节点零丢包，但河北、吉林存在高丢包，云南、陕西有小幅丢包；IPv6 基本全不通，大量节点显示失败，整体教育网 IPv4 尚可，IPv6 基本不可用。

<img src="https://github.com/ecscoupon/pictures/blob/main/tyvpscepingda.png" alt="教育网回程路由延迟测试结果">


**国际节点TCP互联网络测试结果：**  国际互联 IPv4/IPv6 全部节点无丢包，亚洲节点延迟最优，日本仅 1ms，香港、新加坡也很低；美西延迟适中，美洲中部东部、欧洲、巴西延迟偏高，IPv6 各区域延迟趋势同 IPv4，整体跨境连通性很好。

<img src="https://github.com/ecscoupon/pictures/blob/main/tyvpscepingd.png" alt="国际节点TCP互联网络测试">

**单线程上行和下行带宽速度测试：** 采用 BBR+fq 拥塞控制，国内三网单线测速：北京整体速度不错，上海电信、广东电信回程重传偏高、速度偏弱，联通与移动表现更好；IPv6 国内移动测速速度偏低；国际 Apple 节点上下行带宽充足无丢包。

<img src="https://github.com/ecscoupon/pictures/blob/main/tyvpsceping.png" alt="单线程上行和下行带宽速度测试">

**回程路由节点详细测试结果：**

<img src="https://github.com/ecscoupon/pictures/blob/main/tyvpscepin.png" alt="回程路由节点">

**IPv4网络质量体检报告：** IP 归属加拿大 Cluster Logic，无 NAT，BBR+fq，国内三网延迟尚可，电信回程分 CMI/163，联通移动走 CMI，国内测速失败，亚洲国际节点延迟低带宽足，欧美延迟偏高。

<img src="https://github.com/ecscoupon/pictures/blob/main/tyvpscepi.png" alt="IPv4网络质量体检报告">

**IPv6网络质量检测报告：**

<img src="https://github.com/ecscoupon/pictures/blob/main/tyvpscep.png" alt="IPv6网络质量检测报告">

**IPv4质量检测数据报告：** IP 定位日本东京，机房广播 IP，IP2Location 高风险、IPQS 标记可疑 IP；TikTok/Youtube/ChatGPT 原生解锁，Disney + 等被屏蔽，Netflix 仅自制库，25 端口可用，邮箱黑名单情况尚可。

<img src="https://github.com/ecscoupon/pictures/blob/main/tyvpsce.png" alt="IPv4质量检测数据报告">

**IPv6质量检测数据报告：**

<img src="https://github.com/ecscoupon/pictures/blob/main/tyvpsc.png" alt="IPv6质量检测数据报告">

## 本次测评小结 - 仅供参考

这台 AS25820 IT7 Networks 东京 VPS，KVM 虚拟化，AMD Genoa EPYC 2 核 2 线程，1G 内存，19G NVMe 硬盘，硬件性能满足轻量建站、网络测试；IP 物理定位东京、注册地加拿大，为机房广播 IP，部分风控库标记高风险 / 可疑 IP。

网络方面：BBR+fq 拥塞控制。国内三网回程联通 4837 线路最稳，电信分 163/CMI 存在少量节点丢包，移动全 CMI 线路，整体无严重大包丢包；教育网 IPv4 部分节点丢包，IPv6 基本失效。国际互联亚洲节点延迟极低，欧美延迟偏高，国际带宽充足。单线测速北京三网速度较好，上海、广东电信重传偏高。

流媒体解锁：TikTok、YouTube、ChatGPT 原生解锁，Netflix 仅自制内容，Disney+、亚马逊 PV、Reddit 屏蔽；25 端口出站可用。适合轻量建站、跨境网络测试，IP 存在风控风险，不适合重度流媒体需求。
