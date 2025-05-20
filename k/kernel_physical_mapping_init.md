# Function: <code>kernel_physical_mapping_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int start, long unsigned int end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8181c83e)
Location: arch/x86/mm/init_64.c:599
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff8181c83e-ffffffff8181ca09: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81896955)
Location: arch/x86/mm/init_64.c:562
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81896955-ffffffff81896b0b: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff818cb042)
Location: arch/x86/mm/init_64.c:552
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff818cb042-ffffffff818cb1f6: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81902610)
Location: arch/x86/mm/init_64.c:684
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81902610-ffffffff819027d1: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8198c58d)
Location: arch/x86/mm/init_64.c:684
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff8198c58d-ffffffff8198c736: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff819e8e7b)
Location: arch/x86/mm/init_64.c:695
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff819e8e7b-ffffffff819e9020: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a24704)
Location: arch/x86/mm/init_64.c:690
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
```
**Symbols:**

```
ffffffff81a24704-ffffffff81a24966: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a94cf0)
Location: arch/x86/mm/init_64.c:779
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81a94cf0-ffffffff81a94d00: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81acc5d0)
Location: arch/x86/mm/init_64.c:779
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81acc5d0-ffffffff81acc5e0: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81bc504c)
Location: arch/x86/mm/init_64.c:787
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81bc504c-ffffffff81bc505d: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c3df1d)
Location: arch/x86/mm/init_64.c:782
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81c3df1d-ffffffff81c3df2e: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81c30266)
Location: arch/x86/mm/init_64.c:782
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81c30266-ffffffff81c30277: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81d4e9f1)
Location: arch/x86/mm/init_64.c:783
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81d4e9f1-ffffffff81d4ea02: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f1e800)
Location: arch/x86/mm/init_64.c:782
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81f1e800-ffffffff81f1e820: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820c72c0)
Location: arch/x86/mm/init_64.c:783
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff820c72c0-ffffffff820c72e0: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8214b350)
Location: arch/x86/mm/init_64.c:783
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff8214b350-ffffffff8214b370: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8222de00)
Location: arch/x86/mm/init_64.c:783
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff8222de00-ffffffff8222de20: kernel_physical_mapping_init (STB_GLOBAL)
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
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a6b440)
Location: arch/x86/mm/init_64.c:779
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81a6b440-ffffffff81a6b450: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a2798d)
Location: arch/x86/mm/init_64.c:779
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81a2798d-ffffffff81a2799d: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ad7850)
Location: arch/x86/mm/init_64.c:779
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81ad7850-ffffffff81ad7860: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int kernel_physical_mapping_init(long unsigned int paddr_start, long unsigned int paddr_end, long unsigned int page_size_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81ae3d10)
Location: arch/x86/mm/init_64.c:779
Inline: False
Direct callers:
  - arch/x86/mm/init.c:init_memory_mapping
```
**Symbols:**

```
ffffffff81ae3d10-ffffffff81ae3d20: kernel_physical_mapping_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int paddr_start</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int paddr_end</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int start</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int end</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pgprot_t prot</code>
</li>
</ul>
</details>
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
