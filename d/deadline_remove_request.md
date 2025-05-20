# Function: <code>deadline_remove_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff813dca0f)
Location: block/deadline-iosched.c:116
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff81422640)
Location: block/deadline-iosched.c:115
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff8143d77a)
Location: block/deadline-iosched.c:115
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff8144cbaa)
Location: block/deadline-iosched.c:115
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff814792aa)
Location: block/deadline-iosched.c:115
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff814addbe)
Location: block/deadline-iosched.c:119
Inline: True
Inline callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void deadline_remove_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814c7c90)
Location: block/mq-deadline.c:108
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
ffffffff814c7c90-ffffffff814c7d40: deadline_remove_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void deadline_remove_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814f6510)
Location: block/mq-deadline.c:109
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
ffffffff814f6510-ffffffff814f65c0: deadline_remove_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void deadline_remove_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff815143a0)
Location: block/mq-deadline.c:109
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
ffffffff815143a0-ffffffff8151444e: deadline_remove_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void deadline_remove_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff815751f0)
Location: block/mq-deadline.c:109
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
ffffffff815751f0-ffffffff8157529b: deadline_remove_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void deadline_remove_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81591fd0)
Location: block/mq-deadline.c:109
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
ffffffff81591fd0-ffffffff8159207b: deadline_remove_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void deadline_remove_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81598e10)
Location: block/mq-deadline.c:111
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
ffffffff81598e10-ffffffff81598ebb: deadline_remove_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void deadline_remove_request(struct request_queue *q, struct dd_per_prio *per_prio, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81601090)
Location: block/mq-deadline.c:192
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
ffffffff81601090-ffffffff81601144: deadline_remove_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void deadline_remove_request(struct request_queue *q, struct dd_per_prio *per_prio, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff816b3890)
Location: block/mq-deadline.c:169
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
ffffffff816b3890-ffffffff816b3967: deadline_remove_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void deadline_remove_request(struct request_queue *q, struct dd_per_prio *per_prio, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff817730e0)
Location: block/mq-deadline.c:183
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
ffffffff817730e0-ffffffff817731b6: deadline_remove_request (STB_LOCAL)
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
In block/mq-deadline.c (ffffffff817b35d7)
Location: block/mq-deadline.c:210
Inline: True
Inline callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
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
In block/mq-deadline.c (ffffffff817f74e1)
Location: block/mq-deadline.c:210
Inline: True
Inline callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
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
void deadline_remove_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffff800010618e90)
Location: block/mq-deadline.c:109
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
ffff800010618e90-ffff800010618f80: deadline_remove_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void deadline_remove_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (c07c3a6c)
Location: block/mq-deadline.c:109
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
c07c3a6c-c07c3b28: deadline_remove_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void deadline_remove_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (c0000000007b8430)
Location: block/mq-deadline.c:109
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
c0000000007b8430-c0000000007b8574: deadline_remove_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void deadline_remove_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffe00044ed00)
Location: block/mq-deadline.c:109
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
ffffffe00044ed00-ffffffe00044edc8: deadline_remove_request (STB_LOCAL)
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
void deadline_remove_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff8150c980)
Location: block/mq-deadline.c:109
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
ffffffff8150c980-ffffffff8150ca2e: deadline_remove_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void deadline_remove_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff814fcdb0)
Location: block/mq-deadline.c:109
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
ffffffff814fcdb0-ffffffff814fce5e: deadline_remove_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void deadline_remove_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81508a10)
Location: block/mq-deadline.c:109
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
ffffffff81508a10-ffffffff81508abe: deadline_remove_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void deadline_remove_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81522110)
Location: block/mq-deadline.c:109
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
```
**Symbols:**

```
ffffffff81522110-ffffffff815221be: deadline_remove_request (STB_LOCAL)
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
<code>struct dd_per_prio *per_prio</code>
</li>
<li>
<b>Param reordered. </b>
<code>q, rq</code> ➡️ <code>q, per_prio, rq</code>
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
