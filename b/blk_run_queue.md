# Function: <code>blk_run_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_run_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b5460)
Location: block/blk-core.c:369
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_kick_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff813b5460-ffffffff813b549a: blk_run_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_run_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fa2e0)
Location: block/blk-core.c:369
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_kick_queue
```
**Symbols:**

```
ffffffff813fa2e0-ffffffff813fa31a: blk_run_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_run_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81413c60)
Location: block/blk-core.c:370
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_kick_queue
```
**Symbols:**

```
ffffffff81413c60-ffffffff81413c9a: blk_run_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_run_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81422440)
Location: block/blk-core.c:431
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_kick_queue
```
**Symbols:**

```
ffffffff81422440-ffffffff81422488: blk_run_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_run_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144d520)
Location: block/blk-core.c:464
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_kick_queue
```
**Symbols:**

```
ffffffff8144d520-ffffffff8144d568: blk_run_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_run_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814807b0)
Location: block/blk-core.c:525
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_kick_queue
```
**Symbols:**

```
ffffffff814807b0-ffffffff814807f8: blk_run_queue (STB_GLOBAL)
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
