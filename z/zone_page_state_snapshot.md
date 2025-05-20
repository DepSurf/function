# Function: <code>zone_page_state_snapshot</code>

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
In mm/page_alloc.c (ffffffff81192e43)
Location: include/linux/vmstat.h:147
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811aaaec)
Location: include/linux/vmstat.h:164
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
```
```
In mm/vmscan.c (ffffffff811ba784)
Location: include/linux/vmstat.h:164
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff811d1fa6)
Location: include/linux/vmstat.h:164
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bb01b)
Location: include/linux/vmstat.h:164
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
```
```
In mm/vmscan.c (ffffffff811cae14)
Location: include/linux/vmstat.h:164
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_inactive_list
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff811e1ed5)
Location: include/linux/vmstat.h:164
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c3108)
Location: include/linux/vmstat.h:163
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
```
```
In mm/vmscan.c (ffffffff811d0f3c)
Location: include/linux/vmstat.h:163
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff811ebcdc)
Location: include/linux/vmstat.h:163
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d7eb7)
Location: include/linux/vmstat.h:203
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
```
```
In mm/vmscan.c (ffffffff811e6426)
Location: include/linux/vmstat.h:203
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff8120205c)
Location: include/linux/vmstat.h:203
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f91a3)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
```
```
In mm/vmscan.c (ffffffff812079d5)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff8122344a)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120b74c)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
```
```
In mm/vmscan.c (ffffffff8121a555)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff812364aa)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81229dc5)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff812479af)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff812719c7)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81237c45)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff81255e0f)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff81280874)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81266c65)
Location: include/linux/vmstat.h:222
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff812844ff)
Location: include/linux/vmstat.h:222
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff812b28d9)
Location: include/linux/vmstat.h:222
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812716b5)
Location: include/linux/vmstat.h:231
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff8128e7ff)
Location: include/linux/vmstat.h:231
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff812be449)
Location: include/linux/vmstat.h:231
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812769b5)
Location: include/linux/vmstat.h:231
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff81293e96)
Location: include/linux/vmstat.h:231
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff812c34de)
Location: include/linux/vmstat.h:231
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b41c5)
Location: include/linux/vmstat.h:224
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff812d4407)
Location: include/linux/vmstat.h:224
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff8130724e)
Location: include/linux/vmstat.h:224
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81310cd0)
Location: include/linux/vmstat.h:224
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff81333370)
Location: include/linux/vmstat.h:224
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff8136f570)
Location: include/linux/vmstat.h:224
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8138419d)
Location: include/linux/vmstat.h:218
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff813aa06f)
Location: include/linux/vmstat.h:218
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff813ebb10)
Location: include/linux/vmstat.h:218
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b54a7)
Location: include/linux/vmstat.h:224
Inline: True
Inline callers:
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff813dd31c)
Location: include/linux/vmstat.h:224
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff81420b20)
Location: include/linux/vmstat.h:224
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813de497)
Location: include/linux/vmstat.h:224
Inline: True
Inline callers:
  - mm/vmscan.c:allow_direct_reclaim
  - mm/vmscan.c:reclaim_throttle
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff8140727c)
Location: include/linux/vmstat.h:224
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff8144d8e0)
Location: include/linux/vmstat.h:224
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c895c)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffff8000102ed3a4)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffff800010318594)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f2c08)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (c05112ec)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (c0532d80)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000384aa4)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (c0000000003b1050)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (c0000000003eacec)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e7f04)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffe0002019ea)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffe00021e41e)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81230295)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff8124e45f)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff81278ec4)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81223355)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff812413ff)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff8126adb4)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122e035)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff8124c1ff)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff81276c64)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123d435)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
  - mm/vmscan.c:zone_reclaimable_pages
```
```
In mm/compaction.c (ffffffff8125bb5f)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/compaction.c:compaction_zonelist_suitable
```
```
In mm/page_alloc.c (ffffffff81286811)
Location: include/linux/vmstat.h:214
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:zone_watermark_ok_safe
```
</details>
</li>
</ul>

## Differences
