Tang 分子科学计算平台
====================

.. raw:: html

   <section class="tang-hero">
     <div class="hero-copy">
       <span class="hero-kicker">TANG MOLECULAR SCIENCE</span>
       <h1>一个界面，连接 Windows 与科学计算环境</h1>
       <p>在 Windows 中准备任务，由便携式 WSL 后端自动选择电子结构或分子动力学计算引擎，并将结果带回 Windows。</p>
       <div class="hero-tags">
         <span>Electronic Structure</span>
         <span>Nuclear Motion</span>
         <span>Molecular Dynamics</span>
       </div>
     </div>
     <div class="hero-orbit" aria-hidden="true">
       <i></i>
       <b></b>
       <em></em>
     </div>
   </section>

快速入口
--------

.. raw:: html

   <div class="module-grid">
     <a class="module-card blue" href="modules/electronic-structure.html">
       <strong>电子结构理论</strong>
       <span>WFT、DFT、SUHF、NEB、POM</span>
       <small>Support · 徐昕 · 苏忠明 · 曲泽星</small>
     </a>

     <a class="module-card violet" href="modules/nuclear-motion.html">
       <strong>核运动理论</strong>
       <span>为后续核运动计算模块预留</span>
       <small>Support · 李辉</small>
     </a>

     <a class="module-card green" href="modules/molecular-dynamics.html">
       <strong>分子动力学</strong>
       <span>基于 PYGAMD 的 GPU 加速模拟</span>
       <small>Support · 朱有亮 · 吕中元</small>
     </a>
   </div>

.. toctree::
   :maxdepth: 2
   :caption: 开始使用

   guide/introduction
   guide/installation
   guide/quick-start
   guide/gui

.. toctree::
   :maxdepth: 2
   :caption: 计算模块

   modules/electronic-structure
   modules/nuclear-motion
   modules/molecular-dynamics

.. toctree::
   :maxdepth: 2
   :caption: 系统与维护

   reference/architecture
   reference/task-routing
   reference/troubleshooting
   reference/build-and-release

.. toctree::
   :maxdepth: 1
   :caption: 关于

   about/support