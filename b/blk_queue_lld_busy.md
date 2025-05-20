# Function: <code>blk_queue_lld_busy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_queue_lld_busy(struct request_queue *q, lld_busy_fn *fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff813bdeb0)
Location: block/blk-settings.c:74
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
```
**Symbols:**

```
ffffffff813bdeb0-ffffffff813bdec2: blk_queue_lld_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_lld_busy(struct request_queue *q, lld_busy_fn *fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81401e10)
Location: block/blk-settings.c:74
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
```
**Symbols:**

```
ffffffff81401e10-ffffffff81401e22: blk_queue_lld_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_lld_busy(struct request_queue *q, lld_busy_fn *fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141ba80)
Location: block/blk-settings.c:75
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
```
**Symbols:**

```
ffffffff8141ba80-ffffffff8141ba92: blk_queue_lld_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_lld_busy(struct request_queue *q, lld_busy_fn *fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81429a80)
Location: block/blk-settings.c:75
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_queue
```
**Symbols:**

```
ffffffff81429a80-ffffffff81429a92: blk_queue_lld_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_lld_busy(struct request_queue *q, lld_busy_fn *fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81454c40)
Location: block/blk-settings.c:76
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
```
**Symbols:**

```
ffffffff81454c40-ffffffff81454c52: blk_queue_lld_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_queue_lld_busy(struct request_queue *q, lld_busy_fn *fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814880b0)
Location: block/blk-settings.c:76
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_old_alloc_queue
```
**Symbols:**

```
ffffffff814880b0-ffffffff814880c2: blk_queue_lld_busy (STB_GLOBAL)
```
</details>
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
</ul>
