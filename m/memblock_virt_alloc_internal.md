# Function: <code>memblock_virt_alloc_internal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *memblock_virt_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f8b183)
Location: mm/memblock.c:1251
Inline: False
Direct callers:
  - mm/memblock.c:memblock_virt_alloc_try_nid_nopanic
  - mm/memblock.c:memblock_virt_alloc_try_nid
```
**Symbols:**

```
ffffffff81f8b183-ffffffff81f8b2ea: memblock_virt_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *memblock_virt_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81fb4dca)
Location: mm/memblock.c:1252
Inline: False
Direct callers:
  - mm/memblock.c:memblock_virt_alloc_try_nid
  - mm/memblock.c:memblock_virt_alloc_try_nid_nopanic
```
**Symbols:**

```
ffffffff81fb4dca-ffffffff81fb4f2e: memblock_virt_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *memblock_virt_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ff17ae)
Location: mm/memblock.c:1252
Inline: False
Direct callers:
  - mm/memblock.c:memblock_virt_alloc_try_nid
  - mm/memblock.c:memblock_virt_alloc_try_nid_nopanic
```
**Symbols:**

```
ffffffff81ff17ae-ffffffff81ff1915: memblock_virt_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *memblock_virt_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820d3c0a)
Location: mm/memblock.c:1276
Inline: False
Direct callers:
  - mm/memblock.c:memblock_virt_alloc_try_nid
  - mm/memblock.c:memblock_virt_alloc_try_nid_nopanic
```
**Symbols:**

```
ffffffff820d3c0a-ffffffff820d3d66: memblock_virt_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *memblock_virt_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff826dc62a)
Location: mm/memblock.c:1248
Inline: False
Direct callers:
  - mm/memblock.c:memblock_virt_alloc_try_nid
  - mm/memblock.c:memblock_virt_alloc_try_nid_nopanic
  - mm/memblock.c:memblock_virt_alloc_try_nid_raw
```
**Symbols:**

```
ffffffff826dc62a-ffffffff826dc775: memblock_virt_alloc_internal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *memblock_virt_alloc_internal(phys_addr_t size, phys_addr_t align, phys_addr_t min_addr, phys_addr_t max_addr, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82706b26)
Location: mm/memblock.c:1257
Inline: False
Direct callers:
  - mm/memblock.c:memblock_virt_alloc_try_nid
  - mm/memblock.c:memblock_virt_alloc_try_nid_nopanic
  - mm/memblock.c:memblock_virt_alloc_try_nid_raw
```
**Symbols:**

```
ffffffff82706b26-ffffffff82706c6d: memblock_virt_alloc_internal (STB_LOCAL)
```
</details>
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
</ul>
