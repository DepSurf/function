# Function: <code>blk_rq_set_block_pc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_set_block_pc(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b4750)
Location: block/blk-core.c:1365
Inline: True
Inline callers:
  - block/blk-core.c:blk_make_request
Direct callers:
  - block/scsi_ioctl.c:sg_io
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff813b4750-ffffffff813b4797: blk_rq_set_block_pc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_rq_set_block_pc(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fa160)
Location: block/blk-core.c:1327
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_lib.c:scsi_execute
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff813fa160-ffffffff813fa188: blk_rq_set_block_pc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_rq_set_block_pc(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81413ae0)
Location: block/blk-core.c:1328
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff81413ae0-ffffffff81413b08: blk_rq_set_block_pc (STB_GLOBAL)
```
</details>
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
In <code>ppc64el</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
