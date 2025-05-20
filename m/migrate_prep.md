# Function: <code>migrate_prep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int migrate_prep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff811f12d0)
Location: mm/migrate.c:54
Inline: True
Inline callers:
  - mm/migrate.c:SyS_move_pages
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:do_migrate_pages
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
ffffffff811f12d0-ffffffff811f12e2: migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int migrate_prep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812128ae)
Location: mm/migrate.c:56
Inline: True
Inline callers:
  - mm/migrate.c:SyS_move_pages
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
**Symbols:**

```
ffffffff812111d0-ffffffff812111e2: migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int migrate_prep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81224b6f)
Location: mm/migrate.c:56
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:do_migrate_pages
```
**Symbols:**

```
ffffffff81223390-ffffffff812233a2: migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int migrate_prep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8123025a)
Location: mm/migrate.c:58
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/mempolicy.c:SYSC_mbind
```
**Symbols:**

```
ffffffff8122eda0-ffffffff8122edb2: migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int migrate_prep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8124deea)
Location: mm/migrate.c:62
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/mempolicy.c:SYSC_mbind
```
**Symbols:**

```
ffffffff8124ba50-ffffffff8124ba62: migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int migrate_prep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812719c8)
Location: mm/migrate.c:63
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff8126f4f0-ffffffff8126f502: migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int migrate_prep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81285fe8)
Location: mm/migrate.c:63
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81283b80-ffffffff81283b92: migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int migrate_prep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a053d)
Location: mm/migrate.c:63
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff8129ed80-ffffffff8129ed92: migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int migrate_prep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b18da)
Location: mm/migrate.c:64
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff812af770-ffffffff812af782: migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int migrate_prep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e719a)
Location: mm/migrate.c:65
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
Direct callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
ffffffff812e5800-ffffffff812e5812: migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void migrate_prep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f2719)
Location: mm/migrate.c:65
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
Direct callers:
  - mm/page_alloc.c:__alloc_contig_migrate_range
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_migrate_pages
```
**Symbols:**

```
ffffffff812f0be0-ffffffff812f0bf0: migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int migrate_prep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff800010351efc)
Location: mm/migrate.c:64
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffff800010350568-ffff800010350588: migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int migrate_prep();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0551c70)
Location: mm/migrate.c:64
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
c0551c70-c0551c90: migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int migrate_prep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0000000004387cc)
Location: mm/migrate.c:64
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:do_mbind
```
**Symbols:**

```
c000000000435270-c0000000004352a8: migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int migrate_prep();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffe00023f164)
Location: mm/migrate.c:64
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffe00023f164-ffffffe00023f188: migrate_prep (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int migrate_prep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a9eba)
Location: mm/migrate.c:64
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff812a7d50-ffffffff812a7d62: migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int migrate_prep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129b81a)
Location: mm/migrate.c:64
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81299710-ffffffff81299722: migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int migrate_prep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a7cca)
Location: mm/migrate.c:64
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff812a5b60-ffffffff812a5b72: migrate_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int migrate_prep();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b7fca)
Location: mm/migrate.c:64
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_move
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff812b5eb0-ffffffff812b5ec2: migrate_prep (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
