# Function: <code>iowrite32</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814027f0)
Location: lib/iomap.c:124
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/char/tpm/tpm_tis.c:tpm_tis_resume
  - drivers/char/tpm/tpm_tis.c:tis_int_handler
  - drivers/char/tpm/tpm_tis.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis.c:tpm_tis_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
```
**Symbols:**

```
ffffffff814027f0-ffffffff81402821: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8144a4a0)
Location: lib/iomap.c:124
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff8144a4a0-ffffffff8144a4d1: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81468e60)
Location: lib/iomap.c:124
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81468e60-ffffffff81468e91: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8146e540)
Location: lib/iomap.c:124
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff8146e540-ffffffff8146e571: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8149a870)
Location: lib/iomap.c:125
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff8149a870-ffffffff8149a8a3: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814cfb20)
Location: lib/iomap.c:125
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff814cfb20-ffffffff814cfb53: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814e4430)
Location: lib/iomap.c:125
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff814e4430-ffffffff814e4463: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81510c30)
Location: lib/iomap.c:201
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81510c30-ffffffff81510c61: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815316a0)
Location: lib/iomap.c:201
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff815316a0-ffffffff815316d1: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81595c00)
Location: lib/iomap.c:201
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_relinquish_locality
  - drivers/char/tpm/tpm_crb.c:crb_request_locality
  - drivers/char/tpm/tpm_crb.c:crb_cmd_ready
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81595c00-ffffffff81595c4b: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815b1690)
Location: lib/iomap.c:201
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_relinquish_locality
  - drivers/char/tpm/tpm_crb.c:crb_request_locality
  - drivers/char/tpm/tpm_crb.c:crb_cmd_ready
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff815b1690-ffffffff815b16db: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815bc4a0)
Location: lib/iomap.c:201
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_relinquish_locality
  - drivers/char/tpm/tpm_crb.c:crb_request_locality
  - drivers/char/tpm/tpm_crb.c:crb_cmd_ready
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff815bc4a0-ffffffff815bc4eb: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff816232f0)
Location: lib/iomap.c:201
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_finalize_features
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_relinquish_locality
  - drivers/char/tpm/tpm_crb.c:crb_request_locality
  - drivers/char/tpm/tpm_crb.c:crb_cmd_ready
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff816232f0-ffffffff8162333b: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff816f3140)
Location: lib/iomap.c:201
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_queue_address
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_features
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_relinquish_locality
  - drivers/char/tpm/tpm_crb.c:crb_request_locality
  - drivers/char/tpm/tpm_crb.c:crb_cmd_ready
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff816f3140-ffffffff816f31ba: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff817e5050)
Location: lib/iomap.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_queue_address
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_features
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_relinquish_locality
  - drivers/char/tpm/tpm_crb.c:crb_request_locality
  - drivers/char/tpm/tpm_crb.c:crb_cmd_ready
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite32le
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff817e5050-ffffffff817e50ca: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81825090)
Location: lib/iomap.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_queue_address
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_features
  - drivers/virtio/virtio_pci_modern.c:vp_notify_with_data
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_relinquish_locality
  - drivers/char/tpm/tpm_crb.c:crb_request_locality
  - drivers/char/tpm/tpm_crb.c:crb_cmd_ready
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
  - drivers/char/tpm/tpm_crb.c:crb_try_pluton_doorbell
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite32le
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81825090-ffffffff8182510a: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81876aa0)
Location: lib/iomap.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/pci/quirks.c:reset_ivb_igd
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_address
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_driver_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_features
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_queue_address
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_features
  - drivers/virtio/virtio_pci_modern.c:vp_notify_with_data
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_relinquish_locality
  - drivers/char/tpm/tpm_crb.c:crb_request_locality
  - drivers/char/tpm/tpm_crb.c:crb_cmd_ready
  - drivers/char/tpm/tpm_crb.c:crb_go_idle
  - drivers/char/tpm/tpm_crb.c:crb_try_pluton_doorbell
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite32le
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81876aa0-ffffffff81876b1a: iowrite32 (STB_GLOBAL)
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
In drivers/irqchip/irq-renesas-irqc.c (ffff800010676ad8)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_type
```
```
In drivers/bus/brcmstb_gisb.c (ffff8000106801e4)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_decode_addr
```
```
In drivers/pinctrl/sh-pfc/core.c (ffff8000106b0138)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_config_mux
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_write
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_write
```
```
In drivers/gpio/gpio-xgene.c (ffff8000106d64e0)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/gpio/gpio-xgene.c:xgene_gpio_resume
  - drivers/gpio/gpio-xgene.c:xgene_gpio_dir_out
  - drivers/gpio/gpio-xgene.c:xgene_gpio_dir_in
  - drivers/gpio/gpio-xgene.c:__xgene_gpio_set
```
```
In drivers/pci/quirks.c (ffff8000106ff170)
Location: include/asm-generic/io.h:736
Inline: True
```
```
In drivers/pci/controller/dwc/pci-layerscape.c (ffff800010733520)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init
```
```
In drivers/clk/clk-hsdk-pll.c (ffff8000107c84b0)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_core_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_core_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_core_update_rate
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
```
```
In drivers/clk/clk-qoriq.c (ffff8000107c8730)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/clk/clk-qoriq.c:mux_set_parent
```
```
In drivers/soc/renesas/rcar-rst.c (ffff80001081e198)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-rst.c:rcar_rst_enable_wdt_reset
```
```
In drivers/soc/renesas/rcar-sysc.c (ffff80001081e270)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
```
```
In drivers/virtio/virtio_pci_modern.c (ffff800010827774)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_legacy.c (ffff80001082904c)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
```
In drivers/char/tpm/tpm_tis.c (ffff8000108c283c)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
```
```
In drivers/char/tpm/tpm_crb.c (ffff8000108c2e80)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
```
```
In drivers/ata/libata-sff.c (ffff8000109b12e0)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_setup
```
```
In drivers/net/ethernet/freescale/xgmac_mdio.c (ffff8000109eda88)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_read
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_mdio_write
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fb548)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list
  - drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list
  - drivers/net/ethernet/smsc/smc91x.c:smc_set_multicast_list
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media
  - drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_configure
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_check_media
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_fixed
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_fixed
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_fixed
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_write
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_write
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_read
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_read
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
```
```
In drivers/edac/altera_edac.c (ffff800010b16dc8)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/edac/altera_edac.c:altr_sdram_probe
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b56aa4)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
```
```
In drivers/firmware/arm_scmi/perf.c (ffff800010b58304)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_set
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_set
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_set
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b63d5c)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_write32
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b66100)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_set_next
  - drivers/clocksource/sh_tmu.c:sh_tmu_set_next
  - drivers/clocksource/sh_tmu.c:sh_tmu_set_next
  - drivers/clocksource/sh_tmu.c:__sh_tmu_enable
  - drivers/clocksource/sh_tmu.c:__sh_tmu_enable
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
```
```
In drivers/memory/fsl_ifc.c (ffff800010b8b6f8)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
  - drivers/memory/fsl_ifc.c:fsl_ifc_ctrl_probe
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
In arch/arm/mach-npcm/platsmp.c (c0334e28)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - arch/arm/mach-npcm/platsmp.c:npcm7xx_smp_boot_secondary
```
```
In arch/arm/mach-shmobile/setup-r8a7740.c (c1519814)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_generic_init
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
```
```
In arch/arm/mach-shmobile/setup-rcar-gen2.c (c1519bdc)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init
```
```
In arch/arm/mach-shmobile/smp-emev2.c (c151a630)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/smp-emev2.c:emev2_smp_prepare_cpus
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081ef6c)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_write32
```
```
In drivers/irqchip/irq-renesas-irqc.c (c081fe90)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_handler
  - drivers/irqchip/irq-renesas-irqc.c:irqc_irq_set_type
```
```
In drivers/bus/brcmstb_gisb.c (c0823f64)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/bus/brcmstb_gisb.c:gisb_write
```
```
In drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c (c084c818)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_set
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_config_set
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_set_direction
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_set_direction
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_unmask
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_mask
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcmgpio_irq_ack
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_clr
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm_gpio_set
```
```
In drivers/pinctrl/sh-pfc/core.c (c0853a50)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_config_mux
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_write
  - drivers/pinctrl/sh-pfc/core.c:sh_pfc_write
```
```
In drivers/pinctrl/sh-pfc/pfc-r8a7778.c (c08559f8)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pfc-r8a7778.c:r8a7778_pinmux_set_bias
```
```
In drivers/pinctrl/sh-pfc/pfc-sh73a0.c (c0855c28)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_vccq_mc0_endisable
```
```
In drivers/pci/quirks.c (c0896d2c)
Location: include/asm-generic/io.h:736
Inline: True
```
```
In drivers/pci/controller/pci-rcar-gen2.c (c08adaa8)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_setup
  - drivers/pci/controller/pci-rcar-gen2.c:rcar_pci_cfg_base
```
```
In drivers/clk/clk-hsdk-pll.c (c08f4da4)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
```
```
In drivers/clk/clk-qoriq.c (c08f5780)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/clk/clk-qoriq.c:mux_set_parent
```
```
In drivers/soc/renesas/rcar-rst.c (c0938588)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-rst.c:rcar_rst_enable_wdt_reset
```
```
In drivers/soc/renesas/rcar-sysc.c (c0938610)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
  - drivers/soc/renesas/rcar-sysc.c:rcar_sysc_power
```
```
In drivers/virtio/virtio_pci_modern.c (c094556c)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
```
```
In drivers/virtio/virtio_pci_legacy.c (c0946cd4)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
```
In drivers/char/tpm/tpm_tis.c (c09baf84)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
```
```
In drivers/iommu/ipmmu-vmsa.c (c09c23ac)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_resume_noirq
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_remove
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_probe
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_detach_device
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_irq
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_domain_setup_context
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_utlb_enable
  - drivers/iommu/ipmmu-vmsa.c:ipmmu_utlb_enable
```
```
In drivers/ata/libata-sff.c (c0a7ebac)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_setup
```
```
In drivers/net/ethernet/freescale/xgmac_mdio.c (c0acf2c0)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/xgmac_mdio.c:xgmac_write32
```
```
In drivers/firmware/arm_scmi/driver.c (c0c37960)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
  - drivers/firmware/arm_scmi/driver.c:scmi_tx_prepare
```
```
In drivers/firmware/arm_scmi/perf.c (c0c3985c)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_level_set
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_set
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_limits_set
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_cmt.c (c0c441a0)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_write32
```
```
In drivers/clocksource/sh_tmu.c (c0c46358)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_set_next
  - drivers/clocksource/sh_tmu.c:sh_tmu_set_next
  - drivers/clocksource/sh_tmu.c:sh_tmu_set_next
  - drivers/clocksource/sh_tmu.c:__sh_tmu_enable
  - drivers/clocksource/sh_tmu.c:__sh_tmu_enable
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
```
```
In drivers/clocksource/em_sti.c (c0c46d90)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/clocksource/em_sti.c:em_sti_clock_event_next
  - drivers/clocksource/em_sti.c:em_sti_clock_event_next
  - drivers/clocksource/em_sti.c:em_sti_clock_event_next
  - drivers/clocksource/em_sti.c:em_sti_clock_event_next
  - drivers/clocksource/em_sti.c:em_sti_clock_event_next
  - drivers/clocksource/em_sti.c:em_sti_stop
  - drivers/clocksource/em_sti.c:em_sti_start
  - drivers/clocksource/em_sti.c:em_sti_start
  - drivers/clocksource/em_sti.c:em_sti_start
  - drivers/clocksource/em_sti.c:em_sti_start
  - drivers/clocksource/em_sti.c:em_sti_start
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iomap.c (c0000000007e6e20)
Location: lib/iomap.c:201
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_finalize_features
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
```
**Symbols:**

```
c0000000007e6e20-c0000000007e6ecc: iowrite32 (STB_GLOBAL)
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
In drivers/pci/quirks.c (ffffffe0004ce058)
Location: include/asm-generic/io.h:736
Inline: True
```
```
In drivers/clk/clk-hsdk-pll.c (ffffffe0005151b8)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/clk/clk-hsdk-pll.c:hsdk_pll_comm_update_rate
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffe00051d7d0)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_iowrite64_twopart
  - drivers/virtio/virtio_pci_modern.c:vp_iowrite64_twopart
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffe00051f508)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
```
```
In drivers/char/tpm/tpm_tis.c (ffffffe0005739e0)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
```
```
In drivers/ata/libata-sff.c (ffffffe00060c538)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_setup
```
```
In drivers/spi/spi-sifive.c (ffffffe00061c23a)
Location: include/asm-generic/io.h:736
Inline: True
Inline callers:
  - drivers/spi/spi-sifive.c:sifive_spi_remove
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_probe
  - drivers/spi/spi-sifive.c:sifive_spi_transfer_one
  - drivers/spi/spi-sifive.c:sifive_spi_transfer_one
  - drivers/spi/spi-sifive.c:sifive_spi_transfer_one
  - drivers/spi/spi-sifive.c:sifive_spi_transfer_one
  - drivers/spi/spi-sifive.c:sifive_spi_set_cs
  - drivers/spi/spi-sifive.c:sifive_spi_prepare_message
  - drivers/spi/spi-sifive.c:sifive_spi_prepare_message
  - drivers/spi/spi-sifive.c:sifive_spi_prepare_message
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
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81529c80)
Location: lib/iomap.c:201
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
```
**Symbols:**

```
ffffffff81529c80-ffffffff81529cb1: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81519f60)
Location: lib/iomap.c:201
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81519f60-ffffffff81519f91: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81525d10)
Location: lib/iomap.c:201
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81525d10-ffffffff81525d41: iowrite32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iowrite32(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8153f690)
Location: lib/iomap.c:201
Inline: False
Direct callers:
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - arch/x86/kernel/early-quirks.c:apple_airport_reset
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_modern.c:vp_get_features
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_clkrun_enable
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write32
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/char/tpm/tpm_crb.c:crb_send
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/ata_piix.c:piix_init_one
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_write
  - drivers/ata/ata_piix.c:piix_sidpr_scr_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff8153f690-ffffffff8153f6c1: iowrite32 (STB_GLOBAL)
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
