# Function: <code>get_fullness_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
enum fullness_group get_fullness_group(struct page *page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81205260)
Location: mm/zsmalloc.c:623
Inline: True
Direct callers:
  - mm/zsmalloc.c:fix_fullness_group
```
**Symbols:**

```
ffffffff81205260-ffffffff812052a6: get_fullness_group (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff81229fc3)
Location: mm/zsmalloc.c:727
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
In mm/zsmalloc.c (ffffffff8123c513)
Location: mm/zsmalloc.c:727
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
In mm/zsmalloc.c (ffffffff81248163)
Location: mm/zsmalloc.c:720
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
In mm/zsmalloc.c (ffffffff81268323)
Location: mm/zsmalloc.c:724
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
In mm/zsmalloc.c (ffffffff8128ccbc)
Location: mm/zsmalloc.c:706
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
In mm/zsmalloc.c (ffffffff812a1c3c)
Location: mm/zsmalloc.c:706
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
In mm/zsmalloc.c (ffffffff812bcecc)
Location: mm/zsmalloc.c:696
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
In mm/zsmalloc.c (ffffffff812cedbc)
Location: mm/zsmalloc.c:693
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
In mm/zsmalloc.c (ffffffff813065e1)
Location: mm/zsmalloc.c:693
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
In mm/zsmalloc.c (ffffffff81312349)
Location: mm/zsmalloc.c:689
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
In mm/zsmalloc.c (ffffffff8131816a)
Location: mm/zsmalloc.c:689
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
In mm/zsmalloc.c (ffffffff81364670)
Location: mm/zsmalloc.c:689
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
In mm/zsmalloc.c (ffffffff813e2623)
Location: mm/zsmalloc.c:690
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
In mm/zsmalloc.c (ffffffff81469b50)
Location: mm/zsmalloc.c:738
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
In mm/zsmalloc.c (ffffffff8149ed17)
Location: mm/zsmalloc.c:664
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
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
In mm/zsmalloc.c (ffffffff814ce489)
Location: mm/zsmalloc.c:664
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
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
In mm/zsmalloc.c (ffff800010373a08)
Location: mm/zsmalloc.c:693
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
In mm/zsmalloc.c (c0560048)
Location: mm/zsmalloc.c:693
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
In mm/zsmalloc.c (c00000000046576c)
Location: mm/zsmalloc.c:693
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
In mm/zsmalloc.c (ffffffe00024c760)
Location: mm/zsmalloc.c:693
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
In mm/zsmalloc.c (ffffffff812c739c)
Location: mm/zsmalloc.c:693
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
In mm/zsmalloc.c (ffffffff812b83dc)
Location: mm/zsmalloc.c:693
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
In mm/zsmalloc.c (ffffffff812c51ac)
Location: mm/zsmalloc.c:693
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
In mm/zsmalloc.c (ffffffff812d5c8c)
Location: mm/zsmalloc.c:693
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
<b>Regular</b>
<ul>
</ul>
