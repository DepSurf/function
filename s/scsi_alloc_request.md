# Function: <code>scsi_alloc_request</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct request *scsi_alloc_request(struct request_queue *q, unsigned int op, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81a00751)
Location: drivers/scsi/scsi_lib.c:1128
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_execute
Direct callers:
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff819fef60-ffffffff819fef95: scsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct request *scsi_alloc_request(struct request_queue *q, blk_opf_t opf, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7ed81)
Location: drivers/scsi/scsi_lib.c:1133
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_execute
Direct callers:
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff81b7d550-ffffffff81b7d585: scsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct request *scsi_alloc_request(struct request_queue *q, blk_opf_t opf, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd2d43)
Location: drivers/scsi/scsi_lib.c:1134
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_execute_cmd
Direct callers:
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff81bd12e0-ffffffff81bd1315: scsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct request *scsi_alloc_request(struct request_queue *q, blk_opf_t opf, blk_mq_req_flags_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c279b3)
Location: drivers/scsi/scsi_lib.c:1133
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_execute_cmd
Direct callers:
  - drivers/scsi/scsi_ioctl.c:sg_scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/scsi_bsg.c:scsi_bsg_sg_io_fn
  - drivers/scsi/sr.c:sr_read_cdda_bpc
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff81c25f50-ffffffff81c25f85: scsi_alloc_request (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>blk_opf_t opf</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int op</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
