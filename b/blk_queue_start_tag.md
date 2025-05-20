# Function: <code>blk_queue_start_tag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_queue_start_tag(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-tag.c (ffffffff813bbe30)
Location: block/blk-tag.c:313
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
**Symbols:**

```
ffffffff813bbe30-ffffffff813bbfe4: blk_queue_start_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_queue_start_tag(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-tag.c (ffffffff813ffc40)
Location: block/blk-tag.c:313
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
**Symbols:**

```
ffffffff813ffc40-ffffffff813ffdf3: blk_queue_start_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_queue_start_tag(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-tag.c (ffffffff814194f0)
Location: block/blk-tag.c:313
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
**Symbols:**

```
ffffffff814194f0-ffffffff81419695: blk_queue_start_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_queue_start_tag(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-tag.c (ffffffff81427420)
Location: block/blk-tag.c:310
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
**Symbols:**

```
ffffffff81427420-ffffffff814275c8: blk_queue_start_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_queue_start_tag(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-tag.c (ffffffff81452420)
Location: block/blk-tag.c:310
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
**Symbols:**

```
ffffffff81452420-ffffffff814525c8: blk_queue_start_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int blk_queue_start_tag(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-tag.c (0)
Location: block/blk-tag.c:309
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
**Symbols:**

```
ffffffff81485dce-ffffffff81485e09: blk_queue_start_tag.cold.8 (STB_LOCAL)
ffffffff81485890-ffffffff814859d4: blk_queue_start_tag (STB_GLOBAL)
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
