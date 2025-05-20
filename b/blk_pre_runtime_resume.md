# Function: <code>blk_pre_runtime_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b8970)
Location: block/blk-core.c:3480
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff813b8970-ffffffff813b89b6: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fc760)
Location: block/blk-core.c:3453
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff813fc760-ffffffff813fc7a6: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81416100)
Location: block/blk-core.c:3411
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff81416100-ffffffff81416146: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81423790)
Location: block/blk-core.c:3520
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff81423790-ffffffff814237d7: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144ec40)
Location: block/blk-core.c:3744
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff8144ec40-ffffffff8144ec87: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81481460)
Location: block/blk-core.c:3875
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff81481460-ffffffff814814a6: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff814d5ff0)
Location: block/blk-pm.c:149
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff814d5ff0-ffffffff814d6039: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81501e50)
Location: block/blk-pm.c:149
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff81501e50-ffffffff81501e99: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8151fd00)
Location: block/blk-pm.c:149
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff8151fd00-ffffffff8151fd46: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81580c90)
Location: block/blk-pm.c:149
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff81580c90-ffffffff81580cd6: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8159dc70)
Location: block/blk-pm.c:152
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff8159dc70-ffffffff8159dcb6: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff815a48b0)
Location: block/blk-pm.c:152
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff815a48b0-ffffffff815a48f6: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8160d2c0)
Location: block/blk-pm.c:152
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff8160d2c0-ffffffff8160d306: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff816c1470)
Location: block/blk-pm.c:152
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff816c1470-ffffffff816c14b9: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81782570)
Location: block/blk-pm.c:152
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff81782570-ffffffff817825b9: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff817c26a0)
Location: block/blk-pm.c:150
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff817c26a0-ffffffff817c26ec: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81807400)
Location: block/blk-pm.c:150
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff81807400-ffffffff81807449: blk_pre_runtime_resume (STB_GLOBAL)
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
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffff800010628a58)
Location: block/blk-pm.c:149
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffff800010628a58-ffff800010628af8: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (c07d0154)
Location: block/blk-pm.c:149
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
c07d0154-c07d01a8: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (c0000000007ca600)
Location: block/blk-pm.c:149
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
c0000000007ca600-c0000000007ca6a0: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffe000459f0a)
Location: block/blk-pm.c:149
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffe000459f0a-ffffffe000459f84: blk_pre_runtime_resume (STB_GLOBAL)
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
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff815182e0)
Location: block/blk-pm.c:149
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff815182e0-ffffffff81518326: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff815085f0)
Location: block/blk-pm.c:149
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff815085f0-ffffffff81508630: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81514370)
Location: block/blk-pm.c:149
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff81514370-ffffffff815143b6: blk_pre_runtime_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_pre_runtime_resume(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8152db10)
Location: block/blk-pm.c:149
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
  - drivers/scsi/scsi_pm.c:scsi_runtime_resume
```
**Symbols:**

```
ffffffff8152db10-ffffffff8152db4d: blk_pre_runtime_resume (STB_GLOBAL)
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
