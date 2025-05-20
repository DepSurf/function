# Function: <code>numa_zonelist_order_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81193b10)
Location: mm/page_alloc.c:3945
Inline: False
```
**Symbols:**

```
ffffffff81193b10-ffffffff81193cc3: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811abfd0)
Location: mm/page_alloc.c:4442
Inline: False
```
**Symbols:**

```
ffffffff811abfd0-ffffffff811ac183: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bc5b0)
Location: mm/page_alloc.c:4600
Inline: False
```
**Symbols:**

```
ffffffff811bc5b0-ffffffff811bc763: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c4770)
Location: mm/page_alloc.c:4887
Inline: False
```
**Symbols:**

```
ffffffff811c4770-ffffffff811c492f: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d9580)
Location: mm/page_alloc.c:4967
Inline: False
```
**Symbols:**

```
ffffffff811d9580-ffffffff811d95d3: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f9ec0)
Location: mm/page_alloc.c:5106
Inline: False
```
**Symbols:**

```
ffffffff811f9ec0-ffffffff811f9f1a: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120c570)
Location: mm/page_alloc.c:5272
Inline: False
```
**Symbols:**

```
ffffffff8120c570-ffffffff8120c5ca: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812727b0)
Location: mm/page_alloc.c:5458
Inline: False
```
**Symbols:**

```
ffffffff812727b0-ffffffff8127280f: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81281610)
Location: mm/page_alloc.c:5476
Inline: False
```
**Symbols:**

```
ffffffff81281610-ffffffff8128166f: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5575
Inline: False
```
**Symbols:**

```
ffffffff812b52f0-ffffffff812b5309: numa_zonelist_order_handler.cold (STB_LOCAL)
ffffffff812b3b00-ffffffff812b3b30: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5741
Inline: False
```
**Symbols:**

```
ffffffff81be8624-ffffffff81be863d: numa_zonelist_order_handler.cold (STB_LOCAL)
ffffffff812bf5d0-ffffffff812bf600: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:5943
Inline: False
```
**Symbols:**

```
ffffffff81bda427-ffffffff81bda440: numa_zonelist_order_handler.cold (STB_LOCAL)
ffffffff812c4c50-ffffffff812c4c80: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:6126
Inline: False
```
**Symbols:**

```
ffffffff81cbe484-ffffffff81cbe49d: numa_zonelist_order_handler.cold (STB_LOCAL)
ffffffff81308cf0-ffffffff81308d20: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:6183
Inline: False
```
**Symbols:**

```
ffffffff81e703c7-ffffffff81e703e0: numa_zonelist_order_handler.cold (STB_LOCAL)
ffffffff813711a0-ffffffff813711ee: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813ee7e0)
Location: mm/page_alloc.c:6351
Inline: False
```
**Symbols:**

```
ffffffff813ee7e0-ffffffff813ee84b: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff814199b0)
Location: mm/page_alloc.c:4900
Inline: True
```
**Symbols:**

```
ffffffff814199b0-ffffffff81419a1b: numa_zonelist_order_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff814466f0)
Location: mm/page_alloc.c:4989
Inline: True
```
**Symbols:**

```
ffffffff814466f0-ffffffff8144675b: numa_zonelist_order_handler (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010319a98)
Location: mm/page_alloc.c:5476
Inline: False
```
**Symbols:**

```
ffff800010319a98-ffff800010319b44: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ec7a0)
Location: mm/page_alloc.c:5476
Inline: False
```
**Symbols:**

```
c0000000003ec7a0-c0000000003ec85c: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81279c60)
Location: mm/page_alloc.c:5476
Inline: False
```
**Symbols:**

```
ffffffff81279c60-ffffffff81279cbf: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126bb50)
Location: mm/page_alloc.c:5476
Inline: False
```
**Symbols:**

```
ffffffff8126bb50-ffffffff8126bbaf: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81277a00)
Location: mm/page_alloc.c:5476
Inline: False
```
**Symbols:**

```
ffffffff81277a00-ffffffff81277a5f: numa_zonelist_order_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int numa_zonelist_order_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812875f0)
Location: mm/page_alloc.c:5476
Inline: False
```
**Symbols:**

```
ffffffff812875f0-ffffffff8128764f: numa_zonelist_order_handler (STB_GLOBAL)
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
