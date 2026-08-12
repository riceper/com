<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>代齐振 简历</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background: #e6e9ef;
            font-family: "PingFang SC", "Microsoft YaHei", "Helvetica Neue", Arial, sans-serif;
            padding: 30px 20px;
            display: flex;
            justify-content: center;
        }
        .resume {
            max-width: 1000px;
            width: 100%;
            background: #ffffff;
            box-shadow: 0 8px 32px rgba(0,0,0,0.10);
            padding: 40px 48px 48px 48px;
            border-radius: 12px;
            line-height: 1.6;
            color: #1e2a3a;
        }

        /* 头部信息 */
        .header {
            display: flex;
            justify-content: space-between;
            align-items: baseline;
            flex-wrap: wrap;
            border-bottom: 3px double #2d4a7a;
            padding-bottom: 12px;
            margin-bottom: 24px;
        }
        .name {
            font-size: 36px;
            font-weight: 700;
            letter-spacing: 4px;
            color: #0b1c2e;
        }
        .contact {
            font-size: 16px;
            color: #2c3e50;
            text-align: right;
        }
        .contact span {
            display: inline-block;
            margin-left: 12px;
        }

        /* 通用标题 */
        h2 {
            font-size: 20px;
            font-weight: 700;
            color: #1a2d44;
            margin: 28px 0 12px 0;
            padding-left: 12px;
            border-left: 6px solid #2d4a7a;
            line-height: 1.3;
        }
        h3 {
            font-size: 18px;
            font-weight: 600;
            color: #1f3a57;
            margin: 18px 0 8px 0;
        }

        /* 列表 */
        ul, .list-dash {
            list-style: none;
            padding-left: 0;
            margin: 6px 0 12px 0;
        }
        ul li, .list-dash li {
            padding-left: 22px;
            position: relative;
            margin-bottom: 4px;
        }
        ul li::before {
            content: "•";
            color: #2d4a7a;
            font-weight: bold;
            position: absolute;
            left: 4px;
        }
        .list-dash li::before {
            content: "—";
            color: #2d4a7a;
            font-weight: bold;
            position: absolute;
            left: 0;
        }

        /* 工作经验条目 */
        .company {
            margin-top: 20px;
            border-bottom: 1px dashed #d0d7e2;
            padding-bottom: 16px;
        }
        .company:last-child {
            border-bottom: none;
        }
        .company-header {
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            align-items: baseline;
            margin-bottom: 4px;
        }
        .company-name {
            font-size: 20px;
            font-weight: 700;
            color: #0b1c2e;
        }
        .company-title {
            font-weight: 600;
            color: #1f3a57;
            margin-right: 12px;
        }
        .company-time {
            font-weight: 400;
            color: #4a5d72;
            font-size: 15px;
        }
        .company-desc {
            margin-top: 6px;
            padding-left: 8px;
        }
        .company-desc p {
            margin: 6px 0;
        }
        .sub-section {
            font-weight: 600;
            color: #1f3a57;
            margin: 10px 0 4px 0;
        }
        .sub-section-number {
            font-weight: 600;
            color: #1f3a57;
        }
        .indent-block {
            padding-left: 20px;
            margin: 4px 0;
        }

        /* 项目经验 */
        .project-item {
            margin: 12px 0;
        }
        .project-title {
            font-weight: 700;
            color: #1f3a57;
        }
        .project-detail {
            padding-left: 20px;
        }

        /* 技能标签 */
        .skill-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 8px 16px;
            margin: 6px 0 12px 0;
        }
        .skill-tag {
            background: #eef2f7;
            padding: 4px 14px;
            border-radius: 20px;
            font-size: 14px;
            color: #1a2d44;
            border: 1px solid #d0d7e2;
        }

        /* 页脚 */
        .footer-note {
            margin-top: 28px;
            text-align: center;
            font-size: 13px;
            color: #6b7f94;
            border-top: 1px solid #d0d7e2;
            padding-top: 18px;
        }

        @media (max-width: 700px) {
            .resume {
                padding: 20px 18px 24px 18px;
            }
            .header {
                flex-direction: column;
                align-items: flex-start;
            }
            .contact {
                text-align: left;
                margin-top: 6px;
            }
            .contact span {
                margin-left: 0;
                margin-right: 12px;
            }
            .company-header {
                flex-direction: column;
                align-items: flex-start;
            }
            .company-time {
                margin-top: 2px;
            }
        }
        @media (max-width: 420px) {
            .name {
                font-size: 28px;
            }
            .resume {
                padding: 12px 10px 16px 10px;
            }
            .indent-block {
                padding-left: 12px;
            }
        }
    </style>
</head>
<body>
<div class="resume">

    <!-- 头部 -->
    <div class="header">
        <div class="name">代齐振</div>
        <div class="contact">
            <span>手机：13006668389</span>
            <span>微信：day0910</span>
            <span>邮箱： day0910@foxmail.com</span>
        </div>
    </div>

    <!-- 专业资质 -->
    <h2>专业资质</h2>
    <ul>
        <li>一级人力资源管理师（专业资质）</li>
        <li>高级人力资源管理实战经验（HRVP全景视角）</li>
        <li>生产经营单位安全总监（深圳市应急管理局认证）</li>
        <li>IATF16949/ISO9001/ISO14001/ISO18001/ISO13485体系认证内审员</li>
    </ul>

    <!-- 个人优势 -->
    <h2>个人优势</h2>
    <p>20+年制造业HR全体系化管理经验（期间兼任董助或总助 10+年），深耕汽车/电子/新能源/光电/数码/注塑等智能制造领域，聚焦中型制造企业人力效能提升与合规风控，兼具战略高度与实战落地能力。擅长搭建适配制造业的HR四支柱模型、技能人才梯队及IPO合规体系，主导过3家制造企业HR体系0-1搭建；处理20+起复杂劳资纠纷（含竞业限制/技术保密）；</p>

    <!-- 核心资历 -->
    <h2>核心资历</h2>
    <ul class="list-dash">
        <li>精通制造企业HR四支柱模型搭建与HRBP转型，驱动人力部门从成本中心向利润中心转型，深度支撑2家企业IPO全流程人力合规与人才稳定；</li>
        <li>稳熟制造业技术人才梯队建设，搭建“学徒- 技工- 高级技师”三级成长体系，累计培养高潜人才200+人；</li>
        <li>深谱ISO/IATF16949/RBA等制造行业体系规范，构建“风险预警- 调解- 仲裁”三级ER机制，IPO期间化解关键岗位稳定性风险；</li>
        <li>通过数字化人力平台搭建，组织架构优化，弹性用工模式设计，实现人力成本下降，生产人均效能提升；</li>
        <li>熟练掌握制造业稳岗补贴、智能园区补贴、高新技术企业认证等各类申报流程，累计为原企业争取专项资金超650万元，协助争取融资资金超400万元；</li>
    </ul>

    <!-- 求职意向 -->
    <h2>求职意向</h2>
    <p>工作类型：全职 &nbsp;|&nbsp; 期望职位：人资总监 &nbsp;|&nbsp; 期望月薪：面议 &nbsp;|&nbsp; 到岗时间：5天内 &nbsp;|&nbsp; 期望城市：深圳/珠三角 &nbsp;|&nbsp; 期望行业：不限</p>

    <!-- 工作经验 -->
    <h2>工作经验</h2>

    <!-- 公司1 -->
    <div class="company">
        <div class="company-header">
            <span class="company-name">CQ中山市某电子科技有限公司[在职涉密]</span>
            <span>
                <span class="company-title">人资总监兼总助</span>
                <span class="company-time">（2025.01- 至今）民企/300+人</span>
            </span>
        </div>
        <div class="company-desc">
            <p><strong>工作描述：</strong>（主营BMS电池方案板、智能控制模组）</p>
            <div class="sub-section">1.行政人事管理</div>
            <ul>
                <li>建立人力资源系统，全面负责人力资源各模块的规划组织、实施开展、考核优化工作；</li>
                <li>参与公司战略规划及目标制定，据公司规划制定人力资源规划起草、修改和完善人力资源相关管理制度和工作流程；</li>
                <li>结合公司战略及销售目标规划，规划组织架构，岗位规划，人员优化异动调配，招聘计划，人才培养等；</li>
                <li>制定并导入绩效方案，监督各部门绩效考评过程并不断完善绩效管理体系；</li>
                <li>制定并完善激励机制、设计并完善公司薪酬设计，负责薪酬计算发管理为薪酬决策提供支持；</li>
                <li>制定培训计划，实施培训方案，成立培训小组，组织完成培训工作和培训后的情况跟踪，完善培训体系；</li>
                <li>受理员工投诉，处理劳动争议、纠纷，进行劳动诉讼；</li>
                <li>指导人事主管梳理本部门的日常事务管理工作，后期进行监管，协助完成本部门员工工作考核指标、激励及部门资金的预算和控制等工作；</li>
                <li>指导规划员工活动，推动公司理念及企业文化的形成；</li>
            </ul>
            <div class="sub-section">2.兼总助工作</div>
            <ul>
                <li>协助总经理开展全业务线诊断与组织效能提升，通过业务模块价值拆解与团队架构重构，建立“目标- 执行- 考核- 激励”闭环管理体系，推动公司整体业绩同比增长 47.2% ；</li>
                <li>全程参与并推动与某半导体公司的战略合作，创新采用“以租代售+分期确权”轻资产模式，规避一次性大额资金投入风险，成功达成15亩智能制造工业园合作协议，总合作金额7560万元，为公司产能扩张与产业升级奠定核心物理基础；</li>
                <li>担任数字化转型项目总负责人，牵头完成ERP、PLM、SRM、WMS、CRM、OA、MES、QMS八大核心系统的数据打通与流程集成，构建公司级数字化全息指挥看板，实现从客户订单到售后服务的全流程可视化、可追溯管理。</li>
                <li>主导“智能制造数字化车间”专项补贴申报全流程（含政策解读、材料撰写、答辩及现场验收），为公司争取数字化转型补贴资金65万元；</li>
                <li>协助建立研发项目精细化管理体系，引入ABC分类法对在研项目进行分级管控与资源动态配置，明确各阶段里程碑节点与交付标准，研发项目按时交付率；</li>
                <li>商标、技术专利方面的申请及管理；</li>
            </ul>
        </div>
    </div>

    <!-- 公司2 -->
    <div class="company">
        <div class="company-header">
            <span class="company-name">WG深圳市维高模塑有限公司</span>
            <span>
                <span class="company-title">行政总监兼总助</span>
                <span class="company-time">2021/9- 2024- 12民企/700+人</span>
            </span>
        </div>
        <div class="company-desc">
            <p>（主营汽车配件、模具注塑，含模具技术研发团队120+人）</p>
            <div class="sub-section">1.战略人力体系搭建</div>
            <ul>
                <li>落地OD/COE/HRBP/SSC四支柱模型，针对科技制造业研发驱动特点，COE新增“人才发展组”，专注技术人才薪酬设计、职业发展通道搭建；主导组织架构优化与岗位编制预算，将研发部门按技术方向拆分为3个专项小组，人力成本占比下降 8% ，人均效能显著提升；</li>
                <li>运用BSC工具分解战略目标，结合科技制造企业“技术创新+生产效率”双核心需求，构建OKR绩效管理体系，设计“宽带薪酬+项目跟投”激励体系，研发人员可参与核心项目跟投，项目成功后享受分红，核心研发人才留存率大幅提升；</li>
            </ul>
            <div class="sub-section">2.人才发展与梯队建设</div>
            <ul>
                <li>搭建TD（人才发展）体系，针对科技制造业技术迭代快的特点，主导内训师项目，培养多名内训师，开发“模具设计进阶”“汽车配件工艺优化”等10多门专项课程；推进各岗位继任者计划，重点储备研发组长、生产主管等关键岗位人才，满足科技企业扩张期用人需求，关键岗位空缺填补时间大幅缩短；</li>
                <li>主导人才九宫格盘点（98人参与，其中研发人员45人），输出52名高潜人才IDP计划，针对研发类高潜人才制定“技术导师+项目历练”培养方案，后续晋升/调薪率达 70%</li>
            </ul>
            <div class="sub-section">3.业务深度融合，深入一线</div>
            <ul>
                <li>以HRBP身份嵌入研发、生产部门，明确技术岗位能力模型，年度个人完成核心招聘35人（研发类27人，含5名资深模具设计师），满足制造企业扩张期技术人才需求。</li>
            </ul>
            <div class="sub-section">4.兼任总助工作：</div>
            <ul>
                <li>对接银行、担保公司等金融机构，统筹企业融资方案编制与申报，协助完成2轮共计超380万元融资落地，保障生产扩张与研发投入资金需求，跟踪资金使用合规性，配合财务部门完成年度审计与报表核对；</li>
                <li>牵头MES系统全公司落地推广，统筹需求调研、流程梳理、员工培训及上线运维，覆盖生产计划、库存管理、订单跟踪等核心模块，实现生产数据实时同步，订单交付周期缩短；</li>
                <li>主导研发专利项目全流程管控，梳理核心技术成果，跟踪专利撰写、查重及申报进度，累计完成15项实用新型专利、3项发明专利申报，其中10项已获授权；建立专利台账，统筹专利维护与技术保密管理；</li>
                <li>政府关系维护：对接科技局、工信局等部门，跟进产业扶持政策申报，协助企业争取研发补贴20多万元；统筹政府部门调研、检查等接待工作，确保沟通顺畅高效；</li>
                <li>统筹公司高层会议、跨部门专项会议的筹备、议程梳理及纪要编制，跟踪决议事项落地进度；规范印章使用流程，建立印章台账，负责公章、合同章等核心印章的保管与使用审批，确保零违规用印记录。</li>
            </ul>
        </div>
    </div>

    <!-- 公司3 -->
    <div class="company">
        <div class="company-header">
            <span class="company-name">CARVE 河南凯旺科技有限公司</span>
            <span>
                <span class="company-title">人资服务中心总监</span>
                <span class="company-time">2020/2- 2021/08股份|4000+人</span>
            </span>
        </div>
        <div class="company-desc">
            <p><strong>工作描述：</strong></p>
            <ul>
                <li>OD（组织发展）与薪酬体系：针对科技企业“研发+生产”双轮模式，设计制造企业“管理/技术双轨晋升体系”，技术轨设5个层级（助理工程师-首席专家），核心技术人才晋升周期缩短 30%</li>
                <li>搭建SSC（共享服务中心）标准化：整合薪酬核算、考勤管理等事务性工作，引入数字化人力管理平台，实现薪酬核算自动化提升效率，释放HRBP精力聚焦业务赋能；</li>
                <li>主导ER（员工关系）合规体系建设：构建“风险预警-调解-仲裁”三级ER机制，完善员工保密协议与竞业限制条款；处理3起重大劳资纠纷（含研发人员技术保密争议），同时保障提升员工满意度及生产运营稳定；</li>
                <li>厂务管理：协调工厂行政事务，包括食宿、安全、环境及设备维护，确保生产与办公顺利进行；</li>
                <li>政策与合规：确保人力资源政策符合法律法规，跟踪行业趋势与法规变化，及时调整策略；</li>
                <li>报告与决策支持：分析人力资源数据，定期向管理层提供人力资源状况、绩效及趋势报告，为战略决策提供支持。</li>
            </ul>
        </div>
    </div>

    <!-- 公司4 -->
    <div class="company">
        <div class="company-header">
            <span class="company-name">VIDO 深圳市原道数码电子有限公司</span>
            <span>
                <span class="company-title">综管部总监兼总助</span>
                <span class="company-time">2013/09- 2019/12私营|800+人</span>
            </span>
        </div>
        <div class="company-desc">
            <p><strong>工作描述：</strong></p>
            <ul>
                <li>构建HRBP业务伙伴机制，深入研发、生产等6大业务线，针对数码电子产品迭代快的特点，HRBP与研发团队同步参与产品立项会，明确人才需求；主导组织架构优化与岗位价值评估，将研发部门按产品类别拆分为平板、智能穿戴等4个小组，推动人均产出提升 22% 新产品上市周期缩短 15%</li>
                <li>设计“职级体系+宽带薪酬”双轨制，技术轨薪酬涨幅与研发成果挂钩；建立人才梯队动态盘点机制，每季度盘点核心岗位继任者，储备研发项目经理、硬件工程师等关键人才，保证关键岗位人才断层率下降；</li>
                <li>统筹行政后勤数字化转型，推动ERP（鼎捷）、九段系统、OA系统集成，实现行政物资采购、人力事务等流程线上化，SSC共享中心费用及后勤运营成本降低；</li>
            </ul>
            <div class="sub-section">4.后期兼任总助期间：</div>
            <ul>
                <li>针对数码电子产品质量投诉，建立“快速响应- 原因分析- 整改优化”机制；主导推进产品CCC认证及ISO体系，结合科技产品安全标准，完善质量管控流程，产品合格率提升；并且多次主导ISO/RBA审厂并通过；</li>
                <li>协助制定战略规划、年度经营规划，并督促跟进落地执行，承担部门间协调与沟通解决并反馈；</li>
                <li>协助总经理跟进跨部门任务的进度；</li>
                <li>维护核心政府部门、合作商及重要客户关系，辅助整合内外资源，信息汇总分析并形成专业报告，做好“决策支撑”与风险管控”的双岗位协同，全方位服务公司发展。</li>
            </ul>
        </div>
    </div>

    <!-- 公司5 -->
    <div class="company">
        <div class="company-header">
            <span class="company-name">PW鹏威集团（香港）有限公司</span>
            <span>
                <span class="company-title">集团HRVP兼董助</span>
                <span class="company-time">2010/4- 2013/8合资|20000+人</span>
            </span>
        </div>
        <div class="company-desc">
            <p>（集团涉及光电、数码电子、快销品、房地产、电子商务、科技制造板块等）</p>
            <ul>
                <li>制造板块人力战略：制定制造板块“人才引进+内部培养”双策略，搭建“技术-管理-专家”三通道发展体系，适配制造企业技术人才多元发展需求；</li>
                <li>牵头人力资源专家中心（COE）体系化建设，明确其在制造企业人才育留、合规风控等关键HR需求响应及专项方案输出中的核心作用，强化战略人力支撑能力；同步创新构建“平衡计分卡（BSC）战略解码-关键绩效指标（KPI）量化落地”融合型绩效体系，实现战略目标从“解码-分解-考核”全流程闭环管理，推动集团及制造板块年度核心战略目标达成；</li>
                <li>人才培养体系：主导“鹏威商学院”项目，开设“精益生产”“研发项目管理”等制造专项课程，与8所高校建立校企合作，成立“鹏威班”，累计输送300+技能人才至制造板块，培养中高层管理干部420人；</li>
            </ul>
            <div class="sub-section">4.兼任董助期间：</div>
            <ul>
                <li>聚焦制造板块核心多元职能，以“战略统筹+专业落地”双维度推进工作，跟踪制造板块战略落地进度；</li>
                <li>统筹跨部门重大项目推进，协调解决执行中的资源瓶颈与协同问题，保障核心目标达成；</li>
                <li>牵头研判政府科技补贴政策，精准匹配制造板块研发升级与人才引育需求，统筹申报工作获批资金超500万元，300万元定向用于研发设备采购及核心技术人才引进，同步搭建人才梯队；</li>
                <li>协助董事长开展商务洽谈、高层对接等活动；统筹重大商务会议、行业交流的筹备与执行，拓展企业资源网络；</li>
                <li>主导集团ER合规体系建设，规范制造板块劳资关系；对接外部法律顾问，牵头处置重大纠纷，成功化解制造板块1起核心知识产权侵权纠纷，筑牢合规防线；</li>
                <li>整合行业动态、市场数据及内部运营信息，形成专项报告供董事长决策参考；</li>
                <li>统筹董事长日程管理、重要文件流转与督办，保障决策高效落地。</li>
            </ul>
        </div>
    </div>

    <!-- 公司6 -->
    <div class="company">
        <div class="company-header">
            <span class="company-name">BYD比亚迪股份有限公司</span>
            <span>
                <span class="company-title">招聘主管- 人事经理</span>
                <span class="company-time">2007/3- 2010/3股份|5000+人</span>
            </span>
        </div>
        <div class="company-desc">
            <p><strong>工作描述：</strong></p>
            <ul>
                <li>生产人力保障：针对新能源产线扩张，制定“批量招聘+定向培养”方案，工人招聘到岗周期缩短至10天，保证招聘达成率；</li>
                <li>绩效激励创新：设计“产能- 能耗- 绩效- 晋升”联动机制，适配制造企业生产型岗位特点，提升员工生产积极性。</li>
            </ul>
        </div>
    </div>

    <!-- 公司7 -->
    <div class="company">
        <div class="company-header">
            <span class="company-name">MALOG 名浪卫浴洁具有限公司</span>
            <span>
                <span class="company-title">人事专员- 人事主管- 人事经理</span>
                <span class="company-time">2003/8- 2006/12私营|300+人</span>
            </span>
        </div>
        <div class="company-desc">
            <p>（机加、铸造、压铸制造企业）</p>
            <ul>
                <li>编制制造企业HR核心规范，建立关键岗位流失预警模型，通过岗位津贴与职业发展沟通，降低核心岗位流失率。</li>
            </ul>
        </div>
    </div>

    <!-- 公司8 -->
    <div class="company">
        <div class="company-header">
            <span class="company-name">JQ河南金雀集团沈阳分公司</span>
            <span>
                <span class="company-title">实习生-总务</span>
                <span class="company-time">2002/7- 2002/12 国企|500+人</span>
            </span>
        </div>
        <div class="company-desc">
            <p>（仪表、自动化制造企业）</p>
            <ul>
                <li>负责行政后勤事务，同时保障办公网络及电脑维护，含办公设备（打印、复印、传真机）等；</li>
            </ul>
        </div>
    </div>

    <!-- 项目经验 -->
    <h2>项目经验</h2>
    <div class="project-item">
        <div class="project-title">人才盘点项目（2022.05- 2022.07）</div>
        <div class="project-detail">
            运用九宫格盘点98名核心员工（研发45人），建立关键岗位继任者储备库，制定“技术导师+项目历练”培养方案，提升高潜人才晋升率
        </div>
    </div>
    <div class="project-item">
        <div class="project-title">内训师选培项目（2022.03- 2023.09）</div>
        <div class="project-detail">
            建立内训师队伍，建立内训师队伍，选拔30名技术骨干、管理精英担任内训师，开发“模具设计进阶”“汽车配件工艺优化”等10多门专项课程，将公司优秀技术经验、生产管理方法沉淀；三年内累计开展培训50场，覆盖员工1200人次，支撑制造企业技能人才自主培养。
        </div>
    </div>
    <div class="project-item">
        <div class="project-title">鹏威商学院项目（2011.06- 2012.08）</div>
        <div class="project-detail">
            主导集团筹建“鹏威商学院”，开设“科技企业精益生产”“研发项目管理”等特色课程；组织多次校园招聘及宣讲会，招聘50多名应届硕士，其中30多人投身制造板块研发、生产岗位；与中原工学院、东莞理工、河南师大、郑州航天航空、南阳理工、南阳师范、上海交大、武汉大学等知名大学建立稳定的校园招聘关系；在南阳理工学院、中原工学院成立“鹏威班”，累计向集团输送学生300余人，“鹏威商学院”培训中高级管理人员120余人，基层管理300余人。
        </div>
    </div>

    <!-- 教育经历 -->
    <h2>教育经历</h2>
    <p>黄河科技大学 本科 计算机信息管理 2003</p>

    <!-- 技能特长 -->
    <h2>技能特长（包含IT技能、语言能力、证书、成绩、培训经历）</h2>
    <h3>全链路数字化工具</h3>
    <p>数字化平台：ERP、PLM、SRM、WMS、CRM、OA、MES、QMS</p>
    <p>协同办公平台：钉钉、企业微信、泛微、飞书、SAP、Workday、九段、北森、用友、ZKTeco</p>
    <h3>核心专业能力</h3>
    <ul>
        <li>制造企业HR体系搭建（四支柱模型、SSC共享服务中心）</li>
        <li>技能人才梯队建设（校企合作、内训体系、双轨晋升）</li>
        <li>IPO人力合规与股权激励落地</li>
        <li>劳资纠纷处置（竞业限制、技术保密、群体性事件）</li>
        <li>政府补贴申报与体系认证（ISO、IATF16949、高新技术企业）</li>
    </ul>
    <h3>其他能力</h3>
    <p>AdobePhotoshop、Adobelllustrator、CorelDRAW C1驾驶证</p>

    <!-- 页脚（可选） -->
    <div class="footer-note">履历中有从业过公司的简要说明，所括所属行业、主营产品、企业规模人数等信息，不尽之处可电话联系我</div>

</div>
</body>
</html>
