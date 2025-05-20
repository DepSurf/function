# Function: <code>elv_rb_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b3c90)
Location: block/elevator.c:318
Inline: True
Direct callers:
  - block/deadline-iosched.c:deadline_merged_request
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
  - block/cfq-iosched.c:cfq_remove_request
```
**Symbols:**

```
ffffffff813b3c90-ffffffff813b3cc8: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f7890)
Location: block/elevator.c:318
Inline: True
Direct callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
  - block/deadline-iosched.c:deadline_merged_request
  - block/cfq-iosched.c:cfq_remove_request
```
**Symbols:**

```
ffffffff813f7890-ffffffff813f78c8: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81411040)
Location: block/elevator.c:318
Inline: True
Direct callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
  - block/deadline-iosched.c:deadline_merged_request
  - block/cfq-iosched.c:cfq_remove_request
```
**Symbols:**

```
ffffffff81411040-ffffffff81411078: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141ea10)
Location: block/elevator.c:344
Inline: True
Direct callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
  - block/deadline-iosched.c:deadline_merged_request
  - block/cfq-iosched.c:cfq_remove_request
```
**Symbols:**

```
ffffffff8141ea10-ffffffff8141ea48: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814494e0)
Location: block/elevator.c:361
Inline: True
Direct callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
  - block/deadline-iosched.c:deadline_merged_request
  - block/cfq-iosched.c:cfq_remove_request
```
**Symbols:**

```
ffffffff814494e0-ffffffff81449518: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147c130)
Location: block/elevator.c:330
Inline: True
Direct callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
  - block/deadline-iosched.c:deadline_merged_requests
  - block/deadline-iosched.c:deadline_merged_request
  - block/cfq-iosched.c:cfq_remove_request
```
**Symbols:**

```
ffffffff8147c130-ffffffff8147c15f: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149a1a0)
Location: block/elevator.c:265
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff8149a1a0-ffffffff8149a1cf: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814c8270)
Location: block/elevator.c:266
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff814c8270-ffffffff814c829f: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814e1360)
Location: block/elevator.c:276
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff814e1360-ffffffff814e138f: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8153feb0)
Location: block/elevator.c:276
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff8153feb0-ffffffff8153fedf: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8155c650)
Location: block/elevator.c:275
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff8155c650-ffffffff8155c67f: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81564ee0)
Location: block/elevator.c:275
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff81564ee0-ffffffff81564f0f: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815c91d0)
Location: block/elevator.c:275
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff815c91d0-ffffffff815c91ff: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81674400)
Location: block/elevator.c:280
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff81674400-ffffffff81674440: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81730100)
Location: block/elevator.c:248
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff81730100-ffffffff81730140: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8176c330)
Location: block/elevator.c:248
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffffffff8176c330-ffffffff8176c370: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817ae520)
Location: block/elevator.c:248
Inline: False
Direct callers:
  - block/mq-deadline.c:__dd_dispatch_request
  - block/mq-deadline.c:dd_merged_requests
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffffffff817ae520-ffffffff817ae560: elv_rb_del (STB_GLOBAL)
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
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105de310)
Location: block/elevator.c:276
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffff8000105de310-ffff8000105de364: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078b3e0)
Location: block/elevator.c:276
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
c078b3e0-c078b420: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c00000000076f9c0)
Location: block/elevator.c:276
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
c00000000076f9c0-c00000000076fa2c: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe000420f30)
Location: block/elevator.c:276
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffe000420f30-ffffffe000420f76: elv_rb_del (STB_GLOBAL)
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
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d9940)
Location: block/elevator.c:276
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff814d9940-ffffffff814d996f: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ca2f0)
Location: block/elevator.c:276
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff814ca2f0-ffffffff814ca31f: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d59d0)
Location: block/elevator.c:276
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff814d59d0-ffffffff814d59ff: elv_rb_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void elv_rb_del(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ee5f0)
Location: block/elevator.c:276
Inline: True
Direct callers:
  - block/mq-deadline.c:dd_request_merged
  - block/mq-deadline.c:deadline_remove_request
```
**Symbols:**

```
ffffffff814ee5f0-ffffffff814ee61f: elv_rb_del (STB_GLOBAL)
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
