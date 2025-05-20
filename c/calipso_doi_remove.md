# Function: <code>calipso_doi_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff8186f610)
Location: net/ipv6/calipso.c:448
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818836ed)
Location: net/netlabel/netlabel_calipso.c:447
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff8186f610-ffffffff8186f720: calipso_doi_remove (STB_LOCAL)
ffffffff818838d0-ffffffff818838f0: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818a2580)
Location: net/ipv6/calipso.c:448
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b7f8d)
Location: net/netlabel/netlabel_calipso.c:450
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff818a2580-ffffffff818a2690: calipso_doi_remove (STB_LOCAL)
ffffffff818b8170-ffffffff818b8190: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818c8b80)
Location: net/ipv6/calipso.c:448
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818de86d)
Location: net/netlabel/netlabel_calipso.c:450
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff818c8b80-ffffffff818c8c8c: calipso_doi_remove (STB_LOCAL)
ffffffff818dea60-ffffffff818dea80: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff8194c210)
Location: net/ipv6/calipso.c:448
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8196447d)
Location: net/netlabel/netlabel_calipso.c:450
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff8194c210-ffffffff8194c322: calipso_doi_remove (STB_LOCAL)
ffffffff819646a0-ffffffff819646c6: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819a68c0)
Location: net/ipv6/calipso.c:448
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bdd27)
Location: net/netlabel/netlabel_calipso.c:450
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff819a68c0-ffffffff819a69d2: calipso_doi_remove (STB_LOCAL)
ffffffff819bdf40-ffffffff819bdf66: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819dd420)
Location: net/ipv6/calipso.c:448
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4ec7)
Location: net/netlabel/netlabel_calipso.c:450
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff819dd420-ffffffff819dd532: calipso_doi_remove (STB_LOCAL)
ffffffff819f50e0-ffffffff819f5106: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a4b550)
Location: net/ipv6/calipso.c:434
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a6438b)
Location: net/netlabel/netlabel_calipso.c:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff81a4b550-ffffffff81a4b65e: calipso_doi_remove (STB_LOCAL)
ffffffff81a645b0-ffffffff81a645d6: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a82120)
Location: net/ipv6/calipso.c:434
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9af0b)
Location: net/netlabel/netlabel_calipso.c:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff81a82120-ffffffff81a8222e: calipso_doi_remove (STB_LOCAL)
ffffffff81a9b130-ffffffff81a9b156: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b7dca0)
Location: net/ipv6/calipso.c:434
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b9670b)
Location: net/netlabel/netlabel_calipso.c:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff81b7dca0-ffffffff81b7ddde: calipso_doi_remove (STB_LOCAL)
ffffffff81b96990-ffffffff81b969b6: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b8c330)
Location: net/ipv6/calipso.c:437
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba637b)
Location: net/netlabel/netlabel_calipso.c:438
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff81b8c330-ffffffff81b8c41d: calipso_doi_remove (STB_LOCAL)
ffffffff81ba6600-ffffffff81ba6626: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b7ba70)
Location: net/ipv6/calipso.c:437
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b9550b)
Location: net/netlabel/netlabel_calipso.c:438
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff81b7ba70-ffffffff81b7bb5d: calipso_doi_remove (STB_LOCAL)
ffffffff81b95790-ffffffff81b957b6: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81c46770)
Location: net/ipv6/calipso.c:437
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61d0b)
Location: net/netlabel/netlabel_calipso.c:438
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff81c46770-ffffffff81c4685d: calipso_doi_remove (STB_LOCAL)
ffffffff81c61fc0-ffffffff81c61fe6: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81de5130)
Location: net/ipv6/calipso.c:437
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e04343)
Location: net/netlabel/netlabel_calipso.c:438
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff81de5130-ffffffff81de522b: calipso_doi_remove (STB_LOCAL)
ffffffff81e04670-ffffffff81e046a6: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81fb78e0)
Location: net/ipv6/calipso.c:437
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd9323)
Location: net/netlabel/netlabel_calipso.c:439
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff81fb78e0-ffffffff81fb79db: calipso_doi_remove (STB_LOCAL)
ffffffff81fd96b0-ffffffff81fd96e6: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff82018080)
Location: net/ipv6/calipso.c:437
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82054ff3)
Location: net/netlabel/netlabel_calipso.c:439
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff82018080-ffffffff8201817b: calipso_doi_remove (STB_LOCAL)
ffffffff82055380-ffffffff820553b6: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff820e7050)
Location: net/ipv6/calipso.c:437
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff821278ce)
Location: net/netlabel/netlabel_calipso.c:442
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff820e7050-ffffffff820e714b: calipso_doi_remove (STB_LOCAL)
ffffffff82127ca0-ffffffff82127cd6: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffff800010d4df88)
Location: net/ipv6/calipso.c:434
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6ab8c)
Location: net/netlabel/netlabel_calipso.c:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffff800010d4df88-ffff800010d4e0f8: calipso_doi_remove (STB_LOCAL)
ffff800010d6ae20-ffff800010d6ae6c: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (c0e4e204)
Location: net/ipv6/calipso.c:434
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (c0e690e4)
Location: net/netlabel/netlabel_calipso.c:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
c0e4e204-c0e4e360: calipso_doi_remove (STB_LOCAL)
c0e69384-c0e693c0: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (c000000000e839f0)
Location: net/ipv6/calipso.c:434
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea7fb8)
Location: net/netlabel/netlabel_calipso.c:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
c000000000e839f0-c000000000e83c04: calipso_doi_remove (STB_LOCAL)
c000000000ea8370-c000000000ea83c8: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffe000887452)
Location: net/ipv6/calipso.c:434
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d5ea)
Location: net/netlabel/netlabel_calipso.c:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffe000887452-ffffffe0008875f6: calipso_doi_remove (STB_LOCAL)
ffffffe00089d7c2-ffffffe00089d800: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a217b0)
Location: net/ipv6/calipso.c:434
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a3a29b)
Location: net/netlabel/netlabel_calipso.c:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff81a217b0-ffffffff81a218be: calipso_doi_remove (STB_LOCAL)
ffffffff81a3a4c0-ffffffff81a3a4e6: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819de570)
Location: net/ipv6/calipso.c:434
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6ebb)
Location: net/netlabel/netlabel_calipso.c:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff819de570-ffffffff819de67e: calipso_doi_remove (STB_LOCAL)
ffffffff819f70e0-ffffffff819f7106: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a8c230)
Location: net/ipv6/calipso.c:434
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa614b)
Location: net/netlabel/netlabel_calipso.c:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff81a8c230-ffffffff81a8c33e: calipso_doi_remove (STB_LOCAL)
ffffffff81aa6370-ffffffff81aa6396: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_remove(u32 doi, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a984f0)
Location: net/ipv6/calipso.c:434
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab24eb)
Location: net/netlabel/netlabel_calipso.c:437
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_remove
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_del
```
**Symbols:**

```
ffffffff81a984f0-ffffffff81a9860d: calipso_doi_remove (STB_LOCAL)
ffffffff81ab2710-ffffffff81ab2736: calipso_doi_remove (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
