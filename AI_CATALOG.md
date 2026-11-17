# AI 模型目录（Model Catalog）

> 本仓库只上传 **3D 模型（GLB）** 与本目录文件，不含游戏代码。
> 面向 AI/Agent：每个模型都有唯一 ID、分类、子类、作用描述与适用场景，可直接用于检索、选型与场景组装。

- 模型总数：**115**（ACNH 风格包 60 + 都市动漫风格包 55）
- 机器可读版：[`catalog.json`](catalog.json)（字段见文末）
- 格式：glTF 2.0 二进制（`.glb`），静态网格、无骨骼动画（角色以朝向/浮动表现）

## 动物森友会风（ACNH 风格包）

粉彩圆润的玩具感风格，岛屿生活场景；6 类别 / 26 子类 / 60 个模型。

目录：`models/acnh_style/`

## 都市动漫风（复古 × 潮流风格包）

参考《绝区零》高层视觉语言的原创都市动漫风格，高对比、霓虹、切角、CRT/街机/唱片母题；8 类别 / 26 子类 / 55 个已生成模型（全集 130 个，75 个待生成）。

目录：`models/urban_style/`

### 动物森友会风（ACNH 风格包） · 全部模型

| ID | 名称 | 类别 | 子类 | 作用 / 适用场景 | 路径 |
|---|---|---|---|---|---|
| `bld_cottage_01` | 玩家小屋 | 建筑 | 居住建筑 | 奶油色墙、薄荷绿圆润屋顶、圆形窗、木门与窗台花箱的单层小屋，适合作为玩家住宅或小镇主屋。｜小镇出生点；玩家住宅 | `models/acnh_style/01_buildings/models_text/bld_cottage_01.glb` |
| `bld_shop_01` | 杂货商店 | 建筑 | 商业与集市 | 带条纹遮阳篷、木箱与门口铃铛的街角小店，适合作为商店或交易点。｜商店交互点；街区节点 | `models/acnh_style/01_buildings/models_text/bld_shop_01.glb` |
| `bld_museum_01` | 博物馆 | 建筑 | 公共设施 | 新古典风格小博物馆，石柱、猫头鹰徽记与暖色灯光，适合作为收集品展示点。｜博物馆交互点；收集品展示 | `models/acnh_style/01_buildings/models_text/bld_museum_01.glb` |
| `bld_services_01` | 服务处 | 建筑 | 公共设施 | 绿色屋顶的公共服务建筑，带公告板与小旗，适合作为任务或公告中心。｜任务中心；公告板 | `models/acnh_style/01_buildings/models_text/bld_services_01.glb` |
| `bld_bridge_01` | 木桥 | 建筑 | 连接与地标 | 拱形木桥配绳索护栏，跨过小溪，适合连接两个场景区域。｜区域连接；河流跨越 | `models/acnh_style/01_buildings/models_text/bld_bridge_01.glb` |
| `bld_dock_01` | 码头 | 建筑 | 连接与地标 | 带路灯、木箱与救生圈的木质码头，适合作为钓鱼或出海交互点。｜钓鱼点；出海点 | `models/acnh_style/01_buildings/models_text/bld_dock_01.glb` |
| `bld_cafe` | 咖啡馆 | 建筑 | 商业与集市 | 粉彩外墙、条纹遮阳篷与户外小桌的咖啡馆，适合作为休息或社交点。｜社交点；休息区 | `models/acnh_style/01_buildings/models_text/bld_cafe.glb` |
| `bld_lighthouse` | 灯塔 | 建筑 | 连接与地标 | 奶油与珊瑚色条纹的圆润灯塔，适合作为海岸地标。｜海岸地标；导航点 | `models/acnh_style/01_buildings/models_text/bld_lighthouse.glb` |
| `bld_treehouse` | 树屋 | 建筑 | 居住建筑 | 带木梯、圆窗与串灯的树屋，适合作为森林隐藏点。｜森林隐藏点；秘密基地 | `models/acnh_style/01_buildings/models_text/bld_treehouse.glb` |
| `bld_stall` | 路边摊 | 建筑 | 商业与集市 | 带条纹顶棚与果篮的木质路边摊，适合作为集市节点。｜集市节点；临时商店 | `models/acnh_style/01_buildings/models_text/bld_stall.glb` |
| `chr_cat_01` | 猫咪村民 | 角色 | 动物村民 | 奶油色猫咪村民，蓝色马甲，大脑袋短身体，微笑挥手。｜NPC；对话角色 | `models/acnh_style/02_characters/models_text/chr_cat_01.glb` |
| `chr_dog_01` | 狗狗村民 | 角色 | 动物村民 | 柴犬风狗狗村民，绿色连帽衫，开心表情。｜NPC；运动型角色 | `models/acnh_style/02_characters/models_text/chr_dog_01.glb` |
| `chr_rabbit_01` | 兔子村民 | 角色 | 动物村民 | 蜜桃色兔子村民，背带裤，长耳朵，温柔可爱。｜NPC；商店店员 | `models/acnh_style/02_characters/models_text/chr_rabbit_01.glb` |
| `chr_deer_01` | 小鹿村民 | 角色 | 动物村民 | 小鹿村民，碎花裙，温柔微笑，适合森林主题。｜NPC；森林向导 | `models/acnh_style/02_characters/models_text/chr_deer_01.glb` |
| `chr_duck_01` | 鸭子村民 | 角色 | 动物村民 | 黄色小鸭村民，穿雨衣，圆润体型。｜NPC；天气相关角色 | `models/acnh_style/02_characters/models_text/chr_duck_01.glb` |
| `chr_player_01` | 玩家角色 | 角色 | 玩家角色 | 人类小孩玩家角色，圆头、休闲 T 恤、短裤、运动鞋与小背包。｜玩家化身；主角 | `models/acnh_style/02_characters/models_text/chr_player_01.glb` |
| `chr_bear` | 熊村民 | 角色 | 动物村民 | 圆胖熊村民，针织开衫，温暖笑容。｜NPC；商店店主 | `models/acnh_style/02_characters/models_text/chr_bear.glb` |
| `chr_squirrel` | 松鼠村民 | 角色 | 动物村民 | 大尾巴松鼠村民，绿色围裙，活泼可爱。｜NPC；园艺店员 | `models/acnh_style/02_characters/models_text/chr_squirrel.glb` |
| `chr_frog` | 青蛙村民 | 角色 | 动物村民 | 绿色青蛙村民，黄色雨帽，活泼。｜NPC；池塘向导 | `models/acnh_style/02_characters/models_text/chr_frog.glb` |
| `chr_owl` | 猫头鹰馆长 | 角色 | 特殊 NPC | 戴圆眼镜与领结的猫头鹰馆长，适合博物馆场景。｜博物馆馆长；知识型 NPC | `models/acnh_style/02_characters/models_text/chr_owl.glb` |
| `nat_tree_broadleaf_01` | 阔叶树 | 自然 | 树木 | 圆球形树冠、粗短树干的阔叶树，带草地小土丘。｜场景填充；树荫 | `models/acnh_style/03_nature/models_text/nat_tree_broadleaf_01.glb` |
| `nat_tree_sakura_01` | 樱花树 | 自然 | 树木 | 粉色樱花冠、花瓣点缀的樱花树，适合春季场景。｜春季场景；拍照点 | `models/acnh_style/03_nature/models_text/nat_tree_sakura_01.glb` |
| `nat_tree_palm_01` | 棕榈树 | 自然 | 树木 | 弯曲树干、大片棕榈叶的棕榈树，适合沙滩场景。｜沙滩场景；热带区域 | `models/acnh_style/03_nature/models_text/nat_tree_palm_01.glb` |
| `nat_tree_pine_01` | 松树 | 自然 | 树木 | 三层锥形松针、深绿与暖棕的松树，适合山地或冬季。｜山地场景；冬季区域 | `models/acnh_style/03_nature/models_text/nat_tree_pine_01.glb` |
| `nat_flowerbed_01` | 花丛 | 自然 | 花草 | 一小簇多色花朵与嫩绿叶的花丛，适合点缀路径与房屋。｜路径点缀；房屋花园 | `models/acnh_style/03_nature/models_text/nat_flowerbed_01.glb` |
| `nat_rock_01` | 岩石 | 自然 | 地面自然物 | 圆润灰岩，带苔藓点缀，低矮，适合作为障碍或景观。｜障碍物；景观石 | `models/acnh_style/03_nature/models_text/nat_rock_01.glb` |
| `nat_bush_flower` | 花灌木 | 自然 | 花草 | 开满粉彩小花的圆润灌木，适合作为绿篱。｜绿篱；路径边缘 | `models/acnh_style/03_nature/models_text/nat_bush_flower.glb` |
| `nat_tree_fruit` | 果树 | 自然 | 树木 | 挂满橙色果实的圆润果树，适合果园场景。｜果园；采集点 | `models/acnh_style/03_nature/models_text/nat_tree_fruit.glb` |
| `nat_mushroom` | 蘑菇丛 | 自然 | 地面自然物 | 红帽奶油斑点的圆润蘑菇丛，适合森林地面。｜森林地面；采集点 | `models/acnh_style/03_nature/models_text/nat_mushroom.glb` |
| `nat_stump` | 树桩 | 自然 | 地面自然物 | 带年轮与苔藓的圆润树桩，适合作为座椅或装饰。｜休息点；森林装饰 | `models/acnh_style/03_nature/models_text/nat_stump.glb` |
| `fur_table_wood_01` | 木桌 | 家具 | 桌台 | 圆角桌面、浅木纹、四条短腿的木质餐桌。｜室内布置；餐厅 | `models/acnh_style/04_furniture/models_text/fur_table_wood_01.glb` |
| `fur_chair_wood_01` | 木椅 | 家具 | 坐具 | 圆角椅背、软坐垫、浅木色的木椅。｜室内布置；餐厅 | `models/acnh_style/04_furniture/models_text/fur_chair_wood_01.glb` |
| `fur_sofa_pastel_01` | 粉彩沙发 | 家具 | 坐具 | 蜜桃粉布艺沙发，圆润扶手，两个靠垫。｜客厅布置；休息区 | `models/acnh_style/04_furniture/models_text/fur_sofa_pastel_01.glb` |
| `fur_bed_cozy_01` | 温馨床 | 家具 | 卧具 | 木框床、奶油色床品与格纹毯的温馨床。｜卧室布置；玩家房屋 | `models/acnh_style/04_furniture/models_text/fur_bed_cozy_01.glb` |
| `fur_shelf_book_01` | 书架 | 家具 | 收纳 | 三层木书架，彩色书脊与小盆栽。｜书房布置；商店陈列 | `models/acnh_style/04_furniture/models_text/fur_shelf_book_01.glb` |
| `fur_lamp_01` | 台灯 | 家具 | 灯具 | 暖黄灯罩、木底座、柔和光晕的台灯。｜室内照明；床头灯 | `models/acnh_style/04_furniture/models_text/fur_lamp_01.glb` |
| `fur_kitchen` | 厨房台面 | 家具 | 桌台 | 粉彩厨房台面，木柜、水槽与厨具，适合厨房场景。｜厨房布置；料理交互点 | `models/acnh_style/04_furniture/models_text/fur_kitchen.glb` |
| `fur_rug` | 圆地毯 | 家具 | 装饰 | 粉彩同心圆图案的圆形编织地毯。｜客厅地面；卧室装饰 | `models/acnh_style/04_furniture/models_text/fur_rug.glb` |
| `fur_wardrobe` | 衣柜 | 家具 | 收纳 | 粉彩木衣柜，双门、圆把手与小花雕刻。｜卧室布置；换装点 | `models/acnh_style/04_furniture/models_text/fur_wardrobe.glb` |
| `fur_clock` | 挂钟 | 家具 | 装饰 | 木质圆框、粉彩表盘与叶片指针的挂钟。｜墙面装饰；时间交互点 | `models/acnh_style/04_furniture/models_text/fur_clock.glb` |
| `prp_net_01` | 捕虫网 | 道具 | 工具 | 木柄、白色网兜的捕虫网。｜捕虫交互；UI 图标 | `models/acnh_style/05_props/models_text/prp_net_01.glb` |
| `prp_rod_01` | 钓鱼竿 | 道具 | 工具 | 竹节鱼竿、卷线器与红色浮标的钓鱼竿。｜钓鱼交互；UI 图标 | `models/acnh_style/05_props/models_text/prp_rod_01.glb` |
| `prp_can_01` | 浇水壶 | 道具 | 工具 | 薄荷绿壶身、长壶嘴、圆把手的浇水壶。｜浇花交互；园艺任务 | `models/acnh_style/05_props/models_text/prp_can_01.glb` |
| `prp_shovel_01` | 铲子 | 道具 | 工具 | 木柄、圆头金属铲、略带磨损质感的铲子。｜挖掘交互；化石挖掘 | `models/acnh_style/05_props/models_text/prp_shovel_01.glb` |
| `prp_bells_01` | 铃钱袋 | 道具 | 货币 | 米色布袋，金色铃钱符号装饰，鼓鼓的。｜货币图标；奖励掉落 | `models/acnh_style/05_props/models_text/prp_bells_01.glb` |
| `prp_workbench_01` | DIY 工作台 | 道具 | 制作 | 木质工作台，锤子、木板与收纳盒。｜制作交互点；工作坊 | `models/acnh_style/05_props/models_text/prp_workbench_01.glb` |
| `prp_letter` | 信件 | 道具 | 社交物 | 带粉彩火漆与小爱心邮票的信封，无文字。｜邮件系统；任务奖励 | `models/acnh_style/05_props/models_text/prp_letter.glb` |
| `prp_basket` | 野餐篮 | 道具 | 社交物 | 编织野餐篮，格纹布、面包与苹果。｜野餐场景；食物道具 | `models/acnh_style/05_props/models_text/prp_basket.glb` |
| `prp_camera` | 相机 | 道具 | 拍照 | 粉彩机身、圆镜头与背带的复古拍立得相机。｜拍照交互；相册系统 | `models/acnh_style/05_props/models_text/prp_camera.glb` |
| `prp_fishing_trophy` | 钓鱼大赛奖杯 | 道具 | 活动奖励 | 钓鱼大赛的金色奖杯，鱼形徽记、叶片把手与木质底座，适合作为活动成就奖励。｜钓鱼大赛奖励；成就展示 | `models/acnh_style/05_props/models_text/prp_fishing_trophy.glb` |
| `ter_grass_tile_01` | 草地地块 | 地形 | 地面模块 | 方形草地块、圆角边缘、微微起伏，适合拼接地面。｜地面拼接；草地场景 | `models/acnh_style/06_terrain/models_text/ter_grass_tile_01.glb` |
| `ter_path_stone_01` | 石板路 | 地形 | 道路模块 | 不规则圆石拼成的小路片段。｜路径铺设；村庄道路 | `models/acnh_style/06_terrain/models_text/ter_path_stone_01.glb` |
| `ter_boardwalk_01` | 木栈道 | 地形 | 道路模块 | 横向木板、圆角、带钉钉细节的木栈道片段。｜水边栈道；沙滩路径 | `models/acnh_style/06_terrain/models_text/ter_boardwalk_01.glb` |
| `ter_sand_tile_01` | 沙滩地块 | 地形 | 地面模块 | 米白细沙、贝壳点缀的方形沙滩模块。｜沙滩拼接；海岸场景 | `models/acnh_style/06_terrain/models_text/ter_sand_tile_01.glb` |
| `ter_water_edge_01` | 水边 | 地形 | 水岸与水面 | 浅蓝水面与草地交界，白色浪花，圆润岸线。｜河流边缘；池塘边缘 | `models/acnh_style/06_terrain/models_text/ter_water_edge_01.glb` |
| `ter_ramp_01` | 坡道 | 地形 | 高差模块 | 缓坡土路、两侧草边与木桩的坡道模块。｜高低差连接；山丘坡道 | `models/acnh_style/06_terrain/models_text/ter_ramp_01.glb` |
| `ter_cliff` | 悬崖 | 地形 | 高差模块 | 分层草地与泥土侧面的圆润悬崖模块。｜高地边缘；悬崖景观 | `models/acnh_style/06_terrain/models_text/ter_cliff.glb` |
| `ter_dirt_path` | 泥土路 | 地形 | 道路模块 | 圆角边缘、细碎小石子的泥土小路片段。｜自然路径；乡村道路 | `models/acnh_style/06_terrain/models_text/ter_dirt_path.glb` |
| `ter_stairs` | 石阶 | 地形 | 高差模块 | 带苔藓边缘的圆润石阶，三段踏步。｜高低差连接；庭院台阶 | `models/acnh_style/06_terrain/models_text/ter_stairs.glb` |
| `ter_pond` | 小池塘 | 地形 | 水岸与水面 | 浅蓝水面、睡莲叶与圆石边缘的小池塘模块。｜池塘景观；钓鱼点 | `models/acnh_style/06_terrain/models_text/ter_pond.glb` |

### 都市动漫风（复古 × 潮流风格包） · 全部模型

| ID | 名称 | 类别 | 子类 | 作用 / 适用场景 | 路径 |
|---|---|---|---|---|---|
| `u_chr_runner` | 街区跑者 | 角色 / NPC | 街区组 | 原创都市跑者，oversized 外套、运动鞋与斜挎包，适合作为玩家或街区 NPC。｜玩家化身；街区向导 | `models/urban_style/U1_characters/street_crew/models_text/u_chr_runner.glb` |
| `u_chr_fixer` | 委托中介 | 角色 / NPC | 街区组 | 原创委托中介，长外套、耳机与手持终端，负责发布任务与情报。｜任务发布；情报交易 | `models/urban_style/U1_characters/street_crew/models_text/u_chr_fixer.glb` |
| `u_chr_mechanic` | 机械师 | 角色 / NPC | 服务组 | 原创机械师，工装裤、护目镜与扳手，负责修理与制作。｜装备修理；制作台 | `models/urban_style/U1_characters/service_crew/models_text/u_chr_mechanic.glb` |
| `u_chr_vendor` | 街边店主 | 角色 / NPC | 服务组 | 原创街边店主，围裙、棒球帽与手套，负责商店交易。｜商店 NPC；交易 | `models/urban_style/U1_characters/service_crew/models_text/u_chr_vendor.glb` |
| `u_chr_dj` | DJ | 角色 / NPC | 场景组 | 原创街头 DJ，耳机、夹克与便携混音台，负责场景氛围。｜场景氛围；音乐交互 | `models/urban_style/U1_characters/scene_crew/models_text/u_chr_dj.glb` |
| `u_chr_guard` | 安保 | 角色 / NPC | 服务组 | 原创都市安保，战术背心、短棍与耳麦，负责巡逻与门禁。｜门禁；巡逻 | `models/urban_style/U1_characters/service_crew/models_text/u_chr_guard.glb` |
| `u_chr_hacker` | 黑客 | 角色 / NPC | 街区组 | 原创都市黑客，连帽衫、面罩与平板，负责情报与技术交互。｜情报破解；终端交互 | `models/urban_style/U1_characters/street_crew/models_text/u_chr_hacker.glb` |
| `u_chr_student` | 学生 | 角色 / NPC | 场景组 | 原创都市学生，简洁制服外套、背包与运动鞋，用于街区日常氛围。｜街区氛围；支线对话 | `models/urban_style/U1_characters/scene_crew/models_text/u_chr_student.glb` |
| `u_chr_performer` | 街头艺人 | 角色 / NPC | 街区组 | 原创街头艺人，旧夹克与贴纸吉他盒，用于广场与夜市氛围。｜广场表演；氛围 NPC | `models/urban_style/U1_characters/street_crew/models_text/u_chr_performer.glb` |
| `u_chr_android` | 人形机偶 | 角色 / NPC | 场景组 | 原创人形机偶，机械关节、屏幕脸与线缆，用于科幻/工业街区。｜工业区 NPC；终端交互 | `models/urban_style/U1_characters/scene_crew/models_text/u_chr_android.glb` |
| `u_prp_crt_tv` | 复古 CRT 电视 | 都市交互物 | 复古电子 | 复古 CRT 电视，厚后座、旋钮与雪花屏，用于街角、房间与游戏厅。｜街角堆叠；游戏厅 | `models/urban_style/U2_props/retro_electronics/models_text/u_prp_crt_tv.glb` |
| `u_prp_arcade_cabinet` | 街机柜 | 都市交互物 | 复古电子 | 复古街机柜，摇杆、按钮、投币口与小屏幕，可触发街机小游戏。｜街机小游戏；游戏厅 | `models/urban_style/U2_props/retro_electronics/models_text/u_prp_arcade_cabinet.glb` |
| `u_prp_neon_sign` | 霓虹招牌 | 都市交互物 | 复古电子 | 霓虹招牌，抽象几何图形与金属框架，用于街区氛围与任务标记。｜街区照明；任务标记 | `models/urban_style/U2_props/retro_electronics/models_text/u_prp_neon_sign.glb` |
| `u_prp_vending_machine` | 自动售货机 | 都市交互物 | 街道设施 | 自动售货机，玻璃正面、通用罐装饮料与发光面板，可购买消耗品。｜购买消耗品；街角补给 | `models/urban_style/U2_props/street_furniture/models_text/u_prp_vending_machine.glb` |
| `u_prp_dumpster` | 垃圾箱 | 都市交互物 | 街道设施 | 工业垃圾箱，厚重盖子、轮子与磨损金属，可翻找战利品。｜翻找战利品；巷战掩体 | `models/urban_style/U2_props/street_furniture/models_text/u_prp_dumpster.glb` |
| `u_prp_traffic_cone` | 交通锥 | 都市交互物 | 街道设施 | 交通锥，反光带与磨损塑料，用于道路施工与引导。｜道路引导；施工场景 | `models/urban_style/U2_props/street_furniture/models_text/u_prp_traffic_cone.glb` |
| `u_prp_boombox` | 手提音响 | 都市交互物 | 复古电子 | 复古手提音响，卡带仓、双喇叭与提手，用于街头氛围。｜街头音乐；氛围装饰 | `models/urban_style/U2_props/retro_electronics/models_text/u_prp_boombox.glb` |
| `u_prp_skateboard` | 滑板 | 都市交互物 | 街道设施 | 磨损滑板，抽象板面图案与轮子，可拾取或作为街区道具。｜拾取物；街区装饰 | `models/urban_style/U2_props/street_furniture/models_text/u_prp_skateboard.glb` |
| `u_prp_scooter` | 踏板摩托 | 都市交互物 | 街道设施 | 紧凑踏板摩托，圆润车身、车灯与后视镜，用于街道停放。｜街道停放；快递任务 | `models/urban_style/U2_props/street_furniture/models_text/u_prp_scooter.glb` |
| `u_prp_food_cart` | 小吃车 | 都市交互物 | 街道设施 | 街头小吃车，布棚、铁板、凳子与通用碗具，可购买食物。｜购买食物；夜市 | `models/urban_style/U2_props/street_furniture/models_text/u_prp_food_cart.glb` |
| `u_prp_loot_case` | 战利品箱 | 都市交互物 | 商业道具 | 工业战利品箱，卡扣、加固角与发光缝，可开启获得奖励。｜开箱奖励；任务奖励 | `models/urban_style/U2_props/commerce_props/models_text/u_prp_loot_case.glb` |
| `u_prp_vinyl_record` | 黑胶唱片 | 都市交互物 | 影音收藏 | 黑胶唱片，抽象封套与亮面黑盘，可收集或作为任务物品。｜收集品；任务物品 | `models/urban_style/U2_props/media_collectibles/models_text/u_prp_vinyl_record.glb` |
| `u_prp_film_reel` | 胶片盘 | 都市交互物 | 影音收藏 | 胶片盘，齿孔胶片与金属罐，可收集或用于回忆/任务。｜收集品；回忆任务 | `models/urban_style/U2_props/media_collectibles/models_text/u_prp_film_reel.glb` |
| `u_prp_cassette_tape` | 卡带 | 都市交互物 | 影音收藏 | 卡带，抽象标签与透明塑料壳，可收集或作为任务物品。｜收集品；任务物品 | `models/urban_style/U2_props/media_collectibles/models_text/u_prp_cassette_tape.glb` |
| `u_prp_ticket_machine` | 票据机 | 都市交互物 | 商业道具 | 票据机，出票口、按钮与齿孔票据，可购买任务券/车票。｜购买票据；任务券 | `models/urban_style/U2_props/commerce_props/models_text/u_prp_ticket_machine.glb` |
| `u_prp_capsule_machine` | 扭蛋机 | 都市交互物 | 商业道具 | 扭蛋机，玻璃球罩、彩色胶囊与投币口，可抽取随机奖励。｜随机奖励；潮玩收集 | `models/urban_style/U2_props/commerce_props/models_text/u_prp_capsule_machine.glb` |
| `u_prp_retro_console` | 复古游戏机 | 都市交互物 | 复古电子 | 复古游戏机，卡带槽、手柄与灰色塑料外壳，用于室内/游戏厅。｜室内装饰；小游戏入口 | `models/urban_style/U2_props/retro_electronics/models_text/u_prp_retro_console.glb` |
| `u_prp_control_panel` | 控制面板 | 都市交互物 | 复古电子 | 工业控制面板，旋钮、滑块、小屏幕与线缆，用于机关与场景交互。｜机关开关；门禁 | `models/urban_style/U2_props/retro_electronics/models_text/u_prp_control_panel.glb` |
| `u_prp_street_lamp` | 路灯 | 都市交互物 | 街道设施 | 都市路灯，弯臂、金属杆与冷暖光，用于街道照明。｜街道照明；夜景氛围 | `models/urban_style/U2_props/street_furniture/models_text/u_prp_street_lamp.glb` |
| `u_bld_apartment` | 公寓楼 | 都市建筑 | 居住 | 都市公寓楼，混凝土立面、阳台与屋顶水箱，作为街区主体建筑。｜街区主体；玩家住宅 | `models/urban_style/U3_buildings/residential/models_text/u_bld_apartment.glb` |
| `u_bld_convenience_store` | 便利店 | 都市建筑 | 商业 | 街角便利店，玻璃门面、荧光灯与遮阳篷，作为商店交互点。｜商店交互；补给点 | `models/urban_style/U3_buildings/commercial/models_text/u_bld_convenience_store.glb` |
| `u_bld_noodle_shop` | 面馆 | 都市建筑 | 商业 | 小面馆，布帘、凳子与暖光 interior，作为餐饮/休息点。｜购买食物；休息点 | `models/urban_style/U3_buildings/commercial/models_text/u_bld_noodle_shop.glb` |
| `u_bld_arcade` | 游戏厅 | 都市建筑 | 娱乐 | 双层游戏厅，霓虹立面与 CRT 屏幕，可进入街机小游戏。｜街机小游戏；娱乐交互 | `models/urban_style/U3_buildings/entertainment/models_text/u_bld_arcade.glb` |
| `u_bld_garage` | 车库工坊 | 都市建筑 | 工业 | 街边车库工坊，卷帘门、工具与轮胎堆，作为制作/修理点。｜制作台；修理 | `models/urban_style/U3_buildings/industrial/models_text/u_bld_garage.glb` |
| `u_bld_laundromat` | 洗衣店 | 都市建筑 | 商业 | 洗衣店，玻璃门面与成排机器，作为日常商店/休息点。｜日常商店；休息点 | `models/urban_style/U3_buildings/commercial/models_text/u_bld_laundromat.glb` |
| `u_bld_subway_entrance` | 地铁口 | 都市建筑 | 交通 | 地铁口，楼梯、栏杆与空白指示框，用于快速旅行/场景切换。｜快速旅行；场景切换 | `models/urban_style/U3_buildings/transit/models_text/u_bld_subway_entrance.glb` |
| `u_bld_warehouse` | 仓库 | 都市建筑 | 工业 | 工业仓库，波纹金属、装卸台与卷帘门，用于战斗/探索场景。｜探索区域；战斗场景 | `models/urban_style/U3_buildings/industrial/models_text/u_bld_warehouse.glb` |
| `u_bld_security_booth` | 安保亭 | 都市建筑 | 工业 | 小型安保亭，玻璃窗、对讲机与桌子，用于门禁与守卫互动。｜门禁交互；守卫 NPC | `models/urban_style/U3_buildings/industrial/models_text/u_bld_security_booth.glb` |
| `u_bld_billboard` | 广告牌 | 都市建筑 | 娱乐 | 大型广告牌，钢架与抽象空白海报，用于街区地标与任务信息。｜街区地标；任务公告 | `models/urban_style/U3_buildings/entertainment/models_text/u_bld_billboard.glb` |
| `u_ter_asphalt` | 沥青地块 | 都市地形 | 道路 | 模块化沥青地块，裂纹与微湿反光，适合铺路。｜铺路；街区地面 | `models/urban_style/U4_terrain/road/models_text/u_ter_asphalt.glb` |
| `u_ter_crosswalk` | 斑马线 | 都市地形 | 道路 | 模块化斑马线地块，白色条纹与沥青底，用于十字路口。｜路口；街区地面 | `models/urban_style/U4_terrain/road/models_text/u_ter_crosswalk.glb` |
| `u_ter_sidewalk` | 人行道 | 都市地形 | 人行道 | 模块化人行道地块，混凝土板与路缘，用于街区边界。｜街区边界；铺装 | `models/urban_style/U4_terrain/sidewalk/models_text/u_ter_sidewalk.glb` |
| `u_ter_metal_grate` | 金属格栅 | 都市地形 | 工业地面 | 模块化金属格栅，工业深钢色，用于巷战/工业区。｜工业区地面；排水口 | `models/urban_style/U4_terrain/industrial/models_text/u_ter_metal_grate.glb` |
| `u_ter_rooftop` | 屋顶地面 | 都市地形 | 屋顶 | 模块化屋顶地块，混凝土、排水口与小通风口，用于屋顶场景。｜屋顶场景；攀爬路线 | `models/urban_style/U4_terrain/rooftop/models_text/u_ter_rooftop.glb` |
| `u_ter_subway_platform` | 地铁站台 | 都市地形 | 站台 | 模块化地铁站台地块，瓷砖地面与警示条，用于交通场景。｜地铁场景；快速旅行 | `models/urban_style/U4_terrain/transit/models_text/u_ter_subway_platform.glb` |
| `u_ter_neon_puddle` | 霓虹水洼 | 都市地形 | 道路 | 模块化霓虹水洼，湿沥青与霓虹反光，用于夜雨街区。｜夜雨氛围；街区地面 | `models/urban_style/U4_terrain/road/models_text/u_ter_neon_puddle.glb` |
| `u_ter_construction_barrier` | 施工围挡 | 都市地形 | 工业地面 | 模块化施工围挡，金属网与警示条纹，用于封锁区域。｜区域封锁；施工场景 | `models/urban_style/U4_terrain/industrial/models_text/u_ter_construction_barrier.glb` |
| `u_ter_alley_floor` | 巷道路面 | 都市地形 | 工业地面 | 模块化巷道路面，污渍混凝土与排水口，用于后巷场景。｜后巷场景；战斗地面 | `models/urban_style/U4_terrain/industrial/models_text/u_ter_alley_floor.glb` |
| `u_ter_park_tile` | 公园地砖 | 都市地形 | 公园 | 模块化公园地砖，铺石与草边，用于街区绿地。｜绿地；休息区 | `models/urban_style/U4_terrain/park/models_text/u_ter_park_tile.glb` |
| `u_bld_apartment_b` | 高层公寓变体 | 建筑变体 | 建筑变体 | 更高的公寓变体，带外挂楼梯与屋顶水箱。｜街区主体；玩家住宅 | `models/urban_style/U5_variants_a/building_variants/models_text/u_bld_apartment_b.glb` |
| `u_bld_apartment_c` | 转角公寓变体 | 建筑变体 | 建筑变体 | 较矮的转角公寓变体，底层带小店面。｜街区主体；玩家住宅 | `models/urban_style/U5_variants_a/building_variants/models_text/u_bld_apartment_c.glb` |
| `u_bld_convenience_store_b` | 大型便利店变体 | 建筑变体 | 建筑变体 | 更大的便利店变体，双玻璃入口。｜商店交互；补给点 | `models/urban_style/U5_variants_a/building_variants/models_text/u_bld_convenience_store_b.glb` |
| `u_bld_noodle_shop_b` | 巷口面馆变体 | 建筑变体 | 建筑变体 | 更小的巷口面馆变体，窄柜台。｜购买食物；休息点 | `models/urban_style/U5_variants_a/building_variants/models_text/u_bld_noodle_shop_b.glb` |
| `u_bld_arcade_b` | 双层游戏厅变体 | 建筑变体 | 建筑变体 | 双层游戏厅变体，屋顶招牌与外挂楼梯。｜街机小游戏；娱乐交互 | `models/urban_style/U5_variants_a/building_variants/models_text/u_bld_arcade_b.glb` |
| `u_bld_garage_b` | 开门车库变体 | 建筑变体 | 建筑变体 | 卷帘门打开的车库变体，带汽车升降台。｜制作台；修理 | `models/urban_style/U5_variants_a/building_variants/models_text/u_bld_garage_b.glb` |

## AI 识别规则

1. **选包**：要粉彩岛屿/生活场景 → `acnh_style`；要都市/街机/霓虹/高对比动作场景 → `urban_style`。
2. **选类别**：按 `category` 定位（建筑/角色/自然/家具/道具/地形 或 都市对应类别）。
3. **选子类**：用 `subcategory` 收窄（如居住建筑、街头帮派、复古电器、道路……）。
4. **选具体模型**：用 `tags` / `use_cases` 关键词匹配，读 `description` 确认作用。
5. **加载**：`model` 字段即仓库内相对路径，可直接 fetch；单位为米级，按需按包围盒缩放。

## catalog.json 字段

| 字段 | 说明 |
|---|---|
| `id` | 全局唯一资产 ID |
| `name` / `description` | 中文名与作用描述 |
| `pack` / `category` / `subcategory` | 风格包 / 一级类别 / 子类 |
| `use_cases` / `tags` / `roles` | 适用场景、检索标签、游戏内角色（player/shop/nature 等） |
| `target_height` | 建议包围盒高度（米），加载归一化用 |
| `model` | 仓库内 GLB 相对路径 |
