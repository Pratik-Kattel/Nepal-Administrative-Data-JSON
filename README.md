# Nepal Administrative Data JSON

A complete hierarchical JSON dataset of **Nepal’s administrative divisions**, including **provinces, districts, and municipalities (local levels)**.

---

## 📂 Dataset Structure

The JSON is structured hierarchically:

```json
[
  {
    "province_id": 1,
    "name": "Koshi Pradesh",
    "nepali_name": "कोशी प्रदेश",
    "districts": [
      {
        "district_id": 4,
        "name": "Morang",
        "nepali_name": "मोरङ",
        "cities": [
          {"municipality_id": 10, "name": "Biratnagar", "nepali_name": "बिराटनगर"},
          {"municipality_id": 11, "name": "Urlabari", "nepali_name": "उर्लाबारी"}
        ]
      }
    ]
  }
]
