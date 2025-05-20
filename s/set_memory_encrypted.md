# Function: <code>set_memory_encrypted</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810775f0)
Location: arch/x86/mm/pageattr.c:1830
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/mm/mem_encrypt.c:sev_free
```
**Symbols:**

```
ffffffff810775f0-ffffffff81077605: set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107a060)
Location: arch/x86/mm/pageattr.c:1881
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - kernel/dma/direct.c:dma_direct_free
```
**Symbols:**

```
ffffffff8107a060-ffffffff8107a075: set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81080840)
Location: arch/x86/mm/pageattr.c:2065
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
  - kernel/dma/direct.c:dma_direct_free_pages
```
**Symbols:**

```
ffffffff81080840-ffffffff81080855: set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084340)
Location: arch/x86/mm/pageattr.c:2076
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
  - kernel/dma/direct.c:dma_direct_free_pages
```
**Symbols:**

```
ffffffff81084340-ffffffff81084355: set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81085080)
Location: arch/x86/mm/pageattr.c:1982
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
  - kernel/dma/direct.c:dma_direct_free_pages
```
**Symbols:**

```
ffffffff81085080-ffffffff81085095: set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ecc0)
Location: arch/x86/mm/pat/set_memory.c:2018
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/pool.c:atomic_pool_expand
```
**Symbols:**

```
ffffffff8108ecc0-ffffffff8108ecd5: set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108eab0)
Location: arch/x86/mm/pat/set_memory.c:2018
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/pool.c:atomic_pool_expand
```
**Symbols:**

```
ffffffff8108eab0-ffffffff8108eac5: set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f670)
Location: arch/x86/mm/pat/set_memory.c:2026
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/pool.c:atomic_pool_expand
```
**Symbols:**

```
ffffffff8108f670-ffffffff8108f685: set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f130)
Location: arch/x86/mm/pat/set_memory.c:2026
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/pool.c:atomic_pool_expand
```
**Symbols:**

```
ffffffff8109f130-ffffffff8109f145: set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b2c60)
Location: arch/x86/mm/pat/set_memory.c:2083
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/mm/mem_encrypt_amd.c:mem_encrypt_free_decrypted_mem
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/pool.c:atomic_pool_expand
```
**Symbols:**

```
ffffffff810b2c60-ffffffff810b2cd1: set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cd630)
Location: arch/x86/mm/pat/set_memory.c:2187
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/mm/mem_encrypt_amd.c:mem_encrypt_free_decrypted_mem
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/pool.c:atomic_pool_expand
```
**Symbols:**

```
ffffffff810cd630-ffffffff810cd6a1: set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d0cc0)
Location: arch/x86/mm/pat/set_memory.c:2186
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/mm/mem_encrypt_amd.c:mem_encrypt_free_decrypted_mem
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/pool.c:atomic_pool_expand
```
**Symbols:**

```
ffffffff810d0cc0-ffffffff810d0d0f: set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d93a0)
Location: arch/x86/mm/pat/set_memory.c:2190
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/mm/mem_encrypt_amd.c:mem_encrypt_free_decrypted_mem
  - kernel/dma/direct.c:dma_direct_free_pages
  - kernel/dma/direct.c:dma_direct_free
  - kernel/dma/swiotlb.c:swiotlb_alloc_pool
  - kernel/dma/swiotlb.c:swiotlb_exit
  - kernel/dma/pool.c:atomic_pool_expand
```
**Symbols:**

```
ffffffff810d93a0-ffffffff810d93ef: set_memory_encrypted (STB_GLOBAL)
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
Location: include/linux/set_memory.h:43
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
Location: include/linux/set_memory.h:43
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/pseries/svm.c (c000000000103860)
Location: arch/powerpc/platforms/pseries/svm.c:37
Inline: False
Direct callers:
  - kernel/dma/direct.c:dma_direct_free_pages
```
**Symbols:**

```
c000000000103860-c0000000001038b8: set_memory_encrypted (STB_GLOBAL)
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
Location: include/linux/set_memory.h:43
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
int set_memory_encrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084080)
Location: arch/x86/mm/pageattr.c:1982
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
  - kernel/dma/direct.c:dma_direct_free_pages
```
**Symbols:**

```
ffffffff81084080-ffffffff81084095: set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81072cd0)
Location: arch/x86/mm/pageattr.c:1982
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
  - kernel/dma/direct.c:dma_direct_free_pages
```
**Symbols:**

```
ffffffff81072cd0-ffffffff81072ce5: set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084030)
Location: arch/x86/mm/pageattr.c:1982
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
  - kernel/dma/direct.c:dma_direct_free_pages
```
**Symbols:**

```
ffffffff81084030-ffffffff81084045: set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_memory_encrypted(long unsigned int addr, int numpages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81086170)
Location: arch/x86/mm/pageattr.c:1982
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:arch_kexec_pre_free_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
  - kernel/dma/direct.c:dma_direct_free_pages
```
**Symbols:**

```
ffffffff81086170-ffffffff81086185: set_memory_encrypted (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
