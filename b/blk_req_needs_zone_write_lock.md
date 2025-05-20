# Function: <code>blk_req_needs_zone_write_lock</code>

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
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814b7f10)
Location: block/blk-zoned.c:27
Inline: False
Direct callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_next_request
```
**Symbols:**

```
ffffffff814b7f10-ffffffff814b7f7d: blk_req_needs_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814cba10)
Location: block/blk-zoned.c:30
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
```
**Symbols:**

```
ffffffff814cba10-ffffffff814cba7d: blk_req_needs_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814fa350)
Location: block/blk-zoned.c:34
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
```
**Symbols:**

```
ffffffff814fa350-ffffffff814fa3c7: blk_req_needs_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81518060)
Location: block/blk-zoned.c:34
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
```
**Symbols:**

```
ffffffff81518060-ffffffff815180d7: blk_req_needs_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81578960)
Location: block/blk-zoned.c:66
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_fifo_request
```
**Symbols:**

```
ffffffff81578960-ffffffff815789e0: blk_req_needs_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff815951a0)
Location: block/blk-zoned.c:66
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_fifo_request
```
**Symbols:**

```
ffffffff815951a0-ffffffff8159521e: blk_req_needs_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8159bf60)
Location: block/blk-zoned.c:58
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_fifo_request
```
**Symbols:**

```
ffffffff8159bf60-ffffffff8159bfca: blk_req_needs_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:58
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
```
**Symbols:**

```
ffffffff81cda346-ffffffff81cda36b: blk_req_needs_zone_write_lock.cold (STB_LOCAL)
ffffffff816043e0-ffffffff8160445a: blk_req_needs_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:58
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
```
**Symbols:**

```
ffffffff81e8deb9-ffffffff81e8dede: blk_req_needs_zone_write_lock.cold (STB_LOCAL)
ffffffff816b7ad0-ffffffff816b7b81: blk_req_needs_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:58
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
```
**Symbols:**

```
ffffffff82077221-ffffffff82077246: blk_req_needs_zone_write_lock.cold (STB_LOCAL)
ffffffff81777cc0-ffffffff81777d8c: blk_req_needs_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:58
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_next_request
```
**Symbols:**

```
ffffffff820f727e-ffffffff820f72a3: blk_req_needs_zone_write_lock.cold (STB_LOCAL)
ffffffff817b7860-ffffffff817b78fc: blk_req_needs_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:58
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
  - block/mq-deadline.c:deadline_next_request
```
**Symbols:**

```
ffffffff821d4a3a-ffffffff821d4a87: blk_req_needs_zone_write_lock.cold (STB_LOCAL)
ffffffff817fc0b0-ffffffff817fc185: blk_req_needs_zone_write_lock (STB_GLOBAL)
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
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffff80001061f6d8)
Location: block/blk-zoned.c:34
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
```
**Symbols:**

```
ffff80001061f6d8-ffff80001061f798: blk_req_needs_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c07c71f4)
Location: block/blk-zoned.c:34
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
```
**Symbols:**

```
c07c71f4-c07c72c0: blk_req_needs_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c0000000007bf220)
Location: block/blk-zoned.c:34
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
```
**Symbols:**

```
c0000000007bf220-c0000000007bf2b8: blk_req_needs_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffe00045239e)
Location: block/blk-zoned.c:34
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
```
**Symbols:**

```
ffffffe00045239e-ffffffe00045246e: blk_req_needs_zone_write_lock (STB_GLOBAL)
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
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81510640)
Location: block/blk-zoned.c:34
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
```
**Symbols:**

```
ffffffff81510640-ffffffff815106b7: blk_req_needs_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81500960)
Location: block/blk-zoned.c:34
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
```
**Symbols:**

```
ffffffff81500960-ffffffff815009d7: blk_req_needs_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8150c6d0)
Location: block/blk-zoned.c:34
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
```
**Symbols:**

```
ffffffff8150c6d0-ffffffff8150c747: blk_req_needs_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool blk_req_needs_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81525db0)
Location: block/blk-zoned.c:34
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:deadline_next_request
```
**Symbols:**

```
ffffffff81525db0-ffffffff81525e27: blk_req_needs_zone_write_lock (STB_GLOBAL)
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
