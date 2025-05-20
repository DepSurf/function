# Function: <code>zone_for_pfn_range</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81248860)
Location: mm/memory_hotplug.c:894
Inline: True
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:print_allowed_zone
```
**Symbols:**

```
ffffffff81248860-ffffffff812489af: zone_for_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8126c290)
Location: mm/memory_hotplug.c:871
Inline: True
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - drivers/base/memory.c:show_valid_zones
  - drivers/base/memory.c:print_allowed_zone
```
**Symbols:**

```
ffffffff8126c290-ffffffff8126c3d4: zone_for_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81280b30)
Location: mm/memory_hotplug.c:829
Inline: True
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:print_allowed_zone
```
**Symbols:**

```
ffffffff81280b30-ffffffff81280c74: zone_for_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8129cf40)
Location: mm/memory_hotplug.c:808
Inline: True
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:print_allowed_zone
```
**Symbols:**

```
ffffffff8129cf40-ffffffff8129d08f: zone_for_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812ac710)
Location: mm/memory_hotplug.c:791
Inline: True
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:print_allowed_zone
```
**Symbols:**

```
ffffffff812ac710-ffffffff812ac85f: zone_for_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812e1790)
Location: mm/memory_hotplug.c:785
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:print_allowed_zone
```
**Symbols:**

```
ffffffff812e1790-ffffffff812e18ea: zone_for_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812ec6e0)
Location: mm/memory_hotplug.c:780
Inline: False
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
```
**Symbols:**

```
ffffffff812ec6e0-ffffffff812ec837: zone_for_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812c6f80)
Location: mm/memory_hotplug.c:850
Inline: False
Direct callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff812c6f80-ffffffff812c70cf: zone_for_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, struct memory_group *group, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:990
Inline: False
Direct callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff81cbe6d4-ffffffff81cbe72a: zone_for_pfn_range.cold (STB_LOCAL)
ffffffff8130b9b0-ffffffff8130bd4b: zone_for_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, struct memory_group *group, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:989
Inline: False
Direct callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff81e706f1-ffffffff81e7072f: zone_for_pfn_range.cold (STB_LOCAL)
ffffffff813749c0-ffffffff81374cb1: zone_for_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, struct memory_group *group, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:985
Inline: False
Direct callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff8206577f-ffffffff820657bd: zone_for_pfn_range.cold (STB_LOCAL)
ffffffff813f2300-ffffffff813f25f1: zone_for_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, struct memory_group *group, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:979
Inline: False
Direct callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff820e4f70-ffffffff820e4fae: zone_for_pfn_range.cold (STB_LOCAL)
ffffffff81425d40-ffffffff81426031: zone_for_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, struct memory_group *group, long unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1048
Inline: False
Direct callers:
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff821c1c70-ffffffff821c1cae: zone_for_pfn_range.cold (STB_LOCAL)
ffffffff81452f80-ffffffff81453271: zone_for_pfn_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffff80001034e300)
Location: mm/memory_hotplug.c:791
Inline: True
Direct callers:
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffff80001034e300-ffff80001034e4dc: zone_for_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042eab0)
Location: mm/memory_hotplug.c:791
Inline: True
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:print_allowed_zone
```
**Symbols:**

```
c00000000042eab0-c00000000042ec04: zone_for_pfn_range (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a4cf0)
Location: mm/memory_hotplug.c:791
Inline: True
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:print_allowed_zone
```
**Symbols:**

```
ffffffff812a4cf0-ffffffff812a4e3f: zone_for_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812967c0)
Location: mm/memory_hotplug.c:791
Inline: True
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:print_allowed_zone
```
**Symbols:**

```
ffffffff812967c0-ffffffff8129690f: zone_for_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a2b00)
Location: mm/memory_hotplug.c:791
Inline: True
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:print_allowed_zone
```
**Symbols:**

```
ffffffff812a2b00-ffffffff812a2c4f: zone_for_pfn_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct zone *zone_for_pfn_range(int online_type, int nid, unsigned int start_pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812b2d90)
Location: mm/memory_hotplug.c:791
Inline: True
Direct callers:
  - mm/memory_hotplug.c:online_pages
  - drivers/base/memory.c:valid_zones_show
  - drivers/base/memory.c:print_allowed_zone
```
**Symbols:**

```
ffffffff812b2d90-ffffffff812b2edf: zone_for_pfn_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct memory_group *group</code>
</li>
<li>
<b>Param reordered. </b>
<code>online_type, nid, start_pfn, nr_pages</code> ➡️ <code>online_type, nid, group, start_pfn, nr_pages</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int start_pfn</code> ➡️ <code>long unsigned int start_pfn</code>
</li>
</ul>
</details>
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
