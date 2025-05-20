# Function: <code>memblock_alloc_nid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f8b2ea)
Location: mm/memblock.c:1175
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - mm/memblock.c:memblock_alloc_try_nid
```
**Symbols:**

```
ffffffff81f8b2ea-ffffffff81f8b334: memblock_alloc_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81fb4f2e)
Location: mm/memblock.c:1176
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:numa_init
  - mm/memblock.c:memblock_alloc_try_nid
```
**Symbols:**

```
ffffffff81fb4f2e-ffffffff81fb4f78: memblock_alloc_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ff1915)
Location: mm/memblock.c:1176
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/memblock.c:memblock_alloc_try_nid
```
**Symbols:**

```
ffffffff81ff1915-ffffffff81ff195f: memblock_alloc_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820d3d66)
Location: mm/memblock.c:1200
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/memblock.c:memblock_alloc_try_nid
```
**Symbols:**

```
ffffffff820d3d66-ffffffff820d3db5: memblock_alloc_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff826dc775)
Location: mm/memblock.c:1172
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/memblock.c:memblock_alloc_try_nid
```
**Symbols:**

```
ffffffff826dc775-ffffffff826dc7c4: memblock_alloc_nid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_nid(phys_addr_t size, phys_addr_t align, int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82706cbc)
Location: mm/memblock.c:1180
Inline: False
Direct callers:
  - arch/x86/mm/numa.c:alloc_node_data
  - mm/memblock.c:memblock_alloc_try_nid
```
**Symbols:**

```
ffffffff82706cbc-ffffffff82706d09: memblock_alloc_nid (STB_GLOBAL)
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
