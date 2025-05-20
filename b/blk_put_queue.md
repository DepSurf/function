# Function: <code>blk_put_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b57a0)
Location: block/blk-core.c:379
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_release
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
```
**Symbols:**

```
ffffffff813b57a0-ffffffff813b57b7: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fcae1)
Location: block/blk-core.c:379
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
```
**Symbols:**

```
ffffffff813fa610-ffffffff813fa627: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81416481)
Location: block/blk-core.c:380
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
```
**Symbols:**

```
ffffffff81413f90-ffffffff81413fa7: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81424e0d)
Location: block/blk-core.c:443
Inline: True
Inline callers:
  - block/blk-core.c:blk_exit_rl
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
```
**Symbols:**

```
ffffffff81421980-ffffffff81421997: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144fc8d)
Location: block/blk-core.c:476
Inline: True
Inline callers:
  - block/blk-core.c:blk_exit_rl
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
```
**Symbols:**

```
ffffffff8144c4c0-ffffffff8144c4d7: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81482ebd)
Location: block/blk-core.c:537
Inline: True
Inline callers:
  - block/blk-core.c:blk_exit_rl
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
```
**Symbols:**

```
ffffffff8147f760-ffffffff8147f777: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149e80d)
Location: block/blk-core.c:268
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
```
**Symbols:**

```
ffffffff8149cc40-ffffffff8149cc57: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb619)
Location: block/blk-core.c:302
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
```
**Symbols:**

```
ffffffff814cadd0-ffffffff814cade7: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e4809)
Location: block/blk-core.c:305
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
```
**Symbols:**

```
ffffffff814e3fb0-ffffffff814e3fc4: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81543183)
Location: block/blk-core.c:324
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_put_device
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
```
**Symbols:**

```
ffffffff815429c0-ffffffff815429d4: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155f9d5)
Location: block/blk-core.c:337
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_put_device
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
```
**Symbols:**

```
ffffffff8155f060-ffffffff8155f074: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81568115)
Location: block/blk-core.c:338
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
```
**Symbols:**

```
ffffffff815678d0-ffffffff815678e4: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815ccef9)
Location: block/blk-core.c:333
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
```
**Symbols:**

```
ffffffff815cc1c0-ffffffff815cc1d4: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff816785a8)
Location: block/blk-core.c:267
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - block/blk-cgroup.c:blkg_free_workfn
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
```
**Symbols:**

```
ffffffff816781c0-ffffffff816781dd: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817346e0)
Location: block/blk-core.c:287
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_disk_for_queue
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/blk-mq.c:blk_mq_init_queue
  - block/genhd.c:__blk_alloc_disk
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg-lib.c:bsg_setup_queue
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - block/blk-cgroup.c:blkg_free_workfn
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
```
**Symbols:**

```
ffffffff817346e0-ffffffff817347b0: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81770b50)
Location: block/blk-core.c:284
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_disk_for_queue
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/blk-mq.c:blk_mq_init_queue
  - block/genhd.c:__blk_alloc_disk
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg-lib.c:bsg_setup_queue
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_free_workfn
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
```
**Symbols:**

```
ffffffff81770b50-ffffffff81770bf1: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b2dc0)
Location: block/blk-core.c:286
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_disk_for_queue
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/blk-mq.c:__blk_mq_alloc_disk
  - block/blk-mq.c:blk_mq_init_queue
  - block/genhd.c:__blk_alloc_disk
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg-lib.c:bsg_setup_queue
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_free_workfn
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_add_device
```
**Symbols:**

```
ffffffff817b2dc0-ffffffff817b2e5e: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e0f98)
Location: block/blk-core.c:305
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/mmc/core/block.c:mmc_blk_put
```
**Symbols:**

```
ffff8000105e01d8-ffff8000105e0204: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078e47c)
Location: block/blk-core.c:305
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/mmc/core/block.c:mmc_blk_put
```
**Symbols:**

```
c078e324-c078e344: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000774370)
Location: block/blk-core.c:305
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
```
**Symbols:**

```
c000000000774160-c000000000774198: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000423726)
Location: block/blk-core.c:305
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/mmc/core/block.c:mmc_blk_put
```
**Symbols:**

```
ffffffe0004235cc-ffffffe0004235f8: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dcde9)
Location: block/blk-core.c:305
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/nvme/host/pci.c:nvme_pci_free_ctrl
```
**Symbols:**

```
ffffffff814dc590-ffffffff814dc5a4: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd799)
Location: block/blk-core.c:305
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
  - drivers/nvme/host/pci.c:nvme_pci_free_ctrl
```
**Symbols:**

```
ffffffff814ccf40-ffffffff814ccf54: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d8e79)
Location: block/blk-core.c:305
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
```
**Symbols:**

```
ffffffff814d8620-ffffffff814d8634: blk_put_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_put_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f1a89)
Location: block/blk-core.c:305
Inline: True
Inline callers:
  - block/blk-core.c:blk_cleanup_queue
Direct callers:
  - block/genhd.c:disk_release
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
  - block/blk-cgroup.c:blkcg_schedule_throttle
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_exit
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_sysfs.c:scsi_device_dev_release_usercontext
```
**Symbols:**

```
ffffffff814f1230-ffffffff814f1244: blk_put_queue (STB_GLOBAL)
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
