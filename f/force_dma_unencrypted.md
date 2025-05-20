# Function: <code>force_dma_unencrypted</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8110cf83)
Location: kernel/dma/direct.c:27
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
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
In kernel/dma/direct.c (ffffffff81118d1b)
Location: kernel/dma/direct.c:29
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool force_dma_unencrypted(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff8108e200)
Location: arch/x86/mm/mem_encrypt.c:356
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
**Symbols:**

```
ffffffff8108e200-ffffffff8108e263: force_dma_unencrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool force_dma_unencrypted(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff8108ee60)
Location: arch/x86/mm/mem_encrypt.c:354
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
**Symbols:**

```
ffffffff8108ee60-ffffffff8108eec3: force_dma_unencrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool force_dma_unencrypted(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff81095210)
Location: arch/x86/mm/mem_encrypt.c:354
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_common_mmap
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_coherent_ok
  - kernel/dma/direct.c:dma_direct_optimal_gfp_mask
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
**Symbols:**

```
ffffffff81095210-ffffffff81095273: force_dma_unencrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool force_dma_unencrypted(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff810944c0)
Location: arch/x86/mm/mem_encrypt.c:394
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_pgprot
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
**Symbols:**

```
ffffffff810944c0-ffffffff8109452b: force_dma_unencrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool force_dma_unencrypted(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff81094e30)
Location: arch/x86/mm/mem_encrypt.c:393
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_pgprot
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
**Symbols:**

```
ffffffff81094e30-ffffffff81094e96: force_dma_unencrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool force_dma_unencrypted(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/mm/mem_encrypt.c:394
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_pgprot
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
**Symbols:**

```
ffffffff81ca2507-ffffffff81ca2528: force_dma_unencrypted.cold (STB_LOCAL)
ffffffff810a4db0-ffffffff810a4e33: force_dma_unencrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool force_dma_unencrypted(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/mm/mem_encrypt.c:17
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
**Symbols:**

```
ffffffff81e51c84-ffffffff81e51ca5: force_dma_unencrypted.cold (STB_LOCAL)
ffffffff810b9670-ffffffff810b9722: force_dma_unencrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool force_dma_unencrypted(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/mm/mem_encrypt.c:17
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
**Symbols:**

```
ffffffff820553ea-ffffffff8205540b: force_dma_unencrypted.cold (STB_LOCAL)
ffffffff810d52d0-ffffffff810d53a6: force_dma_unencrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool force_dma_unencrypted(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/mm/mem_encrypt.c:17
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
**Symbols:**

```
ffffffff820d39b5-ffffffff820d39d6: force_dma_unencrypted.cold (STB_LOCAL)
ffffffff810d87c0-ffffffff810d8896: force_dma_unencrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool force_dma_unencrypted(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/mm/mem_encrypt.c:18
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_mmap
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc
  - kernel/dma/direct.c:dma_direct_alloc_from_pool
  - kernel/dma/direct.c:dma_direct_get_required_mask
  - kernel/dma/swiotlb.c:swiotlb_alloc_pool
```
**Symbols:**

```
ffffffff821ae823-ffffffff821ae844: force_dma_unencrypted.cold (STB_LOCAL)
ffffffff810e1040-ffffffff810e1116: force_dma_unencrypted (STB_GLOBAL)
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
In kernel/dma/direct.c (0)
Location: include/linux/dma-direct.h:46
Inline: True
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
In kernel/dma/direct.c (0)
Location: include/linux/dma-direct.h:46
Inline: True
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
In kernel/dma/direct.c (c0000000001f5414)
Location: arch/powerpc/include/asm/mem_encrypt.h:18
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
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
In kernel/dma/direct.c (0)
Location: include/linux/dma-direct.h:46
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool force_dma_unencrypted(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff8108de20)
Location: arch/x86/mm/mem_encrypt.c:354
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_coherent_ok
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
**Symbols:**

```
ffffffff8108de20-ffffffff8108de83: force_dma_unencrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool force_dma_unencrypted(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff8107c930)
Location: arch/x86/mm/mem_encrypt.c:354
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
**Symbols:**

```
ffffffff8107c930-ffffffff8107c993: force_dma_unencrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool force_dma_unencrypted(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff8108ddd0)
Location: arch/x86/mm/mem_encrypt.c:354
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
**Symbols:**

```
ffffffff8108ddd0-ffffffff8108de33: force_dma_unencrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool force_dma_unencrypted(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff810901b0)
Location: arch/x86/mm/mem_encrypt.c:354
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:__dma_direct_alloc_pages
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
**Symbols:**

```
ffffffff810901b0-ffffffff81090213: force_dma_unencrypted (STB_GLOBAL)
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
