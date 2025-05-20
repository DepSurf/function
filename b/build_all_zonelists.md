# Function: <code>build_all_zonelists</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81819430)
Location: mm/page_alloc.c:4357
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff81819430-ffffffff81819510: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81892f80)
Location: mm/page_alloc.c:4854
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81892f80-ffffffff81893060: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff818c77d0)
Location: mm/page_alloc.c:5012
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff818c77d0-ffffffff818c78b0: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat, struct zone *zone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff818fef30)
Location: mm/page_alloc.c:5302
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/page_alloc.c:numa_zonelist_order_handler
  - mm/memory_hotplug.c:try_online_node
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff818fef30-ffffffff818ff010: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81989110)
Location: mm/page_alloc.c:5286
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81989110-ffffffff8198919d: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff819e5a70)
Location: mm/page_alloc.c:5425
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff819e5a70-ffffffff819e5afa: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a20d10)
Location: mm/page_alloc.c:5591
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81a20d10-ffffffff81a20d9a: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a91260)
Location: mm/page_alloc.c:5778
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81a91260-ffffffff81a912ec: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ac85a0)
Location: mm/page_alloc.c:5796
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81ac85a0-ffffffff81ac862c: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81bc0fa0)
Location: mm/page_alloc.c:5884
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81bc0fa0-ffffffff81bc102c: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c3a030)
Location: mm/page_alloc.c:6051
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81c3a030-ffffffff81c3a0b5: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81c2c600)
Location: mm/page_alloc.c:6253
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81c2c600-ffffffff81c2c67e: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81d4acf0)
Location: mm/page_alloc.c:6437
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81d4acf0-ffffffff81d4ad88: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81f1a610)
Location: mm/page_alloc.c:6499
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:hotadd_init_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81f1a610-ffffffff81f1a6bd: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff820c2490)
Location: mm/page_alloc.c:6666
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:hotadd_init_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff820c2490-ffffffff820c2538: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82146440)
Location: mm/page_alloc.c:5229
Inline: False
Direct callers:
  - mm/mm_init.c:mm_core_init
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:hotadd_init_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff82146440-ffffffff821464e8: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82228b50)
Location: mm/page_alloc.c:5318
Inline: False
Direct callers:
  - mm/mm_init.c:mm_core_init
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:hotadd_init_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff82228b50-ffffffff82228bf8: build_all_zonelists (STB_GLOBAL)
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
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010d9c400)
Location: mm/page_alloc.c:5796
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffff800010d9c400-ffff800010d9c4b0: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0e98b50)
Location: mm/page_alloc.c:5796
Inline: False
Direct callers:
  - init/main.c:start_kernel
```
**Symbols:**

```
c0e98b50-c0e98be0: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ee720)
Location: mm/page_alloc.c:5796
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
c0000000003ee720-c0000000003ee808: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe0008c4520)
Location: mm/page_alloc.c:5796
Inline: False
Direct callers:
  - init/main.c:start_kernel
```
**Symbols:**

```
ffffffe0008c4520-ffffffe0008c4624: build_all_zonelists (STB_GLOBAL)
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
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a67410)
Location: mm/page_alloc.c:5796
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81a67410-ffffffff81a6749c: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81a23ed0)
Location: mm/page_alloc.c:5796
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81a23ed0-ffffffff81a23f5c: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81ad3820)
Location: mm/page_alloc.c:5796
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81ad3820-ffffffff81ad38ac: build_all_zonelists (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void build_all_zonelists(pg_data_t *pgdat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81adfd20)
Location: mm/page_alloc.c:5796
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:hotadd_new_pgdat
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81adfd20-ffffffff81adfdac: build_all_zonelists (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct zone *zone</code>
</li>
</ul>
</details>
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
