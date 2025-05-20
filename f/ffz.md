# Function: <code>ffz</code>

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
In kernel/signal.c (ffffffff8108d4c7)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff810dcae2)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In mm/page_alloc.c (ffffffff81819376)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff812689dc)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8126b6cc)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In block/blk-flush.c (ffffffff813bd4b1)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - block/blk-flush.c:blk_flush_complete_seq
  - block/blk-flush.c:flush_end_io
```
```
In lib/find_bit.c (ffffffff813fdf3d)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_zero_bit
```
```
In drivers/iommu/amd_iommu.c (ffffffff8152ea0b)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff8169e3de)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_resize
```
```
In net/ipv4/devinet.c (ffffffff817927b9)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff8179b4e8)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
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
In kernel/signal.c (ffffffff81090396)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff810e21ec)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In mm/page_alloc.c (ffffffff81892ec6)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff81294c36)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81297873)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In fs/squashfs/super.c (ffffffff813240a1)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/blk-flush.c (ffffffff814018bb)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/find_bit.c (ffffffff8144559d)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_zero_bit
```
```
In drivers/iommu/amd_iommu.c (ffffffff8158294d)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff816ff709)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_resize
```
```
In net/ipv4/devinet.c (ffffffff817ff5c7)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff81809106)
Location: arch/x86/include/asm/bitops.h:360
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
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
In arch/x86/mm/pkeys.c (ffffffff8107b684)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/signal.c (ffffffff81095316)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff810e88da)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In mm/mprotect.c (ffffffff811f5618)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - mm/mprotect.c:SyS_pkey_alloc
```
```
In fs/binfmt_elf.c (ffffffff812a98f6)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812ac362)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
```
```
In fs/squashfs/super.c (ffffffff81339f31)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/blk-flush.c (ffffffff8141b527)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/find_bit.c (ffffffff81463d8d)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_zero_bit
```
```
In drivers/iommu/amd_iommu.c (ffffffff815aec3d)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff817313b1)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_resize
```
```
In net/ipv4/devinet.c (ffffffff81830527)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff8183a202)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
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
In arch/x86/mm/pkeys.c (ffffffff81079e46)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/signal.c (ffffffff81092585)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff810e7e16)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In mm/mprotect.c (ffffffff812003f9)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - mm/mprotect.c:SyS_pkey_alloc
```
```
In fs/binfmt_elf.c (ffffffff812b65f7)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812b96da)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
```
```
In fs/squashfs/super.c (ffffffff8134ec01)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/blk-flush.c (ffffffff81429603)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/find_bit.c (ffffffff81468e2d)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_zero_bit
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c4839)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
```
```
In drivers/md/bitmap.c (ffffffff8174a27b)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_resize
```
```
In net/ipv4/devinet.c (ffffffff818519d9)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff8185b74b)
Location: arch/x86/include/asm/bitops.h:373
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
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
In arch/x86/mm/pkeys.c (ffffffff810800b6)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/signal.c (ffffffff8109941d)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff810f01c8)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In mm/mprotect.c (ffffffff81218b99)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - mm/mprotect.c:SyS_pkey_alloc
```
```
In fs/binfmt_elf.c (ffffffff812d9edc)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff812dd009)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
```
```
In fs/squashfs/super.c (ffffffff813732b1)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/blk-flush.c (ffffffff814545e0)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/find_bit.c (ffffffff814950ea)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_zero_bit
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162b69d)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff817bc5ab)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_resize
```
```
In net/ipv4/devinet.c (ffffffff818d17bb)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff818db63b)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
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
In arch/x86/mm/pkeys.c (ffffffff810831c1)
Location: arch/x86/include/asm/bitops.h:377
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/signal.c (ffffffff8109d52d)
Location: arch/x86/include/asm/bitops.h:377
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff810f87b2)
Location: arch/x86/include/asm/bitops.h:377
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In mm/mprotect.c (ffffffff8123959c)
Location: arch/x86/include/asm/bitops.h:377
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
```
In fs/binfmt_elf.c (ffffffff81305810)
Location: arch/x86/include/asm/bitops.h:377
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8130916f)
Location: arch/x86/include/asm/bitops.h:377
Inline: True
```
```
In fs/squashfs/super.c (ffffffff813a1bfd)
Location: arch/x86/include/asm/bitops.h:377
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/blk-flush.c (ffffffff81487a51)
Location: arch/x86/include/asm/bitops.h:377
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/find_bit.c (ffffffff814ca498)
Location: arch/x86/include/asm/bitops.h:377
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_zero_bit
```
```
In drivers/iommu/amd_iommu.c (ffffffff816662d3)
Location: arch/x86/include/asm/bitops.h:377
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff818040cc)
Location: arch/x86/include/asm/bitops.h:377
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:bitmap_resize
```
```
In net/ipv4/devinet.c (ffffffff81927c89)
Location: arch/x86/include/asm/bitops.h:377
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff81932264)
Location: arch/x86/include/asm/bitops.h:377
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
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
In arch/x86/mm/pkeys.c (ffffffff81089d71)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/signal.c (ffffffff810a57fb)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff81103f52)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In mm/mprotect.c (ffffffff8124d1cc)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
```
In fs/binfmt_elf.c (ffffffff8131af9e)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8131e97d)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
```
```
In fs/squashfs/super.c (ffffffff813ba9bd)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/blk-flush.c (ffffffff814a1c64)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/find_bit.c (ffffffff814df1b8)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_zero_bit
```
```
In drivers/iommu/amd_iommu.c (ffffffff81684b8c)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff818302cc)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In net/ipv4/devinet.c (ffffffff81956b62)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff81961ac4)
Location: arch/x86/include/asm/bitops.h:374
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
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
In arch/x86/mm/pkeys.c (ffffffff8108dac9)
Location: arch/x86/include/asm/bitops.h:248
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/signal.c (ffffffff810aa4e1)
Location: arch/x86/include/asm/bitops.h:248
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff8110c9a4)
Location: arch/x86/include/asm/bitops.h:248
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In mm/mprotect.c (ffffffff8125f4ea)
Location: arch/x86/include/asm/bitops.h:248
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
```
In fs/binfmt_elf.c (ffffffff813427d0)
Location: arch/x86/include/asm/bitops.h:248
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81346138)
Location: arch/x86/include/asm/bitops.h:248
Inline: True
```
```
In fs/squashfs/super.c (ffffffff813e527d)
Location: arch/x86/include/asm/bitops.h:248
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/blk-flush.c (ffffffff814cfdc0)
Location: arch/x86/include/asm/bitops.h:248
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/find_bit.c (ffffffff8150afc2)
Location: arch/x86/include/asm/bitops.h:248
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_zero_bit
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8158daae)
Location: arch/x86/include/asm/bitops.h:248
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/iommu/amd_iommu.c (ffffffff816bc0ae)
Location: arch/x86/include/asm/bitops.h:248
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff81872fd7)
Location: arch/x86/include/asm/bitops.h:248
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In net/ipv4/devinet.c (ffffffff819bb61b)
Location: arch/x86/include/asm/bitops.h:248
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff819c62f5)
Location: arch/x86/include/asm/bitops.h:248
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
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
In arch/x86/mm/pkeys.c (ffffffff8108e729)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/signal.c (ffffffff810b0ae1)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff81118d84)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In mm/mprotect.c (ffffffff8126dcfa)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
```
In fs/binfmt_elf.c (ffffffff8135ac0d)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8135e43f)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/squashfs/super.c (ffffffff813ff2fd)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/blk-flush.c (ffffffff814e9176)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/find_bit.c (ffffffff81528de2)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_zero_bit
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815af6ce)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e12fc)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/md/md-bitmap.c (ffffffff818a4dd7)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In net/ipv4/devinet.c (ffffffff819f230b)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff819fcea5)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
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
In arch/x86/mm/pkeys.c (ffffffff81094899)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/signal.c (ffffffff810b8f4c)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff811246ec)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In mm/mprotect.c (ffffffff8129e06a)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
```
In fs/binfmt_elf.c (ffffffff8139fb60)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813a2a1b)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/squashfs/super.c (ffffffff8144cc7d)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/blk-flush.c (ffffffff8154815d)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/find_bit.c (ffffffff8158c6b2)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_zero_bit
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8165892e)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/iommu/amd/iommu.c (ffffffff81795df0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:fetch_pte
```
```
In drivers/spi/spi.c (ffffffff81878123)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
```
```
In drivers/md/md-bitmap.c (ffffffff81974765)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In net/ipv4/devinet.c (ffffffff81ae04fc)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeaf96)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
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
In arch/x86/mm/pkeys.c (ffffffff81093c89)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/signal.c (ffffffff810b41fc)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff8112054c)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In mm/mprotect.c (ffffffff812a93fc)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - mm/mprotect.c:__do_sys_pkey_alloc
```
```
In fs/binfmt_elf.c (ffffffff813b0f4e)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813b3a95)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/squashfs/super.c (ffffffff814692dd)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/blk-flush.c (ffffffff81563e46)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/find_bit.c (ffffffff815a9122)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_zero_bit
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff81678d2e)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a4510)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:fetch_pte
```
```
In drivers/spi/spi.c (ffffffff81886a33)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_get_gpio_descs
```
```
In drivers/md/md-bitmap.c (ffffffff81979665)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In net/ipv4/devinet.c (ffffffff81aed37c)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff81af7e66)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
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
In arch/x86/kernel/idt.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In arch/x86/mm/pkeys.c (ffffffff81094649)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In kernel/signal.c (ffffffff810b5e0c)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff81120822)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/events/uprobes.c (ffffffff81256dc9)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In mm/mprotect.c (ffffffff812ae889)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - mm/mprotect.c:__do_sys_pkey_alloc
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff813b803d)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813baa54)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/squashfs/super.c (ffffffff8146e9dd)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/blk-flush.c (ffffffff8156c5d6)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In lib/find_bit.c (ffffffff815b3d62)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - lib/find_bit.c:_find_first_zero_bit
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In lib/idr.c (ffffffff815f1cdf)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8165baa1)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff81767aff)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/misc.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/iommu/amd/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff8178c15b)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:fetch_pte
```
```
In drivers/iommu/intel/dmar.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff8195dc19)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In net/core/sock.c (ffffffff819cac88)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/core/sock.c:proto_register
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81ad8c6e)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae3576)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ncsi/ncsi-manage.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: arch/x86/include/asm/bitops.h:247
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
In arch/x86/kernel/idt.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In arch/x86/mm/pkeys.c (ffffffff810a45cb)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In kernel/signal.c (ffffffff810c8c8c)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff81140d89)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/events/uprobes.c (ffffffff81292b59)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In mm/mprotect.c (ffffffff812f0029)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - mm/mprotect.c:__do_sys_pkey_alloc
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff81407b92)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8140a599)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/squashfs/super.c (ffffffff814c53cc)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/blk-flush.c (ffffffff815d0a89)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In lib/find_bit.c (ffffffff81619f52)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - lib/find_bit.c:_find_first_zero_bit
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In lib/idr.c (ffffffff8165ee46)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff816ce1be)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff816ced89)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff817ec53a)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/misc.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/iommu/amd/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff818132d5)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:first_pte_l7
```
```
In drivers/iommu/intel/dmar.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff81a0354b)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In net/core/sock.c (ffffffff81a7a2b8)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/core/sock.c:proto_register
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81b97b1a)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba2e76)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ncsi/ncsi-manage.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: arch/x86/include/asm/bitops.h:247
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
In arch/x86/kernel/idt.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In arch/x86/kernel/apic/io_apic.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In arch/x86/mm/pkeys.c (ffffffff810b8e23)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/sysctl.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In kernel/signal.c (ffffffff810e0228)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/signal.c:dequeue_signal
  - kernel/signal.c:dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff8116471f)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/events/uprobes.c (ffffffff812e8579)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/events/uprobes.c:pre_ssout
```
```
In mm/percpu.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In mm/mprotect.c (ffffffff81353531)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - mm/mprotect.c:__do_sys_pkey_alloc
```
```
In fs/file.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/binfmt_elf.c (ffffffff8147c8ce)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff8147f2d6)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/ext4/balloc.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/squashfs/super.c (ffffffff815502b0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In security/landlock/fs.c (ffffffff8163a278)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
  - security/landlock/fs.c:check_access_path_dual
```
```
In block/blk-flush.c (ffffffff8167c2b9)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In io_uring/io_uring.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In lib/bitmap.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In lib/find_bit.c (ffffffff816e7492)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - lib/find_bit.c:_find_first_zero_bit
```
```
In lib/sbitmap.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In lib/idr.c (ffffffff81778728)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
```
```
In lib/vsprintf.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff817f6e78)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_next_free_bar
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff817f79e2)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_add_vepf
```
```
In drivers/pci/controller/dwc/pcie-designware-ep.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/acpi/numa/srat.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/xen/grant-table.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/tty/serial/max310x.c (ffffffff8192b35b)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
```
In drivers/char/misc.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/char/agp/generic.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/iommu/amd/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/iommu/amd/io_pgtable.c (ffffffff819542b5)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/iommu/amd/io_pgtable.c:first_pte_l7
```
```
In drivers/iommu/intel/dmar.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/iommu/intel/iommu.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/nvdimm/label.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/net/wwan/wwan_core.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/usb/core/hub.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In drivers/md/md-bitmap.c (ffffffff81b6b209)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In net/core/sock.c (ffffffff81bed081)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/core/sock.c:proto_register
```
```
In net/core/dev.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In net/netlink/genetlink.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff81d29813)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff81d3563a)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ncsi/ncsi-manage.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In net/mptcp/pm_netlink.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In net/mptcp/pm_userspace.c (0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
</details>
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pkeys.c (ffffffff8108d6e9)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/signal.c (ffffffff810aae51)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff81111364)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In mm/mprotect.c (ffffffff8126634a)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
```
In fs/binfmt_elf.c (ffffffff813531ed)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff81356a1f)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/squashfs/super.c (ffffffff813f78dd)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/blk-flush.c (ffffffff814e1756)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/find_bit.c (ffffffff815213c2)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_zero_bit
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a2e8e)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a6d4c)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/md/md-bitmap.c (ffffffff8184ac57)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In net/ipv4/devinet.c (ffffffff819920ab)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff8199cc45)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
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
In arch/x86/mm/pkeys.c (ffffffff8107c219)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/signal.c (ffffffff810997f1)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff81102094)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In mm/mprotect.c (ffffffff8125879a)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
```
In fs/binfmt_elf.c (ffffffff81343ecd)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813476df)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/squashfs/super.c (ffffffff813e835d)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/blk-flush.c (ffffffff814d20e6)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/find_bit.c (ffffffff815116b2)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_zero_bit
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff8159202e)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/iommu/amd_iommu.c (ffffffff8168473c)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/md/md-bitmap.c (ffffffff81812281)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In net/ipv4/devinet.c (ffffffff8194bb6b)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff81956705)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
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
In arch/x86/mm/pkeys.c (ffffffff8108d699)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/signal.c (ffffffff810aa3b1)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff8110f254)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In mm/mprotect.c (ffffffff812640ea)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
```
In fs/binfmt_elf.c (ffffffff81350cbd)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813544ef)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/squashfs/super.c (ffffffff813f4c5d)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/blk-flush.c (ffffffff814dd7e6)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/find_bit.c (ffffffff8151d452)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_zero_bit
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815a341e)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d4fbc)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/md/md-bitmap.c (ffffffff8189a287)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In net/ipv4/devinet.c (ffffffff819fc94b)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff81a074e5)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
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
In arch/x86/mm/pkeys.c (ffffffff8108fa59)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - arch/x86/mm/pkeys.c:__execute_only_pkey
```
```
In kernel/signal.c (ffffffff810b2491)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/signal.c:__dequeue_signal
```
```
In kernel/irq/manage.c (ffffffff8111a784)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - kernel/irq/manage.c:__setup_irq
```
```
In mm/mprotect.c (ffffffff81273aaa)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - mm/mprotect.c:__ia32_sys_pkey_alloc
  - mm/mprotect.c:__x64_sys_pkey_alloc
```
```
In fs/binfmt_elf.c (ffffffff81364256)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
```
```
In fs/compat_binfmt_elf.c (ffffffff813653aa)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:fill_psinfo
```
```
In fs/squashfs/super.c (ffffffff8140a88d)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In block/blk-flush.c (ffffffff814f6646)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:blk_flush_complete_seq
```
```
In lib/find_bit.c (ffffffff81536cc2)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - lib/find_bit.c:find_first_zero_bit
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff815bd81e)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get_first_free_bar
```
```
In drivers/iommu/amd_iommu.c (ffffffff816ef6bc)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_map_page
```
```
In drivers/md/md-bitmap.c (ffffffff818b63a0)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
```
```
In net/ipv4/devinet.c (ffffffff81a06cdb)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff81a11c2e)
Location: arch/x86/include/asm/bitops.h:247
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
```
</details>
</li>
</ul>

## Differences
