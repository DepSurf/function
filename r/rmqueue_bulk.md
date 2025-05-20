# Function: <code>rmqueue_bulk</code>

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
In mm/page_alloc.c (ffffffff81196228)
Location: mm/page_alloc.c:1813
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff811a9ef4)
Location: mm/page_alloc.c:2172
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff811ba444)
Location: mm/page_alloc.c:2217
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c1fd9)
Location: mm/page_alloc.c:2315
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d656a)
Location: mm/page_alloc.c:2353
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f79c5)
Location: mm/page_alloc.c:2462
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120a408)
Location: mm/page_alloc.c:2554
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126f2b7)
Location: mm/page_alloc.c:2730
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127e0f7)
Location: mm/page_alloc.c:2721
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff812b0230)
Location: mm/page_alloc.c:2813
Inline: True
```
**Symbols:**

```
ffffffff812b0230-ffffffff812b06e5: rmqueue_bulk.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff812bbeb0)
Location: mm/page_alloc.c:2893
Inline: True
```
**Symbols:**

```
ffffffff812bbeb0-ffffffff812bc32e: rmqueue_bulk.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff812c0df0)
Location: mm/page_alloc.c:2942
Inline: True
Direct callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff812c0df0-ffffffff812c1269: rmqueue_bulk.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rmqueue_bulk(struct zone *zone, unsigned int order, long unsigned int count, struct list_head *list, int migratetype, unsigned int alloc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3015
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff81303eb0-ffffffff81304619: rmqueue_bulk (STB_LOCAL)
ffffffff81cbd570-ffffffff81cbd5fa: rmqueue_bulk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rmqueue_bulk(struct zone *zone, unsigned int order, long unsigned int count, struct list_head *list, int migratetype, unsigned int alloc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3037
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_bulk
```
**Symbols:**

```
ffffffff8136bfb0-ffffffff8136c765: rmqueue_bulk (STB_LOCAL)
ffffffff81e6f56d-ffffffff81e6f5fe: rmqueue_bulk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rmqueue_bulk(struct zone *zone, unsigned int order, long unsigned int count, struct list_head *list, int migratetype, unsigned int alloc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3116
Inline: False
Direct callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff813e8320-ffffffff813e8aee: rmqueue_bulk (STB_LOCAL)
ffffffff82065328-ffffffff820653b9: rmqueue_bulk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rmqueue_bulk(struct zone *zone, unsigned int order, long unsigned int count, struct list_head *list, int migratetype, unsigned int alloc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2159
Inline: False
Direct callers:
  - mm/page_alloc.c:__rmqueue_pcplist
```
**Symbols:**

```
ffffffff8141d390-ffffffff8141dafc: rmqueue_bulk (STB_LOCAL)
ffffffff820e4b03-ffffffff820e4b94: rmqueue_bulk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rmqueue_bulk(struct zone *zone, unsigned int order, long unsigned int count, struct list_head *list, int migratetype, unsigned int alloc_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2123
Inline: False
Direct callers:
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:__rmqueue_pcplist
```
**Symbols:**

```
ffffffff81449e30-ffffffff8144a59c: rmqueue_bulk (STB_LOCAL)
ffffffff821c179e-ffffffff821c182f: rmqueue_bulk.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010315b9c)
Location: mm/page_alloc.c:2721
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (c0530188)
Location: mm/page_alloc.c:2721
Inline: True
Direct callers:
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
c0530188-c0530750: rmqueue_bulk.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e7c54)
Location: mm/page_alloc.c:2721
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffe00021c1d0)
Location: mm/page_alloc.c:2721
Inline: True
```
**Symbols:**

```
ffffffe00021c1d0-ffffffe00021c6c4: rmqueue_bulk.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81276747)
Location: mm/page_alloc.c:2721
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81268685)
Location: mm/page_alloc.c:2721
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812744e7)
Location: mm/page_alloc.c:2721
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff81283df0)
Location: mm/page_alloc.c:2721
Inline: True
Direct callers:
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff81283df0-ffffffff812843ba: rmqueue_bulk.constprop.0 (STB_LOCAL)
```
</details>
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
