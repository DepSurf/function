# Function: <code>blk_pre_runtime_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b8a40)
Location: block/blk-core.c:3421
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff813b8a40-ffffffff813b8ab6: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fc8b0)
Location: block/blk-core.c:3394
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff813fc8b0-ffffffff813fc926: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81416250)
Location: block/blk-core.c:3352
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff81416250-ffffffff814162c6: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814237e0)
Location: block/blk-core.c:3461
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff814237e0-ffffffff81423856: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144eda0)
Location: block/blk-core.c:3685
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff8144eda0-ffffffff8144ee16: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81481530)
Location: block/blk-core.c:3816
Inline: True
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff81481530-ffffffff814815a6: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff814d5e70)
Location: block/blk-pm.c:61
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff814d5e70-ffffffff814d5f74: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81501cc0)
Location: block/blk-pm.c:61
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff81501cc0-ffffffff81501dd2: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8151fbf0)
Location: block/blk-pm.c:61
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff8151fbf0-ffffffff8151fcff: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81580b80)
Location: block/blk-pm.c:61
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff81580b80-ffffffff81580c8f: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8159dd50)
Location: block/blk-pm.c:61
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff8159dd50-ffffffff8159de40: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff815a4990)
Location: block/blk-pm.c:61
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff815a4990-ffffffff815a4a80: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8160d3a0)
Location: block/blk-pm.c:61
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff8160d3a0-ffffffff8160d490: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff816c1380)
Location: block/blk-pm.c:61
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff816c1380-ffffffff816c1467: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81782470)
Location: block/blk-pm.c:61
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff81782470-ffffffff81782557: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff817c25a0)
Location: block/blk-pm.c:59
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff817c25a0-ffffffff817c268a: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81807300)
Location: block/blk-pm.c:59
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff81807300-ffffffff818073e7: blk_pre_runtime_suspend (STB_GLOBAL)
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
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffff800010628910)
Location: block/blk-pm.c:61
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffff800010628910-ffff800010628a54: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (c07d002c)
Location: block/blk-pm.c:61
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
c07d002c-c07d0154: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (c0000000007ca430)
Location: block/blk-pm.c:61
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
c0000000007ca430-c0000000007ca5f8: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffe000459ddc)
Location: block/blk-pm.c:61
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffe000459ddc-ffffffe000459f0a: blk_pre_runtime_suspend (STB_GLOBAL)
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
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff815181d0)
Location: block/blk-pm.c:61
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff815181d0-ffffffff815182df: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff815084e0)
Location: block/blk-pm.c:61
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff815084e0-ffffffff815085e9: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff81514260)
Location: block/blk-pm.c:61
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff81514260-ffffffff8151436f: blk_pre_runtime_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_pre_runtime_suspend(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-pm.c (ffffffff8152da20)
Location: block/blk-pm.c:61
Inline: False
Direct callers:
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
  - drivers/scsi/scsi_pm.c:scsi_runtime_suspend
```
**Symbols:**

```
ffffffff8152da20-ffffffff8152db07: blk_pre_runtime_suspend (STB_GLOBAL)
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
