# Function: <code>elv_rb_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b3310)
Location: block/elevator.c:297
Inline: False
Direct callers:
  - block/deadline-iosched.c:deadline_add_request
  - block/deadline-iosched.c:deadline_merged_request
  - block/cfq-iosched.c:cfq_add_rq_rb
```
**Symbols:**

```
ffffffff813b3310-ffffffff813b3373: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f7010)
Location: block/elevator.c:297
Inline: False
Direct callers:
  - block/deadline-iosched.c:deadline_merged_request
  - block/deadline-iosched.c:deadline_add_request
  - block/cfq-iosched.c:cfq_add_rq_rb
```
**Symbols:**

```
ffffffff813f7010-ffffffff813f7073: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81410a20)
Location: block/elevator.c:297
Inline: False
Direct callers:
  - block/deadline-iosched.c:deadline_merged_request
  - block/deadline-iosched.c:deadline_add_request
  - block/cfq-iosched.c:cfq_add_rq_rb
```
**Symbols:**

```
ffffffff81410a20-ffffffff81410a83: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141e470)
Location: block/elevator.c:323
Inline: False
Direct callers:
  - block/deadline-iosched.c:deadline_merged_request
  - block/deadline-iosched.c:deadline_add_request
  - block/cfq-iosched.c:cfq_add_rq_rb
```
**Symbols:**

```
ffffffff8141e470-ffffffff8141e4d1: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81448c10)
Location: block/elevator.c:340
Inline: False
Direct callers:
  - block/deadline-iosched.c:deadline_merged_request
  - block/deadline-iosched.c:deadline_add_request
  - block/cfq-iosched.c:cfq_add_rq_rb
```
**Symbols:**

```
ffffffff81448c10-ffffffff81448c71: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147bd00)
Location: block/elevator.c:309
Inline: False
Direct callers:
  - block/deadline-iosched.c:deadline_merged_request
  - block/deadline-iosched.c:deadline_add_request
  - block/cfq-iosched.c:cfq_add_rq_rb
```
**Symbols:**

```
ffffffff8147bd00-ffffffff8147bd55: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149a010)
Location: block/elevator.c:244
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffffffff8149a010-ffffffff8149a065: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814c80d0)
Location: block/elevator.c:245
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffffffff814c80d0-ffffffff814c812b: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814e11c0)
Location: block/elevator.c:255
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffffffff814e11c0-ffffffff814e121b: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8153fdb0)
Location: block/elevator.c:255
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffffffff8153fdb0-ffffffff8153fe11: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8155c550)
Location: block/elevator.c:254
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffffffff8155c550-ffffffff8155c5b1: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81564df0)
Location: block/elevator.c:254
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffffffff81564df0-ffffffff81564e4b: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815c9170)
Location: block/elevator.c:254
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_request
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffffffff815c9170-ffffffff815c91cb: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81674380)
Location: block/elevator.c:259
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffffffff81674380-ffffffff816743fb: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81730070)
Location: block/elevator.c:227
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffffffff81730070-ffffffff817300eb: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8176c2a0)
Location: block/elevator.c:227
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffffffff8176c2a0-ffffffff8176c31b: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817ae490)
Location: block/elevator.c:227
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffffffff817ae490-ffffffff817ae50b: elv_rb_add (STB_GLOBAL)
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
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105de0d0)
Location: block/elevator.c:255
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffff8000105de0d0-ffff8000105de144: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078b1f0)
Location: block/elevator.c:255
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
c078b1f0-c078b268: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c00000000076f920)
Location: block/elevator.c:255
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
c00000000076f920-c00000000076f9b8: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe000420d68)
Location: block/elevator.c:255
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffffffe000420d68-ffffffe000420dca: elv_rb_add (STB_GLOBAL)
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
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d97a0)
Location: block/elevator.c:255
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffffffff814d97a0-ffffffff814d97fb: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ca150)
Location: block/elevator.c:255
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffffffff814ca150-ffffffff814ca1ab: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d5830)
Location: block/elevator.c:255
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffffffff814d5830-ffffffff814d588b: elv_rb_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void elv_rb_add(struct rb_root *root, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ee450)
Location: block/elevator.c:255
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_insert_requests
  - block/mq-deadline.c:dd_request_merged
```
**Symbols:**

```
ffffffff814ee450-ffffffff814ee4ab: elv_rb_add (STB_GLOBAL)
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
