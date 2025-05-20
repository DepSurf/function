# Function: <code>ioread8</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int ioread8(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814026b0)
Location: lib/iomap.c:71
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/char/tpm/tpm_tis.c:get_burstcount
  - drivers/char/tpm/tpm_tis.c:get_burstcount
  - drivers/char/tpm/tpm_tis.c:recv_data
  - drivers/char/tpm/tpm_tis.c:tis_int_handler
  - drivers/char/tpm/tpm_tis.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis.c:tpm_tis_send_data
  - drivers/char/tpm/tpm_tis.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff814026b0-ffffffff814026e7: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int ioread8(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8144a360)
Location: lib/iomap.c:71
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff8144a360-ffffffff8144a397: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int ioread8(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81468d20)
Location: lib/iomap.c:71
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81468d20-ffffffff81468d57: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int ioread8(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8146e400)
Location: lib/iomap.c:71
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff8146e400-ffffffff8146e437: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int ioread8(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8149a730)
Location: lib/iomap.c:72
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff8149a730-ffffffff8149a769: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int ioread8(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814cf9e0)
Location: lib/iomap.c:72
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
```
**Symbols:**

```
ffffffff814cf9e0-ffffffff814cfa19: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int ioread8(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814e42f0)
Location: lib/iomap.c:72
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
```
**Symbols:**

```
ffffffff814e42f0-ffffffff814e4329: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int ioread8(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81510a50)
Location: lib/iomap.c:73
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
```
**Symbols:**

```
ffffffff81510a50-ffffffff81510a87: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int ioread8(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815314c0)
Location: lib/iomap.c:73
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
```
**Symbols:**

```
ffffffff815314c0-ffffffff815314f7: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int ioread8(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81595760)
Location: lib/iomap.c:73
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:atapi_pio_bytes
  - drivers/ata/libata-sff.c:atapi_send_cdb
  - drivers/ata/libata-sff.c:ata_pio_sectors
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
```
**Symbols:**

```
ffffffff81595760-ffffffff815957c1: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int ioread8(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815b11f0)
Location: lib/iomap.c:73
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:atapi_pio_bytes
  - drivers/ata/libata-sff.c:atapi_send_cdb
  - drivers/ata/libata-sff.c:ata_pio_sectors
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
```
**Symbols:**

```
ffffffff815b11f0-ffffffff815b1251: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int ioread8(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815bc000)
Location: lib/iomap.c:73
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_status
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sectors
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
```
**Symbols:**

```
ffffffff815bc000-ffffffff815bc061: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int ioread8(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81622e50)
Location: lib/iomap.c:73
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_status
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:atapi_pio_bytes
  - drivers/ata/libata-sff.c:ata_pio_sectors
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
```
**Symbols:**

```
ffffffff81622e50-ffffffff81622eb1: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int ioread8(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff816f2bd0)
Location: lib/iomap.c:73
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_status
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_generation
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:__ata_sff_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sectors
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
```
**Symbols:**

```
ffffffff816f2bd0-ffffffff816f2c53: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int ioread8(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff817e4a40)
Location: lib/iomap.c:79
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_status
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_generation
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread8
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:__ata_sff_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sectors
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
```
**Symbols:**

```
ffffffff817e4a40-ffffffff817e4ac3: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int ioread8(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81824a80)
Location: lib/iomap.c:79
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_status
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_generation
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread8
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:__ata_sff_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sectors
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
```
**Symbols:**

```
ffffffff81824a80-ffffffff81824b03: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int ioread8(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81876490)
Location: lib/iomap.c:79
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_status
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_generation
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread8
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
  - drivers/ata/libata-sff.c:__ata_sff_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_pio_sectors
  - drivers/ata/libata-sff.c:ata_sff_exec_command
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_dev_select
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
```
**Symbols:**

```
ffffffff81876490-ffffffff81876513: ioread8 (STB_GLOBAL)
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
In drivers/pinctrl/sh-pfc/core.c (ffff8000106afc1c)
Location: include/asm-generic/io.h:686
Inline: True
```
```
In drivers/pci/quirks.c (ffff8000106fca24)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
```
```
In drivers/pci/controller/dwc/pci-layerscape.c (ffff80001147a534)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-layerscape.c:ls_pcie_probe
```
```
In drivers/virtio/virtio_pci_modern.c (ffff8000108272b4)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
```
```
In drivers/virtio/virtio_pci_common.c (ffff8000108284fc)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
```
```
In drivers/virtio/virtio_pci_legacy.c (ffff800010829078)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff800010890120)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
```
```
In drivers/char/tpm/tpm_tis.c (ffff8000108c26a8)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
```
```
In drivers/ata/libata-sff.c (ffff8000109b17a8)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fb590)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
```
```
In drivers/firmware/arm_scmi/perf.c (ffff800010b57f04)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b65bb4)
Location: include/asm-generic/io.h:686
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
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081ed28)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_read8
```
```
In drivers/pinctrl/sh-pfc/core.c (c0853600)
Location: include/asm-generic/io.h:686
Inline: True
```
```
In drivers/pinctrl/sh-pfc/pfc-r8a7740.c (c08556dc)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pfc-r8a7740.c:r8a7740_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-r8a7740.c:r8a7740_pinmux_get_bias
```
```
In drivers/pinctrl/sh-pfc/pfc-sh73a0.c (c0855ba8)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_pinmux_set_bias
  - drivers/pinctrl/sh-pfc/pfc-sh73a0.c:sh73a0_pinmux_get_bias
```
```
In drivers/pci/quirks.c (c0895064)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
```
```
In drivers/virtio/virtio_pci_modern.c (c0945038)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
```
```
In drivers/virtio/virtio_pci_common.c (c0945f90)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
```
```
In drivers/virtio/virtio_pci_legacy.c (c0946d0c)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
```
```
In drivers/tty/serial/8250/8250_pci.c (c098af0c)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
```
```
In drivers/char/tpm/tpm_tis.c (c09baeb4)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
```
```
In drivers/mfd/tc6393xb.c (c0a132f0)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/mfd/tc6393xb.c:tc6393xb_suspend
  - drivers/mfd/tc6393xb.c:tc6393xb_suspend
  - drivers/mfd/tc6393xb.c:tc6393xb_suspend
  - drivers/mfd/tc6393xb.c:tc6393xb_suspend
  - drivers/mfd/tc6393xb.c:tc6393xb_lcd_set_power
```
```
In drivers/ata/libata-sff.c (c0a804a4)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
```
```
In drivers/firmware/arm_scmi/perf.c (c0c396d4)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_mtu2.c (c0c45b2c)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_interrupt
  - drivers/clocksource/sh_mtu2.c:sh_mtu2_start_stop_ch
```
```
In drivers/clocksource/sh_tmu.c (c0c45eec)
Location: include/asm-generic/io.h:686
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
unsigned int ioread8(void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iomap.c (c0000000007e5a10)
Location: lib/iomap.c:73
Inline: True
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
```
**Symbols:**

```
c0000000007e5a10-c0000000007e5b9c: ioread8 (STB_GLOBAL)
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
In drivers/pci/quirks.c (ffffffe0004cc6b8)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffe00051d738)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
```
```
In drivers/virtio/virtio_pci_common.c (ffffffe00051e6d2)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffe00051f4f4)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffe000557196)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
```
```
In drivers/char/tpm/tpm_tis.c (ffffffe000573882)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
```
```
In drivers/ata/libata-sff.c (ffffffe00060e00e)
Location: include/asm-generic/io.h:686
Inline: True
Inline callers:
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_lost_interrupt
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
unsigned int ioread8(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81529aa0)
Location: lib/iomap.c:73
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/ata_generic.c:generic_set_mode
```
**Symbols:**

```
ffffffff81529aa0-ffffffff81529ad7: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int ioread8(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81519d80)
Location: lib/iomap.c:73
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
```
**Symbols:**

```
ffffffff81519d80-ffffffff81519db7: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int ioread8(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81525b30)
Location: lib/iomap.c:73
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
```
**Symbols:**

```
ffffffff81525b30-ffffffff81525b67: ioread8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int ioread8(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8153f4b0)
Location: lib/iomap.c:73
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_get_status
  - drivers/virtio/virtio_pci_modern.c:vp_generation
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_common.c:vp_interrupt
  - drivers/virtio/virtio_pci_legacy.c:del_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_reset
  - drivers/virtio/virtio_pci_legacy.c:vp_get_status
  - drivers/virtio/virtio_pci_legacy.c:vp_get
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_init
  - drivers/tty/serial/8250/8250_pci.c:pci_endrun_init
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/ata/libata-sff.c:ata_pci_bmdma_init
  - drivers/ata/libata-sff.c:ata_bmdma_status
  - drivers/ata/libata-sff.c:ata_bmdma_stop
  - drivers/ata/libata-sff.c:ata_bmdma_start
  - drivers/ata/libata-sff.c:ata_bmdma_setup
  - drivers/ata/libata-sff.c:ata_bmdma_irq_clear
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_devchk
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/libata-sff.c:ata_sff_tf_read
  - drivers/ata/ata_generic.c:generic_set_mode
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
```
**Symbols:**

```
ffffffff8153f4b0-ffffffff8153f4e7: ioread8 (STB_GLOBAL)
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
