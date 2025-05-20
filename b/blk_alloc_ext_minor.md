# Function: <code>blk_alloc_ext_minor</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int blk_alloc_ext_minor();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815e3a44)
Location: block/genhd.c:323
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
Direct callers:
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff815e4770-ffffffff815e479f: blk_alloc_ext_minor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int blk_alloc_ext_minor();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff816934cc)
Location: block/genhd.c:334
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
Direct callers:
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff81693370-ffffffff816933b7: blk_alloc_ext_minor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int blk_alloc_ext_minor();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81752188)
Location: block/genhd.c:311
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
Direct callers:
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff81751fe0-ffffffff81752027: blk_alloc_ext_minor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int blk_alloc_ext_minor();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8178e318)
Location: block/genhd.c:307
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
Direct callers:
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff8178e780-ffffffff8178e7c7: blk_alloc_ext_minor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int blk_alloc_ext_minor();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817d0b97)
Location: block/genhd.c:307
Inline: True
Inline callers:
  - block/genhd.c:device_add_disk
Direct callers:
  - block/partitions/core.c:add_partition
```
**Symbols:**

```
ffffffff817d1040-ffffffff817d1087: blk_alloc_ext_minor (STB_GLOBAL)
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
