# Function: <code>set_migratetype_isolate</code>

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
In mm/page_isolation.c (ffffffff81203cc6)
Location: mm/page_isolation.c:12
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
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
In mm/page_isolation.c (ffffffff81228c88)
Location: mm/page_isolation.c:16
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
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
In mm/page_isolation.c (ffffffff8123b238)
Location: mm/page_isolation.c:16
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
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
In mm/page_isolation.c (ffffffff81246cbb)
Location: mm/page_isolation.c:17
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
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
In mm/page_isolation.c (ffffffff81266e85)
Location: mm/page_isolation.c:18
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
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
In mm/page_isolation.c (ffffffff8128b6fd)
Location: mm/page_isolation.c:18
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
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
In mm/page_isolation.c (ffffffff812a0652)
Location: mm/page_isolation.c:18
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
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
In mm/page_isolation.c (ffffffff812bb8d9)
Location: mm/page_isolation.c:18
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
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
In mm/page_isolation.c (ffffffff812cd7b9)
Location: mm/page_isolation.c:18
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_migratetype_isolate(struct page *page, int migratetype, int isol_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff813038f0)
Location: mm/page_isolation.c:18
Inline: False
Direct callers:
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff813038f0-ffffffff81303a75: set_migratetype_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_migratetype_isolate(struct page *page, int migratetype, int isol_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff8130f6b0)
Location: mm/page_isolation.c:18
Inline: False
Direct callers:
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff8130f6b0-ffffffff8130f7fe: set_migratetype_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff81315bdd)
Location: mm/page_isolation.c:18
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff81361cad)
Location: mm/page_isolation.c:18
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_isolation.c (ffffffff813ddfe0)
Location: mm/page_isolation.c:147
Inline: True
Direct callers:
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
```
**Symbols:**

```
ffffffff813ddfe0-ffffffff813de17a: set_migratetype_isolate.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_isolation.c (ffffffff81464c60)
Location: mm/page_isolation.c:147
Inline: True
Direct callers:
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
```
**Symbols:**

```
ffffffff81464c60-ffffffff81464dfa: set_migratetype_isolate.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_isolation.c (ffffffff8149a730)
Location: mm/page_isolation.c:147
Inline: True
Direct callers:
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
```
**Symbols:**

```
ffffffff8149a730-ffffffff8149a8ca: set_migratetype_isolate.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_isolation.c (ffffffff814c9e20)
Location: mm/page_isolation.c:147
Inline: True
Direct callers:
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:isolate_single_pageblock
  - mm/page_isolation.c:isolate_single_pageblock
```
**Symbols:**

```
ffffffff814c9e20-ffffffff814c9fba: set_migratetype_isolate.isra.0 (STB_LOCAL)
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
In mm/page_isolation.c (ffff800010371aac)
Location: mm/page_isolation.c:18
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (c055ea40)
Location: mm/page_isolation.c:18
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
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
In mm/page_isolation.c (c00000000046327c)
Location: mm/page_isolation.c:18
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
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
In mm/page_isolation.c (ffffffe00024af58)
Location: mm/page_isolation.c:18
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
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
In mm/page_isolation.c (ffffffff812c5d99)
Location: mm/page_isolation.c:18
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
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
In mm/page_isolation.c (ffffffff812b6dd9)
Location: mm/page_isolation.c:18
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
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
In mm/page_isolation.c (ffffffff812c3ba9)
Location: mm/page_isolation.c:18
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff812d4649)
Location: mm/page_isolation.c:18
Inline: True
Inline callers:
  - mm/page_isolation.c:start_isolate_page_range
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
