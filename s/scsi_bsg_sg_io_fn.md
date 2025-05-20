# Function: <code>scsi_bsg_sg_io_fn</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int scsi_bsg_sg_io_fn(struct request_queue *q, struct sg_io_v4 *hdr, fmode_t mode, unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_bsg.c (0)
Location: drivers/scsi/scsi_bsg.c:12
Inline: False
```
**Symbols:**

```
ffffffff818c0ae0-ffffffff818c0dec: scsi_bsg_sg_io_fn (STB_LOCAL)
ffffffff81d0cc25-ffffffff81d0cc57: scsi_bsg_sg_io_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int scsi_bsg_sg_io_fn(struct request_queue *q, struct sg_io_v4 *hdr, fmode_t mode, unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_bsg.c (0)
Location: drivers/scsi/scsi_bsg.c:12
Inline: False
```
**Symbols:**

```
ffffffff81a0d1f0-ffffffff81a0d4b6: scsi_bsg_sg_io_fn (STB_LOCAL)
ffffffff81ed5a60-ffffffff81ed5a8c: scsi_bsg_sg_io_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int scsi_bsg_sg_io_fn(struct request_queue *q, struct sg_io_v4 *hdr, fmode_t mode, unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_bsg.c (0)
Location: drivers/scsi/scsi_bsg.c:12
Inline: False
```
**Symbols:**

```
ffffffff81b8d040-ffffffff81b8d312: scsi_bsg_sg_io_fn (STB_LOCAL)
ffffffff8209bc22-ffffffff8209bc36: scsi_bsg_sg_io_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int scsi_bsg_sg_io_fn(struct request_queue *q, struct sg_io_v4 *hdr, bool open_for_write, unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_bsg.c (0)
Location: drivers/scsi/scsi_bsg.c:12
Inline: False
```
**Symbols:**

```
ffffffff81be1050-ffffffff81be1325: scsi_bsg_sg_io_fn (STB_LOCAL)
ffffffff8211cacf-ffffffff8211cae3: scsi_bsg_sg_io_fn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int scsi_bsg_sg_io_fn(struct request_queue *q, struct sg_io_v4 *hdr, bool open_for_write, unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_bsg.c (0)
Location: drivers/scsi/scsi_bsg.c:12
Inline: False
```
**Symbols:**

```
ffffffff81c36080-ffffffff81c36355: scsi_bsg_sg_io_fn (STB_LOCAL)
ffffffff821fa97f-ffffffff821fa993: scsi_bsg_sg_io_fn.cold (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool open_for_write</code>
</li>
<li>
<b>Param removed. </b>
<code>fmode_t mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
