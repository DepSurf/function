# Function: <code>blk_set_runtime_active</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fc6f0)
Location: block/blk-core.c:3510
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
**Symbols:**

```
ffffffff813fc6f0-ffffffff813fc751: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81415fe0)
Location: block/blk-core.c:3468
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
**Symbols:**

```
ffffffff81415fe0-ffffffff81416041: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814236c0)
Location: block/blk-core.c:3577
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
**Symbols:**

```
ffffffff814236c0-ffffffff81423721: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144eb70)
Location: block/blk-core.c:3801
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
**Symbols:**

```
ffffffff8144eb70-ffffffff8144ebd1: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814815f0)
Location: block/blk-core.c:3932
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
  - drivers/scsi/scsi_pm.c:scsi_bus_resume_common
```
**Symbols:**

```
ffffffff814815f0-ffffffff81481651: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff814d5f80)
Location: block/blk-pm.c:208
Inline: False
```
**Symbols:**

```
ffffffff814d5f80-ffffffff814d5fea: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81501de0)
Location: block/blk-pm.c:208
Inline: False
```
**Symbols:**

```
ffffffff81501de0-ffffffff81501e46: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8151fe80)
Location: block/blk-pm.c:208
Inline: True
```
**Symbols:**

```
ffffffff8151fe80-ffffffff8151feee: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81580e10)
Location: block/blk-pm.c:208
Inline: True
```
**Symbols:**

```
ffffffff81580e10-ffffffff81580e7e: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-pm.c (ffffffff8159dbc0)
Location: block/blk-pm.c:207
Inline: True
```
**Symbols:**

```
ffffffff8159dbc0-ffffffff8159dc48: blk_set_runtime_active.part.0 (STB_LOCAL)
ffffffff8159dc50-ffffffff8159dc6b: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-pm.c (ffffffff815a4800)
Location: block/blk-pm.c:207
Inline: True
```
**Symbols:**

```
ffffffff815a4800-ffffffff815a4888: blk_set_runtime_active.part.0 (STB_LOCAL)
ffffffff815a4890-ffffffff815a48ab: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-pm.c (ffffffff8160d2a5)
Location: block/blk-pm.c:199
Inline: True
Inline callers:
  - block/blk-pm.c:blk_post_runtime_resume
Direct callers:
  - block/blk-pm.c:blk_post_runtime_resume
```
**Symbols:**

```
ffffffff8160d1f0-ffffffff8160d278: blk_set_runtime_active.part.0 (STB_LOCAL)
ffffffff8160d280-ffffffff8160d29b: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff816c1615)
Location: block/blk-pm.c:199
Inline: True
Inline callers:
  - block/blk-pm.c:blk_post_runtime_resume
  - block/blk-pm.c:blk_post_runtime_resume
```
**Symbols:**

```
ffffffff816c1560-ffffffff816c1608: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81782745)
Location: block/blk-pm.c:199
Inline: True
Inline callers:
  - block/blk-pm.c:blk_post_runtime_resume
  - block/blk-pm.c:blk_post_runtime_resume
```
**Symbols:**

```
ffffffff81782680-ffffffff81782728: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff817c2885)
Location: block/blk-pm.c:197
Inline: True
Inline callers:
  - block/blk-pm.c:blk_post_runtime_resume
  - block/blk-pm.c:blk_post_runtime_resume
```
**Symbols:**

```
ffffffff817c27c0-ffffffff817c286b: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffff800010628cb0)
Location: block/blk-pm.c:208
Inline: True
```
**Symbols:**

```
ffff800010628cb0-ffff800010628d64: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (c07d02d0)
Location: block/blk-pm.c:208
Inline: True
```
**Symbols:**

```
c07d02d0-c07d0348: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (c0000000007ca8f0)
Location: block/blk-pm.c:208
Inline: True
```
**Symbols:**

```
c0000000007ca8f0-c0000000007ca9bc: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffe00045a0e8)
Location: block/blk-pm.c:208
Inline: True
```
**Symbols:**

```
ffffffe00045a0e8-ffffffe00045a180: blk_set_runtime_active (STB_GLOBAL)
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
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81518460)
Location: block/blk-pm.c:208
Inline: True
```
**Symbols:**

```
ffffffff81518460-ffffffff815184ce: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81508760)
Location: block/blk-pm.c:208
Inline: True
```
**Symbols:**

```
ffffffff81508760-ffffffff815087c8: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff815144f0)
Location: block/blk-pm.c:208
Inline: True
```
**Symbols:**

```
ffffffff815144f0-ffffffff8151455e: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_set_runtime_active(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8152dc70)
Location: block/blk-pm.c:208
Inline: True
```
**Symbols:**

```
ffffffff8152dc70-ffffffff8152dcd5: blk_set_runtime_active (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
