# Function: <code>ioread16</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int ioread16(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814026f0)
Location: lib/iomap.c:76
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/char/tpm/tpm_tis.c:tpm_tis_init
  - drivers/ata/libata-sff.c:ata_sff_drain_fifo
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
```
**Symbols:**

```
ffffffff814026f0-ffffffff81402729: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int ioread16(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8144a3a0)
Location: lib/iomap.c:76
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
  - drivers/ata/libata-sff.c:ata_sff_drain_fifo
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff8144a3a0-ffffffff8144a3d9: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int ioread16(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81468d60)
Location: lib/iomap.c:76
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
  - drivers/ata/libata-sff.c:ata_sff_drain_fifo
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81468d60-ffffffff81468d99: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int ioread16(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8146e440)
Location: lib/iomap.c:76
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff8146e440-ffffffff8146e479: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int ioread16(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8149a770)
Location: lib/iomap.c:77
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff8149a770-ffffffff8149a7ab: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int ioread16(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814cfa20)
Location: lib/iomap.c:77
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff814cfa20-ffffffff814cfa5b: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int ioread16(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814e4330)
Location: lib/iomap.c:77
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_init
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff814e4330-ffffffff814e436b: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int ioread16(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81510a90)
Location: lib/iomap.c:78
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81510a90-ffffffff81510ac9: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int ioread16(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81531500)
Location: lib/iomap.c:78
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81531500-ffffffff81531539: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int ioread16(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815957d0)
Location: lib/iomap.c:78
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff815957d0-ffffffff81595833: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int ioread16(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815b1260)
Location: lib/iomap.c:78
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff815b1260-ffffffff815b12c3: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int ioread16(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815bc070)
Location: lib/iomap.c:78
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_num_queues
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_size
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_enable
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_config_vector
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff815bc070-ffffffff815bc0d3: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int ioread16(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81622ec0)
Location: lib/iomap.c:78
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_num_queues
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_size
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_enable
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_config_vector
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81622ec0-ffffffff81622f23: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int ioread16(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff816f2c60)
Location: lib/iomap.c:78
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_num_queues
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_size
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_enable
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_config_vector
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_size
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_config_vector
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_queue_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff816f2c60-ffffffff816f2ce5: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int ioread16(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff817e4ae0)
Location: lib/iomap.c:85
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_num_queues
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_size
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_enable
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_config_vector
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_reset
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_size
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_config_vector
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_queue_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread16le
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff817e4ae0-ffffffff817e4b65: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int ioread16(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81824b20)
Location: lib/iomap.c:85
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_num_queues
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_size
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_enable
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_config_vector
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_reset
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_size
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_config_vector
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_queue_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread16le
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81824b20-ffffffff81824ba5: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int ioread16(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81876530)
Location: lib/iomap.c:85
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_avq_index
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_avq_num
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_map_vq_notify
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_num_queues
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_size
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_enable
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_config_vector
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_queue_vector
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_set_queue_reset
  - drivers/virtio/virtio_pci_modern_dev.c:vp_modern_get_queue_reset
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_get_queue_size
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_config_vector
  - drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_queue_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read_bytes
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread16le
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_evaluate
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81876530-ffffffff818765b5: ioread16 (STB_GLOBAL)
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
In drivers/pinctrl/sh-pfc/core.c (ffff8000106afbf8)
Location: include/asm-generic/io.h:694
Inline: True
```
```
In drivers/pci/quirks.c (ffff8000106fcaf4)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
```
```
In drivers/virtio/virtio_pci_modern.c (ffff8000108274b0)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
```
```
In drivers/virtio/virtio_pci_legacy.c (ffff800010829358)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
```
```
In drivers/char/tpm/tpm_tis.c (ffff8000108c2784)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
```
```
In drivers/ata/libata-sff.c (ffff8000109b03f8)
Location: include/asm-generic/io.h:694
Inline: True
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fb2d8)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_seteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_ethtool_geteeprom
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_timeout
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_interrupt
  - drivers/net/ethernet/smsc/smc91x.c:smc_10bt_check_media
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_write
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_read
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_read
  - drivers/net/ethernet/smsc/smc91x.c:smc_phy_read
  - drivers/net/ethernet/smsc/smc91x.c:smc_mii_out
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_tx
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/ethernet/smsc/smc91x.c:smc_shutdown
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
  - drivers/net/ethernet/smsc/smc91x.c:smc_reset
```
```
In drivers/firmware/arm_scmi/perf.c (ffff800010b57f68)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_cmt.c (ffff800010b63c8c)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_read16
```
```
In drivers/clocksource/sh_tmu.c (ffff800010b660c8)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_set_next
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
In drivers/pinctrl/pinctrl-rza1.c (c083c220)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux
  - drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux
  - drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux
  - drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux
  - drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux
  - drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux
  - drivers/pinctrl/pinctrl-rza1.c:rza1_set_mux
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_set
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_get
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_output
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_direction_input
  - drivers/pinctrl/pinctrl-rza1.c:rza1_gpio_get_direction
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset
  - drivers/pinctrl/pinctrl-rza1.c:rza1_pin_reset
```
```
In drivers/pinctrl/sh-pfc/core.c (c08535f0)
Location: include/asm-generic/io.h:694
Inline: True
```
```
In drivers/pci/quirks.c (c0895164)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
```
```
In drivers/clk/renesas/clk-rz.c (c157e884)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/clk/renesas/clk-rz.c:rz_cpg_clocks_init
```
```
In drivers/virtio/virtio_pci_modern.c (c0944e54)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
```
```
In drivers/virtio/virtio_pci_legacy.c (c0946dc8)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
```
```
In drivers/char/tpm/tpm_tis.c (c09baef0)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
```
```
In drivers/mfd/asic3.c (c0a0eebc)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/mfd/asic3.c:asic3_clk_disable
  - drivers/mfd/asic3.c:asic3_clk_enable
  - drivers/mfd/asic3.c:asic3_gpio_set
  - drivers/mfd/asic3.c:asic3_gpio_get
  - drivers/mfd/asic3.c:asic3_gpio_direction
  - drivers/mfd/asic3.c:asic3_gpio_irq_type
  - drivers/mfd/asic3.c:asic3_gpio_irq_type
  - drivers/mfd/asic3.c:asic3_gpio_irq_type
  - drivers/mfd/asic3.c:asic3_unmask_irq
  - drivers/mfd/asic3.c:asic3_unmask_gpio_irq
  - drivers/mfd/asic3.c:asic3_mask_irq
  - drivers/mfd/asic3.c:asic3_mask_gpio_irq
  - drivers/mfd/asic3.c:asic3_irq_demux
  - drivers/mfd/asic3.c:asic3_irq_demux
  - drivers/mfd/asic3.c:asic3_irq_demux
  - drivers/mfd/asic3.c:asic3_set_register
```
```
In drivers/mfd/tc6393xb.c (c0a132d8)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/mfd/tc6393xb.c:tc6393xb_suspend
```
```
In drivers/ata/libata-sff.c (c0a7ffd8)
Location: include/asm-generic/io.h:694
Inline: True
```
```
In drivers/firmware/arm_scmi/perf.c (c0c39748)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/perf.c:scmi_perf_fc_ring_db
```
```
In drivers/clocksource/sh_cmt.c (c0c44090)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/clocksource/sh_cmt.c:sh_cmt_read16
```
```
In drivers/clocksource/sh_mtu2.c (0)
Location: include/asm-generic/io.h:694
Inline: True
```
```
In drivers/clocksource/sh_tmu.c (c0c46328)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/clocksource/sh_tmu.c:sh_tmu_set_next
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
unsigned int ioread16(void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iomap.c (c0000000007e5ef0)
Location: lib/iomap.c:78
Inline: True
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
```
**Symbols:**

```
c0000000007e5ef0-c0000000007e609c: ioread16 (STB_GLOBAL)
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
In drivers/pci/quirks.c (ffffffe0004cc768)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffe00051d59e)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
```
```
In drivers/virtio/virtio_pci_legacy.c (ffffffe00051f59a)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
```
```
In drivers/char/tpm/tpm_tis.c (ffffffe00057394a)
Location: include/asm-generic/io.h:694
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
```
```
In drivers/ata/libata-sff.c (ffffffe00060dbea)
Location: include/asm-generic/io.h:694
Inline: True
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
unsigned int ioread16(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81529ae0)
Location: lib/iomap.c:78
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
```
**Symbols:**

```
ffffffff81529ae0-ffffffff81529b19: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int ioread16(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81519dc0)
Location: lib/iomap.c:78
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81519dc0-ffffffff81519df9: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int ioread16(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81525b70)
Location: lib/iomap.c:78
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff81525b70-ffffffff81525ba9: ioread16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int ioread16(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8153f4f0)
Location: lib/iomap.c:78
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_switchtec_ntb_dma_alias
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_config_vector
  - drivers/virtio/virtio_pci_modern.c:vp_get
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:setup_vq
  - drivers/virtio/virtio_pci_legacy.c:vp_config_vector
  - drivers/char/tpm/tpm_tis.c:tpm_tcg_read16
  - drivers/vfio/pci/vfio_pci_rdwr.c:do_io_rw
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_probe
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
  - drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq
```
**Symbols:**

```
ffffffff8153f4f0-ffffffff8153f529: ioread16 (STB_GLOBAL)
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
