# Function: <code>iowrite8</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81402770)
Location: lib/iomap.c:112
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/char/tpm/tpm_tis.c:tpm_tis_resume
  - drivers/char/tpm/tpm_tis.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis.c:tpm_tis_remove
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/ata/libata-sff.c:ata_sff_set_devctl
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
```
**Symbols:**

```
ffffffff81402770-ffffffff814027a2: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8144a420)
Location: lib/iomap.c:112
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_set_devctl
```
**Symbols:**

```
ffffffff8144a420-ffffffff8144a452: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81468de0)
Location: lib/iomap.c:112
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_set_devctl
```
**Symbols:**

```
ffffffff81468de0-ffffffff81468e12: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8146e4c0)
Location: lib/iomap.c:112
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_set_devctl
```
**Symbols:**

```
ffffffff8146e4c0-ffffffff8146e4f2: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8149a7f0)
Location: lib/iomap.c:113
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_set_devctl
```
**Symbols:**

```
ffffffff8149a7f0-ffffffff8149a824: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814cfaa0)
Location: lib/iomap.c:113
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_set_devctl
```
**Symbols:**

```
ffffffff814cfaa0-ffffffff814cfad4: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814e43b0)
Location: lib/iomap.c:113
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_set_devctl
```
**Symbols:**

```
ffffffff814e43b0-ffffffff814e43e4: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81510bb0)
Location: lib/iomap.c:189
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_set_devctl
```
**Symbols:**

```
ffffffff81510bb0-ffffffff81510be1: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81531620)
Location: lib/iomap.c:189
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_set_devctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
```
**Symbols:**

```
ffffffff81531620-ffffffff81531651: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81595b60)
Location: lib/iomap.c:189
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_postreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_freeze
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_irq_on
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_handler
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
```
**Symbols:**

```
ffffffff81595b60-ffffffff81595bac: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815b15f0)
Location: lib/iomap.c:189
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_postreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_freeze
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_irq_on
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
```
**Symbols:**

```
ffffffff815b15f0-ffffffff815b163c: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815bc400)
Location: lib/iomap.c:189
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_status
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_postreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_freeze
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_irq_on
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
```
**Symbols:**

```
ffffffff815bc400-ffffffff815bc44c: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81623250)
Location: lib/iomap.c:189
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_status
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set_status
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_postreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_freeze
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_irq_on
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
```
**Symbols:**

```
ffffffff81623250-ffffffff8162329c: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff816f3040)
Location: lib/iomap.c:189
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_status
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_status
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_postreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_freeze
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd_do_write
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
```
**Symbols:**

```
ffffffff816f3040-ffffffff816f30bb: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff817e4f30)
Location: lib/iomap.c:203
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_status
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_status
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite8
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_postreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_freeze
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
```
**Symbols:**

```
ffffffff817e4f30-ffffffff817e4fab: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81824f70)
Location: lib/iomap.c:203
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_status
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_status
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite8
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_postreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_freeze
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
```
**Symbols:**

```
ffffffff81824f70-ffffffff81824feb: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81876980)
Location: lib/iomap.c:203
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_status
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_set_status
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite8
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_postreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_thaw
  - drivers/ata/libata-sff.c:ata_sff_freeze
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
```
**Symbols:**

```
ffffffff81876980-ffffffff818769fb: iowrite8 (STB_GLOBAL)
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
In drivers/pinctrl/sh-pfc/core.c (ffff8000106afcb8)
Location: include/asm-generic/io.h:720
Inline: True
```
```
In drivers/pci/controller/dwc/pci-layerscape.c (ffff80001073355c)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_host_init
```
```
In drivers/virtio/virtio_pci_modern.c (ffff8000108272a0)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
```
```
In drivers/virtio/virtio_pci_legacy.c (ffff8000108292d0)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
```
```
In drivers/char/tpm/tpm_tis.c (ffff8000108c273c)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
```
```
In drivers/ata/libata-sff.c (ffff8000109b1688)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_postreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_freeze
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fb560)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_enable
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
```
```
In drivers/firmware/arm_scmi/perf.c (ffff800010b57ed4)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b65c14)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
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
In arch/arm/mach-shmobile/setup-r8a7740.c (c15198c8)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
  - arch/arm/mach-shmobile/setup-r8a7740.c:r8a7740_init_irq_of
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081ef9c)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_write8
```
```
In drivers/pinctrl/sh-pfc/core.c (c085366c)
Location: include/asm-generic/io.h:720
Inline: True
```
```
In drivers/pinctrl/sh-pfc/pfc-r8a7740.c (c0855704)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pfc-r8a7740.c:r8a7740_pinmux_set_bias
```
```
In drivers/pinctrl/sh-pfc/pfc-sh73a0.c (c0855bd0)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_pinmux_set_bias
```
```
In drivers/virtio/virtio_pci_modern.c (c0945014)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
```
```
In drivers/virtio/virtio_pci_legacy.c (c0946ee8)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
```
```
In drivers/char/tpm/tpm_tis.c (c09bafdc)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
```
```
In drivers/mfd/tc6393xb.c (c0a13da0)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_resume
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_probe
  - drivers/mfd/tc6393xb.c:tc6393xb_lcd_set_power
```
```
In drivers/ata/libata-sff.c (c0a7ff80)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_set_devctl
```
```
In drivers/mtd/nand/raw/omap2.c (c0aa9bec)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/mtd/nand/raw/omap2.c:omap_write_buf8
```
```
In drivers/firmware/arm_scmi/perf.c (c0c396f4)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_mtu2.c (c0c45b38)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_interrupt
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_start_stop_ch
```
```
In drivers/clocksource/sh_tmu.c (c0c45f30)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
  - drivers/clocksource/sh_tmu.c:sh_tmu_start_stop_ch
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iomap.c (c0000000007e55b0)
Location: lib/iomap.c:189
Inline: True
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set_status
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set_status
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_set_devctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
```
**Symbols:**

```
c0000000007e55b0-c0000000007e565c: iowrite8 (STB_GLOBAL)
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
In drivers/virtio/virtio_pci_modern.c (ffffffe00051d6fc)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffe00051f6f0)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
```
```
In drivers/char/tpm/tpm_tis.c (ffffffe0005738e6)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
```
```
In drivers/ata/libata-sff.c (ffffffe00060db78)
Location: include/asm-generic/io.h:720
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
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
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81529c00)
Location: lib/iomap.c:189
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_set_devctl
```
**Symbols:**

```
ffffffff81529c00-ffffffff81529c31: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81519ee0)
Location: lib/iomap.c:189
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_set_devctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
```
**Symbols:**

```
ffffffff81519ee0-ffffffff81519f11: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81525c90)
Location: lib/iomap.c:189
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_set_devctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
```
**Symbols:**

```
ffffffff81525c90-ffffffff81525cc1: iowrite8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iowrite8(u8 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8153f610)
Location: lib/iomap.c:189
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_set
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_write_bytes
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_tf_load
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/libata-sff.c:ata_sff_set_devctl
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
```
**Symbols:**

```
ffffffff8153f610-ffffffff8153f641: iowrite8 (STB_GLOBAL)
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
