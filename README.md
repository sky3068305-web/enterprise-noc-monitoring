# enterprise-noc-monitoring
跨國 NOC 戰情室監控
# 跨國企業級網路運營中心 (NOC) 監控系統

## 📌 專案簡介
本專案為獨立建置之跨國 NOC 監控與告警機制，涵蓋台、美、歐三地共 39+ 實體/虛擬化節點，實現 24/7 主動式運維監控。

## 🛠 技術架構與使用工具
- **核心監控引擎:** LibreNMS / SNMP / API 整合
- **虛擬化平台:** VMware ESXi 叢集
- **網路與安全:** Zyxel Switch、Site-to-Site VPN、Firewall 政策配置
- **系統服務:** Nginx (Reverse Proxy) + SSL 加密憑證、Docker 微服務部署
- **自動化腳本:** Python (專案自動化維運與 API 整合)

## 📐 系統架構與展示
(在此貼上你的 LibreNMS 戰情室截圖或架構圖)

## 🚀 專案效益
1. 實現跨國多節點即時流量與錯誤監控，將故障發現時間 (MTTD) 縮短 50%。
2. 整合主動式告警機制，維持系統 99.9% 以上高可用性 (Availability)。
