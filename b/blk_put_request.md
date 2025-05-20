# Function: <code>blk_put_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b6770)
Location: block/blk-core.c:1498
Inline: False
Direct callers:
  - block/blk-core.c:blk_make_request
  - block/scsi_ioctl.c:sg_io
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/bsg.c:blk_complete_sgv4_hdr_rq
  - block/bsg.c:blk_complete_sgv4_hdr_rq
  - drivers/block/virtio_blk.c:virtblk_serial_show
  - drivers/scsi/scsi_lib.c:scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff813b6770-ffffffff813b67ce: blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fb5d0)
Location: block/blk-core.c:1458
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:blk_complete_sgv4_hdr_rq
  - block/bsg.c:blk_complete_sgv4_hdr_rq
  - drivers/block/virtio_blk.c:virtblk_serial_show
  - drivers/scsi/scsi_lib.c:scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff813fb5d0-ffffffff813fb62e: blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814150c0)
Location: block/blk-core.c:1463
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:blk_complete_sgv4_hdr_rq
  - block/bsg.c:blk_complete_sgv4_hdr_rq
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814150c0-ffffffff8141511e: blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81423620)
Location: block/blk-core.c:1566
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:blk_complete_sgv4_hdr_rq
  - block/bsg.c:blk_complete_sgv4_hdr_rq
  - drivers/scsi/scsi_lib.c:scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff81423620-ffffffff8142367b: blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144f010)
Location: block/blk-core.c:1686
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:blk_complete_sgv4_hdr_rq
  - block/bsg.c:blk_complete_sgv4_hdr_rq
  - drivers/scsi/scsi_lib.c:scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff8144f010-ffffffff8144f06b: blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81481bd0)
Location: block/blk-core.c:1783
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:blk_complete_sgv4_hdr_rq
  - block/bsg.c:blk_complete_sgv4_hdr_rq
  - drivers/scsi/scsi_lib.c:scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff81481bd0-ffffffff81481c2d: blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149cfc0)
Location: block/blk-core.c:591
Inline: False
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_ioctl
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff8149cfc0-ffffffff8149cfd0: blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb150)
Location: block/blk-core.c:589
Inline: False
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg-lib.c:bsg_transport_free_rq
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814cb150-ffffffff814cb160: blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e4340)
Location: block/blk-core.c:593
Inline: False
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg-lib.c:bsg_transport_free_rq
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814e4340-ffffffff814e4350: blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81542a70)
Location: block/blk-core.c:635
Inline: False
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg-lib.c:bsg_transport_free_rq
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
```
**Symbols:**

```
ffffffff81542a70-ffffffff81542a80: blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155f3d0)
Location: block/blk-core.c:644
Inline: False
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg-lib.c:bsg_transport_free_rq
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
```
**Symbols:**

```
ffffffff8155f3d0-ffffffff8155f3e0: blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81567c40)
Location: block/blk-core.c:645
Inline: False
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg-lib.c:bsg_transport_free_rq
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_bpc
```
**Symbols:**

```
ffffffff81567c40-ffffffff81567c50: blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cc270)
Location: block/blk-core.c:643
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
**Symbols:**

```
ffffffff815cc270-ffffffff815cc280: blk_put_request (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e0578)
Location: block/blk-core.c:593
Inline: False
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg-lib.c:bsg_transport_free_rq
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/mmc/core/block.c:mmc_ext_csd_open
  - drivers/mmc/core/block.c:mmc_dbg_card_status_get
  - drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd
  - drivers/mmc/core/block.c:mmc_blk_ioctl_cmd
```
**Symbols:**

```
ffff8000105e0578-ffff8000105e05a4: blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078e814)
Location: block/blk-core.c:593
Inline: False
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg-lib.c:bsg_transport_free_rq
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/mmc/core/block.c:mmc_ext_csd_open
  - drivers/mmc/core/block.c:mmc_dbg_card_status_get
  - drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd
  - drivers/mmc/core/block.c:mmc_blk_ioctl_cmd
```
**Symbols:**

```
c078e814-c078e830: blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000774830)
Location: block/blk-core.c:593
Inline: False
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg-lib.c:bsg_transport_free_rq
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
c000000000774830-c000000000774864: blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000423a66)
Location: block/blk-core.c:593
Inline: False
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg-lib.c:bsg_transport_free_rq
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/mmc/core/block.c:mmc_ext_csd_open
  - drivers/mmc/core/block.c:mmc_dbg_card_status_get
  - drivers/mmc/core/block.c:mmc_blk_ioctl_multi_cmd
  - drivers/mmc/core/block.c:mmc_blk_ioctl_cmd
```
**Symbols:**

```
ffffffe000423a66-ffffffe000423a90: blk_put_request (STB_GLOBAL)
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
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dc920)
Location: block/blk-core.c:593
Inline: False
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg-lib.c:bsg_transport_free_rq
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814dc920-ffffffff814dc930: blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd2d0)
Location: block/blk-core.c:593
Inline: False
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg-lib.c:bsg_transport_free_rq
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814cd2d0-ffffffff814cd2e0: blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d89b0)
Location: block/blk-core.c:593
Inline: False
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg-lib.c:bsg_transport_free_rq
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814d89b0-ffffffff814d89c0: blk_put_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_put_request(struct request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f15c0)
Location: block/blk-core.c:593
Inline: False
Direct callers:
  - block/blk-merge.c:blk_attempt_req_merge
  - block/scsi_ioctl.c:sg_scsi_ioctl
  - block/scsi_ioctl.c:sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg.c:bsg_sg_io
  - block/bsg-lib.c:bsg_transport_free_rq
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_audio
```
**Symbols:**

```
ffffffff814f15c0-ffffffff814f15d0: blk_put_request (STB_GLOBAL)
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
