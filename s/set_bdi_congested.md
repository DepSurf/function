# Function: <code>set_bdi_congested</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81311592)
Location: include/linux/backing-dev-defs.h:188
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send_background_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81345a02)
Location: include/linux/backing-dev-defs.h:189
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send_background_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8135b722)
Location: include/linux/backing-dev-defs.h:192
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send_background_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813700ac)
Location: include/linux/backing-dev-defs.h:196
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send_background_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81394db3)
Location: include/linux/backing-dev-defs.h:221
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send_background_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c3ece)
Location: include/linux/backing-dev-defs.h:221
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_send_background_locked
  - fs/fuse/dev.c:fuse_request_send_background_locked
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
In fs/fuse/dev.c (ffffffff813dd6b1)
Location: include/linux/backing-dev-defs.h:223
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_queue_background
```
```
In fs/fuse/control.c (ffffffff813e910b)
Location: include/linux/backing-dev-defs.h:223
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
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
In fs/fuse/dev.c (ffffffff814091f1)
Location: include/linux/backing-dev-defs.h:222
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_queue_background
```
```
In fs/fuse/control.c (ffffffff8141526f)
Location: include/linux/backing-dev-defs.h:222
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
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
In fs/fuse/dev.c (ffffffff8141fec5)
Location: include/linux/backing-dev-defs.h:245
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
```
```
In fs/fuse/control.c (ffffffff8142f09f)
Location: include/linux/backing-dev-defs.h:245
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
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
In fs/fuse/dev.c (ffffffff8146e361)
Location: include/linux/backing-dev-defs.h:243
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_queue_background
```
```
In fs/fuse/control.c (ffffffff8147ef06)
Location: include/linux/backing-dev-defs.h:243
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void set_bdi_congested(struct backing_dev_info *bdi, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812811e0)
Location: mm/backing-dev.c:933
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/dev.c:fuse_request_queue_background
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
**Symbols:**

```
ffffffff812811e0-ffffffff81281208: set_bdi_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_bdi_congested(struct backing_dev_info *bdi, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81286310)
Location: mm/backing-dev.c:932
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
**Symbols:**

```
ffffffff81286310-ffffffff81286338: set_bdi_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void set_bdi_congested(struct backing_dev_info *bdi, int sync);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812c5620)
Location: mm/backing-dev.c:1015
Inline: True
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
**Symbols:**

```
ffffffff812c5620-ffffffff812c5669: set_bdi_congested (STB_GLOBAL)
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
In fs/fuse/dev.c (ffff8000105027a4)
Location: include/linux/backing-dev-defs.h:245
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
```
```
In fs/fuse/control.c (ffff8000105139d8)
Location: include/linux/backing-dev-defs.h:245
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
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
In fs/fuse/dev.c (c06bee54)
Location: include/linux/backing-dev-defs.h:245
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
```
```
In fs/fuse/control.c (c06ce788)
Location: include/linux/backing-dev-defs.h:245
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
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
In fs/fuse/dev.c (c000000000646f6c)
Location: include/linux/backing-dev-defs.h:245
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
```
```
In fs/fuse/control.c (c00000000065b720)
Location: include/linux/backing-dev-defs.h:245
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
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
In fs/fuse/dev.c (ffffffe00036f7bc)
Location: include/linux/backing-dev-defs.h:245
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
```
```
In fs/fuse/control.c (ffffffe00037d6cc)
Location: include/linux/backing-dev-defs.h:245
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
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
In fs/fuse/dev.c (ffffffff814184a5)
Location: include/linux/backing-dev-defs.h:245
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
```
```
In fs/fuse/control.c (ffffffff8142767f)
Location: include/linux/backing-dev-defs.h:245
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
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
In fs/fuse/dev.c (ffffffff81408f25)
Location: include/linux/backing-dev-defs.h:245
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
```
```
In fs/fuse/control.c (ffffffff814180ff)
Location: include/linux/backing-dev-defs.h:245
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
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
In fs/fuse/dev.c (ffffffff81414645)
Location: include/linux/backing-dev-defs.h:245
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
```
```
In fs/fuse/control.c (ffffffff8142381f)
Location: include/linux/backing-dev-defs.h:245
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
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
In fs/fuse/dev.c (ffffffff8142b931)
Location: include/linux/backing-dev-defs.h:245
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
  - fs/fuse/dev.c:fuse_simple_background
```
```
In fs/fuse/control.c (ffffffff8143a42d)
Location: include/linux/backing-dev-defs.h:245
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
