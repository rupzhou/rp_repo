# India raw cotton duty-waiver window — client impact run

Event: India waives 11% customs import duty on raw cotton (July 2026)
Run ID: 20260827T014750Z
Run date: 2026-08-27T01:47:50Z

Business alert: India's raw-cotton import-duty waiver remains active now.
Why it matters: India suppliers that directly control cotton-chain procurement can still lower input cost before the 31 Oct cliff.[1][2][3]
Immediate focus: separate direct-capture factories from CMT/check-only factories, then prioritise financing conversations that can settle inside the window.[1][2][4]

## CP5 run summary
- Families: EVT-TARIFF STRONG; EVT-MARKET-SHIFT MODERATE
- Cluster match: none
- CP3.5 authoritative client total: 90
- Direct or sourcing-control candidates: 24
- CMT / check-only candidates: 66
- Live cotton reference: 89.18 USc/lb on Thu, Aug 27th, 2026[4]
- Duty window: 0% BCD + 0% AIDC until 2026-10-31 (65 days remaining inclusive); project post-window reference remains ~16%.[2][3]

## COMBO summary
| COMBO | Archetype | Clients | Signal | Product | Action |
|---|---|---:|---|---|---|
| COMBO-003 | India Large Vertical Integrator | 2 | EXPAND CANDIDATE (conditional) | PROD-ARP [MULTI-SIGNAL 🎯] | Now |
| COMBO-014 | India Small Woven / FOB direct-capture lane | 22 | EXPAND CANDIDATE (conditional) | PROD-ARP [MULTI-SIGNAL 🎯] | Verify First |
| COMBO-014 | India Small Woven / CMT check-only lane | 66 | CHECK / MONITOR | No financing push until sourcing control is proven | Verify First / Monitor |

## CP3.5 distributions
- By combo: {"COMBO-014": 88, "COMBO-003": 2}
- By product: {"woven": 86, "denim": 1, "home-textile": 3}
- By market: {"US": 44, "multi": 11, "EU/UK": 17, "EU": 7, "EU/US": 2, "ME": 2, "APAC/EU": 1, "APAC": 3, "APAC/US": 3}
- Direct candidate markets: {"US": 14, "multi": 2, "EU/UK": 4, "EU": 2, "EU/US": 1, "ME": 1}
- CMT candidate markets: {"US": 30, "multi": 9, "EU/US": 1, "APAC/EU": 1, "APAC": 3, "EU": 5, "EU/UK": 13, "APAC/US": 3, "ME": 1}
- Match trace: after_country=104 → after_product_focus=92 → after_combo=90

## Recommended outreach order
1. COMBO-003 vertical US rows: COSMO FIRST LIMITED; SAHU GLOBAL PRIVATE LIMITED
2. COMBO-014 FOB US/EU rows with known scale: RASIK PRODUCTS PRIVATE LIMITED; TEXPORT INDUSTRIES PVT. LTD.; SHIVANK UDYOG LTD; AVC TEXTILES; VIVSUN EXPORTS
3. COMBO-014 CMT rows: verify sourcing-control exceptions before any financing push

## KB-GAP summary
| Gap ID | Description | Triggered at | Priority | Route |
|---|---|---|---|---|
| GAP-0 | KB still lacks a canonical explanatory note tying the user-facing 11% relief wording to the underlying BCD+AIDC waiver structure on HS 5201. | CP0 | MEDIUM | KB Expand |
| KBG-CP2-001 | Exact subtype for temporary domestic raw-material duty waiver with expiry-window logic is still approximated under import_export_duty. | CP2 | MEDIUM | KB Expand |
| KBG-CP3-001 | Missing exact raw-material entity for conventional raw cotton / HS 5201; using cotton-yarn and cotton-denim-fabric proxies for downstream reasoning. | CP3 | HIGH | Expert Review |
| KBG-CP4-001 | Per-factory imported-vs-domestic cotton share, procurement ownership, and buyer pass-through terms remain unresolved for most rows and require BD collection. | CP4 | HIGH | Expert Review |

HTML artifact: 20260827T014750Z-india-raw-cotton-duty-waiver-client-cards.html

Sources:
[1] Reuters/Yahoo Finance summary page on India scrapping cotton import duty for five months: https://sg.finance.yahoo.com/news/india-waives-cotton-import-duty-114900071.html
[2] Taxguru summary of Notification No. 19/2026-Customs / heading 5201 / BCD+AIDC exemption: https://taxguru.in/custom-duty/raw-cotton-imports-exempt-bcd-aidc-31st-october-2026.html
[3] Textile Value Chain summary of temporary exemption and effective 11% duty relief framing: https://textilevaluechain.in/textile-industry-welcomes-temporary-exemption-of-cotton-import-duty-until-october-31-2026/
[4] Barchart Cotton #2 Dec 26 futures page used for live cotton reference: https://www.barchart.com/futures/quotes/CTZ26
