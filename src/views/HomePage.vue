<template>
  <el-container>
    <el-header
      style="box-shadow: 0px 15px 10px -15px #72767b; height: 65px; position: fixed; width: 100%; z-index: 9999; background-color: #ffffff; padding:0 15%">
      <el-row>
        <el-col :span="6">
          <img src="../assets/img/0Logo.png" style="height: 45px; margin-left: 30px; margin-top: 10px;" />
        </el-col>
        <el-col :span="18">
          <el-menu mode="horizontal" :default-active="active" :active-text-color="primaryColor" text-color="#000000"
            style="width: 100%; text-align: right; background-color: #ffffff" @select="scrollTo">
            <el-menu-item index="0">项目介绍</el-menu-item>
            <el-menu-item index="2">项目亮点</el-menu-item>
            <el-menu-item index="3">关于我们</el-menu-item>
          </el-menu>
        </el-col>
      </el-row>
    </el-header>

    <el-main style="margin-top: 3%">
      <el-row style="text-align: center">
        <h1 style="font-size: 100px; margin: 0;">
          <span :style="{ 'color': primaryColor }">Geo</span>U
        </h1>
        <h2 style="font-size: 40px; margin: 0;">
          久宇时空智能舱：时空大数据智能服务平台
        </h2>
      </el-row>

      <el-row style="text-align: center; align: center; margin-top: 3%">
        <img src="../assets/img/1SpatiotemporalInformationEnablesHighQualitySocialDevelopment.jpg"
          style="width:65%; margin-bottom: 1%">
      </el-row>

      <el-row>
        <el-col :offset="4" :span="16">
          <p class="justify">
            <strong>久宇时空智能舱</strong>是浙江工业大学地理信息学院发展时空信息与人工智能交叉学科的创新载体项目，
            可为<strong>实景三维</strong>、<strong>低空飞行</strong>、<strong>自动驾驶</strong>、
            <strong>空天地通感算一体化</strong>等新兴产业以及保障社会治理、自然资源、生态环境、绿色能源等可持续发展提供底层技术支撑，
            并通过科产教融汇打造成时空智能领域的科教人一体化交叉学科创新示范项目。
          </p>
          <p class="justify">
            <strong>时空数据面临的挑战：</strong>
            时空数据存在 <strong>数据模态多、数据质量低、数据不对齐、数据安全弱</strong> 等问题。这导致数据治理和服务中出现一系列技术难题，例如：
            数据难以统一表征、数据检索效率低下、数据融合与利用困难、模型难以场景迁移、数据隐私保障不足。
          </p>
        </el-col>
      </el-row>

      <el-row style="text-align: center; align: center; margin-top: 3%">
        <img src="../assets/img/2Architecture.jpg" style="width:65%; margin-bottom: 1%">
      </el-row>

      <el-row>
        <el-col :offset="4" :span="16">
          <p class="justify">
            <strong>解决方案：</strong>
            构建了一个时空大数据智能服务平台 —— 
            <span class="important">GeoU 久宇·时空智能舱</span>。该平台旨在：
          </p>
          <ul class="bullet-list">
            <li>
              <strong>向下：</strong> 为多源异构的时空数据提供统一的接入、存储、计算、治理、建模和安全能力
            </li>
            <li>
              <strong>向上：</strong> 为时空数据消费者（如智慧城市治理、实景三维导航、自然资源测绘）提供高质量、一体化的数据服务
            </li>
          </ul>
        </el-col>
      </el-row>

      <el-row style="text-align: center; align: center; margin-top: 3%">
        <img src="../assets/img/3DataStructure.jpg" style="width:65%; margin-bottom: 1%">
      </el-row>

      <el-divider></el-divider>

      <el-row>
        <el-col :offset="4" :span="16">
          <h3 style="text-align: center; align: center; margin-top: 30px; margin-bottom: 15px; color: #EB6A3F">
            久宇·时空智能舱GeoU：开启时空大数据智能服务新篇章
          </h3>
          <p class="justify">
            时空数据是连接数字世界与物理世界的关键要素。在万物互联的大数据大模型时代，时空信息的提取与知识挖掘需要走向智能化，
            <span class="important">时空智能学</span> 将成为人工智能的重要组成部分。近日，国家最高科技奖获得者
            <span class="important">李德仁院士</span>
            公开提出「时空智能学」概念，称其是利用通导遥智能传感器、云计算和人工智能方法对自然活动和人类活动进行感知、认知，支持智能决策的一门科学和技术，
            是测绘遥感和地理信息学发展的新阶段，是助力时空信息高质量发展、赋能新质生产力的重要途径。
          </p>
        </el-col>
      </el-row>

      <el-row style="text-align: center; align: center; margin-top: 3%">
        <img src="../assets/img/4CalculateStructure.jpg" style="width:65%; margin-bottom: 1%">
      </el-row>

      <el-row>
        <el-col :offset="4" :span="16">
          <p class="justify">
            时空信息产业是数字经济重要组成部分，
            <span class="important">2035 远景目标纲要</span> 多处重点提及时空信息技术，国家
            <strong>「十四五」</strong>规划 <strong>102 项重大工程</strong> 中近 80 项与地理时空信息产业相关，涉及交通强国、国家水网、生态系统等领域。2024 年 4 月，
            <span class="important">中国时空信息集团有限公司</span> 在雄安新区的成立，标志着时空信息开辟万亿级国家战略新兴产业「新赛道」。
          </p>
          <p class="justify">
            在此背景下，浙江工业大学地理信息学院
            <span class="important">陈铁明</span> 教授领衔的时空智能计算与治理科研团队在 2024 年世界互联网大会「互联网之光」博览会上发布了最新研制的科技创新成果
            —— <strong>GeoU 久宇·时空智能舱</strong>，这是一个全新的时空大数据智能服务平台框架。
          </p>
        </el-col>
      </el-row>

      <el-row style="text-align: center; align: center; margin-top: 3%">
        <img src="../assets/img/5AIStructure.jpg" style="width:65%; margin-bottom: 1%">
      </el-row>

      <el-row>
        <el-col :offset="4" :span="16">
          <p class="justify">
            《墨子·经上》称「久，弥异时也；宇，弥异所也。」哲学上的「久」特指时间，「宇」特指空间，因此「久宇」也是古时对「时空」概念的一种科学说法。
            秉承时空智能学的理念，「久宇」对应的英文谐音 GeoU，恰可代表本项目的建设宗旨：地理时空信息（Geo）可为用户（U）提供无处不在的智能服务。
          </p>
        </el-col>
      </el-row>

      <el-row style="text-align: center; align: center; margin-top: 3%">
        <img src="../assets/img/6SecStructure.jpg" style="width:65%; margin-bottom: 1%">
      </el-row>

      <el-row>
        <el-col :offset="4" :span="16">
          <p class="justify">
            久宇时空智能舱（以下简称「久宇」）的研发目标是「让时空数据可见、让时空信息可用、让时空智能可信」。针对时空数据多模态、质量差、计算难、安全弱等技术挑战，
            以时空数据赋能高质量发展为目标，通过突破时空数据统一接入表征、时空数据库基础软件、多模态跨场景时空数据智能计算、时空数据全生命周期安全保障等关键技术，
            向下为多源异构时空数据提供统一的接入、存储、计算、治理、建模和安全能力，向上为时空数据消费者提供高质量、一体化的数据服务。
          </p>
        </el-col>
      </el-row>

      <el-row style="text-align: center; align: center; margin-top: 3%">
        <img src="../assets/img/7DevStructure.jpg" style="width:40%; margin-bottom: 1%">
      </el-row>

      <el-row>
        <el-col :offset="4" :span="16">
          <p class="justify">
            「久宇」的核心技术架构包括 <strong>数据底座、计算底座、智能底座和安全底座</strong> 四大模块。通过这些底层能力的系统化设计，
            「久宇」为用户提供三种应用方式 —— <strong>开箱即用、数据托管和智能定义</strong>，灵活满足不同用户的需求。
            「久宇」是对时空数据智能治理与服务的技术全新升级，通过系统化的底座设计，将复杂多源的时空数据转化为高效、精准、智能的决策资源，
            为时空信息产业高质量发展提供全新的创新应用动能。
          </p>
        </el-col>
      </el-row>

      <el-row style="text-align: center; align: center; margin-top: 3%">
        <img src="../assets/img/8Community.jpg" style="width:65%; margin-bottom: 1%">
      </el-row>

      <el-divider></el-divider>

      <el-row style="margin-top: 3%; text-align: center">
        <h4 style="font-size: 40px; margin: 0;">项目亮点</h4>
      </el-row>

      <el-row style="margin-top: 2%; margin-bottom: 2%; padding: 0 5%;">
        <el-col :offset="7" :span="4">
          <el-card :style="{ 'width': cardDiameter, 'height': cardDiameter }"
            style="border-radius: 230px; text-align: center; box-shadow: 0px 1px 10px 0px #7E7E82">
            <div style="margin-top: 30px;">
              <svg t="1681461908167" class="icon" viewBox="0 0 1024 1024" version="1.1"
                xmlns="http://www.w3.org/2000/svg" p-id="11256" width="50" height="50">
                <path
                  d="M586.666667 855.893333h-149.333334A55.466667 55.466667 0 0 1 384 800v-80.213333A246.613333 246.613333 0 0 1 508.16 264.533333a243.2 243.2 0 0 1 180.053333 73.813334A245.76 245.76 0 0 1 640 719.786667v80.213333a55.466667 55.466667 0 0 1-53.333333 55.893333z m-145.066667-61.44h140.8v-78.506666a56.746667 56.746667 0 0 1 27.306667-48.213334A183.04 183.04 0 0 0 646.4 384a186.453333 186.453333 0 0 0-272.64 5.973333 182.186667 182.186667 0 0 0-48.64 128 184.32 184.32 0 0 0 89.173333 149.76 56.746667 56.746667 0 0 1 27.306667 48.213334z"
                  fill="#dc714b" p-id="11257"></path>
                <path
                  d="M353.28 877.226667m29.44 0l258.56 0q29.44 0 29.44 29.44l0 2.56q0 29.44-29.44 29.44l-258.56 0q-29.44 0-29.44-29.44l0-2.56q0-29.44 29.44-29.44Z"
                  fill="#dc714b" p-id="11258"></path>
                <path
                  d="M507.306667 256a29.866667 29.866667 0 0 1-29.44-30.72V116.053333a29.866667 29.866667 0 1 1 59.306666 0v107.52a30.293333 30.293333 0 0 1-29.866666 32.426667zM908.8 536.746667h-107.946667a30.72 30.72 0 0 1 0-61.44h107.946667a30.72 30.72 0 0 1 0 61.44zM223.146667 546.133333H115.2a30.72 30.72 0 0 1-29.866667-31.146666 30.293333 30.293333 0 0 1 29.866667-30.72h107.946667a30.293333 30.293333 0 0 1 29.866666 30.72 30.72 30.72 0 0 1-29.866666 31.146666zM712.96 335.36a30.72 30.72 0 0 1-21.333333-9.386667 32 32 0 0 1 0-42.666666L768 206.08a29.44 29.44 0 0 1 42.666667 0 32 32 0 0 1 0 42.666667l-76.8 75.946666a28.586667 28.586667 0 0 1-20.906667 10.666667zM304.64 341.333333a29.44 29.44 0 0 1-20.48-8.533333L207.36 256a32.853333 32.853333 0 0 1 0-42.666667 29.866667 29.866667 0 0 1 42.666667 0l75.093333 75.093334a32 32 0 0 1 0 42.666666 29.866667 29.866667 0 0 1-20.48 10.24zM645.973333 517.973333a30.293333 30.293333 0 0 1-28.16-21.333333A91.733333 91.733333 0 0 0 547.84 426.666667a31.146667 31.146667 0 0 1-26.453333-33.706667 30.293333 30.293333 0 0 1 33.28-29.013333 150.613333 150.613333 0 0 1 121.173333 113.066666 31.573333 31.573333 0 0 1-18.773333 39.253334 39.68 39.68 0 0 1-11.093334 1.706666z"
                  fill="#dc714b" p-id="11259"></path>
              </svg>
            </div>
            <div style="margin-top: 15px; font-size: 25px">多模态</div>
          </el-card>
        </el-col>
        <el-col :offset="3" :span="4">
          <el-card :style="{ 'width': cardDiameter, 'height': cardDiameter }"
            style="border-radius: 230px; text-align: center; box-shadow: 0px 1px 10px 0px #7E7E82">
            <div style="margin-top: 30px;">
              <svg t="1681461766337" class="icon" viewBox="0 0 1024 1024" version="1.1"
                xmlns="http://www.w3.org/2000/svg" p-id="9617" id="mx_n_1681461766340" width="50" height="50">
                <path
                  d="M950.044444 671.288889V349.866667c34.133333-11.377778 56.888889-42.666667 56.888889-79.644445 0-48.355556-36.977778-85.333333-85.333333-85.333333-31.288889 0-59.733333 17.066667-73.955556 42.666667l-238.933333-128c0-45.511111-39.822222-85.333333-85.333333-85.333334s-85.333333 36.977778-85.333334 85.333334L199.111111 224.711111C182.044444 199.111111 156.444444 182.044444 125.155556 182.044444c-48.355556 0-85.333333 36.977778-85.333334 85.333334 0 36.977778 22.755556 68.266667 56.888889 79.644444v324.266667c-34.133333 11.377778-56.888889 42.666667-56.888889 79.644444 0 48.355556 36.977778 85.333333 85.333334 85.333333 31.288889 0 59.733333-17.066667 73.955555-42.666667l238.933333 128c0 45.511111 39.822222 85.333333 85.333334 85.333333s85.333333-36.977778 85.333333-85.333333l238.933333-128c14.222222 25.6 42.666667 42.666667 73.955556 42.666667 48.355556 0 85.333333-36.977778 85.333333-85.333334 0-36.977778-25.6-68.266667-56.888889-79.644444z m-59.733333 2.844444l-256-147.911111c2.844444-8.533333 5.688889-19.911111 5.688889-28.444444s-2.844444-19.911111-5.688889-28.444445l233.244445-133.688889 25.6 17.066667v324.266667c-2.844444-5.688889-2.844444-5.688889-2.844445-2.844445z m-287.288889-256c-14.222222-14.222222-31.288889-25.6-54.044444-31.288889V179.2c14.222222-5.688889 28.444444-14.222222 36.977778-25.6l247.466666 133.688889-230.4 130.844444z m-108.088889-238.933333v207.644444c-19.911111 5.688889-39.822222 17.066667-54.044444 31.288889L207.644444 284.444444 455.111111 150.755556c11.377778 11.377778 22.755556 22.755556 39.822222 28.444444zM179.2 332.8l233.244444 133.688889c-2.844444 8.533333-5.688889 19.911111-5.688888 28.444444s2.844444 19.911111 5.688888 28.444445l-256 147.911111h-2.844444V349.866667l25.6-17.066667zM199.111111 713.955556l241.777778-136.533334c14.222222 14.222222 31.288889 25.6 54.044444 31.288889v236.088889c-14.222222 5.688889-28.444444 14.222222-36.977777 25.6l-247.466667-133.688889c-2.844444-8.533333-5.688889-17.066667-11.377778-22.755555z m352.711111 128v-236.088889c19.911111-5.688889 39.822222-17.066667 54.044445-31.288889l241.777777 136.533333c-2.844444 8.533333-5.688889 14.222222-8.533333 22.755556l-247.466667 133.688889c-11.377778-11.377778-25.6-19.911111-39.822222-25.6z"
                  p-id="9618" fill="#dc714b"></path>
              </svg>
            </div>
            <div style="margin-top: 15px; font-size: 25px">强计算</div>
          </el-card>
        </el-col>
      </el-row>

      <el-row style="margin-top: 2%; margin-bottom: 5%; padding: 0 5%;">
        <el-col :offset="3" :span="4">
          <el-card :style="{ 'width': cardDiameter, 'height': cardDiameter }"
            style="border-radius: 230px; text-align: center; box-shadow: 0px 1px 10px 0px #7E7E82">
            <div style="margin-top: 30px">
              <svg t="1673184233076" class="icon" viewBox="0 0 1024 1024" version="1.1"
                xmlns="http://www.w3.org/2000/svg" p-id="2123" :width="iconDiameter" :height="iconDiameter">
                <path
                  d="M512 981.333333c-36.266667 0-70.4-12.8-96-38.4l-38.4-36.266666c-12.8-12.8-29.866667-21.333333-49.066667-21.333334l-53.333333-2.133333c-74.666667-2.133333-132.266667-61.866667-134.4-134.4l-2.133333-53.333333c0-19.2-8.533333-36.266667-21.333334-49.066667l-36.266666-38.4a136.533333 136.533333 0 0 1 0-189.866667l36.266666-38.4c12.8-12.8 21.333333-29.866667 21.333334-49.066666l2.133333-53.333334c2.133333-74.666667 61.866667-132.266667 134.4-134.4l53.333333-2.133333c19.2 0 36.266667-8.533333 49.066667-21.333333l38.4-36.266667a136.533333 136.533333 0 0 1 189.866667 0l38.4 36.266667c12.8 12.8 29.866667 21.333333 49.066666 21.333333l53.333334 2.133333c74.666667 2.133333 132.266667 61.866667 134.4 134.4l2.133333 53.333334c0 19.2 8.533333 36.266667 21.333333 49.066666l36.266667 38.4a136.533333 136.533333 0 0 1 0 189.866667l-38.4 38.4c-12.8 12.8-21.333333 29.866667-21.333333 49.066667l-2.133334 53.333333c-2.133333 74.666667-61.866667 132.266667-134.4 134.4l-53.333333 2.133333c-19.2 0-36.266667 8.533333-49.066667 21.333334l-38.4 36.266666C580.266667 968.533333 546.133333 981.333333 512 981.333333z m0-874.666666c-19.2 0-38.4 8.533333-51.2 21.333333l-38.4 36.266667c-25.6 23.466667-57.6 36.266667-91.733333 38.4H277.333333c-40.533333 0-72.533333 34.133333-74.666666 74.666666l-2.133334 53.333334c0 34.133333-14.933333 66.133333-38.4 91.733333L128 460.8c-27.733333 29.866667-27.733333 74.666667 0 102.4l36.266667 38.4c23.466667 25.6 36.266667 57.6 38.4 91.733333l2.133333 53.333334c2.133333 40.533333 34.133333 72.533333 74.666667 72.533333l53.333333 2.133333c34.133333 0 66.133333 14.933333 91.733333 38.4l38.4 36.266667c29.866667 27.733333 74.666667 27.733333 102.4 0l38.4-36.266667c25.6-23.466667 57.6-36.266667 91.733334-38.4l53.333333-2.133333c40.533333-2.133333 72.533333-32 72.533333-72.533333l2.133334-53.333334c0-34.133333 14.933333-66.133333 38.4-91.733333l36.266666-38.4c27.733333-29.866667 27.733333-74.666667 0-102.4l-36.266666-38.4c-23.466667-25.6-36.266667-57.6-38.4-91.733333l-2.133334-53.333334c-2.133333-40.533333-32-72.533333-72.533333-72.533333l-53.333333-2.133333c-34.133333 0-66.133333-14.933333-91.733334-38.4L563.2 128c-12.8-12.8-32-21.333333-51.2-21.333333z"
                  fill="#EB6A3F" p-id="2124"></path>
                <path
                  d="M469.333333 646.4c-14.933333 0-27.733333-6.4-38.4-14.933333L320 518.4c-12.8-12.8-12.8-32-2.133333-44.8 12.8-12.8 32-12.8 44.8-2.133333 0 0 2.133333 0 2.133333 2.133333l104.533333 104.533333 192-189.866666c12.8-12.8 34.133333-10.666667 44.8 2.133333s10.666667 32 0 42.666667l-198.4 198.4c-10.666667 8.533333-23.466667 14.933333-38.4 14.933333z"
                  fill="#EB6A3F" p-id="2125"></path>
              </svg>
            </div>
            <div style="margin-top: 20px; font-size: 25px">跨学科</div>
          </el-card>
        </el-col>
        <el-col :offset="1" :span="4">
          <el-card :style="{ 'width': cardDiameter, 'height': cardDiameter }"
            style="border-radius: 230px; text-align: center; box-shadow: 0px 1px 10px 0px #7E7E82">
            <div style="margin-top: 30px">
              <svg t="1673194902239" class="icon" viewBox="0 0 1024 1024" version="1.1"
                xmlns="http://www.w3.org/2000/svg" p-id="4644" :width="iconDiameter" :height="iconDiameter">
                <path
                  d="M832 320L576 192H512L256 320v384l256 128h64l256-128V384z m-320 448l-192-96v-256L512 512z m256-96L576 768V512l192-96zM576 448H512L320 352 512 256h64l192 96zM128 283.52L512 64h64l128 72.96v-64L576 0H512L64 256v256h64zM576 960H512l-384-219.52V576H64v192l448 256h64l192-109.44v-64L576 960z m192-850.56v64l192 109.44v456.96l-128 72.96v64l192-108.8V256z"
                  fill="#EB6A3F" p-id="4645"></path>
              </svg>
            </div>
            <div style="margin-top: 20px; font-size: 25px">低代码</div>
          </el-card>
        </el-col>
        <el-col :offset="1" :span="4">
          <el-card :style="{ 'width': cardDiameter, 'height': cardDiameter }"
            style="border-radius: 230px; text-align: center; box-shadow: 0px 1px 10px 0px #7E7E82">
            <div style="margin-top: 30px">
              <svg t="1673184573544" class="icon" viewBox="0 0 1024 1024" version="1.1"
                xmlns="http://www.w3.org/2000/svg" p-id="5875" :width="iconDiameter" :height="iconDiameter">
                <path
                  d="M710.4 710.4c-6.4 0-12.8 0-19.2-6.4L524.8 595.2c-19.2-12.8-19.2-32-12.8-44.8 12.8-12.8 32-19.2 44.8-6.4l166.4 115.2c12.8 12.8 19.2 32 6.4 44.8 0 6.4-6.4 6.4-19.2 6.4z"
                  fill="#EB6A3F" p-id="5876"></path>
                <path
                  d="M537.6 601.6c-19.2 0-32-12.8-32-32v-224c0-19.2 12.8-32 32-32s32 12.8 32 32v224c0 19.2-12.8 32-32 32z"
                  fill="#EB6A3F" p-id="5877"></path>
                <path
                  d="M550.4 966.4c-115.2 0-224-44.8-300.8-128-12.8-12.8-12.8-32 0-44.8 12.8-12.8 32-12.8 44.8 0 70.4 70.4 160 108.8 256 108.8 198.4 0 364.8-160 364.8-364.8s-160-364.8-364.8-364.8c-160 0-307.2 108.8-352 262.4 0 19.2-19.2 32-32 25.6-19.2-6.4-25.6-25.6-25.6-38.4 51.2-179.2 224-307.2 409.6-307.2 236.8 0 428.8 192 428.8 428.8 0 230.4-192 422.4-428.8 422.4z"
                  fill="#EB6A3F" p-id="5878"></path>
                <path
                  d="M160 492.8c-19.2 0-32-6.4-32-25.6l-25.6-166.4c0-19.2 6.4-32 25.6-38.4 19.2 0 32 6.4 38.4 25.6L192 460.8c0 12.8-12.8 32-32 32z"
                  fill="#EB6A3F" p-id="5879"></path>
                <path
                  d="M160 492.8c-12.8 0-25.6-6.4-32-12.8-6.4-19.2 0-38.4 19.2-44.8l160-83.2c12.8-6.4 32 0 44.8 12.8 6.4 12.8 0 32-12.8 44.8l-166.4 83.2H160z"
                  fill="#EB6A3F" p-id="5880"></path>
              </svg>
            </div>
            <div style="margin-top: 20px; font-size: 25px">全时段</div>
          </el-card>
        </el-col>
        <el-col :offset="1" :span="4">
          <el-card :style="{ 'width': cardDiameter, 'height': cardDiameter }"
            style="border-radius: 230px; text-align: center; box-shadow: 0px 1px 10px 0px #7E7E82">
            <div style="margin-top: 30px;">
              <svg t="1673184662915" class="icon" viewBox="0 0 1024 1024" version="1.1"
                xmlns="http://www.w3.org/2000/svg" p-id="6998" :width="iconDiameter" :height="iconDiameter">
                <path
                  d="M499.521829 994.552686a37.112686 37.112686 0 0 1-26.477715-10.620343 35.518171 35.518171 0 0 1-7.314285-40.696686 287.363657 287.363657 0 0 0-61.162058-326.495086 304.669257 304.669257 0 0 0-212.670171-85.825828 311.471543 311.471543 0 0 0-124.167314 25.673143 38.385371 38.385371 0 0 1-41.984-7.080229 35.518171 35.518171 0 0 1-7.314286-40.696686 374.023314 374.023314 0 0 1 76.682971-107.958857 378.88 378.88 0 0 1 265.698743-107.051885h16.427886A529.364114 529.364114 0 0 1 642.018743 67.291429 553.647543 553.647543 0 0 1 842.839771 29.257143a528.910629 528.910629 0 0 1 124.138058 14.145828 35.9424 35.9424 0 0 1 27.384685 26.550858 506.148571 506.148571 0 0 1-142.467657 485.770971 524.785371 524.785371 0 0 1-116.8384 85.825829 364.251429 364.251429 0 0 1-220.891428 348.613485 23.405714 23.405714 0 0 1-14.628572 4.388572zM190.0544 458.371657a377.329371 377.329371 0 0 1 265.640229 107.051886 363.797943 363.797943 0 0 1 104.974628 195.554743 342.879086 342.879086 0 0 1 1.828572 114.102857c3.642514-2.6624 6.392686-6.202514 10.0352-8.777143a287.744 287.744 0 0 0 86.718171-239.908571 34.889143 34.889143 0 0 1 21.006629-36.264229 445.3376 445.3376 0 0 0 119.573942-84.055771 434.658743 434.658743 0 0 0 126.8736-395.498058 442.016914 442.016914 0 0 0-83.982628-7.080228 462.423771 462.423771 0 0 0-324.037486 130.062628 467.748571 467.748571 0 0 0-86.718171 115.902172 37.814857 37.814857 0 0 1-37.434515 19.470628c-10.9568-0.877714-22.820571-1.770057-33.645714-1.770057a300.763429 300.763429 0 0 0-212.6848 85.825829 89.058743 89.058743 0 0 0-9.069714 9.728 238.6944 238.6944 0 0 1 51.112228-4.388572h-0.131657zM139.863771 942.299429a339.382857 339.382857 0 0 1-34.698971-1.770058 38.180571 38.180571 0 0 1-31.9488-30.968685c-0.906971-5.310171-19.163429-138.971429 74.8544-230.941257 44.719543-43.344457 82.154057-62.902857 119.573943-62.902858 44.734171 0 75.761371 30.076343 92.16 46.006858s45.641143 44.2368 47.469714 85.825828c1.828571 37.156571-19.163429 75.205486-64.848457 120.334629-66.618514 64.585143-155.165257 74.327771-202.6496 74.327771z m127.7952-253.908115c-9.069714 0-29.257143 5.310171-66.633142 41.589029a181.935543 181.935543 0 0 0-52.0192 109.714286 192.263314 192.263314 0 0 0-2.735543 30.090971c36.571429-0.892343 98.552686-9.742629 144.223085-53.087086 38.341486-37.156571 43.885714-57.504914 42.9056-65.477485a72.616229 72.616229 0 0 0-25.512228-37.185829c-19.163429-19.470629-30.120229-25.658514-40.199314-25.658514z m471.917715-300.807314a109.714286 109.714286 0 1 1 113.181257-109.714286 111.469714 111.469714 0 0 1-113.152 109.714286z m0-145.978514A37.024914 37.024914 0 0 0 702.186057 277.942857a37.624686 37.624686 0 0 0 37.419886 36.278857A37.054171 37.054171 0 0 0 777.040457 277.942857a36.4544 36.4544 0 0 0-36.571428-36.278857h-0.8192z"
                  fill="#EB6A3F" p-id="6999"></path>
              </svg>
            </div>
            <div style="margin-top: 20px; font-size: 25px">多场景</div>
          </el-card>
        </el-col>
      </el-row>

      <el-divider></el-divider>

      <el-row style="margin-top: 3%; text-align: center; margin-bottom: 3%">
        <h4 style="font-size: 40px; margin: 0;">关于我们</h4>
      </el-row>
      <el-row type="flex">
        <el-col :offset="4" :span="7">
          <div style="position: relative; top: 45%; transform: translateY(-50%)">
            <el-row>
              <img src="../assets/img/9About.svg" style="width: 100%">
            </el-row>
          </div>
        </el-col>
        <el-col :offset="1" :span="8">
          <span class="justify">
            <span class="important">浙江工业大学地理信息学院</span>成立于2024年6月，在自然资源部与浙江省人民政府指导下，
            由 <strong>莫干山地信实验室</strong> 与 <strong>德清县人民政府</strong> 联合共建，
            依托国家在德清打造地理信息全球创新高地优势，聚焦服务<strong>时空信息</strong>和<strong>低空经济</strong>两大国家战略新兴产业，
            发挥时空信息与人工智能交叉学科优势，重点建设发展
            <strong>时空信息与人工智能、空间智能系统与工程、时空智能与交叉应用</strong>等三大特色方向。
          </span>
        </el-col>
      </el-row>
    </el-main>

    <el-footer style="margin-top: 3%; background-color: #333333;">
      <div class="center" style="text-align: center; width: 100%; vertical-align: top">
        <a href="https://beian.miit.gov.cn/#/Integrated/index"
          style="color: rgb(240, 240, 240); text-decoration: none;">浙ICP备15038257号-3 </a>

        <svg t="1673338716645" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg"
          p-id="6821" width="20" height="20">
          <path
            d="M810.666667 170.666667H213.333333a128 128 0 0 0-128 128v426.666666a128 128 0 0 0 128 128h597.333334a128 128 0 0 0 128-128V298.666667a128 128 0 0 0-128-128z m0 85.333333l-277.333334 190.72a42.666667 42.666667 0 0 1-42.666666 0L213.333333 256z"
            p-id="6822" fill="#EB6A3F"></path>
        </svg>
        <span style="font-size: 18px; color: #f0f0f0; padding-left: 7px">Contact us: mingqilv@zjut.edu.cn</span>
      </div>
    </el-footer>
  </el-container>
</template>

<script>
export default {
  name: "HomePage",
  data() {
    return {
      navBackgroundColor: '#001628',
      primaryColor: '#3498db',
      active: '0',
      screenWidth: document.body.clientWidth,
      screenHeight: document.documentElement.clientHeight,
      cardDiameter: "170px",
      cardDiameter2: "170px",
      iconDiameter: 50,
    }
  },
  created() {
    document.documentElement.scrollTop = 0
  },
  mounted() {
    this.onScroll()
    window.addEventListener('scroll', this.onScroll)
    console.log('v1.2')
  },
  destroyed() {
    window.removeEventListener('scroll', this.onScroll)
  },
  methods: {
    onScroll() {
      const navContents = document.querySelectorAll('.el-divider')
      const offsetTopArr = [0]
      navContents.forEach(item => {
        offsetTopArr.push(item.offsetTop)
      })
      const scrollTop = document.documentElement.scrollTop || document.body.scrollTop
      const scrollHeight = document.body.scrollHeight
      const windowHeight = document.documentElement.clientHeight
      let navIndex = 0
      if (scrollTop + windowHeight >= scrollHeight) {
        navIndex = 5
      } else {
        for (let n = 0; n < offsetTopArr.length; n++) {
          if (scrollTop + 65 >= offsetTopArr[n]) {
            navIndex = n
          }
        }
      }
      this.active = String(navIndex)
    },
    scrollTo(index) {
      const navContents = document.querySelectorAll('.el-divider')
      const offsetTopArr = [0]
      navContents.forEach(item => {
        offsetTopArr.push(item.offsetTop)
      })
      var scrollTop = document.documentElement.scrollTop || document.body.scrollTop
      const targetOffsetTop = offsetTopArr[index] - 65

      const STEP = 50
      if (scrollTop > targetOffsetTop) {
        smoothUp()
      } else {
        smoothDown()
      }
      function smoothDown() {
        if (scrollTop < targetOffsetTop) {
          if (targetOffsetTop - scrollTop >= STEP) {
            scrollTop += STEP
          } else {
            scrollTop = targetOffsetTop
          }
          document.body.scrollTop = scrollTop
          document.documentElement.scrollTop = scrollTop
          requestAnimationFrame(smoothDown)
        }
      }
      function smoothUp() {
        if (scrollTop > targetOffsetTop) {
          if (scrollTop - targetOffsetTop >= STEP) {
            scrollTop -= STEP
          } else {
            scrollTop = targetOffsetTop
          }
          document.body.scrollTop = scrollTop
          document.documentElement.scrollTop = scrollTop
          requestAnimationFrame(smoothUp)
        }
      }
    },
    navigateToNewPage(newpage) {
      switch (newpage) {
        case 'kellect4apt': this.$router.push({ name: 'Kellect4APTDataset' }); break;
      }
    }
  }
}
</script>

<style scoped>
body {
  padding: 0;
  margin: 0;
}

.justify {
  font-size: 20px;
  text-align: justify;
  display: inline-block;
  line-height: 2em;
}

strong {
  color: #EB6A3F;
  font-weight: bold;
}

.important {
  color: #EB6A3F;
  font-weight: bold;
  background-color: #FFE5D8; 
  padding: 2px 4px;
  border-radius: 4px;
}

.el-menu .el-menu-item {
  font-size: 18px;
  padding-top: 3px;
}

.el-menu .el-menu-item:hover {
  color: #EB6A3F;
  background-color: #ffffff;
}

.el-menu .el-menu-item.is-active {
  background-color: #ffffff;
}

.center svg,
.center span,
.center img {
  display: inline-block;
  vertical-align: middle;
}

.photo {
  border-radius: 100%;
  margin: 0 auto;
  width: 100%;
  padding-bottom: 10px;
}

.el-footer {
  display: flex;
  width: 100%;
  align-items: center;
}

.mycard {
  cursor: pointer;
}
.mycard:hover {
  transform: scale(1.05);
  transition: all 0.3s;
}

.bullet-list {
  margin-left: 1.5em;
  margin-bottom: 1em;
  list-style-type: disc;
}
</style>
