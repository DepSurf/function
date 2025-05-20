# Function: <code>blk_mq_free_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c3040)
Location: block/blk-mq.c:294
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
```
**Symbols:**

```
ffffffff813c3040-ffffffff813c308c: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81406c80)
Location: block/blk-mq.c:350
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
```
**Symbols:**

```
ffffffff81406c80-ffffffff81406cb0: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81421080)
Location: block/blk-mq.c:350
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/blk-core.c:__blk_put_request
```
**Symbols:**

```
ffffffff81421080-ffffffff814210b4: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142f6c0)
Location: block/blk-mq.c:423
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/blk-core.c:__blk_put_request
```
**Symbols:**

```
ffffffff8142f6c0-ffffffff8142f7d3: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145abc0)
Location: block/blk-mq.c:459
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/blk-core.c:__blk_put_request
```
**Symbols:**

```
ffffffff8145abc0-ffffffff8145ad53: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148dc80)
Location: block/blk-mq.c:486
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/blk-core.c:__blk_put_request
```
**Symbols:**

```
ffffffff8148dc80-ffffffff8148ddd4: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a7570)
Location: block/blk-mq.c:501
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff814a7570-ffffffff814a7661: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d54c0)
Location: block/blk-mq.c:498
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff814d54c0-ffffffff814d55b4: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ee7a0)
Location: block/blk-mq.c:509
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff814ee7a0-ffffffff814ee894: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154f420)
Location: block/blk-mq.c:512
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff8154f420-ffffffff8154f542: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156b760)
Location: block/blk-mq.c:506
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff8156b760-ffffffff8156b8a9: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81573430)
Location: block/blk-mq.c:507
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff81573430-ffffffff81573579: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d79d0)
Location: block/blk-mq.c:514
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/mq-deadline.c:dd_insert_request
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff815d79d0-ffffffff815d7b20: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81685770)
Location: block/blk-mq.c:622
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_free_plug_rqs
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/mq-deadline.c:dd_bio_merge
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
**Symbols:**

```
ffffffff81685770-ffffffff81685885: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81743540)
Location: block/blk-mq.c:728
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:__blk_mq_end_request
  - block/blk-mq.c:blk_mq_free_plug_rqs
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/mq-deadline.c:dd_bio_merge
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:__scsi_execute
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
**Symbols:**

```
ffffffff81743540-ffffffff81743655: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177ed50)
Location: block/blk-mq.c:721
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_end_request
  - block/blk-mq.c:blk_mq_free_plug_rqs
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_bio_merge
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:scsi_execute_cmd
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
**Symbols:**

```
ffffffff8177ed50-ffffffff8177ee09: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c1ac0)
Location: block/blk-mq.c:726
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_put_rq_ref
  - block/blk-mq.c:blk_mq_end_request
  - block/blk-mq.c:blk_mq_free_plug_rqs
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/bsg-lib.c:bsg_transport_sg_io_fn
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_bio_merge
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_error.c:eh_lock_door_done
  - drivers/scsi/scsi_lib.c:scsi_execute_cmd
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
**Symbols:**

```
ffffffff817c1ac0-ffffffff817c1b8a: blk_mq_free_request (STB_GLOBAL)
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
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ee490)
Location: block/blk-mq.c:509
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffff8000105ee490-ffff8000105ee5cc: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0799908)
Location: block/blk-mq.c:509
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
c0799908-c0799a34: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000783240)
Location: block/blk-mq.c:509
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
c000000000783240-c000000000783400: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042cdac)
Location: block/blk-mq.c:509
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffe00042cdac-ffffffe00042cea8: blk_mq_free_request (STB_GLOBAL)
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
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e6d80)
Location: block/blk-mq.c:509
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/mq-deadline.c:dd_bio_merge
  - drivers/nvme/host/core.c:nvme_keep_alive_end_io
  - drivers/nvme/host/core.c:nvme_submit_user_cmd
  - drivers/nvme/host/core.c:__nvme_submit_sync_cmd
  - drivers/nvme/host/lightnvm.c:nvme_nvm_end_io
  - drivers/nvme/host/pci.c:nvme_del_cq_end
  - drivers/nvme/host/pci.c:abort_endio
```
**Symbols:**

```
ffffffff814e6d80-ffffffff814e6e74: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d72f0)
Location: block/blk-mq.c:509
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/mq-deadline.c:dd_bio_merge
  - drivers/nvme/host/core.c:nvme_keep_alive_end_io
  - drivers/nvme/host/core.c:nvme_submit_user_cmd
  - drivers/nvme/host/core.c:__nvme_submit_sync_cmd
  - drivers/nvme/host/pci.c:nvme_del_cq_end
  - drivers/nvme/host/pci.c:abort_endio
```
**Symbols:**

```
ffffffff814d72f0-ffffffff814d73e4: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e2e10)
Location: block/blk-mq.c:509
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff814e2e10-ffffffff814e2f04: blk_mq_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_free_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fbc90)
Location: block/blk-mq.c:509
Inline: False
Direct callers:
  - block/blk-core.c:blk_put_request
  - block/mq-deadline.c:dd_bio_merge
```
**Symbols:**

```
ffffffff814fbc90-ffffffff814fbd84: blk_mq_free_request (STB_GLOBAL)
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
