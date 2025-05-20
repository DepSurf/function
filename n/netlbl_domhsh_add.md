# Function: <code>netlbl_domhsh_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8180c410)
Location: net/netlabel/netlabel_domainhash.c:365
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff8180c410-ffffffff8180c9c0: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8187e4c0)
Location: net/netlabel/netlabel_domainhash.c:417
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff8187e4c0-ffffffff8187eb53: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff818b2d70)
Location: net/netlabel/netlabel_domainhash.c:417
Inline: False
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff818b2d70-ffffffff818b3403: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff818d9720)
Location: net/netlabel/netlabel_domainhash.c:417
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff818d9720-ffffffff818d9db3: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8195f310)
Location: net/netlabel/netlabel_domainhash.c:417
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff8195f310-ffffffff8195f9a3: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819b8af0)
Location: net/netlabel/netlabel_domainhash.c:417
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff819b8af0-ffffffff819b9189: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819efdc0)
Location: net/netlabel/netlabel_domainhash.c:417
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff819efdc0-ffffffff819f0459: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a5f030)
Location: net/netlabel/netlabel_domainhash.c:403
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff81a5f030-ffffffff81a5f58b: netlbl_domhsh_add.part.0 (STB_LOCAL)
ffffffff81a5f590-ffffffff81a5f6fd: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a95c60)
Location: net/netlabel/netlabel_domainhash.c:403
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff81a95c60-ffffffff81a961bb: netlbl_domhsh_add.part.0 (STB_LOCAL)
ffffffff81a961c0-ffffffff81a9632d: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81b91985)
Location: net/netlabel/netlabel_domainhash.c:405
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
**Symbols:**

```
ffffffff81b913e0-ffffffff81b91948: netlbl_domhsh_add.part.0 (STB_LOCAL)
ffffffff81b91950-ffffffff81b9197d: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81ba1693)
Location: net/netlabel/netlabel_domainhash.c:405
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
**Symbols:**

```
ffffffff81ba10f0-ffffffff81ba164e: netlbl_domhsh_add.part.0 (STB_LOCAL)
ffffffff81ba1650-ffffffff81ba167d: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81b90763)
Location: net/netlabel/netlabel_domainhash.c:405
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
**Symbols:**

```
ffffffff81b901c0-ffffffff81b90718: netlbl_domhsh_add.part.0 (STB_LOCAL)
ffffffff81b90720-ffffffff81b9074d: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81c5cf03)
Location: net/netlabel/netlabel_domainhash.c:405
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
**Symbols:**

```
ffffffff81c5c960-ffffffff81c5ceb8: netlbl_domhsh_add.part.0 (STB_LOCAL)
ffffffff81c5cec0-ffffffff81c5ceed: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81dfedf2)
Location: net/netlabel/netlabel_domainhash.c:405
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
**Symbols:**

```
ffffffff81dfe820-ffffffff81dfed9a: netlbl_domhsh_add.part.0 (STB_LOCAL)
ffffffff81dfeda0-ffffffff81dfedd3: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81fd3a82)
Location: net/netlabel/netlabel_domainhash.c:405
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
**Symbols:**

```
ffffffff81fd3490-ffffffff81fd3a0a: netlbl_domhsh_add.part.0 (STB_LOCAL)
ffffffff81fd3a20-ffffffff81fd3a53: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff8204f6e2)
Location: net/netlabel/netlabel_domainhash.c:405
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
**Symbols:**

```
ffffffff8204f0f0-ffffffff8204f668: netlbl_domhsh_add.part.0 (STB_LOCAL)
ffffffff8204f680-ffffffff8204f6b3: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff82121d92)
Location: net/netlabel/netlabel_domainhash.c:405
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
**Symbols:**

```
ffffffff82121770-ffffffff82121d17: netlbl_domhsh_add.part.0 (STB_LOCAL)
ffffffff82121d30-ffffffff82121d63: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffff800010d64b88)
Location: net/netlabel/netlabel_domainhash.c:403
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffff800010d64b88-ffff800010d651cc: netlbl_domhsh_add.part.0 (STB_LOCAL)
ffff800010d651d0-ffff800010d653bc: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (c0e63600)
Location: net/netlabel/netlabel_domainhash.c:403
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
**Symbols:**

```
c0e63600-c0e63c68: netlbl_domhsh_add.part.0 (STB_LOCAL)
c0e63c68-c0e63e4c: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (c000000000ea0930)
Location: net/netlabel/netlabel_domainhash.c:403
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
c000000000ea0930-c000000000ea1088: netlbl_domhsh_add.part.0 (STB_LOCAL)
c000000000ea1090-c000000000ea12c0: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffe000898b18)
Location: net/netlabel/netlabel_domainhash.c:403
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffe000898b18-ffffffe000898fac: netlbl_domhsh_add.part.0 (STB_LOCAL)
ffffffe000898fac-ffffffe000899122: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81a34ff0)
Location: net/netlabel/netlabel_domainhash.c:403
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff81a34ff0-ffffffff81a3554b: netlbl_domhsh_add.part.0 (STB_LOCAL)
ffffffff81a35550-ffffffff81a356bd: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff819f1c10)
Location: net/netlabel/netlabel_domainhash.c:403
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff819f1c10-ffffffff819f216b: netlbl_domhsh_add.part.0 (STB_LOCAL)
ffffffff819f2170-ffffffff819f22dd: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81aa0ea0)
Location: net/netlabel/netlabel_domainhash.c:403
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff81aa0ea0-ffffffff81aa13fb: netlbl_domhsh_add.part.0 (STB_LOCAL)
ffffffff81aa1400-ffffffff81aa156d: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int netlbl_domhsh_add(struct netlbl_dom_map *entry, struct netlbl_audit *audit_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlabel/netlabel_domainhash.c (ffffffff81aad160)
Location: net/netlabel/netlabel_domainhash.c:403
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_add_default
```
**Symbols:**

```
ffffffff81aad160-ffffffff81aad6b4: netlbl_domhsh_add.part.0 (STB_LOCAL)
ffffffff81aad6c0-ffffffff81aad82d: netlbl_domhsh_add (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
