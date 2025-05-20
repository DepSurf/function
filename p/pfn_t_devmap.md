# Function: <code>pfn_t_devmap</code>

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
In mm/memory.c (ffffffff811dd665)
Location: include/linux/pfn_t.h:90
Inline: True
```
```
In mm/huge_memory.c (ffffffff81213e68)
Location: include/linux/pfn_t.h:90
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
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
In mm/memory.c (ffffffff811ed155)
Location: include/linux/pfn_t.h:90
Inline: True
```
```
In mm/huge_memory.c (ffffffff81226268)
Location: include/linux/pfn_t.h:90
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (ffffffff8129ce9f)
Location: include/linux/pfn_t.h:90
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pmd_fault
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
In mm/memory.c (ffffffff811f80e4)
Location: include/linux/pfn_t.h:103
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff812314a8)
Location: include/linux/pfn_t.h:103
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (ffffffff812abbbd)
Location: include/linux/pfn_t.h:103
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
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
In mm/memory.c (ffffffff81210431)
Location: include/linux/pfn_t.h:106
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff8124f675)
Location: include/linux/pfn_t.h:106
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (ffffffff812cc9d9)
Location: include/linux/pfn_t.h:106
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pfn
```
```
In drivers/dax/super.c (ffffffff816a5cc2)
Location: include/linux/pfn_t.h:106
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
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
In mm/memory.c (ffffffff8122fb8e)
Location: include/linux/pfn_t.h:106
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff812736d7)
Location: include/linux/pfn_t.h:106
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (ffffffff812f6d83)
Location: include/linux/pfn_t.h:106
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pfn
```
```
In drivers/dax/super.c (ffffffff816e2116)
Location: include/linux/pfn_t.h:106
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
In mm/memory.c (ffffffff812445ce)
Location: include/linux/pfn_t.h:108
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff81287af1)
Location: include/linux/pfn_t.h:108
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (ffffffff8130be31)
Location: include/linux/pfn_t.h:108
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pfn
```
```
In drivers/dax/super.c (ffffffff81705531)
Location: include/linux/pfn_t.h:108
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
In mm/memory.c (ffffffff81256596)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff812a226a)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (ffffffff81333362)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pfn
```
```
In drivers/dax/super.c (ffffffff8173f6a0)
Location: include/linux/pfn_t.h:101
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
In mm/memory.c (ffffffff81264b26)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff812b361a)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (ffffffff81346f12)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pfn
```
```
In drivers/dax/super.c (ffffffff81763880)
Location: include/linux/pfn_t.h:101
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
In mm/memory.c (ffffffff81292d75)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff812e90ab)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In fs/dax.c (ffffffff8138c5df)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pfn
```
```
In drivers/dax/super.c (ffffffff81823751)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
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
In mm/memory.c (ffffffff8129d615)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff812f451b)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In fs/dax.c (ffffffff8139dd0f)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pfn
```
```
In drivers/dax/super.c (ffffffff81832439)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
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
In mm/memory.c (ffffffff812a2c75)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff812fa76b)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In fs/dax.c (ffffffff813a4f1f)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pfn
```
```
In drivers/dax/super.c (ffffffff81815229)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - drivers/dax/super.c:__generic_fsdax_supported
  - drivers/dax/super.c:__generic_fsdax_supported
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
In mm/memory.c (ffffffff812e60e5)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff813445cb)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In fs/dax.c (ffffffff813f6a73)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_iter
```
```
In drivers/dax/super.c (ffffffff8189fa49)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - drivers/dax/super.c:generic_fsdax_supported
  - drivers/dax/super.c:generic_fsdax_supported
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
In mm/memory.c (ffffffff813456e5)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff813b9b0b)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In fs/dax.c (ffffffff814690a6)
Location: include/linux/pfn_t.h:101
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
In mm/memory.c (ffffffff813bda35)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff8143bffb)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud_prot
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
  - mm/huge_memory.c:vmf_insert_pfn_pmd_prot
```
```
In fs/dax.c (ffffffff814f7b69)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_direct_access
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
In mm/memory.c (ffffffff813f2749)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff81471b1a)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (ffffffff8152e9b9)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_direct_access
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
In mm/memory.c (ffffffff8141d489)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff814a131a)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (ffffffff81563899)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_direct_access
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
In mm/memory.c (ffff8000102fb5c4)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffff8000103546f4)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (ffff80001040a08c)
Location: include/linux/pfn_t.h:101
Inline: True
```
```
In drivers/dax/super.c (0)
Location: include/linux/pfn_t.h:101
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
In mm/memory.c (0)
Location: include/linux/pfn_t.h:108
Inline: True
```
```
In drivers/dax/super.c (0)
Location: include/linux/pfn_t.h:108
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
In mm/memory.c (c0000000003c6824)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (c00000000043b394)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (c0000000005129c4)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pfn
```
```
In drivers/dax/super.c (c000000000a19e3c)
Location: include/linux/pfn_t.h:101
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
In mm/memory.c (0)
Location: include/linux/pfn_t.h:108
Inline: True
```
```
In fs/dax.c (0)
Location: include/linux/pfn_t.h:108
Inline: True
```
```
In drivers/dax/super.c (0)
Location: include/linux/pfn_t.h:108
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
In mm/memory.c (ffffffff8125d176)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff812abbfa)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (ffffffff8133f4f2)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pfn
```
```
In drivers/dax/super.c (ffffffff81717f70)
Location: include/linux/pfn_t.h:101
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
In mm/memory.c (ffffffff8124f5d6)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff8129d4d8)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (ffffffff813301b2)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pfn
```
```
In drivers/dax/super.c (ffffffff816f04a0)
Location: include/linux/pfn_t.h:101
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
In mm/memory.c (ffffffff8125af16)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff812a9a0a)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (ffffffff8133cfc2)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pfn
```
```
In drivers/dax/super.c (ffffffff81756d40)
Location: include/linux/pfn_t.h:101
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
In mm/memory.c (ffffffff8126a8e6)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:insert_pfn
```
```
In mm/huge_memory.c (ffffffff812b985c)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pud
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
```
```
In fs/dax.c (ffffffff813506d2)
Location: include/linux/pfn_t.h:101
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pfn
```
```
In drivers/dax/super.c (ffffffff817721a0)
Location: include/linux/pfn_t.h:101
Inline: True
```
</details>
</li>
</ul>

## Differences
