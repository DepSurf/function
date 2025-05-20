# Function: <code>set_wb_congested</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void set_wb_congested(struct bdi_writeback_congested *congested, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811ae9d0)
Location: mm/backing-dev.c:912
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - block/blk-core.c:get_request
  - block/blk-core.c:blk_update_nr_requests
  - block/blk-core.c:blk_update_nr_requests
```
**Symbols:**

```
ffffffff811ae9d0-ffffffff811ae9f4: set_wb_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void set_wb_congested(struct bdi_writeback_congested *congested, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811c7d80)
Location: mm/backing-dev.c:931
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - block/blk-core.c:get_request
  - block/blk-core.c:blk_update_nr_requests
  - block/blk-core.c:blk_update_nr_requests
```
**Symbols:**

```
ffffffff811c7d80-ffffffff811c7da4: set_wb_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void set_wb_congested(struct bdi_writeback_congested *congested, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811d7ea0)
Location: mm/backing-dev.c:937
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - block/blk-core.c:get_request
  - block/blk-core.c:blk_update_nr_requests
  - block/blk-core.c:blk_update_nr_requests
```
**Symbols:**

```
ffffffff811d7ea0-ffffffff811d7ec4: set_wb_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void set_wb_congested(struct bdi_writeback_congested *congested, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811e0a80)
Location: mm/backing-dev.c:982
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - block/blk-core.c:get_request
  - block/blk-core.c:blk_update_nr_requests
  - block/blk-core.c:blk_update_nr_requests
```
**Symbols:**

```
ffffffff811e0a80-ffffffff811e0aa4: set_wb_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void set_wb_congested(struct bdi_writeback_congested *congested, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811f6a70)
Location: mm/backing-dev.c:997
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - block/blk-core.c:get_request
  - block/blk-core.c:blk_update_nr_requests
  - block/blk-core.c:blk_update_nr_requests
```
**Symbols:**

```
ffffffff811f6a70-ffffffff811f6a94: set_wb_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void set_wb_congested(struct bdi_writeback_congested *congested, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81217d40)
Location: mm/backing-dev.c:995
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - block/blk-core.c:get_request
  - block/blk-core.c:blk_update_nr_requests
  - block/blk-core.c:blk_update_nr_requests
```
**Symbols:**

```
ffffffff81217d40-ffffffff81217d64: set_wb_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void set_wb_congested(struct bdi_writeback_congested *congested, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8122ac50)
Location: mm/backing-dev.c:998
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
**Symbols:**

```
ffffffff8122ac50-ffffffff8122ac74: set_wb_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void set_wb_congested(struct bdi_writeback_congested *congested, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123a8c0)
Location: mm/backing-dev.c:985
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
**Symbols:**

```
ffffffff8123a8c0-ffffffff8123a8e4: set_wb_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void set_wb_congested(struct bdi_writeback_congested *congested, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81248bd0)
Location: mm/backing-dev.c:1066
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
**Symbols:**

```
ffffffff81248bd0-ffffffff81248bf4: set_wb_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void set_wb_congested(struct bdi_writeback_congested *congested, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812768e0)
Location: mm/backing-dev.c:1064
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
**Symbols:**

```
ffffffff812768e0-ffffffff81276904: set_wb_congested (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void set_wb_congested(struct bdi_writeback_congested *congested, int sync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffff8000102dd9f8)
Location: mm/backing-dev.c:1066
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
**Symbols:**

```
ffff8000102dd9f8-ffff8000102ddab0: set_wb_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void set_wb_congested(struct bdi_writeback_congested *congested, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c05035b4)
Location: mm/backing-dev.c:1066
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
**Symbols:**

```
c05035b4-c050360c: set_wb_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void set_wb_congested(struct bdi_writeback_congested *congested, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c00000000039d680)
Location: mm/backing-dev.c:1066
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
**Symbols:**

```
c00000000039d680-c00000000039d6e8: set_wb_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void set_wb_congested(struct bdi_writeback_congested *congested, int sync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffe0001f593e)
Location: mm/backing-dev.c:1066
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
**Symbols:**

```
ffffffe0001f593e-ffffffe0001f5988: set_wb_congested (STB_GLOBAL)
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
void set_wb_congested(struct bdi_writeback_congested *congested, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81241220)
Location: mm/backing-dev.c:1066
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
**Symbols:**

```
ffffffff81241220-ffffffff81241244: set_wb_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void set_wb_congested(struct bdi_writeback_congested *congested, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81234220)
Location: mm/backing-dev.c:1066
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
**Symbols:**

```
ffffffff81234220-ffffffff81234244: set_wb_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void set_wb_congested(struct bdi_writeback_congested *congested, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123efc0)
Location: mm/backing-dev.c:1066
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
**Symbols:**

```
ffffffff8123efc0-ffffffff8123efe4: set_wb_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void set_wb_congested(struct bdi_writeback_congested *congested, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124e710)
Location: mm/backing-dev.c:1066
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
**Symbols:**

```
ffffffff8124e710-ffffffff8124e734: set_wb_congested (STB_GLOBAL)
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
