# Function: <code>eieio</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/io.c (c0000000000308c4)
Location: arch/powerpc/include/asm/synch.h:14
Inline: True
Inline callers:
  - arch/powerpc/kernel/io.c:_memcpy_fromio
  - arch/powerpc/kernel/io.c:_memcpy_fromio
  - arch/powerpc/kernel/io.c:_memcpy_fromio
```
```
In arch/powerpc/mm/book3s64/hash_native.c (c0000000000923b0)
Location: arch/powerpc/include/asm/synch.h:14
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_insert
```
```
In arch/powerpc/lib/sstep.c (c0000000000aa540)
Location: arch/powerpc/include/asm/synch.h:14
Inline: True
Inline callers:
  - arch/powerpc/lib/sstep.c:emulate_update_regs
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011fdf0)
Location: arch/powerpc/include/asm/synch.h:14
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_clear_mod
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
```
```
In arch/powerpc/kvm/book3s_hv_rm_xive.c (c000000000124588)
Location: arch/powerpc/include/asm/synch.h:14
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xive.c:xive_rm_h_xirr
```
```
In drivers/video/fbdev/imsttfb.c (c0000000008c0b7c)
Location: arch/powerpc/include/asm/synch.h:14
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:init_imstt
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_ioctl
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_blank
  - drivers/video/fbdev/imsttfb.c:imsttfb_setcolreg
  - drivers/video/fbdev/imsttfb.c:imsttfb_setcolreg
  - drivers/video/fbdev/imsttfb.c:imsttfb_setcolreg
  - drivers/video/fbdev/imsttfb.c:imsttfb_setcolreg
  - drivers/video/fbdev/imsttfb.c:imsttfb_set_par
  - drivers/video/fbdev/imsttfb.c:imsttfb_set_par
  - drivers/video/fbdev/imsttfb.c:imsttfb_set_par
  - drivers/video/fbdev/imsttfb.c:imsttfb_set_par
  - drivers/video/fbdev/imsttfb.c:imsttfb_set_par
  - drivers/video/fbdev/imsttfb.c:imsttfb_set_par
  - drivers/video/fbdev/imsttfb.c:imsttfb_set_par
  - drivers/video/fbdev/imsttfb.c:imsttfb_set_par
  - drivers/video/fbdev/imsttfb.c:imsttfb_set_par
  - drivers/video/fbdev/imsttfb.c:imsttfb_set_par
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
  - drivers/video/fbdev/imsttfb.c:set_imstt_regvals
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
