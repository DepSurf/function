# Function: <code>elv_dispatch_add_tail</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void elv_dispatch_add_tail(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b3a30)
Location: block/elevator.c:396
Inline: False
Direct callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
```
**Symbols:**

```
ffffffff813b3a30-ffffffff813b3a9c: elv_dispatch_add_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void elv_dispatch_add_tail(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f7710)
Location: block/elevator.c:395
Inline: False
Direct callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
```
**Symbols:**

```
ffffffff813f7710-ffffffff813f777c: elv_dispatch_add_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void elv_dispatch_add_tail(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814111c0)
Location: block/elevator.c:393
Inline: False
Direct callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
```
**Symbols:**

```
ffffffff814111c0-ffffffff8141122c: elv_dispatch_add_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void elv_dispatch_add_tail(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141e7e0)
Location: block/elevator.c:419
Inline: False
Direct callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
```
**Symbols:**

```
ffffffff8141e7e0-ffffffff8141e84f: elv_dispatch_add_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void elv_dispatch_add_tail(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81448e00)
Location: block/elevator.c:436
Inline: False
Direct callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
```
**Symbols:**

```
ffffffff81448e00-ffffffff81448e6f: elv_dispatch_add_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void elv_dispatch_add_tail(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147be20)
Location: block/elevator.c:405
Inline: False
Direct callers:
  - block/deadline-iosched.c:deadline_dispatch_requests
```
**Symbols:**

```
ffffffff8147be20-ffffffff8147be91: elv_dispatch_add_tail (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
