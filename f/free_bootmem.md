# Function: <code>free_bootmem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_bootmem(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81f8aebe)
Location: mm/nobootmem.c:229
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/tce_64.c:free_tce_table
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81f8aebe-ffffffff81f8aec9: free_bootmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_bootmem(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81fb4b01)
Location: mm/nobootmem.c:230
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/tce_64.c:free_tce_table
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81fb4b01-ffffffff81fb4b0c: free_bootmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_bootmem(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff81ff14e7)
Location: mm/nobootmem.c:233
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/tce_64.c:free_tce_table
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff81ff14e7-ffffffff81ff14f2: free_bootmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_bootmem(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff820d3962)
Location: mm/nobootmem.c:217
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/tce_64.c:free_tce_table
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff820d3962-ffffffff820d3972: free_bootmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_bootmem(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff826dc382)
Location: mm/nobootmem.c:218
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/tce_64.c:free_tce_table
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff826dc382-ffffffff826dc392: free_bootmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_bootmem(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/nobootmem.c (ffffffff82706840)
Location: mm/nobootmem.c:218
Inline: False
Direct callers:
  - arch/x86/xen/p2m.c:free_p2m_page
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_free
  - arch/x86/kernel/tce_64.c:free_tce_table
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_init
```
**Symbols:**

```
ffffffff82706840-ffffffff82706850: free_bootmem (STB_GLOBAL)
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
