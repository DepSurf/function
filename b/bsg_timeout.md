# Function: <code>bsg_timeout</code>

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
enum blk_eh_timer_return bsg_timeout(struct request *rq, bool reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814c03c0)
Location: block/bsg-lib.c:314
Inline: False
```
**Symbols:**

```
ffffffff814c03c0-ffffffff814c03e9: bsg_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum blk_eh_timer_return bsg_timeout(struct request *rq, bool reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814eeac0)
Location: block/bsg-lib.c:333
Inline: False
```
**Symbols:**

```
ffffffff814eeac0-ffffffff814eeae9: bsg_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum blk_eh_timer_return bsg_timeout(struct request *rq, bool reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81507f20)
Location: block/bsg-lib.c:335
Inline: False
```
**Symbols:**

```
ffffffff81507f20-ffffffff81507f49: bsg_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum blk_eh_timer_return bsg_timeout(struct request *rq, bool reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81569160)
Location: block/bsg-lib.c:335
Inline: False
```
**Symbols:**

```
ffffffff81569160-ffffffff81569189: bsg_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum blk_eh_timer_return bsg_timeout(struct request *rq, bool reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81583a50)
Location: block/bsg-lib.c:338
Inline: False
```
**Symbols:**

```
ffffffff81583a50-ffffffff81583a79: bsg_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum blk_eh_timer_return bsg_timeout(struct request *rq, bool reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff8158a860)
Location: block/bsg-lib.c:338
Inline: False
```
**Symbols:**

```
ffffffff8158a860-ffffffff8158a889: bsg_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
unsigned int bsg_timeout(struct bsg_device *bd, struct sg_io_v4 *hdr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff815ef4fc)
Location: block/bsg.c:45
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/bsg-lib.c (ffffffff815ef7e0)
Location: block/bsg-lib.c:339
Inline: False
```
**Symbols:**

```
ffffffff815ef7e0-ffffffff815ef809: bsg_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
unsigned int bsg_timeout(struct bsg_device *bd, struct sg_io_v4 *hdr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff816a04bc)
Location: block/bsg.c:45
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/bsg-lib.c (ffffffff816a0780)
Location: block/bsg-lib.c:334
Inline: False
```
**Symbols:**

```
ffffffff816a0780-ffffffff816a07b5: bsg_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
unsigned int bsg_timeout(struct bsg_device *bd, struct sg_io_v4 *hdr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff8175efbc)
Location: block/bsg.c:45
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/bsg-lib.c (ffffffff8175f2d0)
Location: block/bsg-lib.c:335
Inline: False
```
**Symbols:**

```
ffffffff8175f2d0-ffffffff8175f305: bsg_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
unsigned int bsg_timeout(struct bsg_device *bd, struct sg_io_v4 *hdr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff8179debb)
Location: block/bsg.c:45
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/bsg-lib.c (ffffffff8179e1b0)
Location: block/bsg-lib.c:335
Inline: False
```
**Symbols:**

```
ffffffff8179e1b0-ffffffff8179e1e5: bsg_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
unsigned int bsg_timeout(struct bsg_device *bd, struct sg_io_v4 *hdr);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff817e193b)
Location: block/bsg.c:45
Inline: True
Inline callers:
  - block/bsg.c:bsg_sg_io
```
```
In block/bsg-lib.c (ffffffff817e1c30)
Location: block/bsg-lib.c:335
Inline: False
```
**Symbols:**

```
ffffffff817e1c30-ffffffff817e1c65: bsg_timeout (STB_LOCAL)
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
enum blk_eh_timer_return bsg_timeout(struct request *rq, bool reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffff80001060aad8)
Location: block/bsg-lib.c:335
Inline: False
```
**Symbols:**

```
ffff80001060aad8-ffff80001060ab24: bsg_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum blk_eh_timer_return bsg_timeout(struct request *rq, bool reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (c07b5954)
Location: block/bsg-lib.c:335
Inline: False
```
**Symbols:**

```
c07b5954-c07b598c: bsg_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum blk_eh_timer_return bsg_timeout(struct request *rq, bool reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (c0000000007a6ee0)
Location: block/bsg-lib.c:335
Inline: False
```
**Symbols:**

```
c0000000007a6ee0-c0000000007a6f38: bsg_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum blk_eh_timer_return bsg_timeout(struct request *rq, bool reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffe000443b8c)
Location: block/bsg-lib.c:335
Inline: False
```
**Symbols:**

```
ffffffe000443b8c-ffffffe000443bc8: bsg_timeout (STB_LOCAL)
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
enum blk_eh_timer_return bsg_timeout(struct request *rq, bool reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81500500)
Location: block/bsg-lib.c:335
Inline: False
```
**Symbols:**

```
ffffffff81500500-ffffffff81500529: bsg_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum blk_eh_timer_return bsg_timeout(struct request *rq, bool reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814f0a10)
Location: block/bsg-lib.c:335
Inline: False
```
**Symbols:**

```
ffffffff814f0a10-ffffffff814f0a39: bsg_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum blk_eh_timer_return bsg_timeout(struct request *rq, bool reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814fc590)
Location: block/bsg-lib.c:335
Inline: False
```
**Symbols:**

```
ffffffff814fc590-ffffffff814fc5b9: bsg_timeout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum blk_eh_timer_return bsg_timeout(struct request *rq, bool reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81515640)
Location: block/bsg-lib.c:335
Inline: False
```
**Symbols:**

```
ffffffff81515640-ffffffff81515669: bsg_timeout (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bsg_device *bd</code>
</li>
<li>
<b>Param added. </b>
<code>struct sg_io_v4 *hdr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request *rq</code>
</li>
<li>
<b>Param removed. </b>
<code>bool reserved</code>
</li>
<li>
<b>Return type changed. </b>
<code>enum blk_eh_timer_return</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
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
