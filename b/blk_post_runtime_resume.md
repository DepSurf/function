# Function: <code>blk_post_runtime_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b8b40)
Location: block/blk-core.c:3505
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff813b8b40-ffffffff813b8bcc: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fc930)
Location: block/blk-core.c:3478
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff813fc930-ffffffff813fc9bc: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814162d0)
Location: block/blk-core.c:3436
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff814162d0-ffffffff8141635c: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81423860)
Location: block/blk-core.c:3545
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff81423860-ffffffff814238ed: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144ec90)
Location: block/blk-core.c:3769
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff8144ec90-ffffffff8144ed1d: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81481660)
Location: block/blk-core.c:3900
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff81481660-ffffffff814816ec: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff814d6040)
Location: block/blk-pm.c:174
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff814d6040-ffffffff814d60df: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81501f30)
Location: block/blk-pm.c:174
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff81501f30-ffffffff81501fd6: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8151fde0)
Location: block/blk-pm.c:174
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff8151fde0-ffffffff8151fe7f: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81580d70)
Location: block/blk-pm.c:174
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff81580d70-ffffffff81580e0f: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8159de40)
Location: block/blk-pm.c:176
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff8159de40-ffffffff8159de99: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff815a4a80)
Location: block/blk-pm.c:176
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff815a4a80-ffffffff815a4ad9: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_post_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8160d2a0)
Location: block/blk-pm.c:176
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff8160d2a0-ffffffff8160d2bb: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_post_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff816c1610)
Location: block/blk-pm.c:176
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff816c1610-ffffffff816c16b8: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_post_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81782740)
Location: block/blk-pm.c:176
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff81782740-ffffffff817827e8: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_post_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff817c2880)
Location: block/blk-pm.c:174
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff817c2880-ffffffff817c292b: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81807510)
Location: block/blk-pm.c:174
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff81807510-ffffffff818075b8: blk_post_runtime_resume (STB_GLOBAL)
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
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffff800010628af8)
Location: block/blk-pm.c:174
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffff800010628af8-ffff800010628bd8: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (c07d0234)
Location: block/blk-pm.c:174
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
c07d0234-c07d02d0: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (c0000000007ca7c0)
Location: block/blk-pm.c:174
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
c0000000007ca7c0-c0000000007ca8f0: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffe00045a030)
Location: block/blk-pm.c:174
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffe00045a030-ffffffe00045a0e8: blk_post_runtime_resume (STB_GLOBAL)
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
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff815183c0)
Location: block/blk-pm.c:174
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff815183c0-ffffffff8151845f: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff815086c0)
Location: block/blk-pm.c:174
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff815086c0-ffffffff81508759: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81514450)
Location: block/blk-pm.c:174
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff81514450-ffffffff815144ef: blk_post_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_resume(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8152dbd0)
Location: block/blk-pm.c:174
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff8152dbd0-ffffffff8152dc66: blk_post_runtime_resume (STB_GLOBAL)
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int err</code>
</li>
</ul>
</details>
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
