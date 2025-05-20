# Function: <code>mem_encrypt_active</code>

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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (0)
Location: include/linux/mem_encrypt.h:31
Inline: True
```
```
In arch/x86/mm/pageattr.c (ffffffff810774c2)
Location: include/linux/mem_encrypt.h:31
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
```
```
In lib/swiotlb.c (0)
Location: include/linux/mem_encrypt.h:31
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff826ed84d)
Location: include/linux/mem_encrypt.h:31
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
```
In arch/x86/mm/pageattr.c (ffffffff81079f51)
Location: include/linux/mem_encrypt.h:31
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
```
```
In kernel/dma/swiotlb.c (ffffffff8110db82)
Location: include/linux/mem_encrypt.h:31
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff810003c2)
Location: include/linux/mem_encrypt.h:31
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
```
```
In arch/x86/mm/ioremap.c (ffffffff828a43df)
Location: include/linux/mem_encrypt.h:31
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
```
In arch/x86/mm/pageattr.c (ffffffff8108075d)
Location: include/linux/mem_encrypt.h:31
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6d39)
Location: include/linux/mem_encrypt.h:31
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
```
In kernel/dma/swiotlb.c (ffffffff811196d2)
Location: include/linux/mem_encrypt.h:31
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff810003d1)
Location: include/linux/mem_encrypt.h:28
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
```
```
In arch/x86/mm/ioremap.c (ffffffff828bc8a7)
Location: include/linux/mem_encrypt.h:28
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
```
In arch/x86/mm/pageattr.c (ffffffff8108424d)
Location: include/linux/mem_encrypt.h:28
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bf3eb)
Location: include/linux/mem_encrypt.h:28
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
```
In kernel/dma/swiotlb.c (ffffffff81124132)
Location: include/linux/mem_encrypt.h:28
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In fs/proc/vmcore.c (ffffffff8136957d)
Location: include/linux/mem_encrypt.h:28
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8100041d)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
```
```
In arch/x86/mm/ioremap.c (ffffffff828c2d4e)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
```
In arch/x86/mm/pageattr.c (ffffffff81084f8d)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c5866)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
```
In kernel/dma/swiotlb.c (ffffffff811300b7)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In fs/proc/vmcore.c (ffffffff813817cd)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
```
In drivers/iommu/iommu.c (0)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff810005ad)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
```
```
In arch/x86/mm/ioremap.c (ffffffff81088e85)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108ebe1)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce8a5b)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
```
In kernel/dma/swiotlb.c (ffffffff8113ee8e)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In fs/proc/vmcore.c (ffffffff813cbae5)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
```
In drivers/iommu/iommu.c (0)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff81794c9b)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8100069d)
Location: arch/x86/include/asm/mem_encrypt.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
```
```
In arch/x86/mm/ioremap.c (ffffffff810890c5)
Location: arch/x86/include/asm/mem_encrypt.h:105
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e9b1)
Location: arch/x86/include/asm/mem_encrypt.h:105
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd644f)
Location: arch/x86/include/asm/mem_encrypt.h:105
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
```
In kernel/dma/swiotlb.c (ffffffff8113a531)
Location: arch/x86/include/asm/mem_encrypt.h:105
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In fs/proc/vmcore.c (ffffffff813dd775)
Location: arch/x86/include/asm/mem_encrypt.h:105
Inline: True
Inline callers:
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a3160)
Location: arch/x86/include/asm/mem_encrypt.h:105
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type
```
```
In drivers/iommu/iommu.c (0)
Location: arch/x86/include/asm/mem_encrypt.h:105
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81000690)
Location: arch/x86/include/asm/mem_encrypt.h:104
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
```
```
In arch/x86/mm/ioremap.c (ffffffff81089d45)
Location: arch/x86/include/asm/mem_encrypt.h:104
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108f571)
Location: arch/x86/include/asm/mem_encrypt.h:104
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0ea7)
Location: arch/x86/include/asm/mem_encrypt.h:104
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
```
In kernel/dma/swiotlb.c (ffffffff8113ba53)
Location: arch/x86/include/asm/mem_encrypt.h:104
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In fs/proc/vmcore.c (ffffffff813e4655)
Location: arch/x86/include/asm/mem_encrypt.h:104
Inline: True
Inline callers:
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
```
In drivers/iommu/amd/iommu.c (ffffffff81785ee0)
Location: arch/x86/include/asm/mem_encrypt.h:104
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type
```
```
In drivers/iommu/iommu.c (0)
Location: arch/x86/include/asm/mem_encrypt.h:104
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff810007e5)
Location: arch/x86/include/asm/mem_encrypt.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
```
```
In arch/x86/mm/ioremap.c (ffffffff81099215)
Location: arch/x86/include/asm/mem_encrypt.h:105
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:phys_mem_access_encrypted
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109f021)
Location: arch/x86/include/asm/mem_encrypt.h:105
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff832c45c1)
Location: arch/x86/include/asm/mem_encrypt.h:105
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
```
In kernel/dma/swiotlb.c (ffffffff8115eb3f)
Location: arch/x86/include/asm/mem_encrypt.h:105
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In fs/proc/vmcore.c (ffffffff81436225)
Location: arch/x86/include/asm/mem_encrypt.h:105
Inline: True
Inline callers:
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
```
In drivers/iommu/amd/iommu.c (ffffffff8180d4ac)
Location: arch/x86/include/asm/mem_encrypt.h:105
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_def_domain_type
```
```
In drivers/iommu/iommu.c (0)
Location: arch/x86/include/asm/mem_encrypt.h:105
Inline: True
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (0)
Location: include/linux/mem_encrypt.h:21
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/linux/mem_encrypt.h:21
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/mem_encrypt.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/vmcore.c (0)
Location: include/linux/mem_encrypt.h:21
Inline: True
```
```
In drivers/iommu/iommu.c (0)
Location: include/linux/mem_encrypt.h:21
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/dma/swiotlb.c (c0000000001f6be4)
Location: arch/powerpc/include/asm/mem_encrypt.h:13
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In fs/proc/vmcore.c (c000000000567308)
Location: arch/powerpc/include/asm/mem_encrypt.h:13
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
```
In drivers/iommu/iommu.c (0)
Location: arch/powerpc/include/asm/mem_encrypt.h:13
Inline: True
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
In kernel/dma/swiotlb.c (0)
Location: include/linux/mem_encrypt.h:21
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8100041d)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
```
```
In arch/x86/mm/ioremap.c (ffffffff828add24)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
```
In arch/x86/mm/pageattr.c (ffffffff81083f8d)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b07fe)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
```
In kernel/dma/swiotlb.c (ffffffff81128867)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In fs/proc/vmcore.c (ffffffff81379dad)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
```
In drivers/iommu/iommu.c (0)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8100041d)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
```
```
In arch/x86/mm/ioremap.c (ffffffff828a5f97)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
```
In arch/x86/mm/pageattr.c (ffffffff81072bdd)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a8983)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
```
In kernel/dma/swiotlb.c (ffffffff8111b0f7)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In fs/proc/vmcore.c (ffffffff8136a87d)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
```
In drivers/iommu/iommu.c (0)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8100041d)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
```
```
In arch/x86/mm/ioremap.c (ffffffff828c0c23)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
```
In arch/x86/mm/pageattr.c (ffffffff81083f3d)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c36fd)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
```
In kernel/dma/swiotlb.c (ffffffff81126587)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In fs/proc/vmcore.c (ffffffff8137787d)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
```
In drivers/iommu/iommu.c (0)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8100041d)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:__startup_64
```
```
In arch/x86/mm/ioremap.c (ffffffff828c3d6e)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:early_memremap_pgprot_adjust
```
```
In arch/x86/mm/pageattr.c (ffffffff8108607d)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c68a3)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
```
In kernel/dma/swiotlb.c (ffffffff81132bc7)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - kernel/dma/swiotlb.c:swiotlb_tbl_map_single
```
```
In fs/proc/vmcore.c (ffffffff8138b32d)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
Inline callers:
  - fs/proc/vmcore.c:read_vmcore
  - fs/proc/vmcore.c:elfcorehdr_read_notes
```
```
In drivers/iommu/iommu.c (0)
Location: arch/x86/include/asm/mem_encrypt.h:95
Inline: True
```
</details>
</li>
</ul>

## Differences
