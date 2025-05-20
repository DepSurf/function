# Function: <code>kmalloc_fix_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
gfp_t kmalloc_fix_flags(gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81be7311)
Location: mm/slab_common.c:811
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81be7311-ffffffff81be7375: kmalloc_fix_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
gfp_t kmalloc_fix_flags(gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81bd91d7)
Location: mm/slab_common.c:897
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81bd91d7-ffffffff81bd923b: kmalloc_fix_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
gfp_t kmalloc_fix_flags(gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81cbb443)
Location: mm/slab_common.c:931
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order
```
**Symbols:**

```
ffffffff81cbb443-ffffffff81cbb4a7: kmalloc_fix_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
gfp_t kmalloc_fix_flags(gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81e6cfd9)
Location: mm/slab_common.c:919
Inline: False
Direct callers:
  - mm/slab_common.c:kmalloc_order
```
**Symbols:**

```
ffffffff81e6cfd9-ffffffff81e6d04c: kmalloc_fix_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
gfp_t kmalloc_fix_flags(gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813a13be)
Location: mm/slab_common.c:1085
Inline: True
Inline callers:
  - mm/slab_common.c:__kmalloc_large_node
```
**Symbols:**

```
ffffffff813a2740-ffffffff813a27b3: kmalloc_fix_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
gfp_t kmalloc_fix_flags(gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d463a)
Location: mm/slab_common.c:1098
Inline: True
Inline callers:
  - mm/slab_common.c:__kmalloc_large_node
```
**Symbols:**

```
ffffffff813d5c00-ffffffff813d5c73: kmalloc_fix_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
gfp_t kmalloc_fix_flags(gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813ff8d0)
Location: mm/slab_common.c:975
Inline: False
Direct callers:
  - mm/slub.c:__kmalloc_large_node
```
**Symbols:**

```
ffffffff813ff8d0-ffffffff813ff943: kmalloc_fix_flags (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
