# Function: <code>calipso_doi_add</code>

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
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff8186f720)
Location: net/ipv6/calipso.c:359
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8188382e)
Location: net/netlabel/netlabel_calipso.c:409
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff8186f720-ffffffff8186f843: calipso_doi_add (STB_LOCAL)
ffffffff81883890-ffffffff818838af: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818a2690)
Location: net/ipv6/calipso.c:359
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818b80ce)
Location: net/netlabel/netlabel_calipso.c:412
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff818a2690-ffffffff818a27b3: calipso_doi_add (STB_LOCAL)
ffffffff818b8130-ffffffff818b814f: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff818c8c90)
Location: net/ipv6/calipso.c:359
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff818de99d)
Location: net/netlabel/netlabel_calipso.c:412
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff818c8c90-ffffffff818c8da8: calipso_doi_add (STB_LOCAL)
ffffffff818dea20-ffffffff818dea3f: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff8194c330)
Location: net/ipv6/calipso.c:359
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819645ad)
Location: net/netlabel/netlabel_calipso.c:412
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff8194c330-ffffffff8194c448: calipso_doi_add (STB_LOCAL)
ffffffff81964640-ffffffff81964665: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819a6560)
Location: net/ipv6/calipso.c:359
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819bde4d)
Location: net/netlabel/netlabel_calipso.c:412
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff819a6560-ffffffff819a6678: calipso_doi_add (STB_LOCAL)
ffffffff819bdee0-ffffffff819bdf05: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819dd0c0)
Location: net/ipv6/calipso.c:359
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f4fed)
Location: net/netlabel/netlabel_calipso.c:412
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff819dd0c0-ffffffff819dd1d8: calipso_doi_add (STB_LOCAL)
ffffffff819f5080-ffffffff819f50a5: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a4bcd0)
Location: net/ipv6/calipso.c:345
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a644c1)
Location: net/netlabel/netlabel_calipso.c:399
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff81a4bcd0-ffffffff81a4bdee: calipso_doi_add (STB_LOCAL)
ffffffff81a64550-ffffffff81a64575: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a828a0)
Location: net/ipv6/calipso.c:345
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a9b041)
Location: net/netlabel/netlabel_calipso.c:399
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff81a828a0-ffffffff81a829be: calipso_doi_add (STB_LOCAL)
ffffffff81a9b0d0-ffffffff81a9b0f5: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b7db80)
Location: net/ipv6/calipso.c:345
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b96811)
Location: net/netlabel/netlabel_calipso.c:399
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff81b7db80-ffffffff81b7dc9e: calipso_doi_add (STB_LOCAL)
ffffffff81b96930-ffffffff81b96955: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b8ccb0)
Location: net/ipv6/calipso.c:348
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ba6481)
Location: net/netlabel/netlabel_calipso.c:400
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff81b8ccb0-ffffffff81b8cdd5: calipso_doi_add (STB_LOCAL)
ffffffff81ba65a0-ffffffff81ba65c5: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81b7bb60)
Location: net/ipv6/calipso.c:348
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81b95617)
Location: net/netlabel/netlabel_calipso.c:400
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff81b7bb60-ffffffff81b7bc85: calipso_doi_add (STB_LOCAL)
ffffffff81b95730-ffffffff81b95755: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81c46860)
Location: net/ipv6/calipso.c:348
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81c61e47)
Location: net/netlabel/netlabel_calipso.c:400
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff81c46860-ffffffff81c46985: calipso_doi_add (STB_LOCAL)
ffffffff81c61f60-ffffffff81c61f85: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81de52f0)
Location: net/ipv6/calipso.c:348
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81e044ae)
Location: net/netlabel/netlabel_calipso.c:400
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff81de52f0-ffffffff81de5420: calipso_doi_add (STB_LOCAL)
ffffffff81e045f0-ffffffff81e04625: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81fb7ac0)
Location: net/ipv6/calipso.c:348
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fd94ae)
Location: net/netlabel/netlabel_calipso.c:401
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff81fb7ac0-ffffffff81fb7bf0: calipso_doi_add (STB_LOCAL)
ffffffff81fd9610-ffffffff81fd9645: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff82018260)
Location: net/ipv6/calipso.c:348
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff8205517e)
Location: net/netlabel/netlabel_calipso.c:401
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff82018260-ffffffff82018390: calipso_doi_add (STB_LOCAL)
ffffffff820552e0-ffffffff82055315: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff820e7230)
Location: net/ipv6/calipso.c:348
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82127a96)
Location: net/netlabel/netlabel_calipso.c:404
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff820e7230-ffffffff820e7360: calipso_doi_add (STB_LOCAL)
ffffffff82127c00-ffffffff82127c35: calipso_doi_add (STB_GLOBAL)
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
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffff800010d4e0f8)
Location: net/ipv6/calipso.c:345
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffff800010d6ace8)
Location: net/netlabel/netlabel_calipso.c:399
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffff800010d4e0f8-ffff800010d4e270: calipso_doi_add (STB_LOCAL)
ffff800010d6ad90-ffff800010d6addc: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (c0e4e360)
Location: net/ipv6/calipso.c:345
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (c0e69274)
Location: net/netlabel/netlabel_calipso.c:399
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
c0e4e360-c0e4e4bc: calipso_doi_add (STB_LOCAL)
c0e69314-c0e69350: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (c000000000e83c10)
Location: net/ipv6/calipso.c:345
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (c000000000ea817c)
Location: net/netlabel/netlabel_calipso.c:399
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
c000000000e83c10-c000000000e83de4: calipso_doi_add (STB_LOCAL)
c000000000ea82c0-c000000000ea8318: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffe0008872e2)
Location: net/ipv6/calipso.c:345
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffe00089d6e6)
Location: net/netlabel/netlabel_calipso.c:399
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffe0008872e2-ffffffe000887452: calipso_doi_add (STB_LOCAL)
ffffffe00089d754-ffffffe00089d792: calipso_doi_add (STB_GLOBAL)
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
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a21f30)
Location: net/ipv6/calipso.c:345
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81a3a3d1)
Location: net/netlabel/netlabel_calipso.c:399
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff81a21f30-ffffffff81a2204e: calipso_doi_add (STB_LOCAL)
ffffffff81a3a460-ffffffff81a3a485: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff819decf0)
Location: net/ipv6/calipso.c:345
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff819f6ff1)
Location: net/netlabel/netlabel_calipso.c:399
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff819decf0-ffffffff819dee0e: calipso_doi_add (STB_LOCAL)
ffffffff819f7080-ffffffff819f70a5: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a8c9b0)
Location: net/ipv6/calipso.c:345
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81aa6281)
Location: net/netlabel/netlabel_calipso.c:399
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff81a8c9b0-ffffffff81a8cace: calipso_doi_add (STB_LOCAL)
ffffffff81aa6310-ffffffff81aa6335: calipso_doi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
int calipso_doi_add(struct calipso_doi *doi_def, struct netlbl_audit *audit_info);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/calipso.c (ffffffff81a98610)
Location: net/ipv6/calipso.c:345
Inline: False
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81ab2621)
Location: net/netlabel/netlabel_calipso.c:399
Inline: True
Direct callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_add
```
**Symbols:**

```
ffffffff81a98610-ffffffff81a9872c: calipso_doi_add (STB_LOCAL)
ffffffff81ab26b0-ffffffff81ab26d5: calipso_doi_add (STB_GLOBAL)
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
