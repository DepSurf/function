# Function: <code>elevator_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b3cd0)
Location: block/elevator.c:153
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_init_queue
  - block/deadline-iosched.c:deadline_init_queue
  - block/cfq-iosched.c:cfq_init_queue
```
**Symbols:**

```
ffffffff813b3cd0-ffffffff813b3d5a: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f78d0)
Location: block/elevator.c:153
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_init_queue
  - block/deadline-iosched.c:deadline_init_queue
  - block/cfq-iosched.c:cfq_init_queue
```
**Symbols:**

```
ffffffff813f78d0-ffffffff813f795a: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81411230)
Location: block/elevator.c:153
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_init_queue
  - block/deadline-iosched.c:deadline_init_queue
  - block/cfq-iosched.c:cfq_init_queue
```
**Symbols:**

```
ffffffff81411230-ffffffff814112b7: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141ed30)
Location: block/elevator.c:157
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_init_queue
  - block/deadline-iosched.c:deadline_init_queue
  - block/cfq-iosched.c:cfq_init_queue
```
**Symbols:**

```
ffffffff8141ed30-ffffffff8141edcb: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81449810)
Location: block/elevator.c:174
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_init_queue
  - block/deadline-iosched.c:deadline_init_queue
  - block/cfq-iosched.c:cfq_init_queue
```
**Symbols:**

```
ffffffff81449810-ffffffff814498ab: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147c1b0)
Location: block/elevator.c:174
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_init_queue
  - block/deadline-iosched.c:deadline_init_queue
  - block/cfq-iosched.c:cfq_init_queue
```
**Symbols:**

```
ffffffff8147c1b0-ffffffff8147c24b: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149a2d0)
Location: block/elevator.c:153
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_queue
```
**Symbols:**

```
ffffffff8149a2d0-ffffffff8149a350: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814c83b0)
Location: block/elevator.c:154
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_queue
```
**Symbols:**

```
ffffffff814c83b0-ffffffff814c8433: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814e14b0)
Location: block/elevator.c:164
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_queue
```
**Symbols:**

```
ffffffff814e14b0-ffffffff814e1533: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8153fee0)
Location: block/elevator.c:164
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_queue
```
**Symbols:**

```
ffffffff8153fee0-ffffffff8153ff58: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8155c680)
Location: block/elevator.c:164
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_queue
```
**Symbols:**

```
ffffffff8155c680-ffffffff8155c6f8: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81564f10)
Location: block/elevator.c:164
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_queue
```
**Symbols:**

```
ffffffff81564f10-ffffffff81564f88: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815c9290)
Location: block/elevator.c:164
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_sched
```
**Symbols:**

```
ffffffff815c9290-ffffffff815c9308: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81674520)
Location: block/elevator.c:164
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_sched
```
**Symbols:**

```
ffffffff81674520-ffffffff816745a2: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81730260)
Location: block/elevator.c:131
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_sched
```
**Symbols:**

```
ffffffff81730260-ffffffff817302ef: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8176c490)
Location: block/elevator.c:131
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_sched
```
**Symbols:**

```
ffffffff8176c490-ffffffff8176c51f: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817ae680)
Location: block/elevator.c:131
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_sched
```
**Symbols:**

```
ffffffff817ae680-ffffffff817ae743: elevator_alloc (STB_GLOBAL)
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
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105de040)
Location: block/elevator.c:164
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_queue
```
**Symbols:**

```
ffff8000105de040-ffff8000105de0cc: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078b16c)
Location: block/elevator.c:164
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_queue
```
**Symbols:**

```
c078b16c-c078b1f0: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c000000000770490)
Location: block/elevator.c:164
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_queue
```
**Symbols:**

```
c000000000770490-c000000000770554: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe00042109a)
Location: block/elevator.c:164
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_queue
```
**Symbols:**

```
ffffffe00042109a-ffffffe000421122: elevator_alloc (STB_GLOBAL)
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
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d9a90)
Location: block/elevator.c:164
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_queue
```
**Symbols:**

```
ffffffff814d9a90-ffffffff814d9b13: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ca440)
Location: block/elevator.c:164
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_queue
```
**Symbols:**

```
ffffffff814ca440-ffffffff814ca4c3: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d5b20)
Location: block/elevator.c:164
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_queue
```
**Symbols:**

```
ffffffff814d5b20-ffffffff814d5ba3: elevator_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct elevator_queue *elevator_alloc(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ee990)
Location: block/elevator.c:164
Inline: False
Direct callers:
  - block/mq-deadline.c:dd_init_queue
```
**Symbols:**

```
ffffffff814ee990-ffffffff814eea13: elevator_alloc (STB_GLOBAL)
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
