# Function: <code>set_zspage_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zsmalloc.c (ffffffff81205250)
Location: mm/zsmalloc.c:428
Inline: True
Inline callers:
  - mm/zsmalloc.c:fix_fullness_group
  - mm/zsmalloc.c:zs_malloc
Direct callers:
  - mm/zsmalloc.c:fix_fullness_group
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81205250-ffffffff8120525b: set_zspage_mapping.part.8 (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff8122a006)
Location: mm/zsmalloc.c:535
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff8123c556)
Location: mm/zsmalloc.c:535
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812481a6)
Location: mm/zsmalloc.c:528
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff81268366)
Location: mm/zsmalloc.c:529
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff8128ccfd)
Location: mm/zsmalloc.c:521
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812a1c7d)
Location: mm/zsmalloc.c:521
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812bcf13)
Location: mm/zsmalloc.c:527
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812cee03)
Location: mm/zsmalloc.c:524
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff81306599)
Location: mm/zsmalloc.c:524
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff81312301)
Location: mm/zsmalloc.c:520
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff81318189)
Location: mm/zsmalloc.c:520
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff81364690)
Location: mm/zsmalloc.c:520
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff813e2662)
Location: mm/zsmalloc.c:521
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff81469b96)
Location: mm/zsmalloc.c:569
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff8149c0fe)
Location: mm/zsmalloc.c:495
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff814cb81e)
Location: mm/zsmalloc.c:495
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffff800010373a54)
Location: mm/zsmalloc.c:524
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (c05600a4)
Location: mm/zsmalloc.c:524
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (c0000000004657d8)
Location: mm/zsmalloc.c:524
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffe00024c7a0)
Location: mm/zsmalloc.c:524
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812c73e3)
Location: mm/zsmalloc.c:524
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812b8423)
Location: mm/zsmalloc.c:524
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812c51f3)
Location: mm/zsmalloc.c:524
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812d5cd3)
Location: mm/zsmalloc.c:524
Inline: True
Inline callers:
  - mm/zsmalloc.c:putback_zspage
  - mm/zsmalloc.c:zs_malloc
  - mm/zsmalloc.c:fix_fullness_group
```
</details>
</li>
</ul>

## Differences
