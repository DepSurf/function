# Function: <code>rq_qos_wait</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814bda90)
Location: block/blk-rq-qos.c:223
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
ffffffff814bda90-ffffffff814bdbb1: rq_qos_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814ec130)
Location: block/blk-rq-qos.c:227
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
ffffffff814ec130-ffffffff814ec2a8: rq_qos_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81505580)
Location: block/blk-rq-qos.c:249
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
ffffffff81505580-ffffffff815056f8: rq_qos_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81565f40)
Location: block/blk-rq-qos.c:249
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
ffffffff81565f40-ffffffff815660b8: rq_qos_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81580ec0)
Location: block/blk-rq-qos.c:249
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
ffffffff81580ec0-ffffffff81581038: rq_qos_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81588a20)
Location: block/blk-rq-qos.c:249
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
ffffffff81588a20-ffffffff81588b65: rq_qos_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (0)
Location: block/blk-rq-qos.c:249
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
ffffffff81cd9b56-ffffffff81cd9b9d: rq_qos_wait.cold (STB_LOCAL)
ffffffff815ee730-ffffffff815ee890: rq_qos_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (0)
Location: block/blk-rq-qos.c:249
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
ffffffff81e8d5eb-ffffffff81e8d62d: rq_qos_wait.cold (STB_LOCAL)
ffffffff8169f000-ffffffff8169f160: rq_qos_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (0)
Location: block/blk-rq-qos.c:243
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
ffffffff82076c0a-ffffffff82076c4c: rq_qos_wait.cold (STB_LOCAL)
ffffffff8175d8c0-ffffffff8175da20: rq_qos_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (0)
Location: block/blk-rq-qos.c:243
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
ffffffff820f6a28-ffffffff820f6a70: rq_qos_wait.cold (STB_LOCAL)
ffffffff8179c620-ffffffff8179c792: rq_qos_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-rq-qos.c (0)
Location: block/blk-rq-qos.c:243
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
ffffffff821d3e76-ffffffff821d3ebe: rq_qos_wait.cold (STB_LOCAL)
ffffffff817e0080-ffffffff817e01f2: rq_qos_wait (STB_GLOBAL)
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
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffff8000106076f0)
Location: block/blk-rq-qos.c:249
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
ffff8000106076f0-ffff800010607868: rq_qos_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (c07b28b0)
Location: block/blk-rq-qos.c:249
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
c07b28b0-c07b2a40: rq_qos_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (c0000000007a42f0)
Location: block/blk-rq-qos.c:249
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
c0000000007a42f0-c0000000007a4504: rq_qos_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffe0004422a2)
Location: block/blk-rq-qos.c:249
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
ffffffe0004422a2-ffffffe0004423b4: rq_qos_wait (STB_GLOBAL)
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
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814fdb60)
Location: block/blk-rq-qos.c:249
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
ffffffff814fdb60-ffffffff814fdcd8: rq_qos_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814ee070)
Location: block/blk-rq-qos.c:249
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
ffffffff814ee070-ffffffff814ee1e8: rq_qos_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff814f9bf0)
Location: block/blk-rq-qos.c:249
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
ffffffff814f9bf0-ffffffff814f9d68: rq_qos_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rq_qos_wait(struct rq_wait *rqw, void *private_data, acquire_inflight_cb_t *acquire_inflight_cb, cleanup_cb_t *cleanup_cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-rq-qos.c (ffffffff81512c50)
Location: block/blk-rq-qos.c:249
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_wait
```
**Symbols:**

```
ffffffff81512c50-ffffffff81512dc8: rq_qos_wait (STB_GLOBAL)
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
