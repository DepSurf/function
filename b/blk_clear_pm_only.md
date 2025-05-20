# Function: <code>blk_clear_pm_only</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149d250)
Location: block/blk-core.c:257
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffffffff8149d250-ffffffff8149d28a: blk_clear_pm_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb380)
Location: block/blk-core.c:291
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffffffff814cb380-ffffffff814cb3b8: blk_clear_pm_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e4570)
Location: block/blk-core.c:294
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffffffff814e4570-ffffffff814e45a5: blk_clear_pm_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81542e70)
Location: block/blk-core.c:313
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:device_resume_fn
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffffffff81542e70-ffffffff81542ea5: blk_clear_pm_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155f6f0)
Location: block/blk-core.c:316
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:device_resume_fn
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffffffff8155f6f0-ffffffff8155f725: blk_clear_pm_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81567e90)
Location: block/blk-core.c:317
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:device_resume_fn
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffffffff81567e90-ffffffff81567ec5: blk_clear_pm_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cc4e0)
Location: block/blk-core.c:312
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:device_resume_fn
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffffffff815cc4e0-ffffffff815cc515: blk_clear_pm_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff816782c0)
Location: block/blk-core.c:246
Inline: True
Direct callers:
  - block/blk-pm.c:blk_post_runtime_resume
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:device_resume_fn
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffffffff816782c0-ffffffff8167831f: blk_clear_pm_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817345b0)
Location: block/blk-core.c:244
Inline: True
Direct callers:
  - block/blk-pm.c:blk_post_runtime_resume
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:device_resume_fn
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffffffff817345b0-ffffffff8173460f: blk_clear_pm_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817709b0)
Location: block/blk-core.c:247
Inline: True
Direct callers:
  - block/blk-pm.c:blk_post_runtime_resume
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:device_resume_fn
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffffffff817709b0-ffffffff81770a12: blk_clear_pm_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b2c20)
Location: block/blk-core.c:249
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:device_resume_fn
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffffffff817b2c20-ffffffff817b2c82: blk_clear_pm_only (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e0d58)
Location: block/blk-core.c:294
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffff8000105e0d58-ffff8000105e0ddc: blk_clear_pm_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078ec10)
Location: block/blk-core.c:294
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
c078ec10-c078eca0: blk_clear_pm_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000774e60)
Location: block/blk-core.c:294
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
c000000000774e60-c000000000774ee8: blk_clear_pm_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000423cea)
Location: block/blk-core.c:294
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffffffe000423cea-ffffffe000423d3a: blk_clear_pm_only (STB_GLOBAL)
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
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dcb50)
Location: block/blk-core.c:294
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffffffff814dcb50-ffffffff814dcb85: blk_clear_pm_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd500)
Location: block/blk-core.c:294
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffffffff814cd500-ffffffff814cd535: blk_clear_pm_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d8be0)
Location: block/blk-core.c:294
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffffffff814d8be0-ffffffff814d8c15: blk_clear_pm_only (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_clear_pm_only(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f17f0)
Location: block/blk-core.c:294
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/scsi/scsi_lib.c:scsi_device_resume
  - drivers/scsi/scsi_lib.c:scsi_device_quiesce
```
**Symbols:**

```
ffffffff814f17f0-ffffffff814f1825: blk_clear_pm_only (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
