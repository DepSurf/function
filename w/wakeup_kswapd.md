# Function: <code>wakeup_kswapd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, int order, enum zone_type classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a2a20)
Location: mm/vmscan.c:3511
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
**Symbols:**

```
ffffffff811a2a20-ffffffff811a2b57: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, int order, enum zone_type classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b90d0)
Location: mm/vmscan.c:3487
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
```
**Symbols:**

```
ffffffff811b90d0-ffffffff811b921b: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, int order, enum zone_type classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811c9710)
Location: mm/vmscan.c:3498
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
```
**Symbols:**

```
ffffffff811c9710-ffffffff811c985b: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, int order, enum zone_type classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d21c0)
Location: mm/vmscan.c:3603
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
```
**Symbols:**

```
ffffffff811d21c0-ffffffff811d22d2: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, int order, enum zone_type classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e7660)
Location: mm/vmscan.c:3626
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
```
**Symbols:**

```
ffffffff811e7660-ffffffff811e7775: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81208bd0)
Location: mm/vmscan.c:3645
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
```
**Symbols:**

```
ffffffff81208bd0-ffffffff81208d3a: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121b870)
Location: mm/vmscan.c:3937
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff8121b870-ffffffff8121ba11: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122b500)
Location: mm/vmscan.c:3890
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff8122b500-ffffffff8122b6a7: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812393d0)
Location: mm/vmscan.c:3976
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff812393d0-ffffffff81239577: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8126a970)
Location: mm/vmscan.c:3958
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff8126a970-ffffffff8126ab1f: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812753d0)
Location: mm/vmscan.c:3956
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff812753d0-ffffffff8127555a: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8127a6f0)
Location: mm/vmscan.c:4154
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff8127a6f0-ffffffff8127a87a: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b8750)
Location: mm/vmscan.c:4346
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff812b8750-ffffffff812b88da: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81314180)
Location: mm/vmscan.c:4493
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:rmqueue
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
```
**Symbols:**

```
ffffffff81314180-ffffffff81314348: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81388240)
Location: mm/vmscan.c:7433
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:rmqueue
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
```
**Symbols:**

```
ffffffff81388240-ffffffff81388408: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813ba520)
Location: mm/vmscan.c:7797
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:rmqueue
  - mm/migrate.c:numamigrate_isolate_page
  - mm/migrate.c:numamigrate_isolate_page
```
**Symbols:**

```
ffffffff813ba520-ffffffff813ba6e8: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813e3640)
Location: mm/vmscan.c:7164
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:rmqueue
  - mm/migrate.c:migrate_misplaced_folio
```
**Symbols:**

```
ffffffff813e3640-ffffffff813e3808: wakeup_kswapd (STB_GLOBAL)
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
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102ca290)
Location: mm/vmscan.c:3976
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffff8000102ca290-ffff8000102ca45c: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f40ec)
Location: mm/vmscan.c:3976
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
c04f40ec-c04f42bc: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000386c00)
Location: mm/vmscan.c:3976
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
c000000000386c00-c000000000386e98: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e93be)
Location: mm/vmscan.c:3976
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
```
**Symbols:**

```
ffffffe0001e93be-ffffffe0001e9536: wakeup_kswapd (STB_GLOBAL)
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
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81231a20)
Location: mm/vmscan.c:3976
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff81231a20-ffffffff81231bc7: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81224ae0)
Location: mm/vmscan.c:3976
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff81224ae0-ffffffff81224c87: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122f7c0)
Location: mm/vmscan.c:3976
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff8122f7c0-ffffffff8122f967: wakeup_kswapd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wakeup_kswapd(struct zone *zone, gfp_t gfp_flags, int order, enum zone_type classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123ebf0)
Location: mm/vmscan.c:3976
Inline: False
Direct callers:
  - mm/page_alloc.c:wake_all_kswapds
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff8123ebf0-ffffffff8123edaf: wakeup_kswapd (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, order, classzone_idx</code> ➡️ <code>zone, gfp_flags, order, classzone_idx</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>enum zone_type highest_zoneidx</code>
</li>
<li>
<b>Param removed. </b>
<code>enum zone_type classzone_idx</code>
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
