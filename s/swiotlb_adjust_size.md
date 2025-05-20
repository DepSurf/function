# Function: <code>swiotlb_adjust_size</code>

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
void swiotlb_adjust_size(long unsigned int new_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff82fdde27)
Location: kernel/dma/swiotlb.c:164
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sev_setup_arch
```
**Symbols:**

```
ffffffff82fdde27-ffffffff82fdde6a: swiotlb_adjust_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void swiotlb_adjust_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff831e8951)
Location: kernel/dma/swiotlb.c:114
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sev_setup_arch
```
**Symbols:**

```
ffffffff831e8951-ffffffff831e8997: swiotlb_adjust_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void swiotlb_adjust_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff832ccec3)
Location: kernel/dma/swiotlb.c:121
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:sev_setup_arch
```
**Symbols:**

```
ffffffff832ccec3-ffffffff832ccf09: swiotlb_adjust_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void swiotlb_adjust_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff8348099d)
Location: kernel/dma/swiotlb.c:106
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:sev_setup_arch
```
**Symbols:**

```
ffffffff8348099d-ffffffff834809f7: swiotlb_adjust_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void swiotlb_adjust_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff83ead7e0)
Location: kernel/dma/swiotlb.c:172
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:sev_setup_arch
```
**Symbols:**

```
ffffffff83ead7e0-ffffffff83ead85d: swiotlb_adjust_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void swiotlb_adjust_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff836d27c0)
Location: kernel/dma/swiotlb.c:186
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:sev_setup_arch
```
**Symbols:**

```
ffffffff836d27c0-ffffffff836d283d: swiotlb_adjust_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void swiotlb_adjust_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (ffffffff83904580)
Location: kernel/dma/swiotlb.c:209
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_setup_arch
```
**Symbols:**

```
ffffffff83904580-ffffffff839045fd: swiotlb_adjust_size (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int size</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int new_size</code>
</li>
</ul>
</details>
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
