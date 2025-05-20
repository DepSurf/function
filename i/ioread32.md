# Function: <code>ioread32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int ioread32(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81402730)
Location: lib/iomap.c:86
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/char/tpm/tpm_tis.c:tpm_tis_resume
  - drivers/char/tpm/tpm_tis.c:tpm_tis_update_timeouts
  - drivers/char/tpm/tpm_tis.c:tis_int_handler
  - drivers/char/tpm/tpm_tis.c:tis_int_handler
  - drivers/char/tpm/tpm_tis.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis.c:tpm_tis_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
```
**Symbols:**

```
ffffffff81402730-ffffffff81402761: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int ioread32(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8144a3e0)
Location: lib/iomap.c:86
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff8144a3e0-ffffffff8144a411: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int ioread32(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81468da0)
Location: lib/iomap.c:86
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81468da0-ffffffff81468dd1: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int ioread32(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8146e480)
Location: lib/iomap.c:86
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff8146e480-ffffffff8146e4b1: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int ioread32(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8149a7b0)
Location: lib/iomap.c:87
Inline: False
Direct callers:
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff8149a7b0-ffffffff8149a7e3: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int ioread32(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814cfa60)
Location: lib/iomap.c:87
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_req_canceled
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_status
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff814cfa60-ffffffff814cfa93: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int ioread32(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814e4370)
Location: lib/iomap.c:87
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/char/tpm/tpm_crb.c:crb_req_canceled
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_status
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff814e4370-ffffffff814e43a3: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int ioread32(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81510ad0)
Location: lib/iomap.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_req_canceled
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_status
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81510ad0-ffffffff81510b01: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int ioread32(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81531540)
Location: lib/iomap.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_req_canceled
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_status
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81531540-ffffffff81531571: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int ioread32(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81595840)
Location: lib/iomap.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_req_canceled
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_status
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81595840-ffffffff8159589b: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int ioread32(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815b12d0)
Location: lib/iomap.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_req_canceled
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_status
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff815b12d0-ffffffff815b132b: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int ioread32(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815bc0e0)
Location: lib/iomap.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_req_canceled
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_status
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff815bc0e0-ffffffff815bc13b: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int ioread32(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81622f30)
Location: lib/iomap.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_req_canceled
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_status
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81622f30-ffffffff81622f8b: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int ioread32(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff816f2cf0)
Location: lib/iomap.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_enable
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_driver_features
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_features
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_req_canceled
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_status
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff816f2cf0-ffffffff816f2d6d: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int ioread32(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff817e4b80)
Location: lib/iomap.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_enable
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_driver_features
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_features
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_req_canceled
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_status
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread32le
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff817e4b80-ffffffff817e4bfd: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int ioread32(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81824bc0)
Location: lib/iomap.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_enable
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_driver_features
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_features
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_req_canceled
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_status
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread32le
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81824bc0-ffffffff81824c3d: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int ioread32(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff818765d0)
Location: lib/iomap.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_enable
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_driver_features
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_features
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_req_canceled
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_status
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread32le
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff818765d0-ffffffff8187664d: ioread32 (STB_GLOBAL)
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
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676a94)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_type
```
```
In drivers/bus/brcmstb_gisb.c (ffff80001067ffdc)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:gisb_read
```
```
In drivers/pinctrl/sh-pfc/core.c (ffff8000106afc40)
Location: include/asm-generic/io.h:702
Inline: True
```
```
In drivers/gpio/gpio-xgene.c (ffff8000106d6684)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/gpio/gpio-xgene.c:xgene_gpio_suspend
  - drivers/gpio/gpio-xgene.c:xgene_gpio_dir_out
  - drivers/gpio/gpio-xgene.c:xgene_gpio_dir_in
  - drivers/gpio/gpio-xgene.c:xgene_gpio_get_direction
  - drivers/gpio/gpio-xgene.c:__xgene_gpio_set
  - drivers/gpio/gpio-xgene.c:xgene_gpio_get
```
```
In drivers/pci/quirks.c (ffff8000106fcb5c)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
```
```
In drivers/pci/controller/dwc/pci-layerscape.c (ffff800010733594)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_link_up
```
```
In drivers/clk/clk-hsdk-pll.c (ffff8000107c84f8)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_core_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_core_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_recalc_rate
```
```
In drivers/clk/clk-qoriq.c (ffff8000107c8770)
Location: include/asm-generic/io.h:702
Inline: True
```
```
In drivers/soc/fsl/guts.c (ffff800010817e0c)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/soc/fsl/guts.c:fsl_guts_probe
```
```
In drivers/soc/renesas/rcar-rst.c (ffff800011491090)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-rst.c:rcar_rst_read_mode_pins
```
```
In drivers/soc/renesas/rcar-sysc.c (ffff8000114913c4)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
```
```
In drivers/virtio/virtio_mmio.c (ffff800010826bd8)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/virtio/virtio_pci_modern.c (ffff800010827570)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_legacy.c (ffff8000108293a0)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff8000108900ec)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/asm-generic/io.h:702
Inline: True
```
```
In drivers/char/tpm/tpm_tis.c (ffff8000108c27dc)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
```
```
In drivers/char/tpm/tpm_crb.c (ffff8000108c3708)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_req_canceled
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_status
```
```
In drivers/ata/libata-core.c (ffff800010998528)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
```
```
In drivers/net/ethernet/freescale/xgmac_mdio.c (ffff8000109ed780)
Location: include/asm-generic/io.h:702
Inline: True
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fb9fc)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
```
```
In drivers/usb/dwc2/platform.c (ffff800010a3e5fc)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b56864)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout
  - drivers/firmware/arm_scmi/driver.c:scmi_rx_callback
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_fetch_response
  - drivers/firmware/arm_scmi/driver.c:scmi_fetch_response
```
```
In drivers/firmware/arm_scmi/perf.c (ffff800010b58b7c)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b63cd4)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_read32
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b65b14)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_clocksource_read
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
```
```
In drivers/memory/fsl_ifc.c (ffff800010b8b3e0)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_irq
  - drivers/memory/fsl_ifc.c:check_nand_stat
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
In arch/arm/mach-shmobile/setup-rcar-gen2.c (c1519bcc)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init
```
```
In arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c (c151a154)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/regulator-quirk-rcar-gen2.c:rcar_gen2_regulator_quirk
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081ed08)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_read32
```
```
In drivers/irqchip/irq-renesas-irqc.c (c081fe7c)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_type
```
```
In drivers/bus/brcmstb_gisb.c (c0823ef8)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_suspend
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
  - drivers/bus/brcmstb_gisb.c:gisb_arb_get_timeout
```
```
In drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c (c084ce98)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_get
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_handler
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_handler
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_dbg_show
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_clr
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_set
```
```
In drivers/pinctrl/sh-pfc/core.c (c0853530)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_save_reg
```
```
In drivers/pinctrl/sh-pfc/pfc-r8a7778.c (c08559d8)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pfc-r8a7778.c:r8a7778_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7778.c:r8a7778_pinmux_get_bias
```
```
In drivers/pinctrl/sh-pfc/pfc-sh73a0.c (c0855adc)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_vccq_mc0_is_enabled
  - drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_vccq_mc0_endisable
```
```
In drivers/pci/quirks.c (c08951c0)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
```
```
In drivers/pci/controller/pci-rcar-gen2.c (c08ada74)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
```
```
In drivers/clk/clk-hsdk-pll.c (c08f4dcc)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_recalc_rate
```
```
In drivers/clk/clk-qoriq.c (c155601c)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/clk/clk-qoriq.c:clockgen_init
  - drivers/clk/clk-qoriq.c:clockgen_init
```
```
In drivers/clk/renesas/clk-rcar-gen2.c (c1580be8)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-rcar-gen2.c:rcar_gen2_cpg_clocks_init
```
```
In drivers/soc/fsl/guts.c (c0934030)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/soc/fsl/guts.c:fsl_guts_probe
```
```
In drivers/soc/renesas/rcar-rst.c (c1590ac4)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-rst.c:rcar_rst_read_mode_pins
```
```
In drivers/soc/renesas/rcar-sysc.c (c1590e58)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_pd_init
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
```
```
In drivers/virtio/virtio_mmio.c (c0944338)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/virtio/virtio_pci_modern.c (c09451a8)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_legacy.c (c0946de4)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
```
```
In drivers/tty/serial/8250/8250_pci.c (c098aedc)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/asm-generic/io.h:702
Inline: True
```
```
In drivers/char/tpm/tpm_tis.c (c09baf20)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
```
```
In drivers/iommu/ipmmu-vmsa.c (c09c1c84)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_irq
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_irq
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_tlb_invalidate
```
```
In drivers/ata/libata-core.c (c0a68088)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
```
```
In drivers/net/ethernet/freescale/xgmac_mdio.c (c0acf438)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_wait_until_done
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_wait_until_free
```
```
In drivers/usb/dwc2/platform.c (c0b112e8)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
```
In drivers/firmware/arm_scmi/driver.c (c0c37524)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout
  - drivers/firmware/arm_scmi/driver.c:scmi_rx_callback
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_fetch_response
  - drivers/firmware/arm_scmi/driver.c:scmi_fetch_response
```
```
In drivers/firmware/arm_scmi/perf.c (c0c393d0)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_get
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_cmt.c (c0c440b8)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_read32
```
```
In drivers/clocksource/sh_tmu.c (c0c45dbc)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_clocksource_read
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
```
```
In drivers/clocksource/em_sti.c (c0c46a9c)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/clocksource/em_sti.c:em_sti_count
  - drivers/clocksource/em_sti.c:em_sti_count
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
unsigned int ioread32(void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iomap.c (c0000000007e60a0)
Location: lib/iomap.c:88
Inline: True
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
c0000000007e60a0-c0000000007e6220: ioread32 (STB_GLOBAL)
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
In drivers/pci/quirks.c (ffffffe0004cc7b0)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
```
```
In drivers/clk/clk-hsdk-pll.c (ffffffe0005151f0)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_recalc_rate
```
```
In drivers/virtio/virtio_mmio.c (ffffffe00051cc8c)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_get
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffe00051d9a6)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffe00051f5b0)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffe000557174)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
```
```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: include/asm-generic/io.h:702
Inline: True
```
```
In drivers/char/tpm/tpm_tis.c (ffffffe000573990)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
```
```
In drivers/ata/libata-core.c (ffffffe0005f8e44)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
```
```
In drivers/spi/spi-sifive.c (ffffffe00061c392)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_transfer_one
  - drivers/spi/spi-sifive.c:sifive_spi_transfer_one
```
```
In drivers/usb/dwc2/platform.c (ffffffe00065a564)
Location: include/asm-generic/io.h:702
Inline: True
Inline callers:
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
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
unsigned int ioread32(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81529b20)
Location: lib/iomap.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_req_canceled
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_status
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
```
**Symbols:**

```
ffffffff81529b20-ffffffff81529b51: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int ioread32(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81519e00)
Location: lib/iomap.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_req_canceled
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_status
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81519e00-ffffffff81519e31: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int ioread32(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81525bb0)
Location: lib/iomap.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_req_canceled
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_status
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81525bb0-ffffffff81525be1: ioread32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int ioread32(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8153f530)
Location: lib/iomap.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_mmio.c:vm_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get_features
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read32
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_req_canceled
  - drivers/char/tpm/tpm_crb.c:crb_recv
  - drivers/char/tpm/tpm_crb.c:crb_status
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/usb/dwc2/platform.c:dwc2_driver_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_cpu_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff8153f530-ffffffff8153f561: ioread32 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *addr</code> ➡️ <code>const void *addr</code>
</li>
</ul>
</details>
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
