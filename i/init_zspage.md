# Function: <code>init_zspage</code>

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
In mm/zsmalloc.c (ffffffff81205c91)
Location: mm/zsmalloc.c:912
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff8122b082)
Location: mm/zsmalloc.c:1030
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff8123d5ec)
Location: mm/zsmalloc.c:1030
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff81248f88)
Location: mm/zsmalloc.c:1022
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812691b4)
Location: mm/zsmalloc.c:1026
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff8128e170)
Location: mm/zsmalloc.c:1009
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812a3aa0)
Location: mm/zsmalloc.c:996
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812beeac)
Location: mm/zsmalloc.c:986
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812d0e0c)
Location: mm/zsmalloc.c:983
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813057c0)
Location: mm/zsmalloc.c:983
Inline: False
Direct callers:
  - mm/zsmalloc.c:alloc_zspage
```
**Symbols:**

```
ffffffff813057c0-ffffffff813058af: init_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81311520)
Location: mm/zsmalloc.c:976
Inline: False
Direct callers:
  - mm/zsmalloc.c:alloc_zspage
```
**Symbols:**

```
ffffffff81311520-ffffffff8131160f: init_zspage (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff8131782e)
Location: mm/zsmalloc.c:976
Inline: True
Inline callers:
  - mm/zsmalloc.c:alloc_zspage
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
In mm/zsmalloc.c (ffffffff81363ebd)
Location: mm/zsmalloc.c:976
Inline: True
Inline callers:
  - mm/zsmalloc.c:alloc_zspage
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
In mm/zsmalloc.c (ffffffff813e0c65)
Location: mm/zsmalloc.c:973
Inline: True
Inline callers:
  - mm/zsmalloc.c:alloc_zspage
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
In mm/zsmalloc.c (ffffffff814678f5)
Location: mm/zsmalloc.c:1075
Inline: True
Inline callers:
  - mm/zsmalloc.c:alloc_zspage
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
In mm/zsmalloc.c (ffffffff8149d0bc)
Location: mm/zsmalloc.c:905
Inline: True
Inline callers:
  - mm/zsmalloc.c:alloc_zspage
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
In mm/zsmalloc.c (ffffffff814cc87c)
Location: mm/zsmalloc.c:900
Inline: True
Inline callers:
  - mm/zsmalloc.c:alloc_zspage
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
In mm/zsmalloc.c (ffff8000103761d0)
Location: mm/zsmalloc.c:983
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (c0560c78)
Location: mm/zsmalloc.c:983
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (c000000000466230)
Location: mm/zsmalloc.c:983
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffe00024e9a6)
Location: mm/zsmalloc.c:983
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812c93ec)
Location: mm/zsmalloc.c:983
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812ba42c)
Location: mm/zsmalloc.c:983
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812c71fc)
Location: mm/zsmalloc.c:983
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
In mm/zsmalloc.c (ffffffff812d6aa8)
Location: mm/zsmalloc.c:983
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_malloc
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
