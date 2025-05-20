# Function: <code>blk_get_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b5ae0)
Location: block/blk-core.c:879
Inline: False
Direct callers:
  - block/genhd.c:add_disk
  - block/bsg.c:bsg_open
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff813b5ae0-ffffffff813b5b0a: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fa950)
Location: block/blk-core.c:889
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_open
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff813fa950-ffffffff813fa97a: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814142d0)
Location: block/blk-core.c:891
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_open
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff814142d0-ffffffff814142fa: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81424bb7)
Location: block/blk-core.c:1015
Inline: True
Inline callers:
  - block/blk-core.c:blk_init_rl
Direct callers:
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_open
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff81421da0-ffffffff81421dca: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144c8d0)
Location: block/blk-core.c:1093
Inline: True
Direct callers:
  - block/genhd.c:device_add_disk
  - block/bsg.c:bsg_open
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff8144c8d0-ffffffff8144c8fa: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147fbe0)
Location: block/blk-core.c:1198
Inline: True
Direct callers:
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_open
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff8147fbe0-ffffffff8147fc0a: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149cf30)
Location: block/blk-core.c:558
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff8149cf30-ffffffff8149cf57: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb0c0)
Location: block/blk-core.c:556
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff814cb0c0-ffffffff814cb0e7: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e42b0)
Location: block/blk-core.c:560
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff814e42b0-ffffffff814e42d4: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815429e0)
Location: block/blk-core.c:602
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff815429e0-ffffffff81542a04: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155f340)
Location: block/blk-core.c:611
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - block/genhd.c:__device_add_disk
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff8155f340-ffffffff8155f364: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81567bb0)
Location: block/blk-core.c:612
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - block/genhd.c:__device_add_disk
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff81567bb0-ffffffff81567bd4: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cc1e0)
Location: block/blk-core.c:610
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - block/genhd.c:__alloc_disk_node
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff815cc1e0-ffffffff815cc204: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff816781e0)
Location: block/blk-core.c:505
Inline: False
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - block/genhd.c:__alloc_disk_node
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkg_alloc
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff816781e0-ffffffff81678213: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817347c0)
Location: block/blk-core.c:465
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_disk_for_queue
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkg_alloc
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
**Symbols:**

```
ffffffff817347c0-ffffffff81734841: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81770c10)
Location: block/blk-core.c:463
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_disk_for_queue
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkg_alloc
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/sg.c:sg_add_device
```
**Symbols:**

```
ffffffff81770c10-ffffffff81770c94: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b2e70)
Location: block/blk-core.c:465
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_disk_for_queue
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkg_alloc
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/sg.c:sg_add_device
```
**Symbols:**

```
ffffffff817b2e70-ffffffff817b2eeb: blk_get_queue (STB_GLOBAL)
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
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e04a0)
Location: block/blk-core.c:560
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
```
**Symbols:**

```
ffff8000105e04a0-ffff8000105e04e8: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078e708)
Location: block/blk-core.c:560
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
```
**Symbols:**

```
c078e708-c078e744: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000774700)
Location: block/blk-core.c:560
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
c000000000774700-c000000000774758: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe0004239bc)
Location: block/blk-core.c:560
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/mmc/core/block.c:mmc_blk_alloc_req
```
**Symbols:**

```
ffffffe0004239bc-ffffffe0004239fe: blk_get_queue (STB_GLOBAL)
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
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dc890)
Location: block/blk-core.c:560
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/nvme/host/pci.c:nvme_reset_work
```
**Symbols:**

```
ffffffff814dc890-ffffffff814dc8b4: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd240)
Location: block/blk-core.c:560
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/nvme/host/pci.c:nvme_reset_work
```
**Symbols:**

```
ffffffff814cd240-ffffffff814cd264: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d8920)
Location: block/blk-core.c:560
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff814d8920-ffffffff814d8944: blk_get_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool blk_get_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f1530)
Location: block/blk-core.c:560
Inline: False
Direct callers:
  - block/genhd.c:__device_add_disk
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff814f1530-ffffffff814f1554: blk_get_queue (STB_GLOBAL)
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
