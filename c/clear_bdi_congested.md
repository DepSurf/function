# Function: <code>clear_bdi_congested</code>

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
In fs/fuse/dev.c (ffffffff8130fc21)
Location: include/linux/backing-dev-defs.h:183
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:request_end
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
In fs/fuse/dev.c (ffffffff81343780)
Location: include/linux/backing-dev-defs.h:184
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:request_end
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
In fs/fuse/dev.c (ffffffff81359d90)
Location: include/linux/backing-dev-defs.h:187
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:request_end
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
In fs/fuse/dev.c (ffffffff8136e52f)
Location: include/linux/backing-dev-defs.h:191
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:request_end
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
In fs/fuse/dev.c (ffffffff8139314e)
Location: include/linux/backing-dev-defs.h:216
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:request_end
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
In fs/fuse/dev.c (ffffffff813c192a)
Location: include/linux/backing-dev-defs.h:216
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:request_end
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
In fs/fuse/dev.c (ffffffff813daff8)
Location: include/linux/backing-dev-defs.h:218
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/control.c (ffffffff813e90bb)
Location: include/linux/backing-dev-defs.h:218
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
In fs/fuse/dev.c (ffffffff81406bdf)
Location: include/linux/backing-dev-defs.h:217
Inline: True
Inline callers:
  - fs/fuse/dev.c:request_end
  - fs/fuse/dev.c:request_end
```
```
In fs/fuse/control.c (ffffffff8141521e)
Location: include/linux/backing-dev-defs.h:217
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
In fs/fuse/dev.c (ffffffff814200b4)
Location: include/linux/backing-dev-defs.h:240
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/control.c (ffffffff8142f04e)
Location: include/linux/backing-dev-defs.h:240
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
In fs/fuse/dev.c (ffffffff8146edf4)
Location: include/linux/backing-dev-defs.h:238
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/control.c (ffffffff8147ee6c)
Location: include/linux/backing-dev-defs.h:238
Inline: True
Inline callers:
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clear_bdi_congested(struct backing_dev_info *bdi, int sync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81281180)
Location: mm/backing-dev.c:919
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
**Symbols:**

```
ffffffff81281180-ffffffff812811db: clear_bdi_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clear_bdi_congested(struct backing_dev_info *bdi, int sync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812862b0)
Location: mm/backing-dev.c:918
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
**Symbols:**

```
ffffffff812862b0-ffffffff8128630b: clear_bdi_congested (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clear_bdi_congested(struct backing_dev_info *bdi, int sync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812c5520)
Location: mm/backing-dev.c:1001
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
  - fs/fuse/control.c:fuse_conn_congestion_threshold_write
```
**Symbols:**

```
ffffffff812c5520-ffffffff812c55c8: clear_bdi_congested (STB_GLOBAL)
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
In fs/fuse/dev.c (ffff800010502a74)
Location: include/linux/backing-dev-defs.h:240
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/control.c (ffff800010513970)
Location: include/linux/backing-dev-defs.h:240
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
In fs/fuse/dev.c (c06be994)
Location: include/linux/backing-dev-defs.h:240
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/control.c (c06ce72c)
Location: include/linux/backing-dev-defs.h:240
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
In fs/fuse/dev.c (c00000000064697c)
Location: include/linux/backing-dev-defs.h:240
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/control.c (c00000000065b69c)
Location: include/linux/backing-dev-defs.h:240
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
In fs/fuse/dev.c (ffffffe00036f9a8)
Location: include/linux/backing-dev-defs.h:240
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/control.c (ffffffe00037d654)
Location: include/linux/backing-dev-defs.h:240
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
In fs/fuse/dev.c (ffffffff81418694)
Location: include/linux/backing-dev-defs.h:240
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/control.c (ffffffff8142762e)
Location: include/linux/backing-dev-defs.h:240
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
In fs/fuse/dev.c (ffffffff81409114)
Location: include/linux/backing-dev-defs.h:240
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/control.c (ffffffff814180ae)
Location: include/linux/backing-dev-defs.h:240
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
In fs/fuse/dev.c (ffffffff81414834)
Location: include/linux/backing-dev-defs.h:240
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/control.c (ffffffff814237ce)
Location: include/linux/backing-dev-defs.h:240
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
In fs/fuse/dev.c (ffffffff8142b0a0)
Location: include/linux/backing-dev-defs.h:240
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_request_end
  - fs/fuse/dev.c:fuse_request_end
```
```
In fs/fuse/control.c (ffffffff8143a3de)
Location: include/linux/backing-dev-defs.h:240
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
