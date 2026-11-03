<div align="center">

# LabelEditor

**把模板、数据，连到现场打印。**  
**Connect templates, data, and on-site label printing.**

[中文介绍](#中文) · [English](#english) · [产品官网 / Product website](https://devgo.io/products/labeleditor/) · [官网下载 / Official downloads](https://devgo.io/downloads/)

</div>

---

## 中文

LabelEditor 是面向标签设计与打印流程的产品，帮助团队在一个工作流中维护标签模板、准备业务数据、管理打印设备，并追踪打印任务。它适用于生产包装、来料仓储和多工位标签作业，也可以通过 API 与现有业务系统衔接。

### 产品特色

**一套模板，多场景复用**  
在浏览器中编排文字、日期、流水号、条码、二维码、图片、图形和表格。分别维护固定版式和变量数据，可复制模板并结合样例检查尺寸、布局及输出效果。

**从数据到打印，步骤清晰**  
根据模板字段准备并导入业务数据；预览单条记录，选择记录、设备及份数后发起打印。批量任务可关联数据行与执行记录，便于查找异常。

**关注任务状态与追溯**  
围绕任务号、业务标识、模板与设备组织查询，查看任务处理状态和记录。对失败或结果不明的任务先核查再安排补打，避免将请求提交视为实体打印成功。

**连接设备与业务系统**  
维护打印设备、字体和设备参数；针对 ZPL 工作流生成标签输出。通过 API 传入业务数据、选择打印机并查询任务结果，支持权限与身份校验。具体设备参数和字体输出能力取决于目标设备与配置。

**面向现场的协作**  
标签打印可以与 PDA 应用或既有系统中的扫码、数据校验和现场业务流程衔接；功能是否包含在特定安装包中，以具体版本和交付说明为准。

### 功能概览

| 模块 | 主要内容 |
| --- | --- |
| 标签设计与标准化 | 模板尺寸与布局、组件、变量、字体、模板复制与导入导出 |
| 标签预览与 ZPL | 样例及数据预览、ZPL 生成与预览、按设备核对输出 |
| 打印执行 | 单次、多份及批量打印，打印参数与任务处理 |
| 数据导入 | 基于模板字段整理数据、导入记录、逐行检查与打印 |
| API 集成 | 模板变量调用、业务标识、设备选择、鉴权与结果查询 |
| 打印设备与字体 | 设备配置、状态查询、介质参数及字体管理 |
| 打印记录 | 任务状态、业务关联、执行记录与异常排查 |
| 用户与系统管理 | 账号权限、系统设置、授权及部署配置 |

### 典型流程

1. **维护模板**：确定尺寸、内容和变量，使用样例预览。
2. **准备数据**：在系统中准备记录，或由业务系统通过 API 提供。
3. **发起打印**：选择设备、记录与份数，核对后提交。
4. **查询结果**：通过任务号或业务标识查看状态、记录与异常。

### 适用场景

- **生产与包装**：复用产品、规格、批次及条码标签版式。
- **来料与仓储**：整理物料和批次数据，按需预览与批量打印。
- **多工位协同**：集中维护模板和设备，关联业务任务与打印记录。
- **系统集成**：按实际接口与权限，将打印能力接入 ERP、MES、WMS 或其他业务系统。

### 获取与使用

请访问 [产品官网](https://devgo.io/products/labeleditor/) 了解产品，前往 [下载中心](https://devgo.io/downloads/) 查看当前安装包、平台支持和发布说明。安装、授权及升级应按官网对应版本的说明执行。

LabelEditor 主要面向 ZPL 标签工作流。不同版本的功能、授权和集成范围可能不同；打印机型号、字体、耗材及网络条件也会影响实际效果。预览、任务受理或设备回执不能替代目标设备上的实体出纸验收。

---

## English

LabelEditor brings label design and printing into a connected workflow: maintain templates, prepare business data, manage printers, and trace print tasks. It supports production, packaging, warehousing, and integration with existing business systems through APIs.

### Highlights

**Reusable templates**  
Compose text, dates, serial numbers, barcodes, QR codes, images, shapes, and tables in the browser. Maintain fixed layouts separately from variable data and check layouts using sample values.

**A clear path from data to printing**  
Prepare and import data for template fields, preview a record, then select records, a printer, and quantities. Batch tasks can be associated with data rows and execution records for investigation.

**Task visibility and traceability**  
Find tasks by task ID, business identifier, template, or printer. Inspect status and execution records; investigate failures or uncertain outcomes before arranging a controlled reprint.

**Device and system integration**  
Manage printer connections, fonts, and device settings for ZPL workflows. Use APIs to pass business data, select a device, and query results with authentication and access controls. Device settings and font output depend on the target printer and configuration.

**On-site workflows**  
Connect printing with scanning, validation, and operational processes in PDA applications or existing business systems. Included capabilities depend on the specific release and delivery scope.

### Capabilities

| Area | What it covers |
| --- | --- |
| Label design | Layouts, components, variables, fonts, template reuse and import/export |
| Preview & ZPL | Sample and data previews, ZPL generation and output checks |
| Print execution | Individual, multiple-copy and batch printing; task processing |
| Data import | Template-based data preparation, record import and validation |
| API integration | Template variables, business identifiers, authentication and result queries |
| Printers & fonts | Device configuration, status, media settings and font management |
| Print records | Task status, business context, execution history and troubleshooting |
| Administration | Users, permissions, system settings, licensing and deployment |

### Typical workflow

1. **Maintain a template** and preview it with sample values.
2. **Prepare data** in the application or provide it from a business system.
3. **Submit a print task** with the selected device, records and quantities.
4. **Review the result** by task or business ID and investigate exceptions.

### Use cases

- Production and packaging labels for products, specifications, lots and barcodes.
- Receiving and warehouse labels prepared from material and batch records.
- Shared templates and printer management across workstations.
- API integration with ERP, MES, WMS or other business applications.

### Get LabelEditor

Visit the [product website](https://devgo.io/products/labeleditor/) and [download center](https://devgo.io/downloads/) for current installers, platform support and release information. Follow the instructions for the relevant version when installing, licensing or upgrading.

LabelEditor primarily targets ZPL label workflows. Features, licensing and integrations depend on the release; output also depends on the printer, fonts, media and network. A preview, accepted request or device receipt does not replace verification of physical output on the target printer.

---

**Repository scope:** This repository contains product information and website presentation files only. The LabelEditor application source code and installers are not included.
