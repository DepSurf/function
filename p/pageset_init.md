# Function: <code>pageset_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8181cd0f)
Location: mm/page_alloc.c:4617
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:__build_all_zonelists
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81896f27)
Location: mm/page_alloc.c:5153
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:__build_all_zonelists
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff818cb66f)
Location: mm/page_alloc.c:5236
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:__build_all_zonelists
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pageset_init(struct per_cpu_pageset *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bea00)
Location: mm/page_alloc.c:5535
Inline: True
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:__build_all_zonelists
```
**Symbols:**

```
ffffffff811bea00-ffffffff811bea5f: pageset_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pageset_init(struct per_cpu_pageset *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811da339)
Location: mm/page_alloc.c:5507
Inline: True
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
ffffffff811da339-ffffffff811da381: pageset_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pageset_init(struct per_cpu_pageset *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811face5)
Location: mm/page_alloc.c:5645
Inline: True
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
ffffffff811face5-ffffffff811fad2d: pageset_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pageset_init(struct per_cpu_pageset *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120d59c)
Location: mm/page_alloc.c:5890
Inline: True
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
ffffffff8120d59c-ffffffff8120d5d7: pageset_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pageset_init(struct per_cpu_pageset *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81273a20)
Location: mm/page_alloc.c:6076
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
ffffffff81273a20-ffffffff81273a5b: pageset_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pageset_init(struct per_cpu_pageset *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81282890)
Location: mm/page_alloc.c:6094
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
ffffffff81282890-ffffffff812828cb: pageset_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pageset_init(struct per_cpu_pageset *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b4925)
Location: mm/page_alloc.c:6191
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
ffffffff812b4925-ffffffff812b4960: pageset_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pageset_init(struct per_cpu_pageset *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81be7c1c)
Location: mm/page_alloc.c:6419
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
ffffffff81be7c1c-ffffffff81be7c5e: pageset_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pageset_init(struct per_cpu_pageset *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81bd99fb)
Location: mm/page_alloc.c:6640
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
ffffffff81bd99fb-ffffffff81bd9a3d: pageset_init (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pageset_init(struct per_cpu_pageset *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff80001031b114)
Location: mm/page_alloc.c:6094
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
ffff80001031b114-ffff80001031b168: pageset_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pageset_init(struct per_cpu_pageset *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c05350c4)
Location: mm/page_alloc.c:6094
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
c05350c4-c0535110: pageset_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pageset_init(struct per_cpu_pageset *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ee60c)
Location: mm/page_alloc.c:6094
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
c0000000003ee60c-c0000000003ee678: pageset_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe0000472aa)
Location: mm/page_alloc.c:6094
Inline: True
Inline callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pageset_init(struct per_cpu_pageset *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127aee0)
Location: mm/page_alloc.c:6094
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
ffffffff8127aee0-ffffffff8127af1b: pageset_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pageset_init(struct per_cpu_pageset *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126cdc0)
Location: mm/page_alloc.c:6094
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
ffffffff8126cdc0-ffffffff8126cdfb: pageset_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pageset_init(struct per_cpu_pageset *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81278c80)
Location: mm/page_alloc.c:6094
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
ffffffff81278c80-ffffffff81278cbb: pageset_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pageset_init(struct per_cpu_pageset *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81288870)
Location: mm/page_alloc.c:6094
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
ffffffff81288870-ffffffff812888ab: pageset_init (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
