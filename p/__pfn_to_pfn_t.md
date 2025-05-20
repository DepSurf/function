# Function: <code>__pfn_to_pfn_t</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dd71a)
Location: include/linux/pfn_t.h:18
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_pfn_prot
```
```
In drivers/block/brd.c (0)
Location: include/linux/pfn_t.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ed20a)
Location: include/linux/pfn_t.h:18
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_pfn_prot
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
In mm/memory.c (ffffffff811f81bd)
Location: include/linux/pfn_t.h:24
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_pfn_prot
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:24
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
In mm/memory.c (ffffffff8121033d)
Location: include/linux/pfn_t.h:27
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_pfn_prot
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:27
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
In mm/memory.c (ffffffff8122fa9a)
Location: include/linux/pfn_t.h:27
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_pfn_prot
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:27
Inline: True
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
In mm/memory.c (ffffffff812444ce)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:29
Inline: True
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
In mm/memory.c (ffffffff81256471)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:29
Inline: True
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
In mm/memory.c (ffffffff81264a01)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:29
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
In mm/memory.c (ffffffff81292c61)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In fs/dax.c (ffffffff8138d76f)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - fs/dax.c:dax_load_hole
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
In mm/memory.c (ffffffff8129d581)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In fs/dax.c (ffffffff8139eeff)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - fs/dax.c:dax_load_hole
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
In mm/memory.c (ffffffff812a2bb1)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In fs/dax.c (ffffffff813a7794)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
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
In mm/memory.c (ffffffff812e6001)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In fs/dax.c (ffffffff813f6922)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_iter
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
In mm/memory.c (ffffffff813455fe)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In fs/dax.c (ffffffff81469176)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_iter
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
In mm/memory.c (ffffffff813bd8a3)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In fs/dax.c (ffffffff814f9b12)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_pmd_load_hole
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
In mm/memory.c (ffffffff813f25a3)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In fs/dax.c (ffffffff81530fa2)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_pmd_load_hole
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
In mm/memory.c (ffffffff8141d2a3)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In fs/dax.c (ffffffff81565e82)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_pmd_load_hole
```
</details>
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
In mm/memory.c (ffff8000102fb708)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:29
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
In mm/memory.c (c0519f1c)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/memory.c:vmf_insert_pfn_prot
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
In mm/memory.c (c0000000003c6734)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:29
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020ad9c)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:29
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
In mm/memory.c (ffffffff8125d051)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:29
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
In mm/memory.c (ffffffff8124f4b1)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:29
Inline: True
```
```
In drivers/nvdimm/pmem.c (ffffffff816ebd88)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - drivers/nvdimm/pmem.c:__pmem_direct_access
```
```
In drivers/dax/device.c (ffffffff816f1ae9)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - drivers/dax/device.c:dev_dax_huge_fault
  - drivers/dax/device.c:dev_dax_huge_fault
  - drivers/dax/device.c:dev_dax_huge_fault
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
In mm/memory.c (ffffffff8125adf1)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:29
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
In mm/memory.c (ffffffff8126a7c1)
Location: include/linux/pfn_t.h:29
Inline: True
Inline callers:
  - mm/memory.c:vmf_insert_pfn_prot
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:29
Inline: True
```
</details>
</li>
</ul>

## Differences
