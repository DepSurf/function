# Function: <code>blk_post_runtime_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b8ac0)
Location: block/blk-core.c:3453
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff813b8ac0-ffffffff813b8b33: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fc830)
Location: block/blk-core.c:3426
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff813fc830-ffffffff813fc8a3: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814161d0)
Location: block/blk-core.c:3384
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff814161d0-ffffffff81416243: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814238f0)
Location: block/blk-core.c:3493
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff814238f0-ffffffff81423964: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144ed20)
Location: block/blk-core.c:3717
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff8144ed20-ffffffff8144ed94: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814814b0)
Location: block/blk-core.c:3848
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff814814b0-ffffffff81481523: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff814d60e0)
Location: block/blk-pm.c:119
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff814d60e0-ffffffff814d616e: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81501ea0)
Location: block/blk-pm.c:119
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff81501ea0-ffffffff81501f30: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8151fd50)
Location: block/blk-pm.c:119
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff8151fd50-ffffffff8151fddd: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81580ce0)
Location: block/blk-pm.c:119
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff81580ce0-ffffffff81580d6d: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8159dcc0)
Location: block/blk-pm.c:122
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff8159dcc0-ffffffff8159dd4d: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff815a4900)
Location: block/blk-pm.c:122
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff815a4900-ffffffff815a498d: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8160d310)
Location: block/blk-pm.c:122
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff8160d310-ffffffff8160d39d: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff816c14c0)
Location: block/blk-pm.c:122
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff816c14c0-ffffffff816c1560: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff817825d0)
Location: block/blk-pm.c:122
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff817825d0-ffffffff81782670: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff817c2700)
Location: block/blk-pm.c:120
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff817c2700-ffffffff817c27a3: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81807460)
Location: block/blk-pm.c:120
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff81807460-ffffffff81807500: blk_post_runtime_suspend (STB_GLOBAL)
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
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffff800010628bd8)
Location: block/blk-pm.c:119
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffff800010628bd8-ffff800010628cac: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (c07d01a8)
Location: block/blk-pm.c:119
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
c07d01a8-c07d0234: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (c0000000007ca6a0)
Location: block/blk-pm.c:119
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
c0000000007ca6a0-c0000000007ca7c0: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffe000459f84)
Location: block/blk-pm.c:119
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffe000459f84-ffffffe00045a030: blk_post_runtime_suspend (STB_GLOBAL)
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
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81518330)
Location: block/blk-pm.c:119
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff81518330-ffffffff815183bd: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81508630)
Location: block/blk-pm.c:119
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff81508630-ffffffff815086b7: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff815143c0)
Location: block/blk-pm.c:119
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff815143c0-ffffffff8151444d: blk_post_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_post_runtime_suspend(struct request_queue *q, int err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8152db50)
Location: block/blk-pm.c:119
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff8152db50-ffffffff8152dbd0: blk_post_runtime_suspend (STB_GLOBAL)
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
