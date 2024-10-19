---
title: '交通-能源网络协同部署优化'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
# Author notes (optional)
author_notes:
  - 'Equal contribution'

date: '2023-01-02T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
# publication: In *Hugo Blox Builder Conference*
# publication_short: In *ICW*

summary: 过去几十年，关于基础设施站点规划的问题得到了充分地研究。根据规划主体和需求估计的不同，我们将站点规划研究划分为三个阶段。受模型结构和算法效率的限制，在0.0传统规划研究中，大多基于静态的用户能源需求对充电站点进行部署优化。在此基础上，我们在1.0规划中秉承运营与规划一体化的理念，在规划层面进行设施资源配置的同时，考虑系统内各主体的动态运营交互，从而实现设施资源与动态能源需求在时空维度的供需匹配，保障交通与供电网络的动态可持续运营。进一步，在2.0规划中，我们面向交通-能源多网络耦合规划问题，考虑交通流、能量流和信息流之间的耦合互动，综合、高效利用交通和能源系统资源，实现交通、供电与发电网络的协同运作和布局规划，有效解决车流、补给设备、供能不协调的现实问题。

# Summary. An optional shortened abstract.
work_description: |-
  我们针对1.0规划和2.0规划在不同场景中的应用展开了一系列研究。在1.0规划中，分别采用双层优化模型和数据驱动优化模型对高速公路快充网络和城市出租车换电网络进行部署优化。在2.0规划中，针对高速公路场景中两种具有应用前景的交能融合模态:区域电源结构转型和分布式公路交通能源系统建设展开了研究。        

  第一种高速公路交能融合模态是区域电源结构转型。该交能融合模态适用于服务区电网发达、区域能源优势显著的高速公路网络。在该交能融合模态中，公路服务区的电力仅由当地电网进行供应，通过对区域内整体电力结构进行转型优化，实现公路交通用能的清洁化。为实现速公路充电网络部署与区域电源结构转型在时间和空间上的匹配，我们综合考虑设施可持续运营、电动汽车可达性和网络多阶段有序建设，提出了一种以提升网络节能减排效益和优化设备利用率为导向的高速公路充电网络三步骤迭代规划方法。以山东半岛城市群高速公路网络为例，在胶东半岛核电群发展规划的背景下，展开2025年-2045年间的设施网络动态部署方案研究，并阐明了模型中秉承的运营与规划一体化、发挥网络需求诱导作用、保障电动汽车可达性等规划理念对于高速公路充电网络规划与管理的重要性。       

  针对出租车行业的电动化，我们探讨了换电模式下出租车的运输服务与补能服务的运营情况。基于出租车GPS数据，我们在利用离散选择模型对出租车司机在运营过程中的换电行为建模第二种高速公路交能融合模态是分布式公路交通能源系统建设。分布式公路交通能源系统尤其适用于服务区电网薄弱但地区可再生能源丰富的高速公路网络。在该交通融合模态中，公路服务区通过将分布式风机、光伏、储能、可控负荷、主电源进行统一整合，构建既可与大电网并联运行，又可以独立于大电网的、孤岛运行的微型电力网络。在公路交通用能自洽目标的驱动下，为建设一个具有高服务水平、能源自洽和可持续运营的公路“风-光-储-充”能源网络，我们提出了一个嵌套双层优化模型，在实现系统内电动汽车用户、供电设施和发电设施动态交互与协同运行的同时，以公路交通能源网络净现值最大化为目标，对充电站位置与容量及其所配套的风-光-储发电系统设备的额定装机容量与功率进行优化部署。针对性的，提出了一种以启发式算法为主体，结合多智能体仿真技术与整数规划算法的混合求解算法。进一步，选取内蒙古“呼-包-乌”城市群局域高速公路为实际案例。研究表明该模型实现了交通网络、充电网络与发电网络的深度耦合，在交通侧积极发挥基础设施对需求的管理与诱导作用，在能源侧充分挖掘多种可再生能源的发电互补和储能设备的削峰填谷优势。的前提下，采用数据驱动方法对出租车换电网络内的乘客订单请求、司机换电决策和换电站服务操作的动态交互进行仿真建模。仿真系统实现对嵌入换电活动的出租车出行链的重构，并对出租车运输服务和换电设施网络服务进行逐秒高精度仿真与监测。         


abstract: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.



tags:
  - 基础设施选址规划

# Display this page in the Featured widget?
featured: true
---

<!-- **简介** 

新型交通能源系统“源-网-荷-储”的协同运作被广泛认为是有效是有效提升提升两大系统的综合运营效率和推动交通领域低碳化的重要手段。我们在剖析系统内源源互补、源网协调、网荷互动、网储互动和源荷互动等多元动态交互关系的基础上，基于丰富的城市地理、交通和电网大数据，采用数据驱动和多智能体仿真技术，实现交通能源系统中“人-车-路-桩-能-信息”的协同运行与管理。它为新型交通能源系统的运营管理、设施部署、产业评估提供空间粒度精细、时间粒度精确、状态维度丰富的数据基础。 -->