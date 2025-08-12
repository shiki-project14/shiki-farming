# shiki-farming
A farming system for QBCore.
This script allows players to interactively plant, harvest, and sell crops.

---

## 📦 Features
- Farming locations with a target system (qb-target)
- Planting and harvesting with animations
- Harvested items stored in inventory
- Integration with **QBCore inventory**
- Easy configuration via `config.lua`

---

## 📂 Instalasi
1. drag and drop folders shiki-farming to resources
   
2. Copy and paste from the images folder to qb-inventory/html/images

3. qb-core/shared/items.lua

["benih_tomat"] = {
    ["name"] = "benih_tomat",
    ["label"] = "Benih Tomat",
    ["weight"] = 10,
    ["type"] = "item",
    ["image"] = "benih_tomat.png",
    ["unique"] = false,
    ["useable"] = false,
    ["shouldClose"] = true,
    ["combinable"] = nil,
    ["description"] = "Benih tanaman tomat."
},
["benih_kentang"] = {
    ["name"] = "benih_kentang",
    ["label"] = "Benih Kentang",
    ["weight"] = 10,
    ["type"] = "item",
    ["image"] = "benih_kentang.png",
    ["unique"] = false,
    ["useable"] = false,
    ["shouldClose"] = true,
    ["combinable"] = nil,
    ["description"] = "Benih tanaman kentang."
},
["benih_wortel"] = {
    ["name"] = "benih_wortel",
    ["label"] = "Benih Wortel",
    ["weight"] = 10,
    ["type"] = "item",
    ["image"] = "benih_wortel.png",
    ["unique"] = false,
    ["useable"] = false,
    ["shouldClose"] = true,
    ["combinable"] = nil,
    ["description"] = "Benih tanaman wortel."
},

-- Hasil panen
["tomat"] = {
    ["name"] = "tomat",
    ["label"] = "Tomat",
    ["weight"] = 100,
    ["type"] = "item",
    ["image"] = "tomat.png",
    ["unique"] = false,
    ["useable"] = false,
    ["shouldClose"] = true,
    ["combinable"] = nil,
    ["description"] = "Tomat segar hasil panen."
},
["kentang"] = {
    ["name"] = "kentang",
    ["label"] = "Kentang",
    ["weight"] = 100,
    ["type"] = "item",
    ["image"] = "kentang.png",
    ["unique"] = false,
    ["useable"] = false,
    ["shouldClose"] = true,
    ["combinable"] = nil,
    ["description"] = "Kentang segar hasil panen."
},
["wortel"] = {
    ["name"] = "wortel",
    ["label"] = "Wortel",
    ["weight"] = 100,
    ["type"] = "item",
    ["image"] = "wortel.png",
    ["unique"] = false,
    ["useable"] = false,
    ["shouldClose"] = true,
    ["combinable"] = nil,
    ["description"] = "Wortel segar hasil panen."
},
["cabai"] = {
    ["name"] = "cabai",
    ["label"] = "Cabai",
    ["weight"] = 50,
    ["type"] = "item",
    ["image"] = "cabai.png",
    ["unique"] = false,
    ["useable"] = false,
    ["shouldClose"] = true,
    ["combinable"] = nil,
    ["description"] = "Cabai merah segar hasil panen."
},
["ember_air"] = {
    ["name"] = "ember_air",
    ["label"] = "Ember Air",
    ["weight"] = 200,
    ["type"] = "item",
    ["image"] = "ember_air.png",
    ["unique"] = false,
    ["useable"] = true,
    ["shouldClose"] = true,
    ["combinable"] = nil,
    ["description"] = "Berisi air untuk menyiram tanaman."
},
