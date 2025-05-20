# Function: <code>blk_queue_max_hw_sectors</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff813be460)
Location: block/blk-settings.c:237
Inline: False
Direct callers:
  - drivers/block/brd.c:brd_alloc
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:xlvbd_alloc_gendisk
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff813be460-ffffffff813be4db: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814023e0)
Location: block/blk-settings.c:237
Inline: False
Direct callers:
  - drivers/block/brd.c:brd_alloc
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff814023e0-ffffffff8140245b: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141c050)
Location: block/blk-settings.c:241
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff8141c050-ffffffff8141c0d5: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81429fe0)
Location: block/blk-settings.c:236
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81429fe0-ffffffff8142a069: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81455220)
Location: block/blk-settings.c:237
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81455220-ffffffff814552a9: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:237
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81488d99-ffffffff81488dcb: blk_queue_max_hw_sectors.cold.7 (STB_LOCAL)
ffffffff81488610-ffffffff8148866e: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:181
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff814a2c99-ffffffff814a2ccb: blk_queue_max_hw_sectors.cold.6 (STB_LOCAL)
ffffffff814a2530-ffffffff814a258b: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:182
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff814d0d4b-ffffffff814d0d7d: blk_queue_max_hw_sectors.cold (STB_LOCAL)
ffffffff814d0600-ffffffff814d065b: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:183
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff814ea10b-ffffffff814ea13d: blk_queue_max_hw_sectors.cold (STB_LOCAL)
ffffffff814e9980-ffffffff814e99db: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:149
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff815490ad-ffffffff815490df: blk_queue_max_hw_sectors.cold (STB_LOCAL)
ffffffff815487d0-ffffffff8154882e: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:149
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81bf26ef-ffffffff81bf2711: blk_queue_max_hw_sectors.cold (STB_LOCAL)
ffffffff815645a0-ffffffff8156460d: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:122
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81be46b6-ffffffff81be46d8: blk_queue_max_hw_sectors.cold (STB_LOCAL)
ffffffff8156cc70-ffffffff8156ccd9: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:123
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81cd8159-ffffffff81cd817b: blk_queue_max_hw_sectors.cold (STB_LOCAL)
ffffffff815d11b0-ffffffff815d1225: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:122
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81e8b51f-ffffffff81e8b541: blk_queue_max_hw_sectors.cold (STB_LOCAL)
ffffffff8167cb80-ffffffff8167cc06: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817394e0)
Location: block/blk-settings.c:122
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff817394e0-ffffffff81739584: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81775ba0)
Location: block/blk-settings.c:123
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81775ba0-ffffffff81775c56: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817b7e70)
Location: block/blk-settings.c:123
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff817b7e70-ffffffff817b7f23: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffff8000105e7b68)
Location: block/blk-settings.c:183
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffff8000105e7b68-ffff8000105e7c10: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c079452c)
Location: block/blk-settings.c:183
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
c079452c-c07945bc: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c00000000077c350)
Location: block/blk-settings.c:183
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
c00000000077c350-c00000000077c42c: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffe00042886e)
Location: block/blk-settings.c:183
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/mmc/core/queue.c:mmc_init_queue
```
**Symbols:**

```
ffffffe00042886e-ffffffe000428904: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:183
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/nvme/host/core.c:nvme_set_queue_limits
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff814e26eb-ffffffff814e271d: blk_queue_max_hw_sectors.cold (STB_LOCAL)
ffffffff814e1f60-ffffffff814e1fbb: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:183
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_add
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/blk.c:nd_blk_probe
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/nvme/host/core.c:nvme_set_queue_limits
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff814d307b-ffffffff814d30ad: blk_queue_max_hw_sectors.cold (STB_LOCAL)
ffffffff814d28f0-ffffffff814d294b: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:183
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff814de77b-ffffffff814de7ad: blk_queue_max_hw_sectors.cold (STB_LOCAL)
ffffffff814ddff0-ffffffff814de04b: blk_queue_max_hw_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void blk_queue_max_hw_sectors(struct request_queue *q, unsigned int max_hw_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-settings.c (0)
Location: block/blk-settings.c:183
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_create_tgt
  - drivers/block/loop.c:loop_add
  - drivers/block/xen-blkfront.c:blkif_set_queue_limits
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff814f75db-ffffffff814f760d: blk_queue_max_hw_sectors.cold (STB_LOCAL)
ffffffff814f6e50-ffffffff814f6eab: blk_queue_max_hw_sectors (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
