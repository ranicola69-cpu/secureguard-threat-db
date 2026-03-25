<div align="center">

# 🔍 SecureGuard Threat Database

### *Live Threat Intelligence Feed*

[![DPHMS](https://img.shields.io/badge/DPHMS-Threat%20Intel-8B0000?style=for-the-badge)](https://github.com/ranicola69-cpu)
[![JSON](https://img.shields.io/badge/Format-JSON-yellow?style=for-the-badge&logo=json)](https://github.com/ranicola69-cpu/secureguard-threat-db/blob/main/threats.json)
[![Secure Guard](https://img.shields.io/badge/Used%20By-Secure%20Guard-3DDC84?style=for-the-badge)](https://github.com/ranicola69-cpu/secure-guard-blu-g64)

</div>

---

> The centralized threat intelligence database powering the **Secure Guard** app. Updated continuously with new threat signatures, malware hashes, and network IOCs.

---

## 📡 Usage

This database is consumed automatically by [Secure Guard](https://github.com/ranicola69-cpu/secure-guard-blu-g64). The app pulls from this feed on each scan to cross-reference against known threats.

```json
// threats.json structure
{
  "version": "...",
  "updated": "...",
  "threats": [
    {
      "id": "...",
      "name": "...",
      "type": "malware | spyware | adware | network",
      "severity": "low | medium | high | critical",
      "hash": "...",
      "description": "..."
    }
  ]
}
```

---

## 🔗 Integration

| App | Status |
|-----|--------|
| [Secure Guard BLU G64](https://github.com/ranicola69-cpu/secure-guard-blu-g64) | ✅ Live |

---

<div align="center">

*DPHMS — Defense Protocol & High-Mobility Security*

</div>