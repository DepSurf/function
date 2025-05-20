# Function: <code>scsi_req_free_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81443956)
Location: include/scsi/scsi_request.h:24
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff814441f5)
Location: include/scsi/scsi_request.h:24
Inline: True
Inline callers:
  - block/bsg.c:blk_complete_sgv4_hdr_rq
```
```
In drivers/scsi/sg.c (ffffffff8166175d)
Location: include/scsi/scsi_request.h:24
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814703e3)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff81470aa5)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/bsg.c:blk_complete_sgv4_hdr_rq
```
```
In drivers/scsi/sg.c (ffffffff816ca8bd)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814a4564)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff814a4c35)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_free_rq
```
```
In drivers/scsi/sg.c (ffffffff817071ad)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814befbf)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff814bf6f5)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_free_rq
```
```
In drivers/scsi/sg.c (ffffffff81729ced)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814ed557)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff814edf45)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_free_rq
```
```
In drivers/scsi/sg.c (ffffffff8176539d)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81506997)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff81507395)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_free_rq
```
```
In drivers/scsi/sg.c (ffffffff8178938d)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff815677f9)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff81568585)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_free_rq
```
```
In drivers/scsi/sg.c (ffffffff8184c9fd)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81582520)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff81582ec5)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_free_rq
```
```
In drivers/scsi/sg.c (ffffffff8185ce1d)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81589474)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff81589cf5)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_free_rq
```
```
In drivers/scsi/sg.c (ffffffff8183fd0d)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff818aef2d)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:sg_io
```
```
In drivers/scsi/scsi_bsg.c (ffffffff818c0ce5)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
```
```
In drivers/scsi/sg.c (ffffffff818cc5bd)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffff8000106080fc)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffff800010609748)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_free_rq
```
```
In drivers/scsi/sg.c (ffff80001098edf0)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
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
In block/scsi_ioctl.c (c07b3fec)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (c07b4c44)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_free_rq
```
```
In drivers/scsi/sg.c (c0a61124)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (c0000000007a4bb0)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (c0000000007a5d30)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_free_rq
```
```
In drivers/scsi/sg.c (c000000000a50e54)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
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
In block/scsi_ioctl.c (ffffffe0004427e4)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffe0004430ac)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_free_rq
```
```
In drivers/scsi/sg.c (ffffffe0005f3034)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814fef77)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff814ff975)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_free_rq
```
```
In drivers/scsi/sg.c (ffffffff8173da7d)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814ef487)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff814efe85)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_free_rq
```
```
In drivers/scsi/sg.c (ffffffff8171f71d)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814fb007)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff814fba05)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_free_rq
```
```
In drivers/scsi/sg.c (ffffffff8177e20d)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff815140b7)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
```
In block/bsg.c (ffffffff81514ab5)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - block/bsg.c:bsg_scsi_free_rq
```
```
In drivers/scsi/sg.c (ffffffff8179801d)
Location: include/scsi/scsi_request.h:25
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_finish_rem_req
  - drivers/scsi/sg.c:sg_rq_end_io
```
</details>
</li>
</ul>

## Differences
