# Function: <code>blk_rq_map_user_io</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int blk_rq_map_user_io(struct request *req, struct rq_map_data *map_data, void *ubuf, long unsigned int buf_len, gfp_t gfp_mask, bool vec, int iov_count, bool check_iter_count, int rw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-map.c (ffffffff8173c6d0)
Location: block/blk-map.c:696
Inline: True
Direct callers:
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff8173c6d0-ffffffff8173c843: blk_rq_map_user_io.part.0 (STB_LOCAL)
ffffffff8173c860-ffffffff8173c964: blk_rq_map_user_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int blk_rq_map_user_io(struct request *req, struct rq_map_data *map_data, void *ubuf, long unsigned int buf_len, gfp_t gfp_mask, bool vec, int iov_count, bool check_iter_count, int rw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-map.c (ffffffff81778c70)
Location: block/blk-map.c:694
Inline: True
Direct callers:
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff81778c70-ffffffff81778de3: blk_rq_map_user_io.part.0 (STB_LOCAL)
ffffffff81778e00-ffffffff81778eea: blk_rq_map_user_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int blk_rq_map_user_io(struct request *req, struct rq_map_data *map_data, void *ubuf, long unsigned int buf_len, gfp_t gfp_mask, bool vec, int iov_count, bool check_iter_count, int rw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-map.c (ffffffff817bb040)
Location: block/blk-map.c:701
Inline: True
Direct callers:
  - drivers/scsi/scsi_ioctl.c:sg_io
  - drivers/scsi/sg.c:sg_start_req
  - drivers/scsi/sg.c:sg_start_req
```
**Symbols:**

```
ffffffff817bb040-ffffffff817bb1b3: blk_rq_map_user_io.part.0 (STB_LOCAL)
ffffffff817bb1d0-ffffffff817bb2ba: blk_rq_map_user_io (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
