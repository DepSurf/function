# Function: <code>has_transparent_hugepage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81f8d5b5)
Location: arch/x86/include/asm/pgtable.h:178
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811beb65)
Location: arch/x86/include/asm/pgtable.h:185
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_options
```
```
In mm/huge_memory.c (ffffffff81fb7632)
Location: arch/x86/include/asm/pgtable.h:185
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811cf3b5)
Location: arch/x86/include/asm/pgtable.h:185
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_options
```
```
In mm/huge_memory.c (ffffffff81ff3fab)
Location: arch/x86/include/asm/pgtable.h:185
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d7a7f)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_options
```
```
In mm/huge_memory.c (ffffffff820d6788)
Location: arch/x86/include/asm/pgtable.h:225
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811ec8ff)
Location: arch/x86/include/asm/pgtable.h:240
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_options
```
```
In mm/huge_memory.c (ffffffff826df3f6)
Location: arch/x86/include/asm/pgtable.h:240
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
In mm/shmem.c (ffffffff8120deff)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_options
```
```
In mm/huge_memory.c (ffffffff8270981a)
Location: arch/x86/include/asm/pgtable.h:250
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/shmem.c (ffffffff81220a9f)
Location: arch/x86/include/asm/pgtable.h:252
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_options
```
```
In mm/huge_memory.c (ffffffff828c09fc)
Location: arch/x86/include/asm/pgtable.h:252
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/shmem.c (ffffffff8123023f)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_options
```
```
In mm/huge_memory.c (ffffffff828d9d7f)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
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
In mm/shmem.c (ffffffff8123e5e8)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_one
```
```
In mm/huge_memory.c (ffffffff828e2226)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff817606d5)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_devinit
  - drivers/nvdimm/pfn_devs.c:supported_alignments_show
  - drivers/nvdimm/pfn_devs.c:align_store
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
In mm/shmem.c (ffffffff8126b99f)
Location: arch/x86/include/asm/pgtable.h:274
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_one
```
```
In mm/huge_memory.c (ffffffff82cff600)
Location: arch/x86/include/asm/pgtable.h:274
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff818201b7)
Location: arch/x86/include/asm/pgtable.h:274
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/pfn_devs.c:supported_alignments_show
  - drivers/nvdimm/pfn_devs.c:align_store
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
In mm/shmem.c (ffffffff8127635f)
Location: arch/x86/include/asm/pgtable.h:273
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_one
```
```
In mm/huge_memory.c (ffffffff82febfac)
Location: arch/x86/include/asm/pgtable.h:273
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8182f0e7)
Location: arch/x86/include/asm/pgtable.h:273
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/pfn_devs.c:supported_alignments_show
  - drivers/nvdimm/pfn_devs.c:align_store
```
```
In drivers/dax/bus.c (ffffffff81832fcd)
Location: arch/x86/include/asm/pgtable.h:273
Inline: True
Inline callers:
  - drivers/dax/bus.c:align_store
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
In mm/shmem.c (ffffffff8127b717)
Location: arch/x86/include/asm/pgtable.h:273
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_one
```
```
In mm/huge_memory.c (ffffffff831f680b)
Location: arch/x86/include/asm/pgtable.h:273
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8181239c)
Location: arch/x86/include/asm/pgtable.h:273
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/pfn_devs.c:supported_alignments_show
  - drivers/nvdimm/pfn_devs.c:align_store
```
```
In drivers/dax/bus.c (ffffffff81816151)
Location: arch/x86/include/asm/pgtable.h:273
Inline: True
Inline callers:
  - drivers/dax/bus.c:align_store
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
In mm/shmem.c (ffffffff812b9600)
Location: arch/x86/include/asm/pgtable.h:244
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_one
```
```
In mm/huge_memory.c (ffffffff832dd321)
Location: arch/x86/include/asm/pgtable.h:244
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8189c9a2)
Location: arch/x86/include/asm/pgtable.h:244
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/pfn_devs.c:supported_alignments_show
  - drivers/nvdimm/pfn_devs.c:align_store
```
```
In drivers/dax/bus.c (ffffffff818a0781)
Location: arch/x86/include/asm/pgtable.h:244
Inline: True
Inline callers:
  - drivers/dax/bus.c:align_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813154f0)
Location: arch/x86/include/asm/pgtable.h:247
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_one
```
```
In mm/huge_memory.c (ffffffff83492b5b)
Location: arch/x86/include/asm/pgtable.h:247
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff819e6281)
Location: arch/x86/include/asm/pgtable.h:247
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/pfn_devs.c:supported_alignments_show
  - drivers/nvdimm/pfn_devs.c:align_store
```
```
In drivers/dax/bus.c (ffffffff819e9d96)
Location: arch/x86/include/asm/pgtable.h:247
Inline: True
Inline callers:
  - drivers/dax/bus.c:align_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813893f0)
Location: arch/x86/include/asm/pgtable.h:248
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_one
```
```
In mm/huge_memory.c (ffffffff83ec6a65)
Location: arch/x86/include/asm/pgtable.h:248
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81b6221e)
Location: arch/x86/include/asm/pgtable.h:248
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/pfn_devs.c:supported_alignments_show
  - drivers/nvdimm/pfn_devs.c:align_store
```
```
In drivers/dax/bus.c (ffffffff81b667a6)
Location: arch/x86/include/asm/pgtable.h:248
Inline: True
Inline callers:
  - drivers/dax/bus.c:align_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813bb6a0)
Location: arch/x86/include/asm/pgtable.h:249
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_one
```
```
In mm/huge_memory.c (ffffffff836eba55)
Location: arch/x86/include/asm/pgtable.h:249
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81bb5821)
Location: arch/x86/include/asm/pgtable.h:249
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/pfn_devs.c:supported_alignments_show
  - drivers/nvdimm/pfn_devs.c:align_store
```
```
In drivers/dax/bus.c (ffffffff81bb9b93)
Location: arch/x86/include/asm/pgtable.h:249
Inline: True
Inline callers:
  - drivers/dax/bus.c:align_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813e61c0)
Location: arch/x86/include/asm/pgtable.h:285
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_one
```
```
In mm/huge_memory.c (ffffffff8391eb17)
Location: arch/x86/include/asm/pgtable.h:285
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81c09d9f)
Location: arch/x86/include/asm/pgtable.h:285
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_create
  - drivers/nvdimm/pfn_devs.c:supported_alignments_show
  - drivers/nvdimm/pfn_devs.c:align_store
```
```
In drivers/dax/bus.c (ffffffff81c0e1f3)
Location: arch/x86/include/asm/pgtable.h:285
Inline: True
Inline callers:
  - drivers/dax/bus.c:align_store
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int has_transparent_hugepage();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c00000000038e6b0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1145
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_parse_one
Direct callers:
  - mm/shmem.c:shmem_init
```
```
In mm/huge_memory.c (c000000001385ab8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1145
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In drivers/nvdimm/pfn_devs.c (c000000000a15b70)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:1145
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_devinit
  - drivers/nvdimm/pfn_devs.c:supported_alignments_show
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
c00000000038dd70-c00000000038ddd4: has_transparent_hugepage (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In mm/shmem.c (ffffffff81236c38)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_one
```
```
In mm/huge_memory.c (ffffffff828cb0da)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81714dc5)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_devinit
  - drivers/nvdimm/pfn_devs.c:supported_alignments_show
  - drivers/nvdimm/pfn_devs.c:align_store
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
In mm/shmem.c (ffffffff81229c98)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_one
```
```
In mm/huge_memory.c (ffffffff828c37ff)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff816e8845)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_devinit
  - drivers/nvdimm/pfn_devs.c:supported_alignments_show
  - drivers/nvdimm/pfn_devs.c:align_store
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
In mm/shmem.c (ffffffff812349d8)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_one
```
```
In mm/huge_memory.c (ffffffff828dde5a)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81753b95)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_devinit
  - drivers/nvdimm/pfn_devs.c:supported_alignments_show
  - drivers/nvdimm/pfn_devs.c:align_store
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
In mm/shmem.c (ffffffff81244b38)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/shmem.c:shmem_enabled_store
  - mm/shmem.c:shmem_init
  - mm/shmem.c:shmem_parse_one
```
```
In mm/huge_memory.c (ffffffff828e3271)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff8176f005)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_validate
  - drivers/nvdimm/pfn_devs.c:nd_pfn_devinit
  - drivers/nvdimm/pfn_devs.c:supported_alignments_show
  - drivers/nvdimm/pfn_devs.c:align_store
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
