# Function: <code>memblock_alloc_base_nid</code>

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
In mm/memblock.c (ffffffff81f8b306)
Location: mm/memblock.c:1168
Inline: True
Inline callers:
  - mm/memblock.c:memblock_alloc_nid
  - mm/memblock.c:__memblock_alloc_base
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
In mm/memblock.c (ffffffff81fb4f79)
Location: mm/memblock.c:1169
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_alloc_base
  - mm/memblock.c:memblock_alloc_nid
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
In mm/memblock.c (ffffffff81ff1960)
Location: mm/memblock.c:1169
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_alloc_base
  - mm/memblock.c:memblock_alloc_nid
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
In mm/memblock.c (ffffffff820d3dbb)
Location: mm/memblock.c:1193
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_alloc_base
  - mm/memblock.c:memblock_alloc_nid
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
In mm/memblock.c (ffffffff826dc7ca)
Location: mm/memblock.c:1165
Inline: True
Inline callers:
  - mm/memblock.c:__memblock_alloc_base
  - mm/memblock.c:memblock_alloc_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_base_nid(phys_addr_t size, phys_addr_t align, phys_addr_t max_addr, int nid, ulong flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82706c6d)
Location: mm/memblock.c:1173
Inline: False
Direct callers:
  - mm/memblock.c:__memblock_alloc_base
  - mm/memblock.c:memblock_alloc_nid
```
**Symbols:**

```
ffffffff82706c6d-ffffffff82706cbc: memblock_alloc_base_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_base_nid(phys_addr_t size, phys_addr_t align, phys_addr_t max_addr, int nid, enum memblock_flags flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828bde85)
Location: mm/memblock.c:1292
Inline: False
Direct callers:
  - mm/memblock.c:__memblock_alloc_base
  - mm/memblock.c:memblock_phys_alloc_nid
```
**Symbols:**

```
ffffffff828bde85-ffffffff828bdeea: memblock_alloc_base_nid (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>ulong flags</code> ➡️ <code>enum memblock_flags flags</code>
</li>
</ul>
</details>
</li>
</ul>
