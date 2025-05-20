# Function: <code>__fls</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81f6beda)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
```
```
In kernel/time/timer.c (ffffffff810ee39c)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - kernel/time/timer.c:mod_timer
```
```
In security/selinux/ss/ebitmap.c (ffffffff8134dac8)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff813fe04d)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff8152a706)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff817a047a)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff817cb2fb)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff817dacb7)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_1
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
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81f94232)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
```
```
In security/selinux/ss/ebitmap.c (ffffffff81383ab5)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff814456b1)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff8157db46)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff8180e061)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff81837e90)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff818488c8)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_1
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
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff81fcf83e)
Location: arch/x86/include/asm/bitops.h:387
Inline: True
```
```
In security/selinux/ss/ebitmap.c (ffffffff8139a535)
Location: arch/x86/include/asm/bitops.h:387
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff81463ea1)
Location: arch/x86/include/asm/bitops.h:387
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff815aa0e6)
Location: arch/x86/include/asm/bitops.h:387
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff8183f4c0)
Location: arch/x86/include/asm/bitops.h:387
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff81869e50)
Location: arch/x86/include/asm/bitops.h:387
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff8187a718)
Location: arch/x86/include/asm/bitops.h:387
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_1
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
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff820b029d)
Location: arch/x86/include/asm/bitops.h:387
Inline: True
```
```
In security/selinux/ss/ebitmap.c (ffffffff813b09e2)
Location: arch/x86/include/asm/bitops.h:387
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff81468f31)
Location: arch/x86/include/asm/bitops.h:387
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff815bfd76)
Location: arch/x86/include/asm/bitops.h:387
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81860a47)
Location: arch/x86/include/asm/bitops.h:387
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff8188e31f)
Location: arch/x86/include/asm/bitops.h:387
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff8189fe26)
Location: arch/x86/include/asm/bitops.h:387
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_1
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
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff826b6aa9)
Location: arch/x86/include/asm/bitops.h:388
Inline: True
```
```
In security/selinux/ss/ebitmap.c (ffffffff813d6a84)
Location: arch/x86/include/asm/bitops.h:388
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff814951fe)
Location: arch/x86/include/asm/bitops.h:388
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81626396)
Location: arch/x86/include/asm/bitops.h:388
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff818e0ac7)
Location: arch/x86/include/asm/bitops.h:388
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff8190f3c1)
Location: arch/x86/include/asm/bitops.h:388
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81922c3a)
Location: arch/x86/include/asm/bitops.h:388
Inline: True
```
```
In lib/int_sqrt.c (ffffffff819733c9)
Location: arch/x86/include/asm/bitops.h:388
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
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff826e02d2)
Location: arch/x86/include/asm/bitops.h:391
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In security/selinux/ss/ebitmap.c (ffffffff8140709b)
Location: arch/x86/include/asm/bitops.h:391
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff814ca4f9)
Location: arch/x86/include/asm/bitops.h:391
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81660fd5)
Location: arch/x86/include/asm/bitops.h:391
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81937230)
Location: arch/x86/include/asm/bitops.h:391
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff819664c0)
Location: arch/x86/include/asm/bitops.h:391
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff8197ae9e)
Location: arch/x86/include/asm/bitops.h:391
Inline: True
```
```
In lib/int_sqrt.c (ffffffff819cf859)
Location: arch/x86/include/asm/bitops.h:391
Inline: True
Inline callers:
  - lib/int_sqrt.c:int_sqrt
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
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff82896292)
Location: arch/x86/include/asm/bitops.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In security/selinux/ss/ebitmap.c (ffffffff81422beb)
Location: arch/x86/include/asm/bitops.h:388
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff814df219)
Location: arch/x86/include/asm/bitops.h:388
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff8167f8a5)
Location: arch/x86/include/asm/bitops.h:388
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81966c20)
Location: arch/x86/include/asm/bitops.h:388
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff8199b96f)
Location: arch/x86/include/asm/bitops.h:388
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff819b0b6e)
Location: arch/x86/include/asm/bitops.h:388
Inline: True
```
```
In lib/int_sqrt.c (ffffffff81a08c99)
Location: arch/x86/include/asm/bitops.h:388
Inline: True
Inline callers:
  - lib/int_sqrt.c:int_sqrt
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
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828ade3c)
Location: arch/x86/include/asm/bitops.h:262
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In security/selinux/ss/ebitmap.c (ffffffff81450878)
Location: arch/x86/include/asm/bitops.h:262
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff8150b087)
Location: arch/x86/include/asm/bitops.h:262
Inline: True
```
```
In lib/math/int_sqrt.c (ffffffff815107ac)
Location: arch/x86/include/asm/bitops.h:262
Inline: True
Inline callers:
  - lib/math/int_sqrt.c:int_sqrt
```
```
In drivers/iommu/iommu.c (ffffffff816b6c95)
Location: arch/x86/include/asm/bitops.h:262
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff819cccc4)
Location: arch/x86/include/asm/bitops.h:262
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff81a078a2)
Location: arch/x86/include/asm/bitops.h:262
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1ede1)
Location: arch/x86/include/asm/bitops.h:262
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
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828b1180)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In security/selinux/ss/ebitmap.c (ffffffff8146a658)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff81528ea7)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In lib/math/int_sqrt.c (ffffffff8152e6ac)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - lib/math/int_sqrt.c:int_sqrt
```
```
In drivers/iommu/iommu.c (ffffffff816d9825)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81a03839)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff81a3e412)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81a55a61)
Location: arch/x86/include/asm/bitops.h:261
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
In arch/x86/kernel/fpu/xstate.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff82cd62f0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In security/selinux/ss/ebitmap.c (ffffffff814bebca)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff8158c707)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In lib/math/int_sqrt.c (ffffffff8159258c)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - lib/math/int_sqrt.c:int_sqrt
```
```
In drivers/iommu/iommu.c (ffffffff8178dac5)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a1759)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81af2e62)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_node
```
```
In net/ipv6/addrconf.c (ffffffff81b3316a)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4d7f4)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
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
In arch/x86/kernel/fpu/xstate.c (ffffffff81043f53)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_supervisor_to_kernel
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff82fc22b3)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In security/selinux/ss/ebitmap.c (ffffffff814dc5ea)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff815a9177)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In lib/math/int_sqrt.c (ffffffff815af102)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - lib/math/int_sqrt.c:int_sqrt
```
```
In drivers/iommu/iommu.c (ffffffff817b9835)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818ae924)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
```
```
In net/ipv4/fib_trie.c (ffffffff81affd72)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_node
```
```
In net/ipv6/addrconf.c (ffffffff81b41a8a)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5c464)
Location: arch/x86/include/asm/bitops.h:261
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
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In arch/x86/kernel/fpu/xstate.c (ffffffff81045c53)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:copy_supervisor_to_kernel
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff831cc8ea)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In kernel/sched/isolation.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In security/selinux/ss/ebitmap.c (ffffffff814e2f1c)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff815b3e9a)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In lib/math/int_sqrt.c (ffffffff815b9eb2)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - lib/math/int_sqrt.c:int_sqrt
```
```
In lib/pldmfw/pldmfw.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff8179c9e5)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81892c48)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
```
```
In net/ipv4/fib_trie.c (ffffffff81aeb4d3)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff81b2f77a)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4a98f)
Location: arch/x86/include/asm/bitops.h:261
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
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff832ae8f0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In mm/page_alloc.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In security/selinux/ss/ebitmap.c (ffffffff8153c17e)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff8161a09f)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In lib/math/int_sqrt.c (ffffffff8162083b)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - lib/math/int_sqrt.c:int_sqrt
```
```
In lib/pldmfw/pldmfw.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff8180e8ab)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff818249d0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_pgsize
  - drivers/iommu/iommu.c:iommu_pgsize
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8192566a)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
```
```
In net/ipv4/fib_trie.c (ffffffff81bab838)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff81bf5afa)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81c11cf0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
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
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff8345f8ce)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In mm/page_alloc.c (ffffffff8136afc7)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - mm/page_alloc.c:split_free_page
```
```
In security/selinux/ss/ebitmap.c (ffffffff815d3a7f)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff816e763f)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In lib/math/int_sqrt.c (ffffffff816ee99b)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - lib/math/int_sqrt.c:int_sqrt
```
```
In lib/pldmfw/pldmfw.c (0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff8194fb84)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81964970)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_pgsize
  - drivers/iommu/iommu.c:iommu_pgsize
```
```
In drivers/iommu/dma-iommu.c (ffffffff8196bf79)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81a7df80)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_dirty_pages
```
```
In net/ipv4/fib_trie.c (ffffffff81d3e6b0)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff81d8ed00)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_get_saddr_eval
```
```
In net/ipv6/ip6_fib.c (ffffffff81dad1f1)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
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
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff83e8109d)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
```
```
In mm/page_alloc.c (ffffffff813e72a7)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
Inline callers:
  - mm/page_alloc.c:split_free_page
```
```
In security/selinux/ss/ebitmap.c (ffffffff81681b1f)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff817d71df)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
```
```
In lib/math/int_sqrt.c (ffffffff817df59b)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
Inline callers:
  - lib/math/int_sqrt.c:int_sqrt
```
```
In lib/pldmfw/pldmfw.c (0)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab4cd4)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81acda50)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_pgsize
  - drivers/iommu/iommu.c:iommu_pgsize
```
```
In drivers/iommu/dma-iommu.c (ffffffff81ad6347)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81f07290)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff81f5cce0)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_get_saddr_eval
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7cc49)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
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
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff836a43d5)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b6410)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
```
```
In mm/page_alloc.c (ffffffff8141c3d2)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
Inline callers:
  - mm/page_alloc.c:split_free_page
```
```
In security/selinux/ss/ebitmap.c (ffffffff816b9ce9)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff818162ac)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
```
```
In lib/math/int_sqrt.c (ffffffff8181ed7b)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
Inline callers:
  - lib/math/int_sqrt.c:int_sqrt
```
```
In lib/pldmfw/pldmfw.c (0)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b012d4)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81b1c580)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_pgsize
  - drivers/iommu/iommu.c:iommu_pgsize
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b24adb)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81f66d38)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff81fbc9e8)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_get_saddr_eval
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdce6c)
Location: arch/x86/include/asm/bitops.h:294
Inline: True
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
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/include/asm/bitops.h:293
Inline: True
```
```
In arch/x86/hyperv/hv_apic.c (0)
Location: arch/x86/include/asm/bitops.h:293
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff838d4455)
Location: arch/x86/include/asm/bitops.h:293
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e6d20)
Location: arch/x86/include/asm/bitops.h:293
Inline: True
```
```
In kernel/smp.c (0)
Location: arch/x86/include/asm/bitops.h:293
Inline: True
```
```
In mm/mm_init.c (0)
Location: arch/x86/include/asm/bitops.h:293
Inline: True
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:293
Inline: True
```
```
In mm/page_alloc.c (ffffffff81448e92)
Location: arch/x86/include/asm/bitops.h:293
Inline: True
Inline callers:
  - mm/page_alloc.c:split_free_page
```
```
In security/selinux/ss/ebitmap.c (ffffffff816f6779)
Location: arch/x86/include/asm/bitops.h:293
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff8185b3ec)
Location: arch/x86/include/asm/bitops.h:293
Inline: True
```
```
In lib/math/int_sqrt.c (ffffffff81864cfb)
Location: arch/x86/include/asm/bitops.h:293
Inline: True
Inline callers:
  - lib/math/int_sqrt.c:int_sqrt
```
```
In lib/pldmfw/pldmfw.c (0)
Location: arch/x86/include/asm/bitops.h:293
Inline: True
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b56790)
Location: arch/x86/include/asm/bitops.h:293
Inline: True
```
```
In drivers/iommu/iommu.c (ffffffff81b73b00)
Location: arch/x86/include/asm/bitops.h:293
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_pgsize
  - drivers/iommu/iommu.c:iommu_pgsize
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7b74b)
Location: arch/x86/include/asm/bitops.h:293
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff8202d31c)
Location: arch/x86/include/asm/bitops.h:293
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff82089e08)
Location: arch/x86/include/asm/bitops.h:293
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_get_saddr_eval
```
```
In net/ipv6/ip6_fib.c (ffffffff820aa9cc)
Location: arch/x86/include/asm/bitops.h:293
Inline: True
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
In init/initramfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In arch/arm64/kernel/fpsimd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In arch/arm64/kernel/vdso.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In arch/arm64/kernel/hw_breakpoint.c (ffff8000100a58ec)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - arch/arm64/kernel/hw_breakpoint.c:watchpoint_handler
```
```
In arch/arm64/kernel/suspend.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In arch/arm64/kernel/pci.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In arch/arm64/kernel/armv8_deprecated.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In arch/arm64/mm/context.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In arch/arm64/mm/hugetlbpage.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In arch/arm64/net/bpf_jit_comp.c (ffff8000100b3dfc)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - arch/arm64/net/bpf_jit_comp.c:build_insn
  - arch/arm64/net/bpf_jit_comp.c:build_insn
```
```
In virt/kvm/kvm_main.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In virt/kvm/coalesced_mmio.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In virt/kvm/eventfd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In virt/kvm/vfio.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In virt/kvm/arm/arm.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In virt/kvm/arm/mmu.c (ffff8000100cc19c)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:kvm_arch_mmu_enable_log_dirty_pt_masked
```
```
In arch/arm64/kvm/va_layout.c (ffff8000100cf85c)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - arch/arm64/kvm/va_layout.c:compute_layout
```
```
In arch/arm64/kvm/reset.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-init.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-irqfd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-v4.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-mmio-v3.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-its.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In virt/kvm/arm/vgic/vgic-debug.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In virt/kvm/irqchip.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In arch/arm/xen/p2m.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/firmware/efi/libstub/random.c (ffff800011441094)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/firmware/efi/libstub/random.c:efi_random_alloc
```
```
In kernel/fork.c (ffff800011441bf8)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/resource.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/umh.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/params.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/async.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/ucount.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/groups.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/sched/core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/sched/fair.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/sched/rt.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/sched/cpupri.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/sched/cpudeadline.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/sched/topology.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/sched/autogroup.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/sched/debug.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/sched/cpuacct.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/sched/cpufreq_schedutil.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/power/console.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/power/wakelock.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/irq/generic-chip.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/irq/irqdomain.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/irq/msi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/irq/affinity.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/dma/mapping.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/dma/direct.c (ffff800010194cd4)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/contiguous.c (ffff800010195578)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - kernel/dma/contiguous.c:dma_alloc_contiguous
```
```
In kernel/dma/coherent.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/dma/virt.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/dma/swiotlb.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/dma/remap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/profile.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/time/timekeeping.c (ffff8000101a31d4)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:scale64_check_overflow
  - kernel/time/timekeeping.c:scale64_check_overflow
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In kernel/futex.c (ffff8000114494d8)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/module.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/acct.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/kexec_core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/kexec.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/cgroup/cgroup.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/cgroup/namespace.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/cgroup/pids.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/cgroup/rdma.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/cgroup/cpuset.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/user_namespace.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/audit.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/audit_watch.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/audit_fsnotify.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/audit_tree.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/kprobes.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/debug/kdb/kdb_main.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/relay.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/tracepoint.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/trace/ftrace.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/trace/ring_buffer.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/trace/trace.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/trace/trace_stat.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/trace/trace_printk.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/trace/tracing_map.c (ffff80001022e7c8)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_functions.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/trace/fgraph.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/trace/trace_events.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/trace/trace_syscalls.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/trace/trace_event_perf.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/trace/trace_events_filter.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/trace/trace_events_hist.c (ffff800010244c64)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:parse_map_size
  - kernel/trace/trace_events_hist.c:hist_field_log2
  - kernel/trace/trace_events_hist.c:hist_field_log2
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/trace/trace_probe.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/bpf/core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/bpf/syscall.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/bpf/inode.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/bpf/tnum.c (ffff800010276bb4)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_range
```
```
In kernel/bpf/hashtab.c (ffff800010277804)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/bpf/lpm_trie.c (ffff80001027d658)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/bpf/devmap.c (ffff8000102869dc)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/cpumap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/bpf/stackmap.c (ffff80001028b848)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/cgroup.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/events/core.c (ffff8000102925b8)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/events/ring_buffer.c (ffff8000102a3008)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
```
```
In kernel/events/callchain.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/events/hw_breakpoint.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/events/uprobes.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/padata.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In kernel/jump_label.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In certs/system_keyring.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In certs/blacklist.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/mempool.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/page-writeback.c (ffff8000102ba548)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/readahead.c (ffff8000102befac)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - mm/readahead.c:get_init_ra_size
```
```
In mm/vmscan.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/shmem.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/percpu.c (ffff8000102e413c)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/slab_common.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/list_lru.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/workingset.c (ffff800011455ec8)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/gup.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/memory.c (ffff8000102f3f2c)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/vmalloc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/process_vm_access.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/page_alloc.c (ffff800010312ac0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_batchsize
```
```
In mm/memblock.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/swapfile.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/zswap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/dmapool.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/hugetlb.c (ffff800011459d80)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/sparse.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/sparse-vmemmap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/mmu_notifier.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/ksm.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/slub.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/memory_hotplug.c (ffff80001034daac)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages_range
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/vmpressure.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/memory-failure.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/zpool.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/zbud.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/cma.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/hmm.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In mm/memfd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/read_write.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/super.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/char_dev.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/exec.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/pipe.c (ffff80001038fb24)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/namei.c (ffff800010391d58)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - fs/namei.c:hashlen_string
```
```
In fs/select.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/dcache.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/file.c (ffff8000103b0b24)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/namespace.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/seq_file.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/xattr.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/libfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/splice.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/sync.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/fs_context.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/fsopen.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/block_dev.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/notify/group.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/notify/inotify/inotify_fsnotify.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/aio.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/io_uring.c (ffff800010402e94)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
  - fs/io_uring.c:ring_pages
```
```
In fs/crypto/crypto.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/crypto/fname.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/crypto/hooks.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/crypto/keyring.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/crypto/keysetup_v1.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/verity/enable.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/verity/hash_algs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/verity/open.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/verity/verify.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/verity/signature.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/binfmt_elf.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/mbcache.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/posix_acl.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/coredump.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/fhandle.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/proc/root.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/proc/base.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/proc/generic.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/proc/self.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/proc/thread_self.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/proc/kcore.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/proc/vmcore.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/kernfs/mount.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/kernfs/dir.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/kernfs/file.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/kernfs/symlink.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/sysfs/dir.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/sysfs/mount.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/configfs/inode.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/configfs/dir.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/configfs/symlink.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ext4/dir.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ext4/fsmap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ext4/hash.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ext4/indirect.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ext4/inline.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ext4/mballoc.c (ffff80001048e004)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/mmp.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ext4/resize.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ext4/super.c (ffff8000104bcc50)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/ext4/sysfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/jbd2/journal.c (ffff8000104d67d8)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - fs/jbd2/journal.c:get_slab
  - fs/jbd2/journal.c:jbd2_journal_create_slab
```
```
In fs/squashfs/block.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/squashfs/cache.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/squashfs/dir.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/squashfs/file.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/squashfs/namei.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/squashfs/super.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/squashfs/decompressor.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/squashfs/file_direct.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/squashfs/page_actor.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/squashfs/decompressor_single.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/squashfs/xattr.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/squashfs/lz4_wrapper.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/squashfs/lzo_wrapper.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/squashfs/xz_wrapper.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/squashfs/zlib_wrapper.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/squashfs/zstd_wrapper.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ramfs/inode.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/fat/namei_vfat.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ecryptfs/inode.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ecryptfs/crypto.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ecryptfs/messaging.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/unicode/utf8-core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/fuse/dev.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/fuse/file.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/fuse/inode.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/fuse/acl.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/debugfs/file.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/tracefs/inode.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/pstore/inode.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/pstore/platform.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/efivarfs/inode.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/efivarfs/file.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In fs/efivarfs/super.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In ipc/util.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In ipc/sem.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In ipc/shm.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In ipc/namespace.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/keys/key.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/keys/user_defined.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/keys/big_key.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/commoncap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/security.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/selinux/selinuxfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/selinux/netif.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/selinux/netnode.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/selinux/netport.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/selinux/ibpkey.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/selinux/ss/ebitmap.c (ffff8000105592b4)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/selinux/ss/policydb.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/selinux/ss/services.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/selinux/ss/conditional.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/selinux/xfrm.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/selinux/netlabel.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/smack/smack_access.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/smack/smackfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/tomoyo/audit.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/tomoyo/common.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/tomoyo/condition.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/tomoyo/domain.c (ffff80001057f504)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - security/tomoyo/domain.c:get_order
```
```
In security/tomoyo/memory.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/tomoyo/realpath.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/apparmor/apparmorfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/apparmor/lib.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/apparmor/match.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/apparmor/domain.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/apparmor/policy.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/apparmor/procattr.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/apparmor/lsm.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/apparmor/policy_ns.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/apparmor/label.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/apparmor/mount.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/apparmor/crypto.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/safesetid/securityfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/device_cgroup.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/integrity/digsig.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/integrity/platform_certs/load_uefi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/integrity/platform_certs/keyring_handler.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/integrity/ima/ima_queue.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (ffff8000105afeb4)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/integrity/ima/ima_template.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/integrity/ima/ima_modsig.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/integrity/evm/evm_main.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In security/integrity/evm/evm_secfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/api.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/cipher.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/algapi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/aead.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/ablkcipher.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/blkcipher.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/skcipher.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/ahash.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/shash.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/acompress.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/algboss.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/gf128mul.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/cts.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/xts.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/gcm.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/deflate.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/rng.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/asymmetric_keys/asymmetric_type.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/bio.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/blk-core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/blk-mq.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/blk-stat.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/genhd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/badblocks.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/partitions/check.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/partitions/aix.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/partitions/ldm.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/partitions/efi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/bsg.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/bsg-lib.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/cmdline-parser.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/bio-integrity.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/blk-wbt.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In block/sed-opal.c (ffff8000106258b8)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - block/sed-opal.c:add_token_u64
```
```
In lib/bitmap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/clz_ctz.c (ffff800010633644)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzdi2
```
```
In lib/find_bit.c (ffff8000106337b0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/kfifo.c (ffff800010633c1c)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_alloc
```
```
In lib/rhashtable.c (ffff800010635f50)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
```
```
In lib/once.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/generic-radix-tree.c (ffff800010638440)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
```
```
In lib/string_helpers.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/math/int_sqrt.c (ffff80001063ac34)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - lib/math/int_sqrt.c:int_sqrt
```
```
In lib/assoc_array.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/genalloc.c (ffff800010643f3c)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In lib/zlib_inflate/infutil.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/xz/xz_dec_stream.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/xz/xz_dec_lzma2.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/error-inject.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/dynamic_debug.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/nlattr.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/cpu_rmap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/mpi/mpicoder.c (ffff800010663764)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_read_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_data
```
```
In lib/mpi/mpi-bit.c (ffff80001066391c)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - lib/mpi/mpi-bit.c:mpi_get_nbits
```
```
In lib/mpi/mpih-mul.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/mpi/mpi-pow.c (ffff8000106654dc)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - lib/mpi/mpi-pow.c:mpi_powm
  - lib/mpi/mpi-pow.c:mpi_powm
```
```
In lib/mpi/mpiutil.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/digsig.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/strncpy_from_user.c (ffff800010666c48)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:do_strncpy_from_user
```
```
In lib/strnlen_user.c (ffff800010666fbc)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - lib/strnlen_user.c:do_strnlen_user
```
```
In lib/sg_split.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/irq-al-fic.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/irq-sun4i.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/irq-gic-v2m.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/irq-gic-v3.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-mbi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff8000106745cc)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_create_device
  - drivers/irqchip/irq-gic-v3-its.c:its_free_pending_table
  - drivers/irqchip/irq-gic-v3-its.c:its_allocate_pending_table
  - drivers/irqchip/irq-gic-v3-its.c:its_parse_indirect_baser
  - drivers/irqchip/irq-gic-v3-its.c:its_free_prop_table
  - drivers/irqchip/irq-gic-v3-its.c:its_allocate_prop_table
```
```
In drivers/irqchip/irq-gic-v3-its-platform-msi.c (ffff8000106750f0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-platform-msi.c:its_pmsi_prepare
```
```
In drivers/irqchip/irq-gic-v3-its-pci-msi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c (ffff8000106758cc)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its-fsl-mc-msi.c:its_fsl_mc_msi_prepare
```
```
In drivers/irqchip/irq-partition-percpu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/irq-bcm7038-l1.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/irq-brcmstb-l2.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/irq-mtk-sysirq.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/irq-mtk-cirq.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/irq-imx-gpcv2.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/irq-mvebu-icu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/irq-mvebu-odmi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/irq-sni-exiu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/irq-meson-gpio.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/qcom-pdc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/irq-ti-sci-inta.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/bus/fsl-mc/fsl-mc-bus.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/phy/phy-core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pinctrl/core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pinctrl/devicetree.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pinctrl/pinconf-generic.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pinctrl/pinctrl-ocelot.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pinctrl/bcm/pinctrl-bcm2835.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pinctrl/berlin/berlin.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pinctrl/freescale/pinctrl-imx.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pinctrl/mvebu/pinctrl-mvebu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pinctrl/qcom/pinctrl-msm.c (ffff8000106ae8c4)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinmux_set_mux
```
```
In drivers/pinctrl/sunxi/pinctrl-sunxi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/gpio/gpiolib-devprop.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/gpio/gpiolib-acpi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/gpio/gpio-stmpe.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pwm/core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pwm/sysfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/bus.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/probe.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/pci.c (ffff8000106e8390)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/setup-bus.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/slot.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/pcie/portdrv_core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/hotplug/pciehp_core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/hotplug/acpiphp_glue.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/msi.c (ffff8000107139c8)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/iov.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/ecam.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffff80001071bd48)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_set_msi
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffff80001071c5f8)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffff80001071cf1c)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:__pci_epc_mem_init
```
```
In drivers/pci/controller/pcie-cadence.c (ffff80001071cff8)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffff80001071e0a4)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
```
```
In drivers/pci/controller/pcie-rcar.c (ffff800010721320)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_inbound_ranges
  - drivers/pci/controller/pcie-rcar.c:rcar_pcie_setup_window
```
```
In drivers/pci/controller/pcie-xilinx-nwl.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/controller/pci-xgene-msi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pci/controller/pcie-rockchip-ep.c (ffff8000107293e4)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar
  - drivers/pci/controller/pcie-rockchip-ep.c:rockchip_pcie_ep_set_bar
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/rapidio/rio.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/video/backlight/backlight.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/video/fbdev/core/fbmon.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/video/fbdev/core/fbsysfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/video/fbdev/core/modedb.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/video/fbdev/core/fbcvt.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/video/fbdev/core/bitblit.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/video/fbdev/core/softcursor.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_rotate.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_cw.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ud.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ccw.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/video/fbdev/amba-clcd.c (ffff80001075bd74)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
```
```
In drivers/video/fbdev/efifb.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/video/fbdev/simplefb.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/video/of_display_timing.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/char/ipmi/ipmi_dmi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/osl.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/utils.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/nvs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/glue.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/scan.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpi_processor.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/ec.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/dock.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/pci_root.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/pci_link.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/pci_irq.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpi_apd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpi_platform.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/power.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/sysfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/property.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpi_lpat.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpi_watchdog.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/dsfield.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/dsmethod.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/dsobject.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/dspkginit.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/dswstate.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/evregion.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/evrgnini.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/exconfig.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/exfldio.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/exnames.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/exoparg3.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/exstorob.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/hwxface.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/hwpci.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/nsaccess.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/nsinit.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/nsnames.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/nsparse.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/nsutils.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/nsxfeval.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/nsxfname.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/rscreate.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/rsutils.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/tbdata.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/utalloc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/utcopy.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/uteval.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/utids.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/utmutex.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/utobject.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/utosi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpica/utxface.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/pci_mcfg.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/ac.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/button.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/pci_slot.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/processor_idle.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/container.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/thermal.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/hmat/hmat.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/acpi_memhotplug.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/battery.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/apei/apei-base.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/apei/hest.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/apei/erst.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/apei/ghes.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/acpi/arm64/iort.c (ffff8000107b2890)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/acpi/arm64/iort.c:iort_dma_setup
```
```
In drivers/pnp/core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pnp/card.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pnp/driver.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pnp/resource.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pnp/quirks.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pnp/system.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/amba/bus.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/clk-bulk.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/clkdev.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/clk.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/clk-divider.c (ffff8000107c3fb0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/clk/clk-fixed-factor.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/clk-fixed-rate.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/clk-gate.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/clk-mux.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/clk-composite.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/clk-fractional-divider.c (ffff8000107c702c)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/clk-hsdk-pll.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/clk-qoriq.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/clk-xgene.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/bcm/clk-iproc-armpll.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/bcm/clk-iproc-pll.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/bcm/clk-iproc-asiu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/bcm/clk-bcm2835.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/berlin/berlin2-avpll.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/berlin/berlin2-pll.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/berlin/berlin2-div.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/hisilicon/clk.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/hisilicon/clkgate-separated.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/hisilicon/clkdivider-hi6220.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-busy.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-composite-8m.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-cpu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-composite-7ulp.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-divider-gate.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-fixup-div.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-fixup-mux.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-frac-pll.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-gate-exclusive.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-gate2.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-pfd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-pfdv2.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-pllv1.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-pllv2.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-pllv3.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-pllv4.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-sccg-pll.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-pll14xx.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-scu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/imx/clk-lpcg-scu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/mediatek/clk-mtk.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/mediatek/clk-pll.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/mediatek/clk-gate.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/mediatek/clk-apmixed.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/mediatek/clk-cpumux.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/mediatek/reset.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/mediatek/clk-mux.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/mvebu/armada-37xx-periph.c (ffff8000107e92d0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/clk/mvebu/armada-37xx-periph.c:armada_3700_periph_clock_probe
```
```
In drivers/clk/mvebu/cp110-system-controller.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/renesas/r9a06g032-clocks.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/renesas/rcar-gen3-cpg.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/renesas/renesas-cpg-mssr.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/renesas/clk-div6.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/rockchip/clk.c (ffff8000107ec9e0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/clk/rockchip/clk.c:rockchip_fractional_approximation
```
```
In drivers/clk/rockchip/clk-pll.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/rockchip/clk-cpu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/rockchip/clk-half-divider.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/rockchip/clk-inverter.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/rockchip/clk-mmc-phase.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/rockchip/clk-muxgrf.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/rockchip/clk-ddr.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/rockchip/softrst.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/socfpga/clk-pll-s10.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/socfpga/clk-periph-s10.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/socfpga/clk-gate-s10.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/sunxi/clk-factors.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/sunxi/clk-sunxi.c (ffff8000107f203c)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sunxi.c:sun6i_get_ahb1_factors
  - drivers/clk/sunxi/clk-sunxi.c:sun5i_a13_get_ahb_factors
```
```
In drivers/clk/sunxi/clk-a10-hosc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/sunxi/clk-a10-mod1.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/sunxi/clk-a10-pll2.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/sunxi/clk-a10-ve.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/sunxi/clk-a20-gmac.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/sunxi/clk-mod0.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/sunxi/clk-simple-gates.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/sunxi/clk-sun4i-display.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/sunxi/clk-sun4i-pll3.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/sunxi/clk-sun4i-tcon-ch1.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/sunxi/clk-sun8i-bus-gates.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/sunxi/clk-sun8i-mbus.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/sunxi/clk-sun9i-core.c (ffff8000107f3334)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-sun9i-core.c:sun9i_a80_get_apb1_factors
  - drivers/clk/sunxi/clk-sun9i-core.c:sun9i_a80_get_ahb_factors
```
```
In drivers/clk/sunxi/clk-usb.c (ffff80001148e268)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/clk/sunxi/clk-usb.c:sunxi_usb_clk_setup
```
```
In drivers/clk/sunxi/clk-sun9i-cpus.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_common.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_nkmp.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/versatile/clk-sp810.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/zynqmp/pll.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/zynqmp/clk-gate-zynqmp.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/zynqmp/divider.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/zynqmp/clk-mux-zynqmp.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clk/zynqmp/clkc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/dma/dmaengine.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/dma/acpi-dma.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/dma/of-dma.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/dma/amba-pl08x.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/dma/bcm2835-dma.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/dma/mv_xor.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/soc/bcm/brcmstb/common.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/soc/fsl/qbman/bman.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/soc/fsl/qbman/qman.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/soc/imx/soc-imx8.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/soc/amlogic/meson-gx-socinfo.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/soc/amlogic/meson-mx-socinfo.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/soc/qcom/rpmh.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/soc/qcom/smem_state.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/soc/renesas/renesas-soc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/soc/renesas/rcar-sysc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/xen/balloon.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/xen/time.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/xen/events/events_base.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/xen/arm-device.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/xen/sys-hypervisor.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/xen/swiotlb-xen.c (ffff80001083e350)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/xen/swiotlb-xen.c:xen_swiotlb_alloc_coherent
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/regulator/core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/regulator/fixed-helper.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/reset/core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/reset/reset-sunxi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/pty.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/tty_audit.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/vt/consolemap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/vt/vt.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/serial/8250/8250_of.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/serial/amba-pl011.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/serial/imx.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/serial/msm_serial.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/serial/kgdb_nmi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/tty/serdev/core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/char/mem.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/char/hw_random/core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/char/tpm/tpm-chip.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/char/tpm/tpmrm-dev.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/char/tpm/tpm2-space.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/char/tpm/eventlog/tpm1.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/char/tpm/eventlog/acpi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/iommu/iommu.c (ffff8000108c4f48)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/iommu/iommu-sysfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/iommu/dma-iommu.c (ffff8000108ca018)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap
```
```
In drivers/iommu/io-pgtable-arm.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/iommu/iova.c (ffff8000108cdef0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/iommu/iova.c:iova_rcache_get
  - drivers/iommu/iova.c:iova_rcache_insert
  - drivers/iommu/iova.c:alloc_iova
```
```
In drivers/iommu/arm-smmu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d5aa8)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/iommu/qcom_iommu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/iommu/virtio-iommu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/connector/cn_queue.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/lightnvm/core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/component.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/bus.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/class.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/platform.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/cpu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/map.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/devres.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/attribute_container.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/property.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/swnode.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/power/common.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/power/wakeup_stats.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/power/domain.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/power/clock_ops.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/firmware_loader/fallback.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/node.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/memory.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/regmap/regmap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/regmap/regcache-flat.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/regmap/regmap-debugfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/soc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/devcoredump.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/platform-msi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/base/arch_topology.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/block/xen-blkfront.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/misc/sram.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/misc/vexpress-syscfg.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/mfd/twl4030-irq.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/mfd/syscon.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/nvdimm/core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/nvdimm/dimm.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/dax/bus.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/dma-buf/sync_file.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/scsi/scsi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/scsi/hosts.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/scsi/scsicam.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/scsi/scsi_lib.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/scsi/scsi_scan.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/scsi/scsi_logging.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/scsi/sr_ioctl.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/scsi/sr_vendor.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/scsi/sg.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/ata/libata-core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/ata/libata-transport.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/ata/libata-acpi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/ata/libata-zpodd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/ata/libahci_platform.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/spi/spi-mem.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/spi/spi-fsl-spi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/spi/spi-omap2-mcspi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/phy/mdio-boardinfo.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/phy/mdio_device.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/tun.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/ethernet/freescale/fman/fman_muram.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/ethernet/freescale/fman/fman.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/ethernet/freescale/fman/fman_keygen.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/ethernet/freescale/fman/fman_port.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/ethernet/freescale/fman/mac.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/ethernet/freescale/fman/fman_dtsec.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/ethernet/freescale/fman/fman_memac.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/ethernet/freescale/fman/fman_tgec.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/slip/slhc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/core/usb.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/core/hcd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/core/urb.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/core/message.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/core/driver.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/core/config.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/core/file.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/core/buffer.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/core/endpoint.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/core/quirks.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/core/port.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/phy/phy-ulpi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a54684)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/host/xhci.c (ffff800010a74b50)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a79aa8)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/host/xhci-mtk-sch.c (ffff800010a8d888)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/usb/roles/class.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/input/serio/serio.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/input/input.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/input/input-mt.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/input/ff-core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/input/evdev.c (ffff800010a9e260)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/rtc/class.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/rtc/nvmem.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/rtc/rtc-sun6i.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/i2c/i2c-boardinfo.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/i2c/i2c-dev.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/media/cec/cec-core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/media/cec/cec-pin.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/pps/kapi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/ptp/ptp_sysfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/hwmon/hwmon.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/thermal/thermal_sysfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/thermal/thermal_hwmon.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/thermal/of-thermal.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/thermal/power_allocator.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/thermal/cpu_cooling.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/watchdog/watchdog_pretimeout.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/md/md-bitmap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/md/dm-init.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/md/dm-table.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/md/dm-linear.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/md/dm-io.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/md/dm-stats.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/edac/edac_mc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/edac/edac_device.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/edac/edac_mc_sysfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/edac/edac_pci.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/edac/ghes_edac.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/opp/core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/opp/cpu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/opp/of.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/cpufreq/cpufreq_stats.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/cpufreq/cpufreq_userspace.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/cpufreq/cpufreq_ondemand.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/cpufreq/cpufreq_conservative.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/cpufreq/cpufreq_governor.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/cpufreq/cpufreq-dt.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/cpuidle/sysfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/cpuidle/cpuidle-psci.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/mmc/core/bus.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/mmc/core/host.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/mmc/core/sd.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/mmc/core/sd_ops.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/mmc/core/block.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/mmc/core/queue.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/leds/led-triggers.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/firmware/arm_sdei.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/firmware/dmi_scan.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/firmware/dmi-id.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/firmware/memmap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/firmware/raspberrypi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/firmware/qcom_scm-64.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/firmware/arm_scmi/bus.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/firmware/meson/meson_sm.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/firmware/efi/efi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/firmware/efi/vars.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/firmware/efi/memmap.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/firmware/efi/efivars.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/firmware/efi/esrt.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clocksource/sh_cmt.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clocksource/sh_tmu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clocksource/mmio.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clocksource/timer-rockchip.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/clocksource/arm_arch_timer.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/of/base.c (ffff800010b6a860)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/of/base.c:of_populate_phandle_cache
```
```
In drivers/of/device.c (ffff800010b6c88c)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/of/device.c:of_dma_configure
```
```
In drivers/of/platform.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/of/dynamic.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/of/fdt.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/of/irq.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/of/of_reserved_mem.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/of/overlay.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/mailbox/pcc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/mailbox/ti-msgmgr.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/remoteproc/remoteproc_core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/remoteproc/remoteproc_virtio.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/devfreq/governor_userspace.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/extcon/extcon.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/memory/fsl_ifc.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/vme/vme.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/powercap/powercap_sys.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/perf/arm_pmu.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/nvmem/core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/sock.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/scm.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/net_namespace.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/sysctl_net_core.c (ffff800010bc53dc)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/ethtool.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/dev_addr_lists.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/dst.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/neighbour.c (ffff800010be7d64)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_hash_free_rcu
```
```
In net/core/rtnetlink.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/filter.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/sock_reuseport.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/xdp.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/flow_offload.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/net-sysfs.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/skmsg.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/drop_monitor.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/netprio_cgroup.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/lwtunnel.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/sock_map.c (ffff800010c1f944)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/devlink.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffff800010c31028)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
```
In net/sched/sch_generic.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/sched/sch_mq.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/sched/sch_api.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/sched/cls_api.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/sched/act_api.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/sched/sch_fifo.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/sched/ematch.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/netlink/af_netlink.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/bpf/test_run.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/netfilter/nf_log.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/ip_options.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/ip_output.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/ip_sockglue.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/inet_hashtables.c (ffff800010c698a8)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
```
```
In net/ipv4/tcp.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/tcp_input.c (ffff800010c76d3c)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffff800010c91b88)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/udp.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffff800010cb6f9c)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/fib_trie.c (ffff800010cbc2c8)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/metrics.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/nexthop.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/tcp_cubic.c (ffff800010cd2a1c)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/xfrm/xfrm_hash.c (ffff800010ce99bc)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
```
In net/unix/af_unix.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv6/addrconf.c (ffff800010cff3ec)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv6/route.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffff800010d1a098)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv6/calipso.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/packet/af_packet.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/wireless/wext-core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/wireless/wext-priv.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/rfkill/core.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/rfkill/input.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/dcb/dcbnl.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ncsi/ncsi-manage.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/xdp/xdp_umem.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/xdp/xsk_queue.c (ffff800010d816cc)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
```
```
In lib/argv_split.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/decompress_bunzip2.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/decompress_inflate.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/decompress_unlzma.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/decompress_unlzo.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/decompress_unxz.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/idr.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/kobject.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/memcat_p.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/string.c (ffff800010d92d74)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In arch/arm/mm/dma-mapping.c (c031e238)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - arch/arm/mm/dma-mapping.c:arm_iommu_alloc_attrs
```
```
In security/selinux/ss/ebitmap.c (c070db28)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (c07d9b80)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/math/int_sqrt.c (c07e0d6c)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/irqchip/irq-orion.c (c081464c)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/irqchip/irq-orion.c:orion_bridge_irq_handler
  - drivers/irqchip/irq-orion.c:orion_handle_irq
```
```
In drivers/irqchip/irq-rda-intc.c (c03027f4)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - drivers/irqchip/irq-rda-intc.c:rda_handle_irq
```
```
In drivers/iommu/iommu.c (c09bc450)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/iommu/io-pgtable-arm.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In drivers/net/ethernet/freescale/fec_main.c (0)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In sound/core/pcm_lib.c (c0c987ec)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - sound/core/pcm_lib.c:snd_pcm_hw_param_last
```
```
In net/ipv4/fib_trie.c (c0dc7b28)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (c0e073a4)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv6/ip6_fib.c (c0e1fb30)
Location: include/asm-generic/bitops/builtin-__fls.h:11
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
In security/selinux/ss/ebitmap.c (c0000000006b72a4)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (c0000000007d8b48)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In lib/math/int_sqrt.c (c0000000007e1cec)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - lib/math/int_sqrt.c:int_sqrt
```
```
In drivers/iommu/iommu.c (c00000000096b118)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv4/fib_trie.c (c000000000dd5e9c)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (c000000000e28a1c)
Location: include/asm-generic/bitops/builtin-__fls.h:11
Inline: True
```
```
In net/ipv6/ip6_fib.c (c000000000e47f44)
Location: include/asm-generic/bitops/builtin-__fls.h:11
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
In init/initramfs.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In arch/riscv/kernel/vdso.c (ffffffe0000b7526)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - arch/riscv/kernel/vdso.c:get_order
```
```
In arch/riscv/net/bpf_jit_comp.c (ffffffe0000baada)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/fork.c (ffffffe0000042ae)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/fork.c:fork_init
```
```
In kernel/resource.c (ffffffe0000c7a30)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/resource.c:get_order
```
```
In kernel/umh.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/workqueue.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/params.c (ffffffe0000ddcd8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/kthread.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/async.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/ucount.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/kmod.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/groups.c (ffffffe0000e3eda)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/groups.c:get_order
```
```
In kernel/sched/core.c (ffffffe0000ece78)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/sched/core.c:get_order
```
```
In kernel/sched/fair.c (ffffffe0000ee4e4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/sched/fair.c:get_order
```
```
In kernel/sched/rt.c (ffffffe0000f6c66)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/sched/rt.c:get_order
```
```
In kernel/sched/cpupri.c (ffffffe0000ff836)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/sched/cpupri.c:get_order
```
```
In kernel/sched/cpudeadline.c (ffffffe0000ffd22)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/sched/cpudeadline.c:get_order
```
```
In kernel/sched/topology.c (ffffffe0001004e6)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/sched/autogroup.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/sched/debug.c (ffffffe000103cea)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/sched/debug.c:get_order
```
```
In kernel/sched/cpuacct.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/sched/psi.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/power/qos.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/printk/printk.c (ffffffe0000078a4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/printk/printk.c:log_buf_len_update
```
```
In kernel/irq/irqdesc.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/irq/manage.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/irq/generic-chip.c (ffffffe000118c4e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:get_order
```
```
In kernel/irq/irqdomain.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/irq/msi.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/irq/affinity.c (ffffffe00011d556)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/irq/affinity.c:get_order
```
```
In kernel/dma/mapping.c (ffffffe00012603a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_free_attrs
```
```
In kernel/dma/direct.c (ffffffe000126b88)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_get_required_mask
```
```
In kernel/dma/contiguous.c (ffffffe000127238)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/dma/contiguous.c:dma_alloc_contiguous
```
```
In kernel/dma/coherent.c (ffffffe00012749c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/dma/virt.c (ffffffe000127af2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/dma/virt.c:dma_virt_free
  - kernel/dma/virt.c:dma_virt_alloc
```
```
In kernel/dma/swiotlb.c (ffffffe000127c6e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/profile.c (ffffffe0001293ec)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/profile.c:get_order
```
```
In kernel/time/timekeeping.c (ffffffe000130dc2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:timekeeping_advance
  - kernel/time/timekeeping.c:scale64_check_overflow
  - kernel/time/timekeeping.c:scale64_check_overflow
  - kernel/time/timekeeping.c:scale64_check_overflow
  - kernel/time/timekeeping.c:scale64_check_overflow
```
```
In kernel/futex.c (ffffffe00000a942)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/futex.c:futex_init
```
```
In kernel/module.c (ffffffe000142dda)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/acct.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/cgroup/cgroup.c (ffffffe000149dee)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/cgroup/namespace.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/cgroup/legacy_freezer.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/cgroup/pids.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/cgroup/rdma.c (ffffffe000156344)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:get_order
```
```
In kernel/cgroup/cpuset.c (ffffffe000157016)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/user_namespace.c (ffffffe00015b9e4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/user_namespace.c:get_order
```
```
In kernel/audit.c (ffffffe00015e0ae)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/audit.c:get_order
```
```
In kernel/auditfilter.c (ffffffe000160d6a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/audit_watch.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/audit_fsnotify.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/audit_tree.c (ffffffe00016785e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/seccomp.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/relay.c (ffffffe00016ce62)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/taskstats.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/tracepoint.c (ffffffe00016f382)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffe000170dea)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/trace/ring_buffer.c (ffffffe000176d4e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:get_order
```
```
In kernel/trace/trace.c (ffffffe00017d85c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/trace/trace_stat.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/trace/trace_printk.c (ffffffe0001872ee)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_printk.c:get_order
```
```
In kernel/trace/trace_functions.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/trace/trace_functions_graph.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/trace/blktrace.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/trace/fgraph.c (ffffffe00018ef82)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:get_order
```
```
In kernel/trace/trace_events.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/trace/trace_syscalls.c (ffffffe000193b3a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:get_order
```
```
In kernel/trace/trace_events_filter.c (ffffffe000194afa)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/trace/trace_events_trigger.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/bpf/core.c (ffffffe00019b438)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/bpf/syscall.c (ffffffe00019db68)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/bpf/verifier.c (ffffffe0001a278e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/bpf/inode.c (ffffffe0001adb48)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/bpf/inode.c:get_order
```
```
In kernel/bpf/tnum.c (ffffffe0001aee98)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/bpf/tnum.c:tnum_range
```
```
In kernel/bpf/hashtab.c (ffffffe0001b0308)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/arraymap.c (ffffffe0001b3174)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
```
In kernel/bpf/lpm_trie.c (ffffffe0001b5040)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/bpf/btf.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/bpf/devmap.c (ffffffe0001bbe78)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_init_map
```
```
In kernel/bpf/cpumap.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/bpf/xskmap.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/bpf/offload.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/bpf/stackmap.c (ffffffe0001bf444)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
```
In kernel/bpf/cgroup.c (ffffffe0001c1182)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In kernel/events/core.c (ffffffe0001c334c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/events/core.c:perf_calculate_period
  - kernel/events/core.c:perf_calculate_period
  - kernel/events/core.c:perf_calculate_period
```
```
In kernel/events/ring_buffer.c (ffffffe0001d18b6)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_alloc
  - kernel/events/ring_buffer.c:get_order
```
```
In kernel/events/callchain.c (ffffffe0001d1bb2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_order
```
```
In kernel/padata.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In certs/system_keyring.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In certs/blacklist.c (ffffffe0001d3a80)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - certs/blacklist.c:get_order
```
```
In mm/mempool.c (ffffffe0001da198)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In mm/page-writeback.c (ffffffe0001de3cc)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - mm/page-writeback.c:wb_min_pause
  - mm/page-writeback.c:wb_min_pause
```
```
In mm/readahead.c (ffffffe0001e129e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - mm/readahead.c:get_init_ra_size
```
```
In mm/vmscan.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In mm/shmem.c (ffffffe0001ed806)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In mm/vmstat.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In mm/percpu.c (ffffffe0001fa826)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
  - mm/percpu.c:get_order
```
```
In mm/slab_common.c (ffffffe0001fa9e8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - mm/slab_common.c:get_order
```
```
In mm/list_lru.c (ffffffe000202bae)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - mm/list_lru.c:get_order
```
```
In mm/workingset.c (ffffffe000014e32)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - mm/workingset.c:workingset_init
```
```
In mm/gup.c (ffffffe00020436a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - mm/gup.c:get_order
```
```
In mm/memory.c (ffffffe000205d3a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In mm/vmalloc.c (ffffffe00021556e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In mm/process_vm_access.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In mm/page_alloc.c (ffffffe0000169aa)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - mm/page_alloc.c:zone_batchsize
  - mm/page_alloc.c:alloc_pages_exact
```
```
In mm/memblock.c (ffffffe000220442)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - mm/memblock.c:get_order
```
```
In mm/swapfile.c (ffffffe000228b40)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - mm/swapfile.c:get_order
```
```
In mm/zswap.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In mm/dmapool.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In mm/hugetlb.c (ffffffe00001815a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
```
```
In mm/sparse-vmemmap.c (ffffffe0002324ae)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - mm/sparse-vmemmap.c:get_order
```
```
In mm/mmu_notifier.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In mm/slub.c (ffffffe0002388c0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - mm/slub.c:alloc_loc_track
```
```
In mm/memcontrol.c (ffffffe00024199a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In mm/vmpressure.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In mm/hugetlb_cgroup.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In mm/zpool.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In mm/zbud.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In mm/zsmalloc.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In mm/cma.c (ffffffe00024f50c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - mm/cma.c:get_order
```
```
In mm/hmm.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In mm/memfd.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/read_write.c (ffffffe000255110)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/read_write.c:get_order
```
```
In fs/super.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/char_dev.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/exec.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/pipe.c (ffffffe00025f98a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/namei.c (ffffffe00026163a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/select.c (ffffffe00026a816)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/select.c:get_order
```
```
In fs/dcache.c (ffffffe00026c204)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/dcache.c:get_order
```
```
In fs/file.c (ffffffe000274f42)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/file.c:alloc_fdtable
```
```
In fs/namespace.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/seq_file.c (ffffffe00027dc80)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/xattr.c (ffffffe00027edfa)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/xattr.c:get_order
```
```
In fs/libfs.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/splice.c (ffffffe00028a520)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/splice.c:get_order
```
```
In fs/sync.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/fs_context.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/fsopen.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/block_dev.c (ffffffe0002971c6)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/notify/group.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/notify/inotify/inotify_fsnotify.c (ffffffe00029fb42)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_fsnotify.c:get_order
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffe0002a0d78)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:get_order
```
```
In fs/eventpoll.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/signalfd.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/timerfd.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/eventfd.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/userfaultfd.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/aio.c (ffffffe0002a9bd8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/io_uring.c (ffffffe0002b063e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/io_uring.c:io_uring_create
  - fs/io_uring.c:ring_pages
  - fs/io_uring.c:ring_pages
```
```
In fs/crypto/crypto.c (ffffffe0002b48ac)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/crypto/crypto.c:get_order
```
```
In fs/crypto/fname.c (ffffffe0002b529e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/crypto/hooks.c (ffffffe0002b5e0e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/crypto/hooks.c:get_order
```
```
In fs/crypto/keyring.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b8170)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/verity/enable.c (ffffffe0002b93d2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/verity/hash_algs.c (ffffffe0002b9cca)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/verity/open.c (ffffffe0002ba45a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/verity/open.c:get_order
```
```
In fs/verity/verify.c (ffffffe0002bac70)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/verity/verify.c:get_order
```
```
In fs/verity/signature.c (ffffffe0002bb49e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/verity/signature.c:get_order
```
```
In fs/binfmt_elf.c (ffffffe0002c07e2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/binfmt_flat.c (ffffffe0002c2834)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/binfmt_flat.c:get_order
```
```
In fs/mbcache.c (ffffffe0002c3ff4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/posix_acl.c (ffffffe0002c4a8c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/posix_acl.c:get_order
```
```
In fs/coredump.c (ffffffe0002c5cc6)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/coredump.c:get_order
```
```
In fs/fhandle.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/iomap/direct-io.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffe0002d242c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:get_order
```
```
In fs/proc/root.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/proc/base.c (ffffffe0002d4dca)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/proc/base.c:get_order
```
```
In fs/proc/generic.c (ffffffe0002d9754)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/proc/generic.c:get_order
```
```
In fs/proc/self.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/proc/thread_self.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/proc/proc_sysctl.c (ffffffe0002df256)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/proc/kcore.c (ffffffe0002e23c4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/kernfs/mount.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/kernfs/dir.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/kernfs/file.c (ffffffe0002e6cc2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/kernfs/symlink.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/sysfs/dir.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/sysfs/mount.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/configfs/inode.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/configfs/file.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/configfs/dir.c (ffffffe0002eaa64)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/configfs/symlink.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/devpts/inode.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/dcookies.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/ext4/block_validity.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/ext4/dir.c (ffffffe0002f13ac)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/ext4/extents.c (ffffffe0002f29ea)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/ext4/extents.c:get_order
```
```
In fs/ext4/fsmap.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/ext4/hash.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/ext4/indirect.c (ffffffe00030319e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_calc_metadata_amount
```
```
In fs/ext4/inline.c (ffffffe0003040bc)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/ext4/mballoc.c (ffffffe000313c66)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_groupinfo_create_slab
  - fs/ext4/mballoc.c:ext4_mb_alloc_groupinfo
```
```
In fs/ext4/mmp.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/ext4/resize.c (ffffffe000327040)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/ext4/super.c (ffffffe000338956)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_alloc_flex_bg_array
```
```
In fs/ext4/sysfs.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/ext4/xattr.c (ffffffe00033d4b4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/ext4/acl.c (ffffffe000341584)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/ext4/acl.c:get_order
```
```
In fs/jbd2/revoke.c (ffffffe000348f7e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:get_order
```
```
In fs/jbd2/journal.c (ffffffe00034b3e0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/squashfs/block.c (ffffffe00034e972)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/squashfs/block.c:get_order
```
```
In fs/squashfs/cache.c (ffffffe00034ee74)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/squashfs/dir.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/squashfs/file.c (ffffffe0003500ba)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/squashfs/file.c:get_order
```
```
In fs/squashfs/namei.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/squashfs/super.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/squashfs/decompressor.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/squashfs/file_direct.c (ffffffe0003529b8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/squashfs/file_direct.c:get_order
```
```
In fs/squashfs/page_actor.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/squashfs/decompressor_single.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/squashfs/xattr.c (ffffffe00035328e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/squashfs/xattr.c:get_order
```
```
In fs/squashfs/lz4_wrapper.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/squashfs/lzo_wrapper.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/squashfs/xz_wrapper.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/squashfs/zlib_wrapper.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/squashfs/zstd_wrapper.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/ramfs/inode.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/hugetlbfs/inode.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/fat/inode.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffe00035ffe8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:get_order
```
```
In fs/ecryptfs/inode.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/ecryptfs/mmap.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffe0003658d8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/ecryptfs/keystore.c (ffffffe000367e96)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/ecryptfs/messaging.c (ffffffe00036be26)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/ecryptfs/miscdev.c (ffffffe00036be7c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/ecryptfs/miscdev.c:get_order
```
```
In fs/unicode/utf8-core.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/fuse/dev.c (ffffffe00036ed78)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - fs/fuse/dev.c:get_order
```
```
In fs/fuse/file.c (ffffffe0003759c0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/fuse/inode.c (ffffffe00037c052)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/fuse/acl.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/debugfs/inode.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/debugfs/file.c (ffffffe000381fda)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/tracefs/inode.c (ffffffe0003825e2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/pstore/inode.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In fs/pstore/platform.c (ffffffe000383b98)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In ipc/util.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In ipc/msgutil.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In ipc/sem.c (ffffffe0003876d4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - ipc/sem.c:get_order
```
```
In ipc/shm.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In ipc/mqueue.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In ipc/namespace.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/keys/key.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/keys/keyring.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/keys/keyctl.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/keys/request_key_auth.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/keys/user_defined.c (ffffffe000396334)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/keys/user_defined.c:get_order
```
```
In security/keys/dh.c (ffffffe000397068)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/keys/keyctl_pkey.c (ffffffe000397812)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/keys/keyctl_pkey.c:get_order
```
```
In security/keys/big_key.c (ffffffe000397f8c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/keys/trusted.c (ffffffe00039861a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039a6f8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/commoncap.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/security.c (ffffffe00039e416)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/selinux/avc.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/selinux/hooks.c (ffffffe0003a6eba)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/selinux/selinuxfs.c (ffffffe0003acbe6)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:get_order
```
```
In security/selinux/netif.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/selinux/netnode.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/selinux/netport.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/selinux/ibpkey.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/selinux/ss/ebitmap.c (ffffffe0003b033e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In security/selinux/ss/hashtab.c (ffffffe0003b0ef8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/selinux/ss/sidtab.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/selinux/ss/policydb.c (ffffffe0003b4700)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/selinux/ss/services.c (ffffffe0003b8c02)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/selinux/ss/conditional.c (ffffffe0003be2e8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/selinux/xfrm.c (ffffffe0003c02fc)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/selinux/xfrm.c:get_order
```
```
In security/selinux/netlabel.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/smack/smack_lsm.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/smack/smack_access.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/smack/smackfs.c (ffffffe0003c7eda)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/tomoyo/audit.c (ffffffe0003ca400)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/tomoyo/common.c (ffffffe0003cb894)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/tomoyo/condition.c (ffffffe0003cee70)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/tomoyo/condition.c:get_order
```
```
In security/tomoyo/domain.c (ffffffe0003d034e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/tomoyo/domain.c:get_order
```
```
In security/tomoyo/memory.c (ffffffe0003d408c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/tomoyo/memory.c:get_order
```
```
In security/tomoyo/realpath.c (ffffffe0003d59d2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffe0003d847e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:get_order
```
```
In security/apparmor/lib.c (ffffffe0003dd168)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/apparmor/lib.c:get_order
```
```
In security/apparmor/match.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/apparmor/domain.c (ffffffe0003df0aa)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/apparmor/domain.c:get_order
```
```
In security/apparmor/policy.c (ffffffe0003e2d26)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/apparmor/policy_unpack.c (ffffffe0003e4e64)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/apparmor/procattr.c (ffffffe0003e66b2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/apparmor/procattr.c:get_order
```
```
In security/apparmor/lsm.c (ffffffe0003e6db8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/apparmor/lsm.c:get_order
```
```
In security/apparmor/policy_ns.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/apparmor/label.c (ffffffe0003ebf7c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/apparmor/mount.c (ffffffe0003ef3ce)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/apparmor/mount.c:get_order
```
```
In security/apparmor/crypto.c (ffffffe0003f2de6)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/yama/yama_lsm.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/safesetid/securityfs.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/device_cgroup.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/integrity/digsig.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/integrity/ima/ima_queue.c (ffffffe0003f6374)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:get_order
```
```
In security/integrity/ima/ima_crypto.c (ffffffe0003f7bf4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:param_set_bufsize
```
```
In security/integrity/ima/ima_api.c (ffffffe0003f813e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:get_order
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/integrity/ima/ima_template.c (ffffffe0003fa0ba)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/integrity/ima/ima_template_lib.c (ffffffe0003fa88c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/integrity/ima/ima_template_lib.c:get_order
```
```
In security/integrity/ima/ima_modsig.c (ffffffe0003fbe2a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/integrity/ima/ima_modsig.c:get_order
```
```
In security/integrity/evm/evm_main.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (ffffffe0003fc946)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:get_order
```
```
In security/integrity/evm/evm_secfs.c (ffffffe0003fd28a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:get_order
```
```
In crypto/api.c (ffffffe0003fd7d6)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - crypto/api.c:get_order
```
```
In crypto/cipher.c (ffffffe0003fe43a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - crypto/cipher.c:get_order
```
```
In crypto/algapi.c (ffffffe0003ff082)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - crypto/algapi.c:get_order
```
```
In crypto/aead.c (ffffffe0004016a2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In crypto/ablkcipher.c (ffffffe000401ce2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In crypto/blkcipher.c (ffffffe000402646)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In crypto/skcipher.c (ffffffe000403d2e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In crypto/ahash.c (ffffffe00040585a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In crypto/shash.c (ffffffe000405e86)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - crypto/shash.c:get_order
```
```
In crypto/rsa-pkcs1pad.c (ffffffe0004082dc)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In crypto/acompress.c (ffffffe000408df0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - crypto/acompress.c:get_order
```
```
In crypto/algboss.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In crypto/gf128mul.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In crypto/cts.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In crypto/xts.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In crypto/ctr.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In crypto/gcm.c (ffffffe00040fdda)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - crypto/gcm.c:get_order
```
```
In crypto/deflate.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In crypto/rng.c (ffffffe000414eb8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - crypto/rng.c:get_order
```
```
In crypto/drbg.c (ffffffe000415dd6)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (ffffffe0004181e4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:get_order
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffe000418780)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:get_order
```
```
In crypto/asymmetric_keys/public_key.c (ffffffe000419972)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In crypto/asymmetric_keys/x509_cert_parser.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffe00041b12e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffe00041c2a0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffe00041cc5a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In block/bio.c (ffffffe00041d920)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - block/bio.c:get_order
```
```
In block/blk-core.c (ffffffe000422166)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - block/blk-core.c:get_order
```
```
In block/blk-mq.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In block/blk-stat.c (ffffffe000432b30)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - block/blk-stat.c:get_order
```
```
In block/genhd.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In block/partition-generic.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In block/badblocks.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In block/partitions/check.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In block/partitions/aix.c (ffffffe00043ba50)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In block/partitions/ldm.c (ffffffe00043c814)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - block/partitions/ldm.c:get_order
```
```
In block/partitions/efi.c (ffffffe000440f3a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In block/scsi_ioctl.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In block/bsg.c (ffffffe0004430da)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - block/bsg.c:get_order
```
```
In block/bsg-lib.c (ffffffe000443d64)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - block/bsg-lib.c:get_order
```
```
In block/blk-cgroup.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In block/blk-iocost.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In block/cmdline-parser.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In block/bio-integrity.c (ffffffe00044fe70)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In block/blk-zoned.c (ffffffe000452572)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
  - block/blk-zoned.c:blkdev_report_zones
  - block/blk-zoned.c:blkdev_nr_zones
```
```
In block/blk-wbt.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In block/sed-opal.c (ffffffe000456b04)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - block/sed-opal.c:add_token_u64
```
```
In lib/bitmap.c (ffffffe00045b936)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/bitmap.c:get_order
```
```
In lib/scatterlist.c (ffffffe00045c4ca)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/scatterlist.c:get_order
```
```
In lib/clz_ctz.c (ffffffe0004615d0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/clz_ctz.c:__clzdi2
```
```
In lib/find_bit.c (ffffffe0004617aa)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In lib/kfifo.c (ffffffe000461bf6)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
  - lib/kfifo.c:__kfifo_alloc
  - lib/kfifo.c:get_order
```
```
In lib/rhashtable.c (ffffffe000463e5a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rht_deferred_worker
```
```
In lib/once.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In lib/generic-radix-tree.c (ffffffe0004654fc)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
```
```
In lib/string_helpers.c (ffffffe000465c74)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In lib/math/int_sqrt.c (ffffffe000467172)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/math/int_sqrt.c:int_sqrt
```
```
In lib/assoc_array.c (ffffffe00046d5f4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In lib/genalloc.c (ffffffe000470d1c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_first_fit_order_align
```
```
In lib/zlib_inflate/infutil.c (ffffffe000472baa)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/zlib_inflate/infutil.c:get_order
```
```
In lib/xz/xz_dec_stream.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In lib/xz/xz_dec_lzma2.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In lib/dynamic_debug.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In lib/nlattr.c (ffffffe00048e556)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/nlattr.c:get_order
```
```
In lib/cpu_rmap.c (ffffffe00048ee9e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/cpu_rmap.c:get_order
```
```
In lib/mpi/mpicoder.c (ffffffe00048fa74)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_data
  - lib/mpi/mpicoder.c:get_order
```
```
In lib/mpi/mpi-bit.c (ffffffe00048ffca)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/mpi/mpi-bit.c:mpi_get_nbits
```
```
In lib/mpi/mpih-mul.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In lib/mpi/mpi-pow.c (ffffffe000491622)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/mpi/mpi-pow.c:mpi_powm
  - lib/mpi/mpi-pow.c:mpi_powm
```
```
In lib/mpi/mpiutil.c (ffffffe000491bf2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:get_order
```
```
In lib/digsig.c (ffffffe000492558)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/digsig.c:get_order
```
```
In lib/strncpy_from_user.c (ffffffe000492b64)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/strncpy_from_user.c:strncpy_from_user
```
```
In lib/strnlen_user.c (ffffffe000492c76)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/strnlen_user.c:strnlen_user
```
```
In drivers/irqchip/irq-al-fic.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/phy/phy-core.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pinctrl/core.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pinctrl/devicetree.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pinctrl/pinconf-generic.c (ffffffe00049cc2c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/pinctrl/pinconf-generic.c:get_order
```
```
In drivers/pinctrl/pinctrl-ocelot.c (ffffffe0004a3588)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-ocelot.c:get_order
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a6362)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/gpio/gpiolib-devprop.c (ffffffe0004aaf2c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-devprop.c:get_order
```
```
In drivers/gpio/gpiolib-sysfs.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/gpio/gpio-stmpe.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pwm/core.c (ffffffe0004b1124)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/pwm/core.c:get_order
```
```
In drivers/pwm/sysfs.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pwm/pwm-sifive.c (ffffffe0004b2c88)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/pwm/pwm-sifive.c:pwm_sifive_update_clock
```
```
In drivers/pci/bus.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/probe.c (ffffffe0004b5478)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/pci/probe.c:get_order
```
```
In drivers/pci/pci.c (ffffffe0004bb778)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/pci-driver.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/pci-sysfs.c (ffffffe0004c2854)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:consistent_dma_mask_bits_show
  - drivers/pci/pci-sysfs.c:dma_mask_bits_show
```
```
In drivers/pci/vpd.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/setup-bus.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/slot.c (ffffffe0004c93e0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/pcie/portdrv_core.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/pcie/aspm.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/pcie/aer.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/pcie/pme.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/hotplug/pciehp_core.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/msi.c (ffffffe0004ddcb8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/pci/msi.c:msi_setup_entry
  - drivers/pci/msi.c:msi_setup_entry
```
```
In drivers/pci/iov.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/ecam.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffe0004e2748)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__order_base_2
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffe0004e32a8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_alloc_space
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffe0004e3b90)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_free_addr
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_mem_alloc_addr
  - drivers/pci/endpoint/pci-epc-mem.c:__pci_epc_mem_init
  - drivers/pci/endpoint/pci-epc-mem.c:get_order
```
```
In drivers/pci/controller/pcie-cadence.c (ffffffe0004e3c58)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
  - drivers/pci/controller/pcie-cadence.c:cdns_pcie_set_outbound_region
```
```
In drivers/pci/controller/pcie-cadence-ep.c (ffffffe0004e51c8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
  - drivers/pci/controller/pcie-cadence-ep.c:cdns_pcie_ep_set_bar
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffe0004e861a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/rapidio/rio.c (ffffffe0004eb926)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffe0004f4a84)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffe0004f6658)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/video/fbdev/core/fbcmap.c (ffffffe0004f71aa)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcmap.c:get_order
```
```
In drivers/video/fbdev/core/fbsysfs.c (ffffffe0004f78da)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbsysfs.c:get_order
```
```
In drivers/video/fbdev/core/modedb.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/video/fbdev/core/fbcvt.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004fcf92)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/video/fbdev/core/bitblit.c (ffffffe0005002d8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/video/fbdev/core/bitblit.c:get_order
```
```
In drivers/video/fbdev/core/softcursor.c (ffffffe000500cbe)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/video/fbdev/core/softcursor.c:get_order
```
```
In drivers/video/fbdev/core/fbcon_rotate.c (ffffffe0005013ac)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon_rotate.c:get_order
```
```
In drivers/video/fbdev/core/fbcon_cw.c (ffffffe000501a50)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon_cw.c:get_order
```
```
In drivers/video/fbdev/core/fbcon_ud.c (ffffffe0005027a6)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon_ud.c:get_order
```
```
In drivers/video/fbdev/core/fbcon_ccw.c (ffffffe0005035d0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon_ccw.c:get_order
```
```
In drivers/video/fbdev/simplefb.c (ffffffe000507cb6)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/video/of_display_timing.c (ffffffe000508b12)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/clk/clk-bulk.c (ffffffe00050975c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/clk/clk-bulk.c:get_order
```
```
In drivers/clk/clkdev.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/clk/clk.c (ffffffe00050c0f8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/clk/clk-divider.c (ffffffe000511c1e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
  - drivers/clk/clk-divider.c:_next_div
```
```
In drivers/clk/clk-fixed-factor.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/clk/clk-fixed-rate.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/clk/clk-gate.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/clk/clk-mux.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/clk/clk-composite.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/clk/clk-fractional-divider.c (ffffffe0005140be)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/clk/clk-gpio.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/clk/clk-hsdk-pll.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/clk/analogbits/wrpll-cln28hpc.c (ffffffe000515300)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/clk/analogbits/wrpll-cln28hpc.c:wrpll_configure_for_rate
```
```
In drivers/dma/dmaengine.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/dma/of-dma.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffe00051852c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:get_order
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffe00051e79c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/regulator/core.c (ffffffe0005227b8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/regulator/fixed-helper.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/reset/core.c (ffffffe00052bbb2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/reset/core.c:get_order
```
```
In drivers/tty/tty_io.c (ffffffe00052d96c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/tty/tty_ldisc.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/tty/tty_buffer.c (ffffffe0005360c6)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/tty/tty_buffer.c:get_order
```
```
In drivers/tty/pty.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/tty/tty_audit.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/tty/sysrq.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/tty/vt/vc_screen.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/tty/vt/selection.c (ffffffe00053d844)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:get_order
```
```
In drivers/tty/vt/keyboard.c (ffffffe00053e6d6)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:get_order
```
```
In drivers/tty/vt/consolemap.c (ffffffe000541eac)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffe0005457e8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/tty/hvc/hvc_console.c (ffffffe00054a376)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:get_order
```
```
In drivers/tty/serial/serial_core.c (ffffffe00054b984)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:get_order
```
```
In drivers/tty/serial/8250/8250_core.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/tty/serial/8250/8250_port.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffe000557d6a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:get_order
```
```
In drivers/tty/serial/8250/8250_of.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/tty/serdev/core.c (ffffffe00055ee64)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:get_order
```
```
In drivers/char/mem.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/char/random.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/char/virtio_console.c (ffffffe000564b3c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:get_order
```
```
In drivers/char/hw_random/core.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/char/tpm/tpm-chip.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/char/tpm/tpm-dev.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffe000569ff4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:get_order
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056b6f4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:get_order
```
```
In drivers/char/tpm/tpmrm-dev.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/char/tpm/tpm2-space.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/char/tpm/eventlog/tpm1.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/connector/cn_queue.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/lightnvm/core.c (ffffffe0005753c0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/component.c (ffffffe000577344)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/core.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/bus.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/class.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/platform.c (ffffffe00058040e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/base/platform.c:get_order
```
```
In drivers/base/cpu.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/map.c (ffffffe000581b0e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/devres.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/attribute_container.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/property.c (ffffffe00058490e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/base/property.c:get_order
```
```
In drivers/base/cacheinfo.c (ffffffe00058531a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/base/cacheinfo.c:get_order
```
```
In drivers/base/swnode.c (ffffffe000586ef8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/power/common.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/power/qos.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/power/wakeirq.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/power/domain.c (ffffffe00058ebf2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/power/clock_ops.c (ffffffe000590b7e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/firmware_loader/main.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/firmware_loader/fallback.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/regmap/regmap.c (ffffffe000593994)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:get_order
```
```
In drivers/base/regmap/regcache.c (ffffffe0005987d6)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/base/regmap/regcache.c:get_order
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffe000599b9e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/regmap/regcache-flat.c (ffffffe00059a23e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-flat.c:get_order
```
```
In drivers/base/regmap/regmap-debugfs.c (ffffffe00059a726)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/regmap/regmap-mmio.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/regmap/regmap-irq.c (ffffffe00059ce2e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/devcoredump.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/platform-msi.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/base/arch_topology.c (ffffffe00059f2fe)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:get_order
```
```
In drivers/block/loop.c (ffffffe0005a0818)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/misc/sram.c (ffffffe0005a295a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/misc/sram.c:get_order
```
```
In drivers/mfd/wm831x-auxadc.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/mfd/twl4030-irq.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/mfd/mfd-core.c (ffffffe0005b3a74)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/mfd/mfd-core.c:get_order
```
```
In drivers/mfd/ezx-pcap.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/mfd/aat2870-core.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/mfd/syscon.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/nvdimm/core.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/nvdimm/bus.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/nvdimm/dimm_devs.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/nvdimm/dimm.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/nvdimm/region_devs.c (ffffffe0005c47fe)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:get_order
```
```
In drivers/nvdimm/namespace_devs.c (ffffffe0005c8c76)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/nvdimm/badrange.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/nvdimm/btt_devs.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/dax/bus.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/dma-buf/dma-buf.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/dma-buf/dma-fence.c (ffffffe0005d2cf0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:get_order
```
```
In drivers/dma-buf/dma-fence-array.c (ffffffe0005d3e6c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-array.c:get_order
```
```
In drivers/dma-buf/dma-resv.c (ffffffe0005d4982)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:get_order
```
```
In drivers/dma-buf/sync_file.c (ffffffe0005d5954)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/dma-buf/sw_sync.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/dma-buf/udmabuf.c (ffffffe0005d71f8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/scsi/scsi.c (ffffffe0005d7914)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:get_order
```
```
In drivers/scsi/hosts.c (ffffffe0005d9088)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:get_order
```
```
In drivers/scsi/scsicam.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffe0005dab4e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:get_order
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005df262)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffe0005e1b3a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/scsi/scsi_devinfo.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/scsi/scsi_logging.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/scsi/sd.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/scsi/sr_ioctl.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/scsi/sr_vendor.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/scsi/sg.c (ffffffe0005f457c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/ata/libata-core.c (ffffffe0005f9ae2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffe0005ffb20)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/ata/libata-transport.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/ata/libata-pmp.c (ffffffe00060fe60)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/ata/libata-pmp.c:get_order
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffe000611eb0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/gpu/vga/vgaarb.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/spi/spi.c (ffffffe000616b78)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/spi/spi-mem.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/spi/spi-fsl-spi.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/net/phy/mdio-boardinfo.c (ffffffe00061cf5c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/net/phy/mdio-boardinfo.c:get_order
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (ffffffe000622b8a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:get_order
```
```
In drivers/net/phy/mdio_device.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/net/phy/sfp-bus.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/net/phy/fixed_phy.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/net/tun.c (ffffffe0006259f0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/net/tun.c:get_order
```
```
In drivers/net/ppp/ppp_generic.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/net/slip/slhc.c (ffffffe00062f94c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/net/slip/slhc.c:get_order
```
```
In drivers/cdrom/cdrom.c (ffffffe000633056)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/usb/core/usb.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/usb/core/hub.c (ffffffe000638f14)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/usb/core/hcd.c (ffffffe00063ffc6)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/usb/core/urb.c (ffffffe000643282)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:get_order
```
```
In drivers/usb/core/message.c (ffffffe000645472)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/usb/core/driver.c (ffffffe000646ebe)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:get_order
```
```
In drivers/usb/core/config.c (ffffffe00064988e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/usb/core/file.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/usb/core/buffer.c (ffffffe00064ad88)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:get_order
```
```
In drivers/usb/core/endpoint.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffe00064e23c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/usb/core/quirks.c (ffffffe00065162e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/usb/core/quirks.c:get_order
```
```
In drivers/usb/core/port.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/usb/dwc2/hcd.c (ffffffe00065c0f2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/usb/dwc2/hcd_ddma.c (ffffffe000669e8a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe00066ef96)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffe00067b7ec)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/usb/host/uhci-hcd.c (ffffffe000683aba)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffe00068cc8a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:get_order
```
```
In drivers/usb/host/xhci-mem.c (ffffffe00069127a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/usb/host/xhci-dbgtty.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/usb/host/xhci-debugfs.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/input/serio/serio.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/input/input.c (ffffffe0006a7c20)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/input/input-mt.c (ffffffe0006aab12)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/input/input-poller.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/input/ff-core.c (ffffffe0006ab5d0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/input/mousedev.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/input/evdev.c (ffffffe0006adef4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_open
```
```
In drivers/input/keyboard/atkbd.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/input/misc/uinput.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/rtc/class.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/rtc/nvmem.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/i2c/i2c-boardinfo.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/i2c/i2c-core-base.c (ffffffe0006b6d2c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:get_order
```
```
In drivers/i2c/i2c-core-smbus.c (ffffffe0006baa26)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-smbus.c:get_order
```
```
In drivers/i2c/i2c-dev.c (ffffffe0006bcdfa)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/media/cec/cec-core.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/media/cec/cec-adap.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/media/cec/cec-api.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/media/cec/cec-notifier.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/pps/kapi.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/ptp/ptp_clock.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/ptp/ptp_chardev.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/ptp/ptp_sysfs.c (ffffffe0006c7368)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/ptp/ptp_sysfs.c:get_order
```
```
In drivers/power/supply/power_supply_core.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/power/supply/power_supply_sysfs.c (ffffffe0006c9f48)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:get_order
```
```
In drivers/hwmon/hwmon.c (ffffffe0006cd974)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/thermal/thermal_core.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/thermal/thermal_sysfs.c (ffffffe0006d24aa)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/thermal/thermal_hwmon.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/thermal/of-thermal.c (ffffffe0006d43da)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/thermal/power_allocator.c (ffffffe0006d52ca)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/thermal/devfreq_cooling.c (ffffffe0006d62d6)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/watchdog/watchdog_pretimeout.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/md/md.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffe0006e9942)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/md/dm-init.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/md/dm-table.c (ffffffe0006f202c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/md/dm-linear.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/md/dm-stripe.c (ffffffe0006f50d2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:get_order
```
```
In drivers/md/dm-ioctl.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/md/dm-io.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/md/dm-kcopyd.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/md/dm-stats.c (ffffffe0006f9db8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:get_order
```
```
In drivers/edac/edac_mc.c (ffffffe0006fd39c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_handle_error
```
```
In drivers/edac/edac_device.c (ffffffe0006fdc56)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:get_order
```
```
In drivers/edac/edac_mc_sysfs.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/edac/edac_pci.c (ffffffe0006ffc64)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:get_order
```
```
In drivers/edac/edac_pci_sysfs.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/opp/core.c (ffffffe000701478)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/opp/of.c (ffffffe00070346e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/opp/of.c:get_order
```
```
In drivers/mmc/core/bus.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/mmc/core/host.c (ffffffe000709f22)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:get_order
```
```
In drivers/mmc/core/mmc_ops.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/mmc/core/sd.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/mmc/core/sd_ops.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/mmc/core/sdio_cis.c (ffffffe00071301a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_cis.c:get_order
```
```
In drivers/mmc/core/block.c (ffffffe00071713a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/mmc/core/queue.c (ffffffe000719546)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/mmc/core/queue.c:get_order
```
```
In drivers/mmc/host/mmc_spi.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/mmc/host/of_mmc_spi.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/leds/led-core.c (ffffffe00071c286)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/leds/led-core.c:get_order
```
```
In drivers/leds/led-triggers.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/of/base.c (ffffffe00071ffee)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/of/base.c:of_populate_phandle_cache
  - drivers/of/base.c:get_order
```
```
In drivers/of/device.c (ffffffe000721ab8)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/of/device.c:of_dma_configure
  - drivers/of/device.c:get_order
```
```
In drivers/of/platform.c (ffffffe000721ea4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/of/platform.c:get_order
```
```
In drivers/of/dynamic.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/of/fdt.c (ffffffe0007256de)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - drivers/of/fdt.c:get_order
```
```
In drivers/of/irq.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/of/of_reserved_mem.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/of/overlay.c (ffffffe00072a3fc)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/devfreq/devfreq.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/devfreq/devfreq-event.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/devfreq/governor_userspace.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/extcon/extcon.c (ffffffe000731570)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/vme/vme.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/powercap/powercap_sys.c (ffffffe000735172)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In drivers/nvmem/core.c (ffffffe0007375fc)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/core/sock.c (ffffffe00073db92)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/core/scm.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/core/gen_estimator.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/core/net_namespace.c (ffffffe00074d7d0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/core/net_namespace.c:get_order
```
```
In net/core/sysctl_net_core.c (ffffffe000752302)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
  - net/core/sysctl_net_core.c:rps_sock_flow_sysctl
```
```
In net/core/dev.c (ffffffe0007558aa)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/core/ethtool.c (ffffffe000762a48)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/core/dev_addr_lists.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/core/dst.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/core/neighbour.c (ffffffe000768666)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/core/rtnetlink.c (ffffffe00076ef16)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/core/filter.c (ffffffe00077b240)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/core/sock_diag.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/core/sock_reuseport.c (ffffffe00078379a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:get_order
```
```
In net/core/xdp.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/core/flow_offload.c (ffffffe000785b94)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/core/flow_offload.c:get_order
```
```
In net/core/net-sysfs.c (ffffffe000787936)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/core/net-sysfs.c:get_order
```
```
In net/core/skmsg.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/core/netpoll.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/core/fib_rules.c (ffffffe00078dce0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/core/fib_rules.c:get_order
```
```
In net/core/drop_monitor.c (ffffffe000794b8a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/core/drop_monitor.c:get_order
```
```
In net/core/netprio_cgroup.c (ffffffe000796c2e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:get_order
```
```
In net/core/netclassid_cgroup.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/core/lwtunnel.c (ffffffe000797534)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/core/lwtunnel.c:get_order
```
```
In net/core/sock_map.c (ffffffe000799738)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/core/devlink.c (ffffffe00079d09a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a7934)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
  - net/core/bpf_sk_storage.c:get_order
```
```
In net/sched/sch_generic.c (ffffffe0007a93c4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/sched/sch_generic.c:get_order
```
```
In net/sched/sch_mq.c (ffffffe0007aba70)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/sched/sch_mq.c:get_order
```
```
In net/sched/sch_api.c (ffffffe0007ac55a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/sched/sch_api.c:get_order
```
```
In net/sched/cls_api.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/sched/act_api.c (ffffffe0007b4b28)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/sched/act_api.c:get_order
```
```
In net/sched/sch_fifo.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/sched/ematch.c (ffffffe0007b7136)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/sched/ematch.c:get_order
```
```
In net/netlink/af_netlink.c (ffffffe0007b87ea)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/netlink/genetlink.c (ffffffe0007bc2cc)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/bpf/test_run.c (ffffffe0007bd5d4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/bpf/test_run.c:get_order
```
```
In net/netfilter/nf_log.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/netfilter/nf_queue.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv4/route.c (ffffffe0007c1d04)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv4/ip_options.c (ffffffe0007c88e4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:get_order
```
```
In net/ipv4/ip_output.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffe0007cd34a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:get_order
```
```
In net/ipv4/inet_hashtables.c (ffffffe0007cf87a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_locks_alloc
  - net/ipv4/inet_hashtables.c:get_order
```
```
In net/ipv4/tcp.c (ffffffe0007d43cc)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffe0007d9d94)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_sndbuf_expand
  - net/ipv4/tcp_input.c:get_order
```
```
In net/ipv4/tcp_ipv4.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv4/tcp_metrics.c (ffffffe0007f1c24)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv4/tcp_fastopen.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv4/udp.c (ffffffe0007fc572)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/ipv4/udp.c:get_order
```
```
In net/ipv4/devinet.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv4/igmp.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffe00080b898)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv4/fib_semantics.c (ffffffe00080de30)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffe0008127b0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
  - net/ipv4/fib_trie.c:get_order
```
```
In net/ipv4/inet_fragment.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv4/metrics.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffe000818bc4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:get_order
```
```
In net/ipv4/sysctl_net_ipv4.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv4/ipmr_base.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv4/syncookies.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv4/tcp_cubic.c (ffffffe000823f2a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/ipv4/tcp_cubic.c:bictcp_cong_avoid
```
```
In net/ipv4/tcp_bpf.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv4/cipso_ipv4.c (ffffffe000825952)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/xfrm/xfrm_policy.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/xfrm/xfrm_hash.c (ffffffe000837868)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/xfrm/xfrm_hash.c:xfrm_hash_free
  - net/xfrm/xfrm_hash.c:xfrm_hash_alloc
```
```
In net/unix/af_unix.c (ffffffe00083c2b4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv6/anycast.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv6/ip6_output.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffe000849d0c)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv6/addrlabel.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv6/route.c (ffffffe000854e56)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffe00085eac2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv6/ipv6_sockglue.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (ffffffe00087b0b6)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv6/seg6.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ipv6/calipso.c (ffffffe000885d20)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/packet/af_packet.c (ffffffe00088e932)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/8021q/vlan_core.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/wireless/wext-core.c (ffffffe000895d36)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/wireless/wext-core.c:get_order
```
```
In net/wireless/wext-priv.c (ffffffe000896e58)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/wireless/wext-priv.c:get_order
```
```
In net/netlabel/netlabel_kapi.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/netlabel/netlabel_domainhash.c (ffffffe0008998de)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/netlabel/netlabel_mgmt.c (ffffffe00089a558)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffe00089c53a)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffe00089cb62)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/netlabel/netlabel_calipso.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/rfkill/core.c (ffffffe00089dcd6)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/rfkill/core.c:get_order
```
```
In net/rfkill/input.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/dcb/dcbnl.c (ffffffe0008a048e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:get_order
```
```
In net/dns_resolver/dns_key.c (ffffffe0008a2e68)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/dns_resolver/dns_key.c:get_order
```
```
In net/dns_resolver/dns_query.c (ffffffe0008a3396)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/dns_resolver/dns_query.c:get_order
```
```
In net/switchdev/switchdev.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (ffffffe0008a67ce)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/ncsi/ncsi-manage.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/xdp/xdp_umem.c (ffffffe0008ad1d2)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In net/xdp/xsk_queue.c (ffffffe0008adb2e)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
  - net/xdp/xsk_queue.c:xsk_reuseq_prepare
  - net/xdp/xsk_queue.c:xskq_create
```
```
In lib/argv_split.c (ffffffe0008addee)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/argv_split.c:get_order
```
```
In lib/decompress_bunzip2.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In lib/decompress_inflate.c (ffffffe0008aecd4)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/decompress_inflate.c:__ilog2_u64
```
```
In lib/decompress_unlzma.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In lib/decompress_unlzo.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In lib/decompress_unxz.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In lib/idr.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In lib/kobject.c (ffffffe0008b3ccc)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In lib/kobject_uevent.c (0)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
```
```
In lib/memcat_p.c (ffffffe0008b5cbc)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/memcat_p.c:get_order
```
```
In lib/string.c (ffffffe0008bd104)
Location: include/asm-generic/bitops/__fls.h:13
Inline: True
Inline callers:
  - lib/string.c:strscpy
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
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff8289f19f)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In security/selinux/ss/ebitmap.c (ffffffff81462c38)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff81521487)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In lib/math/int_sqrt.c (ffffffff81526c8c)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - lib/math/int_sqrt.c:int_sqrt
```
```
In drivers/iommu/iommu.c (ffffffff8169f275)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff819a35d9)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff819ddaa2)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff819f50f1)
Location: arch/x86/include/asm/bitops.h:261
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
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff8289736c)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In security/selinux/ss/ebitmap.c (ffffffff81453668)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff81511777)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In lib/math/int_sqrt.c (ffffffff81516f6c)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - lib/math/int_sqrt.c:int_sqrt
```
```
In drivers/iommu/iommu.c (ffffffff8167cc65)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff8195d099)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff8199a862)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff819b1eb1)
Location: arch/x86/include/asm/bitops.h:261
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
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828b2162)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In security/selinux/ss/ebitmap.c (ffffffff8145ecd8)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff8151d517)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In lib/math/int_sqrt.c (ffffffff81522d1c)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - lib/math/int_sqrt.c:int_sqrt
```
```
In drivers/iommu/iommu.c (ffffffff816cd4e5)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81a0de79)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff81a48522)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5fb71)
Location: arch/x86/include/asm/bitops.h:261
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
In arch/x86/kernel/cpu/mtrr/cleanup.c (ffffffff828b2190)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/cleanup.c:range_to_mtrr
```
```
In security/selinux/ss/ebitmap.c (ffffffff814764e8)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - security/selinux/ss/ebitmap.c:ebitmap_contains
```
```
In lib/find_bit.c (ffffffff81536d87)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In lib/math/int_sqrt.c (ffffffff8153c69c)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - lib/math/int_sqrt.c:int_sqrt
```
```
In drivers/iommu/iommu.c (ffffffff816e79f5)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In net/ipv4/fib_trie.c (ffffffff81a18689)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_insert_alias
```
```
In net/ipv6/addrconf.c (ffffffff81a54452)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6c021)
Location: arch/x86/include/asm/bitops.h:261
Inline: True
```
</details>
</li>
</ul>

## Differences
