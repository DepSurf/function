# Function: <code>__blk_req_zone_write_lock</code>

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
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814b7fe0)
Location: block/blk-zoned.c:46
Inline: False
Direct callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
```
**Symbols:**

```
ffffffff814b7fe0-ffffffff814b803b: __blk_req_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814cbad0)
Location: block/blk-zoned.c:49
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff814cbad0-ffffffff814cbb2b: __blk_req_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814fa770)
Location: block/blk-zoned.c:53
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff814fa770-ffffffff814fa7cb: __blk_req_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff815186d0)
Location: block/blk-zoned.c:53
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff815186d0-ffffffff8151872b: __blk_req_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81578a50)
Location: block/blk-zoned.c:99
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff81578a50-ffffffff81578ab4: __blk_req_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81595600)
Location: block/blk-zoned.c:99
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff81595600-ffffffff8159565b: __blk_req_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8159c250)
Location: block/blk-zoned.c:91
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff8159c250-ffffffff8159c2ac: __blk_req_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:91
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff81cda3b0-ffffffff81cda3d5: __blk_req_zone_write_lock.cold (STB_LOCAL)
ffffffff81604890-ffffffff8160490f: __blk_req_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:90
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff81e8df8d-ffffffff81e8dfb2: __blk_req_zone_write_lock.cold (STB_LOCAL)
ffffffff816b8020-ffffffff816b80bb: __blk_req_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:87
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff82077331-ffffffff82077356: __blk_req_zone_write_lock.cold (STB_LOCAL)
ffffffff81778630-ffffffff817786d6: __blk_req_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:81
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff820f7347-ffffffff820f736c: __blk_req_zone_write_lock.cold (STB_LOCAL)
ffffffff817b8170-ffffffff817b8216: __blk_req_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:81
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
```
**Symbols:**

```
ffffffff821d4bc1-ffffffff821d4bf3: __blk_req_zone_write_lock.cold (STB_LOCAL)
ffffffff817fca00-ffffffff817fcac2: __blk_req_zone_write_lock (STB_GLOBAL)
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
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffff800010620058)
Location: block/blk-zoned.c:53
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffff800010620058-ffff800010620144: __blk_req_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c07c7628)
Location: block/blk-zoned.c:53
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
c07c7628-c07c771c: __blk_req_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c0000000007bf760)
Location: block/blk-zoned.c:53
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
c0000000007bf760-c0000000007bf808: __blk_req_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffe000452760)
Location: block/blk-zoned.c:53
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffe000452760-ffffffe000452844: __blk_req_zone_write_lock (STB_GLOBAL)
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
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81510cb0)
Location: block/blk-zoned.c:53
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff81510cb0-ffffffff81510d0b: __blk_req_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81500fd0)
Location: block/blk-zoned.c:53
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff81500fd0-ffffffff8150102b: __blk_req_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8150cd40)
Location: block/blk-zoned.c:53
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff8150cd40-ffffffff8150cd9b: __blk_req_zone_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __blk_req_zone_write_lock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81526420)
Location: block/blk-zoned.c:53
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
```
**Symbols:**

```
ffffffff81526420-ffffffff8152647b: __blk_req_zone_write_lock (STB_GLOBAL)
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
