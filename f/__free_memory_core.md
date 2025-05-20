# Function: <code>__free_memory_core</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int __free_memory_core(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81f8aae8)
Location: mm/nobootmem.c:110
Inline: False
Direct callers:
  - mm/nobootmem.c:free_all_bootmem
  - mm/nobootmem.c:free_all_bootmem
  - mm/nobootmem.c:free_all_bootmem
```
**Symbols:**

```
ffffffff81f8aae8-ffffffff81f8ab79: __free_memory_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int __free_memory_core(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81fb472e)
Location: mm/nobootmem.c:111
Inline: False
Direct callers:
  - mm/nobootmem.c:free_all_bootmem
  - mm/nobootmem.c:free_all_bootmem
  - mm/nobootmem.c:free_all_bootmem
```
**Symbols:**

```
ffffffff81fb472e-ffffffff81fb47bf: __free_memory_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int __free_memory_core(phys_addr_t start, phys_addr_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81ff1121)
Location: mm/nobootmem.c:114
Inline: False
Direct callers:
  - mm/nobootmem.c:free_all_bootmem
  - mm/nobootmem.c:free_all_bootmem
  - mm/nobootmem.c:free_all_bootmem
```
**Symbols:**

```
ffffffff81ff1121-ffffffff81ff11ab: __free_memory_core (STB_LOCAL)
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
In mm/nobootmem.c (ffffffff820d3875)
Location: mm/nobootmem.c:114
Inline: True
Inline callers:
  - mm/nobootmem.c:free_all_bootmem
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
In mm/nobootmem.c (ffffffff826dc295)
Location: mm/nobootmem.c:115
Inline: True
Inline callers:
  - mm/nobootmem.c:free_all_bootmem
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
In mm/nobootmem.c (ffffffff82706753)
Location: mm/nobootmem.c:115
Inline: True
Inline callers:
  - mm/nobootmem.c:free_all_bootmem
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
In mm/memblock.c (ffffffff828be5ba)
Location: mm/memblock.c:1907
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff828d7787)
Location: mm/memblock.c:1908
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff828dfbf8)
Location: mm/memblock.c:1908
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff82cfc909)
Location: mm/memblock.c:1960
Inline: True
Inline callers:
  - mm/memblock.c:free_low_memory_core_early
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
In mm/memblock.c (ffffffff82fe9332)
Location: mm/memblock.c:1990
Inline: True
Inline callers:
  - mm/memblock.c:free_low_memory_core_early
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
In mm/memblock.c (ffffffff831f4295)
Location: mm/memblock.c:1991
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff832da666)
Location: mm/memblock.c:2019
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff8348f77c)
Location: mm/memblock.c:2026
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff83ec1ec3)
Location: mm/memblock.c:2044
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff836e680d)
Location: mm/memblock.c:2075
Inline: True
Inline callers:
  - mm/memblock.c:free_low_memory_core_early
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
In mm/memblock.c (ffffffff83919cc6)
Location: mm/memblock.c:2134
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffff800011458d84)
Location: mm/memblock.c:1908
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (c1532cd8)
Location: mm/memblock.c:1908
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (c00000000138268c)
Location: mm/memblock.c:1908
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffe00001734a)
Location: mm/memblock.c:1908
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff828c8aac)
Location: mm/memblock.c:1908
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff828c11d1)
Location: mm/memblock.c:1908
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff828db82c)
Location: mm/memblock.c:1908
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
In mm/memblock.c (ffffffff828e0c4d)
Location: mm/memblock.c:1908
Inline: True
Inline callers:
  - mm/memblock.c:memblock_free_all
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
</ul>
