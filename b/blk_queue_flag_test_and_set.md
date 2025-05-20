# Function: <code>blk_queue_flag_test_and_set</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147da20)
Location: block/blk-core.c:112
Inline: False
Direct callers:
  - block/blk-core.c:blk_set_preempt_only
```
**Symbols:**

```
ffffffff8147da20-ffffffff8147da6e: blk_queue_flag_test_and_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149af40)
Location: block/blk-core.c:100
Inline: False
```
**Symbols:**

```
ffffffff8149af40-ffffffff8149af56: blk_queue_flag_test_and_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814c9070)
Location: block/blk-core.c:101
Inline: False
```
**Symbols:**

```
ffffffff814c9070-ffffffff814c9086: blk_queue_flag_test_and_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e2260)
Location: block/blk-core.c:103
Inline: False
```
**Symbols:**

```
ffffffff814e2260-ffffffff814e2276: blk_queue_flag_test_and_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81540f20)
Location: block/blk-core.c:106
Inline: False
```
**Symbols:**

```
ffffffff81540f20-ffffffff81540f36: blk_queue_flag_test_and_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155dbb0)
Location: block/blk-core.c:105
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
**Symbols:**

```
ffffffff8155dbb0-ffffffff8155dbc6: blk_queue_flag_test_and_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81566410)
Location: block/blk-core.c:106
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
**Symbols:**

```
ffffffff81566410-ffffffff81566426: blk_queue_flag_test_and_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815ca7e0)
Location: block/blk-core.c:104
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_poll_hybrid
```
**Symbols:**

```
ffffffff815ca7e0-ffffffff815ca7f6: blk_queue_flag_test_and_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81675d60)
Location: block/blk-core.c:106
Inline: False
```
**Symbols:**

```
ffffffff81675d60-ffffffff81675d7e: blk_queue_flag_test_and_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81731d20)
Location: block/blk-core.c:104
Inline: False
```
**Symbols:**

```
ffffffff81731d20-ffffffff81731d3e: blk_queue_flag_test_and_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8176e0a0)
Location: block/blk-core.c:104
Inline: False
```
**Symbols:**

```
ffffffff8176e0a0-ffffffff8176e0c1: blk_queue_flag_test_and_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b02d0)
Location: block/blk-core.c:105
Inline: False
```
**Symbols:**

```
ffffffff817b02d0-ffffffff817b02ee: blk_queue_flag_test_and_set (STB_GLOBAL)
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
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e0de0)
Location: block/blk-core.c:103
Inline: False
```
**Symbols:**

```
ffff8000105e0de0-ffff8000105e0e74: blk_queue_flag_test_and_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078e1bc)
Location: block/blk-core.c:103
Inline: False
```
**Symbols:**

```
c078e1bc-c078e1e4: blk_queue_flag_test_and_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000771740)
Location: block/blk-core.c:103
Inline: False
```
**Symbols:**

```
c000000000771740-c000000000771788: blk_queue_flag_test_and_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000421f82)
Location: block/blk-core.c:103
Inline: False
```
**Symbols:**

```
ffffffe000421f82-ffffffe000421fd4: blk_queue_flag_test_and_set (STB_GLOBAL)
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
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814da840)
Location: block/blk-core.c:103
Inline: False
Direct callers:
  - drivers/nvme/host/core.c:nvme_update_disk_info
```
**Symbols:**

```
ffffffff814da840-ffffffff814da856: blk_queue_flag_test_and_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb1f0)
Location: block/blk-core.c:103
Inline: False
Direct callers:
  - drivers/nvme/host/core.c:nvme_update_disk_info
```
**Symbols:**

```
ffffffff814cb1f0-ffffffff814cb206: blk_queue_flag_test_and_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d68d0)
Location: block/blk-core.c:103
Inline: False
```
**Symbols:**

```
ffffffff814d68d0-ffffffff814d68e6: blk_queue_flag_test_and_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool blk_queue_flag_test_and_set(unsigned int flag, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814ef4e0)
Location: block/blk-core.c:103
Inline: False
```
**Symbols:**

```
ffffffff814ef4e0-ffffffff814ef4f6: blk_queue_flag_test_and_set (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
