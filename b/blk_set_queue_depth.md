# Function: <code>blk_set_queue_depth</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141c6a0)
Location: block/blk-settings.c:864
Inline: False
```
**Symbols:**

```
ffffffff8141c6a0-ffffffff8141c6ba: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8142a600)
Location: block/blk-settings.c:876
Inline: False
```
**Symbols:**

```
ffffffff8142a600-ffffffff8142a61a: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81455840)
Location: block/blk-settings.c:877
Inline: False
```
**Symbols:**

```
ffffffff81455840-ffffffff8145585a: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81488be0)
Location: block/blk-settings.c:875
Inline: False
```
**Symbols:**

```
ffffffff81488be0-ffffffff81488bfa: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814a2b00)
Location: block/blk-settings.c:817
Inline: False
```
**Symbols:**

```
ffffffff814a2b00-ffffffff814a2b13: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d0bb0)
Location: block/blk-settings.c:805
Inline: False
```
**Symbols:**

```
ffffffff814d0bb0-ffffffff814d0bc3: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e9f30)
Location: block/blk-settings.c:806
Inline: False
```
**Symbols:**

```
ffffffff814e9f30-ffffffff814e9f4d: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81548de0)
Location: block/blk-settings.c:767
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
```
**Symbols:**

```
ffffffff81548de0-ffffffff81548dfd: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81564d50)
Location: block/blk-settings.c:780
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
```
**Symbols:**

```
ffffffff81564d50-ffffffff81564d6d: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8156d3a0)
Location: block/blk-settings.c:777
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
```
**Symbols:**

```
ffffffff8156d3a0-ffffffff8156d3bd: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff815d1840)
Location: block/blk-settings.c:777
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
```
**Symbols:**

```
ffffffff815d1840-ffffffff815d185d: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8167cdd0)
Location: block/blk-settings.c:809
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
```
**Symbols:**

```
ffffffff8167cdd0-ffffffff8167cdfd: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81739840)
Location: block/blk-settings.c:810
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
```
**Symbols:**

```
ffffffff81739840-ffffffff8173986d: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81775f10)
Location: block/blk-settings.c:816
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
```
**Symbols:**

```
ffffffff81775f10-ffffffff81775f3d: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817b8110)
Location: block/blk-settings.c:818
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
```
**Symbols:**

```
ffffffff817b8110-ffffffff817b8140: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffff8000105e8250)
Location: block/blk-settings.c:806
Inline: False
```
**Symbols:**

```
ffff8000105e8250-ffff8000105e8288: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c0794758)
Location: block/blk-settings.c:806
Inline: False
Direct callers:
  - drivers/scsi/scsi.c:scsi_change_queue_depth
```
**Symbols:**

```
c0794758-c0794788: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (c00000000077ce20)
Location: block/blk-settings.c:806
Inline: False
```
**Symbols:**

```
c00000000077ce20-c00000000077ce68: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffe000428f0a)
Location: block/blk-settings.c:806
Inline: False
```
**Symbols:**

```
ffffffe000428f0a-ffffffe000428f40: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814e2510)
Location: block/blk-settings.c:806
Inline: False
```
**Symbols:**

```
ffffffff814e2510-ffffffff814e252d: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814d2ea0)
Location: block/blk-settings.c:806
Inline: False
```
**Symbols:**

```
ffffffff814d2ea0-ffffffff814d2ebd: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814de5a0)
Location: block/blk-settings.c:806
Inline: False
```
**Symbols:**

```
ffffffff814de5a0-ffffffff814de5bd: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814f7400)
Location: block/blk-settings.c:806
Inline: False
```
**Symbols:**

```
ffffffff814f7400-ffffffff814f741d: blk_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
