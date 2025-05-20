# Function: <code>per_cpu_pages_init</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void per_cpu_pages_init(struct per_cpu_pages *pcp, struct per_cpu_zonestat *pzstats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81cbd15d)
Location: mm/page_alloc.c:6883
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
ffffffff81cbd15d-ffffffff81cbd1ac: per_cpu_pages_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void per_cpu_pages_init(struct per_cpu_pages *pcp, struct per_cpu_zonestat *pzstats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81e6ee58)
Location: mm/page_alloc.c:7004
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
ffffffff81e6ee58-ffffffff81e6eeb5: per_cpu_pages_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void per_cpu_pages_init(struct per_cpu_pages *pcp, struct per_cpu_zonestat *pzstats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813e4220)
Location: mm/page_alloc.c:7176
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
ffffffff813e4220-ffffffff813e42c7: per_cpu_pages_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void per_cpu_pages_init(struct per_cpu_pages *pcp, struct per_cpu_zonestat *pzstats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81419760)
Location: mm/page_alloc.c:5382
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
ffffffff81419760-ffffffff81419827: per_cpu_pages_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void per_cpu_pages_init(struct per_cpu_pages *pcp, struct per_cpu_zonestat *pzstats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff814464a0)
Location: mm/page_alloc.c:5474
Inline: False
Direct callers:
  - mm/page_alloc.c:setup_zone_pageset
  - mm/page_alloc.c:build_all_zonelists_init
```
**Symbols:**

```
ffffffff814464a0-ffffffff8144656f: per_cpu_pages_init (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
