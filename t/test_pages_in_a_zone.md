# Function: <code>test_pages_in_a_zone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int test_pages_in_a_zone(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff811f0260)
Location: mm/memory_hotplug.c:1376
Inline: False
Direct callers:
  - drivers/base/memory.c:show_valid_zones
```
**Symbols:**

```
ffffffff811f0260-ffffffff811f036f: test_pages_in_a_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int test_pages_in_a_zone(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8120f580)
Location: mm/memory_hotplug.c:1496
Inline: False
Direct callers:
  - drivers/base/memory.c:show_valid_zones
```
**Symbols:**

```
ffffffff8120f580-ffffffff8120f685: test_pages_in_a_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int test_pages_in_a_zone(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int *valid_start, long unsigned int *valid_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81221690)
Location: mm/memory_hotplug.c:1489
Inline: False
Direct callers:
  - drivers/base/memory.c:show_valid_zones
```
**Symbols:**

```
ffffffff81221690-ffffffff812217c1: test_pages_in_a_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int test_pages_in_a_zone(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int *valid_start, long unsigned int *valid_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8122d2b0)
Location: mm/memory_hotplug.c:1300
Inline: False
Direct callers:
  - drivers/base/memory.c:show_valid_zones
```
**Symbols:**

```
ffffffff8122d2b0-ffffffff8122d3e8: test_pages_in_a_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int test_pages_in_a_zone(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int *valid_start, long unsigned int *valid_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81248b30)
Location: mm/memory_hotplug.c:1288
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - drivers/base/memory.c:show_valid_zones
```
**Symbols:**

```
ffffffff81248b30-ffffffff81248c71: test_pages_in_a_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int test_pages_in_a_zone(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int *valid_start, long unsigned int *valid_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8126c5c0)
Location: mm/memory_hotplug.c:1297
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - drivers/base/memory.c:show_valid_zones
```
**Symbols:**

```
ffffffff8126c5c0-ffffffff8126c6db: test_pages_in_a_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int test_pages_in_a_zone(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int *valid_start, long unsigned int *valid_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81280e20)
Location: mm/memory_hotplug.c:1270
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff81280e20-ffffffff81280f7f: test_pages_in_a_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int test_pages_in_a_zone(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int *valid_start, long unsigned int *valid_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8129d280)
Location: mm/memory_hotplug.c:1253
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff8129d280-ffffffff8129d40e: test_pages_in_a_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int test_pages_in_a_zone(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int *valid_start, long unsigned int *valid_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812aca50)
Location: mm/memory_hotplug.c:1228
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff812aca50-ffffffff812acbde: test_pages_in_a_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct zone *test_pages_in_a_zone(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812e1a60)
Location: mm/memory_hotplug.c:1190
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff812e1a60-ffffffff812e1be2: test_pages_in_a_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct zone *test_pages_in_a_zone(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812ec9c0)
Location: mm/memory_hotplug.c:1201
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff812ec9c0-ffffffff812ecb49: test_pages_in_a_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct zone *test_pages_in_a_zone(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812c7540)
Location: mm/memory_hotplug.c:1437
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff812c7540-ffffffff812c76cf: test_pages_in_a_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct zone *test_pages_in_a_zone(long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8130c2c0)
Location: mm/memory_hotplug.c:1603
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff8130c2c0-ffffffff8130c48b: test_pages_in_a_zone (STB_GLOBAL)
```
</details>
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int test_pages_in_a_zone(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int *valid_start, long unsigned int *valid_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042ef40)
Location: mm/memory_hotplug.c:1228
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
c00000000042ef40-c00000000042f0e8: test_pages_in_a_zone (STB_GLOBAL)
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
int test_pages_in_a_zone(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int *valid_start, long unsigned int *valid_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a5030)
Location: mm/memory_hotplug.c:1228
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff812a5030-ffffffff812a51be: test_pages_in_a_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int test_pages_in_a_zone(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int *valid_start, long unsigned int *valid_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81296b00)
Location: mm/memory_hotplug.c:1228
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff81296b00-ffffffff81296c8e: test_pages_in_a_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int test_pages_in_a_zone(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int *valid_start, long unsigned int *valid_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a2e40)
Location: mm/memory_hotplug.c:1228
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff812a2e40-ffffffff812a2fce: test_pages_in_a_zone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int test_pages_in_a_zone(long unsigned int start_pfn, long unsigned int end_pfn, long unsigned int *valid_start, long unsigned int *valid_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812b30d0)
Location: mm/memory_hotplug.c:1228
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__offline_pages
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff812b30d0-ffffffff812b325e: test_pages_in_a_zone (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int *valid_start</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int *valid_end</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int *valid_start</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *valid_end</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct zone *</code>
</li>
</ul>
</details>
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
</ul>
<b>Arch</b>
<ul>
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
