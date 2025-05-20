# Function: <code>remove_zspage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void remove_zspage(struct page *page, struct size_class *class, enum fullness_group fullness);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812052b0)
Location: mm/zsmalloc.c:682
Inline: True
Direct callers:
  - mm/zsmalloc.c:fix_fullness_group
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
```
**Symbols:**

```
ffffffff812052b0-ffffffff8120531e: remove_zspage (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff8122a5c4)
Location: mm/zsmalloc.c:780
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
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
In mm/zsmalloc.c (ffffffff8123cb14)
Location: mm/zsmalloc.c:780
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
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
In mm/zsmalloc.c (ffffffff81248824)
Location: mm/zsmalloc.c:773
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
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
In mm/zsmalloc.c (ffffffff812689f4)
Location: mm/zsmalloc.c:777
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
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
In mm/zsmalloc.c (ffffffff8128debd)
Location: mm/zsmalloc.c:759
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
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
In mm/zsmalloc.c (ffffffff812a37ed)
Location: mm/zsmalloc.c:759
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
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
In mm/zsmalloc.c (ffffffff812bebf5)
Location: mm/zsmalloc.c:749
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
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
In mm/zsmalloc.c (ffffffff812d0b55)
Location: mm/zsmalloc.c:746
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81307523)
Location: mm/zsmalloc.c:746
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81313263)
Location: mm/zsmalloc.c:739
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
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
In mm/zsmalloc.c (ffffffff813183d4)
Location: mm/zsmalloc.c:739
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:fix_fullness_group
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
In mm/zsmalloc.c (ffffffff813648dc)
Location: mm/zsmalloc.c:739
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:fix_fullness_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813dfe0a)
Location: mm/zsmalloc.c:740
Inline: True
Inline callers:
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81466c53)
Location: mm/zsmalloc.c:788
Inline: True
Inline callers:
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149eca7)
Location: mm/zsmalloc.c:703
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:fix_fullness_group
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814ce425)
Location: mm/zsmalloc.c:703
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:fix_fullness_group
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
In mm/zsmalloc.c (ffff80001037592c)
Location: mm/zsmalloc.c:746
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
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
In mm/zsmalloc.c (c0560f88)
Location: mm/zsmalloc.c:746
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
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
In mm/zsmalloc.c (c000000000466790)
Location: mm/zsmalloc.c:746
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
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
In mm/zsmalloc.c (ffffffe00024e67e)
Location: mm/zsmalloc.c:746
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
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
In mm/zsmalloc.c (ffffffff812c9135)
Location: mm/zsmalloc.c:746
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
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
In mm/zsmalloc.c (ffffffff812ba175)
Location: mm/zsmalloc.c:746
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
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
In mm/zsmalloc.c (ffffffff812c6f45)
Location: mm/zsmalloc.c:746
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
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
In mm/zsmalloc.c (ffffffff812d62b3)
Location: mm/zsmalloc.c:746
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_isolate
  - mm/zsmalloc.c:isolate_zspage
  - mm/zsmalloc.c:fix_fullness_group
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
