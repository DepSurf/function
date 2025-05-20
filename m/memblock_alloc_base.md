# Function: <code>memblock_alloc_base</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_base(phys_addr_t size, phys_addr_t align, phys_addr_t max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81f8b34b)
Location: mm/memblock.c:1197
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc
  - mm/memblock.c:memblock_alloc_try_nid
```
**Symbols:**

```
ffffffff81f8b34b-ffffffff81f8b379: memblock_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_base(phys_addr_t size, phys_addr_t align, phys_addr_t max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81fb4f8f)
Location: mm/memblock.c:1198
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc
```
**Symbols:**

```
ffffffff81fb4f8f-ffffffff81fb4fbd: memblock_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_base(phys_addr_t size, phys_addr_t align, phys_addr_t max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff81ff1976)
Location: mm/memblock.c:1198
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc
```
**Symbols:**

```
ffffffff81ff1976-ffffffff81ff19a4: memblock_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_base(phys_addr_t size, phys_addr_t align, phys_addr_t max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff820d3dd1)
Location: mm/memblock.c:1222
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc
```
**Symbols:**

```
ffffffff820d3dd1-ffffffff820d3e06: memblock_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_base(phys_addr_t size, phys_addr_t align, phys_addr_t max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff826dc7e0)
Location: mm/memblock.c:1194
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc
```
**Symbols:**

```
ffffffff826dc7e0-ffffffff826dc815: memblock_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_base(phys_addr_t size, phys_addr_t align, phys_addr_t max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff82706d1f)
Location: mm/memblock.c:1202
Inline: False
Direct callers:
  - mm/memblock.c:memblock_alloc_try_nid
  - mm/memblock.c:memblock_alloc
```
**Symbols:**

```
ffffffff82706d1f-ffffffff82706d54: memblock_alloc_base (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
phys_addr_t memblock_alloc_base(phys_addr_t size, phys_addr_t align, phys_addr_t max_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memblock.c (ffffffff828bdf4b)
Location: mm/memblock.c:1321
Inline: False
Direct callers:
  - mm/memblock.c:memblock_phys_alloc_try_nid
  - mm/memblock.c:memblock_phys_alloc
```
**Symbols:**

```
ffffffff828bdf4b-ffffffff828bdf80: memblock_alloc_base (STB_GLOBAL)
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
</ul>
