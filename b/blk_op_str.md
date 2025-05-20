# Function: <code>blk_op_str</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const char *blk_op_str(unsigned int op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814ce05c)
Location: block/blk-core.c:149
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff814c9090-ffffffff814c90b5: blk_op_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const char *blk_op_str(unsigned int op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e7392)
Location: block/blk-core.c:152
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff814e2280-ffffffff814e22a5: blk_op_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const char *blk_op_str(unsigned int op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81540f40)
Location: block/blk-core.c:160
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff81540f40-ffffffff81540f65: blk_op_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const char *blk_op_str(unsigned int op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155dbd0)
Location: block/blk-core.c:159
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff8155dbd0-ffffffff8155dbf5: blk_op_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const char *blk_op_str(unsigned int op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81be45ff)
Location: block/blk-core.c:160
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff81566430-ffffffff81566455: blk_op_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const char *blk_op_str(unsigned int op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cd238)
Location: block/blk-core.c:155
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff815ca800-ffffffff815ca85e: blk_op_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *blk_op_str(unsigned int op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81675d80)
Location: block/blk-core.c:139
Inline: False
Direct callers:
  - block/blk-mq.c:blk_update_request
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff81675d80-ffffffff81675de4: blk_op_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *blk_op_str(enum req_op op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81731d50)
Location: block/blk-core.c:137
Inline: False
Direct callers:
  - block/blk-mq.c:blk_update_request
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff81731d50-ffffffff81731db4: blk_op_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *blk_op_str(enum req_op op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8176e0e0)
Location: block/blk-core.c:137
Inline: False
Direct callers:
  - block/blk-mq.c:blk_update_request
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff8176e0e0-ffffffff8176e144: blk_op_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *blk_op_str(enum req_op op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b0300)
Location: block/blk-core.c:138
Inline: False
Direct callers:
  - block/blk-mq.c:blk_update_request
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff817b0300-ffffffff817b0364: blk_op_str (STB_GLOBAL)
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
const char *blk_op_str(unsigned int op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e3c48)
Location: block/blk-core.c:152
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffff8000105df578-ffff8000105df5ac: blk_op_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const char *blk_op_str(unsigned int op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c07910a0)
Location: block/blk-core.c:152
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
**Symbols:**

```
c078c36c-c078c3ac: blk_op_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const char *blk_op_str(unsigned int op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0000000007777b4)
Location: block/blk-core.c:152
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
**Symbols:**

```
c000000000771790-c0000000007717c4: blk_op_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const char *blk_op_str(unsigned int op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe00042579a)
Location: block/blk-core.c:152
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffe000421fd4-ffffffe000422008: blk_op_str (STB_GLOBAL)
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
const char *blk_op_str(unsigned int op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814df972)
Location: block/blk-core.c:152
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff814da860-ffffffff814da885: blk_op_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const char *blk_op_str(unsigned int op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d0312)
Location: block/blk-core.c:152
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff814cb210-ffffffff814cb235: blk_op_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const char *blk_op_str(unsigned int op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dba02)
Location: block/blk-core.c:152
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff814d68f0-ffffffff814d6915: blk_op_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const char *blk_op_str(unsigned int op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f4877)
Location: block/blk-core.c:152
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_request
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff814ef500-ffffffff814ef525: blk_op_str (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int op</code> ➡️ <code>enum req_op op</code>
</li>
</ul>
</details>
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
