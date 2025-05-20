# Function: <code>__blk_req_zone_write_unlock</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814b7f80)
Location: block/blk-zoned.c:57
Inline: True
Direct callers:
  - block/blk-core.c:__blk_put_request
  - block/deadline-iosched.c:deadline_completed_request
  - block/deadline-iosched.c:deadline_add_request
```
**Symbols:**

```
ffffffff814b7f80-ffffffff814b7fd4: __blk_req_zone_write_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814cbf30)
Location: block/blk-zoned.c:60
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814cbf30-ffffffff814cbf84: __blk_req_zone_write_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814fa7d0)
Location: block/blk-zoned.c:64
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff814fa7d0-ffffffff814fa823: __blk_req_zone_write_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81518730)
Location: block/blk-zoned.c:64
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff81518730-ffffffff81518783: __blk_req_zone_write_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81578ac0)
Location: block/blk-zoned.c:110
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff81578ac0-ffffffff81578b14: __blk_req_zone_write_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81595660)
Location: block/blk-zoned.c:110
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff81595660-ffffffff815956b3: __blk_req_zone_write_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8159c2b0)
Location: block/blk-zoned.c:102
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff8159c2b0-ffffffff8159c303: __blk_req_zone_write_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:102
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_request
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff81cda47f-ffffffff81cda49c: __blk_req_zone_write_unlock.cold (STB_LOCAL)
ffffffff81604a80-ffffffff81604aeb: __blk_req_zone_write_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:101
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff81e8e03c-ffffffff81e8e059: __blk_req_zone_write_unlock.cold (STB_LOCAL)
ffffffff816b8240-ffffffff816b82b9: __blk_req_zone_write_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:98
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff82077356-ffffffff8207737b: __blk_req_zone_write_unlock.cold (STB_LOCAL)
ffffffff817786f0-ffffffff8177876e: __blk_req_zone_write_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:92
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff820f739b-ffffffff820f73c0: __blk_req_zone_write_unlock.cold (STB_LOCAL)
ffffffff817b82d0-ffffffff817b834e: __blk_req_zone_write_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-zoned.c (0)
Location: block/blk-zoned.c:92
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - drivers/scsi/sd_zbc.c:sd_zbc_complete
  - drivers/scsi/sd_zbc.c:sd_zbc_prepare_zone_append
```
**Symbols:**

```
ffffffff821d4d84-ffffffff821d4db6: __blk_req_zone_write_unlock.cold (STB_LOCAL)
ffffffff817fcd90-ffffffff817fce28: __blk_req_zone_write_unlock (STB_GLOBAL)
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
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffff800010620148)
Location: block/blk-zoned.c:64
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffff800010620148-ffff800010620230: __blk_req_zone_write_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c07c771c)
Location: block/blk-zoned.c:64
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
c07c771c-c07c77d4: __blk_req_zone_write_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c0000000007bf810)
Location: block/blk-zoned.c:64
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
c0000000007bf810-c0000000007bf8b8: __blk_req_zone_write_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffe0004528d2)
Location: block/blk-zoned.c:64
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffe0004528d2-ffffffe00045299e: __blk_req_zone_write_unlock (STB_GLOBAL)
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
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81510d10)
Location: block/blk-zoned.c:64
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff81510d10-ffffffff81510d63: __blk_req_zone_write_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81501030)
Location: block/blk-zoned.c:64
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff81501030-ffffffff81501083: __blk_req_zone_write_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8150cda0)
Location: block/blk-zoned.c:64
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff8150cda0-ffffffff8150cdf3: __blk_req_zone_write_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __blk_req_zone_write_unlock(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81526480)
Location: block/blk-zoned.c:64
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_finish_request
  - block/mq-deadline.c:dd_insert_requests
```
**Symbols:**

```
ffffffff81526480-ffffffff815264d3: __blk_req_zone_write_unlock (STB_GLOBAL)
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
