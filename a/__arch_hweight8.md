# Function: <code>__arch_hweight8</code>

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
In lib/memweight.c (ffffffff813fe11f)
Location: arch/x86/include/asm/arch_hweight.h:42
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/memweight.c (ffffffff8144578e)
Location: arch/x86/include/asm/arch_hweight.h:38
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
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
In lib/memweight.c (ffffffff81463f7e)
Location: arch/x86/include/asm/arch_hweight.h:38
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/memweight.c (ffffffff81469000)
Location: arch/x86/include/asm/arch_hweight.h:38
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/memweight.c (ffffffff814952d0)
Location: arch/x86/include/asm/arch_hweight.h:39
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/memweight.c (ffffffff814ca68d)
Location: arch/x86/include/asm/arch_hweight.h:39
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
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
In lib/memweight.c (ffffffff814df3bb)
Location: arch/x86/include/asm/arch_hweight.h:33
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/spi/spi-mem.c (ffffffff817567f5)
Location: arch/x86/include/asm/arch_hweight.h:33
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
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
In lib/memweight.c (ffffffff8150b20b)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/spi/spi-mem.c (ffffffff81792cf5)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
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
In lib/memweight.c (ffffffff8152902b)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/spi/spi-mem.c (ffffffff817b6845)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d67af)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
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
In lib/memweight.c (ffffffff8158c8db)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/spi/spi-mem.c (ffffffff8187d665)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a47fd)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
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
In lib/memweight.c (ffffffff815a934b)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/spi/spi-mem.c (ffffffff8188bb95)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b38a4)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
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
In lib/memweight.c (ffffffff815b3f4b)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/spi/spi-mem.c (ffffffff8186e4f5)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81896a83)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
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
In lib/memweight.c (ffffffff8161a14b)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/spi/spi-mem.c (ffffffff818fe595)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff8192aa15)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
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
In lib/memweight.c (ffffffff816e772b)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/spi/spi-mem.c (ffffffff81a4fe25)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/vfio/pci/vfio_pci_core.c (ffffffff81a81369)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff834bff59)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:intel_hfi_init
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
In lib/memweight.c (ffffffff817d755b)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/spi/spi-mem.c (ffffffff81bd8f05)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff83efec06)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_parse_features
```
```
In net/netlink/genetlink.c (ffffffff81e6eb85)
Location: arch/x86/include/asm/arch_hweight.h:31
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
In lib/memweight.c (ffffffff8181676b)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/spi/spi-mem.c (ffffffff81c2f8f5)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff83724a76)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_parse_features
```
```
In net/netlink/genetlink.c (ffffffff81ecac95)
Location: arch/x86/include/asm/arch_hweight.h:31
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
In lib/memweight.c (ffffffff8185ba4b)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/spi/spi-mem.c (ffffffff81ce27b5)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/thermal/intel/intel_hfi.c (ffffffff839588e6)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/thermal/intel/intel_hfi.c:hfi_parse_features
```
```
In net/netlink/genetlink.c (ffffffff81f8d3c5)
Location: arch/x86/include/asm/arch_hweight.h:31
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
In virt/kvm/arm/vgic/vgic.c (ffff8000100dd1ac)
Location: include/asm-generic/bitops/arch_hweight.h:17
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_flush_hwstate
```
```
In virt/kvm/arm/vgic/vgic-v2.c (ffff8000100dec40)
Location: include/asm-generic/bitops/arch_hweight.h:17
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_populate_lr
```
```
In virt/kvm/arm/vgic/vgic-v3.c (ffff8000100df724)
Location: include/asm-generic/bitops/arch_hweight.h:17
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_populate_lr
```
```
In lib/memweight.c (ffff8000106339e4)
Location: include/asm-generic/bitops/arch_hweight.h:17
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/spi/spi-mem.c (ffff8000109ca408)
Location: include/asm-generic/bitops/arch_hweight.h:17
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b6439c)
Location: include/asm-generic/bitops/arch_hweight.h:17
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b65658)
Location: include/asm-generic/bitops/arch_hweight.h:17
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
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
In lib/memweight.c (c07d9d34)
Location: include/asm-generic/bitops/arch_hweight.h:17
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/mtd/nand/raw/nand_base.c (c0a9b2c8)
Location: include/asm-generic/bitops/arch_hweight.h:17
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/nand_base.c:nand_check_erased_buf
  - drivers/mtd/nand/raw/nand_base.c:nand_check_erased_buf
  - drivers/mtd/nand/raw/nand_base.c:nand_isbad_bbm
```
```
In drivers/mtd/nand/raw/nand_micron.c (c0aa82f8)
Location: include/asm-generic/bitops/arch_hweight.h:17
Inline: True
```
```
In drivers/mtd/nand/raw/omap2.c (c0aaaa7c)
Location: include/asm-generic/bitops/arch_hweight.h:17
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_elm_correct_data
  - drivers/mtd/nand/raw/omap2.c:omap_elm_correct_data
```
```
In drivers/spi/spi-mem.c (c0ab398c)
Location: include/asm-generic/bitops/arch_hweight.h:17
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/clocksource/sh_cmt.c (c0c44e14)
Location: include/asm-generic/bitops/arch_hweight.h:17
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_setup
```
```
In drivers/clocksource/sh_tmu.c (c0c467c4)
Location: include/asm-generic/bitops/arch_hweight.h:17
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
**Symbols:**

```
c0000000000b3b78-c0000000000b3b78: __arch_hweight8 (STB_GLOBAL)
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
In lib/memweight.c (ffffffe0004619b6)
Location: include/asm-generic/bitops/arch_hweight.h:17
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/spi/spi-mem.c (ffffffe000619e38)
Location: include/asm-generic/bitops/arch_hweight.h:17
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
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
In lib/memweight.c (ffffffff8152160b)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/spi/spi-mem.c (ffffffff8177b325)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
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
In lib/memweight.c (ffffffff815118fb)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/spi/spi-mem.c (ffffffff8175b0d5)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff8178085f)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
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
In lib/memweight.c (ffffffff8151d69b)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/spi/spi-mem.c (ffffffff817ab6c5)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817cb62f)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
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
In lib/memweight.c (ffffffff81536f0b)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - lib/memweight.c:memweight
  - lib/memweight.c:memweight
```
```
In drivers/spi/spi-mem.c (ffffffff817c5655)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_buswidth_is_valid
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e58cf)
Location: arch/x86/include/asm/arch_hweight.h:31
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
```
</details>
</li>
</ul>

## Differences
