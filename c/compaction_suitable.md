# Function: <code>compaction_suitable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int compaction_suitable(struct zone *zone, int order, int alloc_flags, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811b73c0)
Location: mm/compaction.c:1326
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_zone
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:kswapd
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811b73c0-ffffffff811b74e9: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811d0eb0)
Location: mm/compaction.c:1421
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811d0eb0-ffffffff811d0f57: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811e0ed0)
Location: mm/compaction.c:1408
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811e0ed0-ffffffff811e0fa9: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811eabc0)
Location: mm/compaction.c:1442
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff811eabc0-ffffffff811eac9f: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81200f30)
Location: mm/compaction.c:1466
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81200f30-ffffffff81201012: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81222350)
Location: mm/compaction.c:1466
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81222350-ffffffff81222429: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812353a0)
Location: mm/compaction.c:1467
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff812353a0-ffffffff81235479: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81246410)
Location: mm/compaction.c:2001
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81246410-ffffffff812464f8: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812548f0)
Location: mm/compaction.c:2001
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff812548f0-ffffffff812549d8: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81283880)
Location: mm/compaction.c:2012
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_zones
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81283880-ffffffff8128396b: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128d920)
Location: mm/compaction.c:2167
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_zones
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff8128d920-ffffffff8128d9eb: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81292f50)
Location: mm/compaction.c:2206
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81292f50-ffffffff81293013: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812d3370)
Location: mm/compaction.c:2198
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff812d3370-ffffffff812d3430: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81332160)
Location: mm/compaction.c:2220
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81332160-ffffffff8133223b: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813a8e30)
Location: mm/compaction.c:2219
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff813a8e30-ffffffff813a8f0b: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool compaction_suitable(struct zone *zone, int order, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813dbff0)
Location: mm/compaction.c:2279
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff813dbff0-ffffffff813dc0ab: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool compaction_suitable(struct zone *zone, int order, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81405f20)
Location: mm/compaction.c:2330
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81405f20-ffffffff81405fdb: compaction_suitable (STB_GLOBAL)
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
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102ebd90)
Location: mm/compaction.c:2001
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffff8000102ebd90-ffff8000102ebecc: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c050fdd8)
Location: mm/compaction.c:2001
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
c050fdd8-c050ff00: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003af510)
Location: mm/compaction.c:2001
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
c0000000003af510-c0000000003af694: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffe0002007e6)
Location: mm/compaction.c:2001
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffe0002007e6-ffffffe0002008e4: compaction_suitable (STB_GLOBAL)
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
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124cf40)
Location: mm/compaction.c:2001
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff8124cf40-ffffffff8124d028: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8123fee0)
Location: mm/compaction.c:2001
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff8123fee0-ffffffff8123ffc8: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124ace0)
Location: mm/compaction.c:2001
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff8124ace0-ffffffff8124adc8: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum compact_result compaction_suitable(struct zone *zone, int order, unsigned int alloc_flags, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8125a560)
Location: mm/compaction.c:2001
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:shrink_node
  - mm/compaction.c:wakeup_kcompactd
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff8125a560-ffffffff8125a651: compaction_suitable (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int alloc_flags</code> ➡️ <code>unsigned int alloc_flags</code>
</li>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>enum compact_result</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int highest_zoneidx</code>
</li>
<li>
<b>Param removed. </b>
<code>int classzone_idx</code>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int alloc_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, order, alloc_flags, highest_zoneidx</code> ➡️ <code>zone, order, highest_zoneidx</code>
</li>
<li>
<b>Return type changed. </b>
<code>enum compact_result</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
