# Function: <code>kernel_physical_mapping_change</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a94d00)
Location: arch/x86/mm/init_64.c:794
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff81a94d00-ffffffff81a94d0d: kernel_physical_mapping_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81acc5e0)
Location: arch/x86/mm/init_64.c:794
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff81acc5e0-ffffffff81acc5ed: kernel_physical_mapping_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc505d)
Location: arch/x86/mm/init_64.c:802
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff81bc505d-ffffffff81bc5083: kernel_physical_mapping_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3df2e)
Location: arch/x86/mm/init_64.c:797
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff81c3df2e-ffffffff81c3df54: kernel_physical_mapping_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c30277)
Location: arch/x86/mm/init_64.c:797
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff81c30277-ffffffff81c3029d: kernel_physical_mapping_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4ea02)
Location: arch/x86/mm/init_64.c:798
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff81d4ea02-ffffffff81d4ea28: kernel_physical_mapping_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f1e820)
Location: arch/x86/mm/init_64.c:797
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff81f1e820-ffffffff81f1e855: kernel_physical_mapping_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c72f0)
Location: arch/x86/mm/init_64.c:798
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff820c72f0-ffffffff820c7325: kernel_physical_mapping_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8214b380)
Location: arch/x86/mm/init_64.c:798
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff8214b380-ffffffff8214b3b5: kernel_physical_mapping_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8222de30)
Location: arch/x86/mm/init_64.c:798
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff8222de30-ffffffff8222de65: kernel_physical_mapping_change (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a6b450)
Location: arch/x86/mm/init_64.c:794
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff81a6b450-ffffffff81a6b45d: kernel_physical_mapping_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a2799d)
Location: arch/x86/mm/init_64.c:794
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff81a2799d-ffffffff81a279aa: kernel_physical_mapping_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ad7860)
Location: arch/x86/mm/init_64.c:794
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff81ad7860-ffffffff81ad786d: kernel_physical_mapping_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_change(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ae3d20)
Location: arch/x86/mm/init_64.c:794
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff81ae3d20-ffffffff81ae3d2d: kernel_physical_mapping_change (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
<b>Arch</b>
<ul>
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
