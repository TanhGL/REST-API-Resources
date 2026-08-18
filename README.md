## Bypass (Bản bypass lh fmap@dev.com)
Tracking_GetListTDByMobiAccount 
- Full tập điểm được gắn theo acc, đi kèm theo là SHD
- Cls kèm theo các SHD
- Lấy log thông tin nhân viên
- Xem màn hình hiển thị và các tác vụ của nhân viên khác (Inside+OmmiAgent)

** Bypass 
- <u>Bypass TLS 1.2/1.3, IMEI</u>
- <b>Chặn</b> phát hiện thiết bị root/jailbreak (loại bỏ check nhà phát triển hoặc tệp tin root/sudo/file Magic)
- <b>Chặn</b> tracking capture
- Giả lập sinh trắc học
- Bỏ qua đăng nhập bất thường.




## Tổng quan dữ liệu Tên miền (Domain Dataset Overview)

Dưới đây là bảng thống kê và phân loại danh sách các tên miền phụ (subdomains) thuộc sở hữu của Tập đoàn **FPT (`fpt.vn`)** dựa trên dữ liệu bạn cung cấp.

---

### 1. Thông tin chung
* **Mã phản hồi (Response Code):** `1` (Thành công)
* **Trạng thái:** Tìm thấy tên miền trong cơ sở dữ liệu (`Domain found in dataset`).
* **Tổng số tên miền phụ:** 100 subdomains.

---

### 2. Bảng phân loại hệ thống Tên miền phụ (Subdomain Categories)

| Nhóm hệ thống | Danh sách tên miền phụ (Subdomains) |
| :--- | :--- |
| **Xác thực & Tài khoản** *(Auth & Identity)* | `accounts.fpt.vn`, `accounts-stag.fpt.vn`, `id.fpt.vn`, `auth.fpt.vn`, `ftelsso-stag.fpt.vn` |
| **Dịch vụ Khách hàng & Cổng thông tin** *(Portals & Care)* | `hi.fpt.vn`, `staging-hi.fpt.vn`, `member.fpt.vn`, `onmember.fpt.vn`, `khachhangthanthiet.fpt.vn`, `fcitizen.fpt.vn` |
| **Hệ thống Kiểm tra Tốc độ** *(Speedtest Nodes)* | `speedtest.fpt.vn`, `speedtest03.fpt.vn` đến `speedtest10.fpt.vn`, `speedtest18.fpt.vn`, `speedtestsgp.fpt.vn`, `speedtesthkg.fpt.vn`, `speedtesthn.fpt.vn`, `speedtestdng.fpt.vn`, `lbspeedhn.fpt.vn` |
| **API & Dịch vụ Tích hợp** *(APIs & Integrations)* | `apis.fpt.vn`, `apis-stag.fpt.vn`, `sapi.fpt.vn`, `cads-api.fpt.vn`, `hifpt-api.fpt.vn`, `hifpt-api-stag.fpt.vn`, `staging-hi-api.fpt.vn`, `ncp-integration.fpt.vn`, `caosangtao-api.fpt.vn`, `s3-api.fpt.vn`, `api-edns1.fpt.vn`, `api-paytv-ctv.fpt.vn` |
| **Thương mại & Bán hàng** *(E-Commerce & Sales)* | `shop.fpt.vn`, `shop-stag.fpt.vn`, `saleplatform-extension.fpt.vn`, `paygate.fpt.vn`, `mobisaleguide.fpt.vn` |
| **Dịch vụ Truyền thông & Giải trí** *(Media & Entertainment)* | `fptplay.fpt.vn`, `camera.fpt.vn`, `smarttv.fpt.vn`, `missonetv.fpt.vn`, `fbox-alwayson.fpt.vn` |
| **Hệ thống Nội bộ & Quản trị** *(Internal Operations & HR)* | `hr.fpt.vn`, `efox.fpt.vn`, `efox-stag.fpt.vn`, `daotao.fpt.vn`, `foxnews.fpt.vn`, `office365.fpt.vn`, `fpms.fpt.vn`, `sims.fpt.vn` |
| **Hệ thống Hỗ trợ & Portal SOP** *(Support & SOP)* | `portal-sop.fpt.vn`, `portal-sop-stg.fpt.vn`, `portal-sop-uat.fpt.vn`, `livechat-sop-uat.fpt.vn`, `ticketportal-stag.fpt.vn`, `chatbotchang.fpt.vn` |
| **Hạ tầng Mạng & Thiết bị** *(Network & Infrastructure)* | `mywifi.fpt.vn`, `ip.fpt.vn`, `proxy.fpt.vn`, `relay.fpt.vn`, `cpemq.fpt.vn`, `cpemq1.fpt.vn` đến `cpemq6.fpt.vn`, `cpemb.fpt.vn`, `isp-mail.fpt.vn`, `isp-mta4.fpt.vn`, `isp-web.fpt.vn`, `mobinetws.fpt.vn` |
| **Dữ liệu & Phân tích** *(Data & Tracking)* | `data.fpt.vn`, `cdp.fpt.vn`, `maas.fpt.vn`, `recom.fpt.vn`, `hifpt-tracking.fpt.vn`, `fbox-kibana.fpt.vn` |
| **Khác** *(Others)* | `www.fpt.vn`, `hcm.fpt.vn`, `fti.fpt.vn`, `usa.fpt.vn`, `qr.fpt.vn`, `f.fpt.vn`, `sr.fpt.vn`, `anh.fpt.vn`, `mediamap.fpt.vn`, `mobimapstag.fpt.vn`, `bblogs.fpt.vn`, `ccatalog.fpt.vn`, `sip-dev.fpt.vn`, `hi-static.fpt.vn` |

---

### 3. JSON Gốc (Raw Data)

```json
{
  "detected_urls": [],
  "domain_siblings": [
    "accounts.fpt.vn",
    "hcm.fpt.vn",
    "staging-hi.fpt.vn",
    "octopus-stream01-cads.fpt.vn",
    "hi.fpt.vn",
    "ncp-integration.fpt.vn",
    "www.fpt.vn",
    "speedtestsgp.fpt.vn",
    "accounts-stag.fpt.vn",
    "id.fpt.vn",
    "shop.fpt.vn",
    "ncp-integration-staging.fpt.vn",
    "api-edns1.fpt.vn",
    "member.fpt.vn",
    "fti.fpt.vn",
    "saleplatform-extension.fpt.vn",
    "auth.fpt.vn",
    "ftelsso-stag.fpt.vn",
    "apis.fpt.vn",
    "hi-static.fpt.vn",
    "staging-hi-api.fpt.vn",
    "speedtesthkg.fpt.vn",
    "fptplay.fpt.vn",
    "sapi.fpt.vn",
    "mobimapstag.fpt.vn",
    "mediamap.fpt.vn",
    "apis-stag.fpt.vn",
    "camera.fpt.vn",
    "shop-stag.fpt.vn",
    "ip.fpt.vn",
    "portal-sop.fpt.vn",
    "speedtest.fpt.vn",
    "hifpt-api-stag.fpt.vn",
    "fcitizen.fpt.vn",
    "hss.fpt.vn",
    "fpro.fpt.vn",
    "bblogs.fpt.vn",
    "foxnews.fpt.vn",
    "proxy.fpt.vn",
    "cpemq1.fpt.vn",
    "portal-sop-stg.fpt.vn",
    "data.fpt.vn",
    "speedtest05.fpt.vn",
    "speedtesthn.fpt.vn",
    "efox.fpt.vn",
    "staging.fpt.vn",
    "fpms.fpt.vn",
    "cads-api.fpt.vn",
    "portal-sop-uat.fpt.vn",
    "hr.fpt.vn",
    "isp-mta4.fpt.vn",
    "mywifi.fpt.vn",
    "isp-mail.fpt.vn",
    "onmember.fpt.vn",
    "hifpt-api.fpt.vn",
    "anh.fpt.vn",
    "speedtestdng.fpt.vn",
    "paygate.fpt.vn",
    "efox-stag.fpt.vn",
    "hifpt-tracking.fpt.vn",
    "speed18.fpt.vn",
    "khachhangthanthiet.fpt.vn",
    "f.fpt.vn",
    "sr.fpt.vn",
    "qr.fpt.vn",
    "mobinetws.fpt.vn",
    "mobisaleguide.fpt.vn",
    "isp-web.fpt.vn",
    "cpemb.fpt.vn",
    "sims.fpt.vn",
    "api-paytv-ctv.fpt.vn",
    "fbox-alwayson.fpt.vn",
    "ccatalog.fpt.vn",
    "usa.fpt.vn",
    "sip-dev.fpt.vn",
    "fbox-kibana.fpt.vn",
    "caosangtao-api.fpt.vn",
    "smarttv.fpt.vn",
    "recom.fpt.vn",
    "missonetv.fpt.vn",
    "daotao.fpt.vn",
    "office365.fpt.vn",
    "speedtest10.fpt.vn",
    "speedtest07.fpt.vn",
    "s3-api.fpt.vn",
    "lbspeedhn.fpt.vn",
    "speedtest09.fpt.vn",
    "speedtest03.fpt.vn",
    "cpemq4.fpt.vn",
    "cpemq5.fpt.vn",
    "cpemq3.fpt.vn",
    "cpemq6.fpt.vn",
    "chatbotchang.fpt.vn",
    "cpemq.fpt.vn",
    "relay.fpt.vn",
    "ticketportal-stag.fpt.vn",
    "maas.fpt.vn",
    "livechat-sop-uat.fpt.vn",
    "cpemq2.fpt.vn",
    "cdp.fpt.vn"
  ],
  "resolutions": [],
  "response_code": 1,
  "verbose_msg": "Domain found in dataset",
  "whois": null

}
```


## REST-API-Resources_FPT 
| Thông tin / Notice | Chi tiết / Details |
| :--- | :--- |
| **Purpose** | Educational purposes only *(Dự án với mục đích học tập)* |
| **Notice** | ⚠️ Unauthorized use, copying, or redistribution is strictly prohibited. *(Không sử dụng hoặc chia sẻ trái phép)* |

| Biến / Cấu hình | URL / Giá trị | Môi trường / Ghi chú |
| :--- | :--- | :--- |
| `API_CUS` | `http://mapapi.fpt.vn/api/private` | Public / Private API |
| `urlGetEmployee` | `http://parcamapi.fpt.vn/api/RPMaintaince/GetInforMobinetUser` | API lấy thông tin nhân viên |
| ~~`urlGetEmployee`~~ *(Old)* | `http://parapi.fpt.vn/api/RadAPI/GetPartnerHR` | *IP: 118.69.135.206 (Đã disable)* |
| ~~`urlGetEmployee`~~ *(Old)* | `http://parapiora.fpt.vn/api/v1/PartnerHR/PartnerHR_GetEmployeeForINFMap` | *Update API getEmployee (Đã disable)* |
| `urlSyncDBArea` | `http://parapiora.fpt.vn/api/ISDeployment/GetPartnerHR_GetMobiName` | IP: 172.20.17.32 |
| `urlGetListCodeContractDeploy` | `http://parapiora.fpt.vn/api/ISDeployment/Get_SupportINF_CheckCusTypeBySub` | IP: 172.20.17.32 |
| `urlGetLocationByContract` | `http://mapapi.fpt.vn/api/private/getContractLatLng` | IP: 172.20.17.32 |
| `urlGetListCodeDeployIndayIQC` | `http://parapiora.fpt.vn/api/SupportINF/SupportINF_GetListFinishDate_IQC` | IP: 172.20.17.50 (STAGING) / 172.20.17.32 (PROD) |
| ~~`reportByInside`~~ *(STG)* | `http://stagparapiora.fpt.vn/api/iqc/get-list-contract-deployment-finished-by-emp-area` | STAGING (172.20.17.50) |
| `reportByInside` | `http://parapiora.fpt.vn/api/iqc/get-list-contract-deployment-finished-by-emp-area` | PRODUCTION |
| `versionCheck` | `http://mapmobile-ws.fpt.net/FMapService.svc/IQC_CheckVersion` | Check version IQC API |
| `typePCTD` | `2` | VIETCN 14/08/2019 add typePCTD |

| Ngày / Giờ | Loại / Kích thước | Tên File / Thư mục |
| :--- | :--- | :--- |
| 5/13/2026 9:36 PM | `<dir>` | `bin` |
| 5/13/2026 9:36 PM | 9,282 B | `data.json` |
| 5/13/2026 9:36 PM | 11 B | `exclude.txt` |
| 5/13/2026 9:36 PM | 110 B | `Fxxxxxx.svc` |
| 5/13/2026 9:36 PM | 91 B | `Global.asax` |
| 5/13/2026 9:36 PM | 9,830 B | `inventory.json` |
| 8/4/2026 12:00 AM | `<dir>` | `Logs` |
| 5/13/2026 9:36 PM | `<dir>` | `Properties` |
| 5/13/2026 9:36 PM | `<dir>` | `Web References` |
| 5/13/2026 9:36 PM | 6,915 B | `Web.config` |
