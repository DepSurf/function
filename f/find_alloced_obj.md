# Function: <code>find_alloced_obj</code>

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
In mm/zsmalloc.c (ffffffff8120611f)
Location: mm/zsmalloc.c:1572
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff8122bdc8)
Location: mm/zsmalloc.c:1732
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff8123e30a)
Location: mm/zsmalloc.c:1692
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff81249d39)
Location: mm/zsmalloc.c:1671
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff81269fc0)
Location: mm/zsmalloc.c:1675
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff8128e8d1)
Location: mm/zsmalloc.c:1678
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812a2a71)
Location: mm/zsmalloc.c:1665
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812bddfc)
Location: mm/zsmalloc.c:1655
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812cfcec)
Location: mm/zsmalloc.c:1652
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int find_alloced_obj(struct size_class *class, struct page *page, int *obj_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81305b10)
Location: mm/zsmalloc.c:1654
Inline: False
```
**Symbols:**

```
ffffffff81305b10-ffffffff81305bb7: find_alloced_obj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int find_alloced_obj(struct size_class *class, struct page *page, int *obj_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81311870)
Location: mm/zsmalloc.c:1603
Inline: False
```
**Symbols:**

```
ffffffff81311870-ffffffff81311917: find_alloced_obj (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff8131800b)
Location: mm/zsmalloc.c:1602
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff81364511)
Location: mm/zsmalloc.c:1601
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff813e2496)
Location: mm/zsmalloc.c:1594
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
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
In mm/zsmalloc.c (ffffffff81469a8d)
Location: mm/zsmalloc.c:1810
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
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
In mm/zsmalloc.c (ffffffff8149e981)
Location: mm/zsmalloc.c:1582
Inline: True
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
In mm/zsmalloc.c (ffffffff814ce13d)
Location: mm/zsmalloc.c:1555
Inline: True
Inline callers:
  - mm/zsmalloc.c:migrate_zspage
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
In mm/zsmalloc.c (ffff800010374874)
Location: mm/zsmalloc.c:1652
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (c056169c)
Location: mm/zsmalloc.c:1652
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (c000000000467be0)
Location: mm/zsmalloc.c:1652
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffe00024d71e)
Location: mm/zsmalloc.c:1652
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812c82cc)
Location: mm/zsmalloc.c:1652
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812b930c)
Location: mm/zsmalloc.c:1652
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812c60dc)
Location: mm/zsmalloc.c:1652
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812d784f)
Location: mm/zsmalloc.c:1652
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
