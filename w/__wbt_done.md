# Function: <code>__wbt_done</code>

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
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __wbt_done(struct rq_wb *rwb, enum wbt_flags wb_acct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff8144a7d9)
Location: block/blk-wbt.c:121
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_done
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_sq_make_request
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-wbt.c:wbt_done
```
**Symbols:**

```
ffffffff81449e80-ffffffff81449f23: __wbt_done.part.21 (STB_LOCAL)
ffffffff8144a750-ffffffff8144a767: __wbt_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __wbt_done(struct rq_wb *rwb, enum wbt_flags wb_acct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff81458a77)
Location: block/blk-wbt.c:121
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_done
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-wbt.c:wbt_done
```
**Symbols:**

```
ffffffff81458290-ffffffff81458336: __wbt_done.part.21 (STB_LOCAL)
ffffffff81458a30-ffffffff81458a48: __wbt_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __wbt_done(struct rq_wb *rwb, enum wbt_flags wb_acct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff814847eb)
Location: block/blk-wbt.c:121
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_done
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-wbt.c:wbt_done
```
**Symbols:**

```
ffffffff81483ff0-ffffffff81484096: __wbt_done.part.21 (STB_LOCAL)
ffffffff814847a0-ffffffff814847b8: __wbt_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __wbt_done(struct rq_wb *rwb, enum wbt_flags wb_acct);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-wbt.c (ffffffff814b962c)
Location: block/blk-wbt.c:147
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_done
Direct callers:
  - block/blk-core.c:blk_queue_bio
  - block/blk-mq.c:blk_mq_make_request
  - block/blk-wbt.c:wbt_done
```
**Symbols:**

```
ffffffff814b8dd0-ffffffff814b8e86: __wbt_done.part.22 (STB_LOCAL)
ffffffff814b95c0-ffffffff814b95d7: __wbt_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __wbt_done(struct rq_qos *rqos, enum wbt_flags wb_acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814cccf0)
Location: block/blk-wbt.c:168
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
```
**Symbols:**

```
ffffffff814cccf0-ffffffff814ccd25: __wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __wbt_done(struct rq_qos *rqos, enum wbt_flags wb_acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814fb770)
Location: block/blk-wbt.c:169
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
```
**Symbols:**

```
ffffffff814fb770-ffffffff814fb7a5: __wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __wbt_done(struct rq_qos *rqos, enum wbt_flags wb_acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff815196c0)
Location: block/blk-wbt.c:169
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
```
**Symbols:**

```
ffffffff815196c0-ffffffff815196f5: __wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8157a049)
Location: block/blk-wbt.c:169
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81596f59)
Location: block/blk-wbt.c:169
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8159deab)
Location: block/blk-wbt.c:170
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8160658b)
Location: block/blk-wbt.c:170
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816ba67b)
Location: block/blk-wbt.c:170
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8177ac3b)
Location: block/blk-wbt.c:171
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817ba7cb)
Location: block/blk-wbt.c:229
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817fef3b)
Location: block/blk-wbt.c:228
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
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
void __wbt_done(struct rq_qos *rqos, enum wbt_flags wb_acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffff800010621148)
Location: block/blk-wbt.c:169
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
```
**Symbols:**

```
ffff800010621148-ffff800010621198: __wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __wbt_done(struct rq_qos *rqos, enum wbt_flags wb_acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c07c892c)
Location: block/blk-wbt.c:169
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
```
**Symbols:**

```
c07c892c-c07c8970: __wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __wbt_done(struct rq_qos *rqos, enum wbt_flags wb_acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c0000000007c0fd0)
Location: block/blk-wbt.c:169
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
```
**Symbols:**

```
c0000000007c0fd0-c0000000007c101c: __wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __wbt_done(struct rq_qos *rqos, enum wbt_flags wb_acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffe000453596)
Location: block/blk-wbt.c:169
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
```
**Symbols:**

```
ffffffe000453596-ffffffe0004535ea: __wbt_done (STB_LOCAL)
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
void __wbt_done(struct rq_qos *rqos, enum wbt_flags wb_acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81511ca0)
Location: block/blk-wbt.c:169
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
```
**Symbols:**

```
ffffffff81511ca0-ffffffff81511cd5: __wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __wbt_done(struct rq_qos *rqos, enum wbt_flags wb_acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81501fc0)
Location: block/blk-wbt.c:169
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
```
**Symbols:**

```
ffffffff81501fc0-ffffffff81501ff5: __wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __wbt_done(struct rq_qos *rqos, enum wbt_flags wb_acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8150dd30)
Location: block/blk-wbt.c:169
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
```
**Symbols:**

```
ffffffff8150dd30-ffffffff8150dd65: __wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __wbt_done(struct rq_qos *rqos, enum wbt_flags wb_acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81527350)
Location: block/blk-wbt.c:169
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_cleanup
  - block/blk-wbt.c:wbt_done
```
**Symbols:**

```
ffffffff81527350-ffffffff81527385: __wbt_done (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rq_qos *rqos</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rq_wb *rwb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
