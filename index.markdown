---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
---
<div class="banner flex">
  <img width="254px" height="48px" src="/assets/images/title.png" />
  <div style="color: #F9F9F9; padding: 12px; margin: 16px 0; font-size: 20px;">一个专为大规模智算集群设计的智能故障控制</div>
  <div class="github flex">
  <a></a>
    <img src="https://img.shields.io/github/stars/grafana/grafana?style=social">
    <img src="https://img.shields.io/github/watchers/grafana/grafana?style=social">
    <img src="https://img.shields.io/github/forks/grafana/grafana?style=social">
  </div>
  <div class="quick-start flex"><a target="_blank" href="http://nhi.fed.zhejianglab.org/doc/manual/index.html">点击开始</a></div>
</div>
<div class="features">
  <div class="title">
    功能特性
  </div>
  <div class="subtitle">Functional Features</div>
  <div class="content flex">
    <div class="left">
      <div class="feature">
        <img src="/assets/images/tag.png" width="28px" height="20px" />
        <span style="vertical-align: middle">遥测数据采集</span>
      </div>
      <p>基于vector实现指标与日志的OneAgent式的高性能遥测数据管道；收集、转换和路由所有的日志、指标数据；采用混合精度采集策略，区分故障判别的核心指标与常规指标；它提供针对智算集群优化过的开箱即用的采集器，同时也兼容opentelemetry、victoria metrics servicescrape等采集协议以支持扩展。</p>
    </div>
    <div class="right basis">
      <img src="/assets/images/data.png"  height="224px" />
    </div>
  </div>
  <div class="content flex">
    <div class="left">
      <img src="/assets/images/monitor.png"   />
    </div>
    <div class="right basis">
      <div class="feature">
        <img src="/assets/images/tag.png" width="28px" height="20px" />
        <span style="vertical-align: middle">集群监控</span>
      </div>
      <p>提供一屏化监控、下钻式拓扑可视化、历史数据回溯，支持指标、日志的检索与可视化分析，提升运维人员运维效率。</p>
    </div>
  </div>
  <div class="content flex">
    <div class="left">
      <div class="feature">
        <img src="/assets/images/tag.png" width="28px" height="20px" />
        <span style="vertical-align: middle">故障告警</span>
      </div>
      <p>针对任何类型的遥测信号（日志、指标）设置警报，创建阈值并设置通知渠道以获取告警通知。系统将自动对告警的严重等级、影响范围进行评估，对节点健康度进行打分；系统在k8s控制平面以crd的形式暴露集群故障诊断结果，作业平台、运维人员可基于此对故障进行半自动化的处置。</p>
    </div>
    <div class="right basis">
      <img src="/assets/images/alarm.png"  height="224px" />
    </div>
  </div>
  <div class="content flex">
    <div class="left">
      <img src="/assets/images/health.png"  height="224px" />
    </div>
    <div class="right basis">
      <div class="feature">
        <img src="/assets/images/tag.png" width="28px" height="20px" />
        <span style="vertical-align: middle">主动健康检查</span>
      </div>
      <p>使用日志、指标等被动式的告警难以将故障覆盖完全。本项目还提供日常巡检、深度检查、训前压测等多种主动式健康检查方式，确保作业运行前无潜在隐患。</p>
    </div>
  </div>
  <div class="content flex">
    <div class="left">
      <div class="feature">
        <img src="/assets/images/tag.png" width="28px" height="20px" />
        <span style="vertical-align: middle">运维智能体</span>
      </div>
      <p>基于LLM的多智能体将会在系统的各个环节发挥效果，提供运维知识库、智能故障判定、根因分析、自动化处置，增强系统自治能力。</p>
    </div>
    <div class="right basis">
      <img src="/assets/images/operator.png"  height="224px" />
    </div>
  </div>
  <div class="content flex">
    <div class="left">
      <img src="/assets/images/clusters.png"  height="224px" />
    </div>
    <div class="right basis">
      <div class="feature">
        <img src="/assets/images/tag.png" width="28px" height="20px" />
        <span style="vertical-align: middle">多集群统一观测</span>
      </div>
      <p>一个数据中心有时会存在多个异构的GPU集群，NanHuInsight提供联邦化的故障控制能力，并且已经适配了主流厂商加速器，可以在同一个页面上获得一致的上述功能的体验，避免与厂商提供的监控系统绑定而需要学习多个监控系统。</p>
    </div>
  </div>
</div>