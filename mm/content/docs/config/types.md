---
title: "Port Types"
description: "A list of the available port types in Masterful Machinery."
lead: "A list of the available port types in Masterful Machinery."
date: 2020-10-06T08:49:31+00:00
lastmod: 2020-10-06T08:49:31+00:00
draft: false
images: []
menu:
  docs:
    parent: "config"
weight: 660
toc: true
---

- `masterfulmachinery:items` (Item Ports)
- `masterfulmachinery:fluids` (Fluid Ports)
- `masterfulmachinery:energy` (Forge Energy Ports)
- `masterfulmachinery:mekanism_gas` (Mekanism Gas Ports)
- `masterfulmachinery:mekanism_slurry` (Mekanism Slurry Ports)
- `masterfulmachinery:create_rotation` (Create Rotation Ports)
- `masterfulmachinery:pncr_pressure` (Pneumaticcraft Pressure Ports)


## Controllers File Config Data Section

- `masterfulmachinery:items` (Item Ports)

```json
{
    "rows": INTEGER,
    "columns": INTEGER
}
```

Replace `INTEGER` with a whole number (integer) for example: `6` or `9` 

---

- `masterfulmachinery:fluids` (Fluid Ports)
```json
{
    "capacity": INTEGER
}
```

Replace `INTEGER` with a whole number (integer) for example: `10000` or `870` 

--- 
- `masterfulmachinery:energy` (Forge Energy Ports)

```json
{
    "capacity": INTEGER
}
```

Replace `INTEGER` with a whole number (integer) for example: `10000` or `870` 

---

- `masterfulmachinery:mekanism_gas` (Mekanism Gas Ports)

```json
{
    "capacity": INTEGER
}
```

Replace `INTEGER` with a whole number (integer) for example: `10000` or `870` 

---

- `masterfulmachinery:mekanism_slurry` (Mekanism Slurry Ports)
```json
{
    "capacity": INTEGER
}
```

Replace `INTEGER` with a whole number (integer) for example: `10000` or `870` 

---

- `masterfulmachinery:create_rotation` (Create Mod Rotational Force)
```json
{
}
```

This port requires an empty data section

---


- `masterfulmachinery:pncr_pressure` (Pneumaticraft Air Pressure)
```json
{
    "dangerPressure": FLOAT,
    "criticalPressure": FLOAT,
    "volume": INTEGER
}
```

Replace `INTEGER` with a whole number (integer) for example: `10000` or `870` 
Replace `FLOAT` with a decimal number (integer) for example: `15.0` or `20.7` 

---




## Process recipe Data Section

- `masterfulmachinery:items` (Item Ports)

```json
{
    "item": STRING,
    "count": INTEGER
}
```

Replace `INTEGER` with a whole number (integer) for example: `6` or `9` 
Replace `STRING` with an item id for example `minecraft:nether_star`

---

- `masterfulmachinery:fluids` (Fluid Ports)
```json
{
    "fluid": STRING,
    "amount": INTEGER
}
```

Replace `INTEGER` with a whole number (integer) for example: `10000` or `870` 
Replace `STRING` with an fluid id for example `minecraft:water`


--- 
- `masterfulmachinery:energy` (Forge Energy Ports)

```json
{
    "amount": INTEGER
}
```

Replace `INTEGER` with a whole number (integer) for example: `10000` or `870` 

---

- `masterfulmachinery:mekanism_gas` (Mekanism Gas Ports)

```json
{
    "gas": STRING,
    "amount": INTEGER
}
```

Replace `INTEGER` with a whole number (integer) for example: `10000` or `870` 
Replace `STRING` with an gas id for example `mekanism:steam`

---

- `masterfulmachinery:mekanism_slurry` (Mekanism Slurry Ports)
```json
{
    "slurry": STRING,
    "amount": INTEGER
}
```

Replace `INTEGER` with a whole number (integer) for example: `10000` or `870` 
Replace `STRING` with an slurry id for example `mekanism:clean_gold`

---

- `masterfulmachinery:create_rotation` (Create Mod Rotational Force)
```json
{
    "speed": FLOAT
}
```

Replace `FLOAT` with a decimal number (integer) for example: `15.0` or `120.7` 

---


- `masterfulmachinery:pncr_pressure` (Pneumaticraft Air Pressure)
```json
{
    "air": INTEGER
}
```

Replace `INTEGER` with a whole number (integer) for example: `100` or `870` 