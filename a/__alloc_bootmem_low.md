# Function: <code>__alloc_bootmem_low</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *__alloc_bootmem_low(long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81f8b056)
Location: mm/nobootmem.c:414
Inline: False
Direct callers:
  - arch/x86/kernel/tce_64.c:alloc_tce_table
```
**Symbols:**

```
ffffffff81f8b056-ffffffff81f8b078: __alloc_bootmem_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *__alloc_bootmem_low(long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81fb4c9d)
Location: mm/nobootmem.c:415
Inline: False
Direct callers:
  - arch/x86/kernel/tce_64.c:alloc_tce_table
```
**Symbols:**

```
ffffffff81fb4c9d-ffffffff81fb4cbf: __alloc_bootmem_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *__alloc_bootmem_low(long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81ff1683)
Location: mm/nobootmem.c:415
Inline: False
Direct callers:
  - arch/x86/kernel/tce_64.c:alloc_tce_table
```
**Symbols:**

```
ffffffff81ff1683-ffffffff81ff16a5: __alloc_bootmem_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *__alloc_bootmem_low(long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff820d3adf)
Location: mm/nobootmem.c:399
Inline: False
Direct callers:
  - arch/x86/kernel/tce_64.c:alloc_tce_table
```
**Symbols:**

```
ffffffff820d3adf-ffffffff820d3b06: __alloc_bootmem_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *__alloc_bootmem_low(long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff826dc4ff)
Location: mm/nobootmem.c:400
Inline: False
Direct callers:
  - arch/x86/kernel/tce_64.c:alloc_tce_table
```
**Symbols:**

```
ffffffff826dc4ff-ffffffff826dc526: __alloc_bootmem_low (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__alloc_bootmem_low(long unsigned int size, long unsigned int align, long unsigned int goal);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff827069e3)
Location: mm/nobootmem.c:400
Inline: False
Direct callers:
  - arch/x86/kernel/tce_64.c:alloc_tce_table
```
**Symbols:**

```
ffffffff827069e3-ffffffff82706a1d: __alloc_bootmem_low (STB_GLOBAL)
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
