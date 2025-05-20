# Function: <code>elv_dispatch_sort</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void elv_dispatch_sort(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b3930)
Location: block/elevator.c:351
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_dispatch
  - block/cfq-iosched.c:cfq_dispatch_insert
```
**Symbols:**

```
ffffffff813b3930-ffffffff813b3a25: elv_dispatch_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void elv_dispatch_sort(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f7630)
Location: block/elevator.c:351
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_dispatch
  - block/cfq-iosched.c:cfq_dispatch_insert
```
**Symbols:**

```
ffffffff813f7630-ffffffff813f770b: elv_dispatch_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void elv_dispatch_sort(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814110d0)
Location: block/elevator.c:351
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_dispatch
  - block/cfq-iosched.c:cfq_dispatch_insert
```
**Symbols:**

```
ffffffff814110d0-ffffffff814111b7: elv_dispatch_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void elv_dispatch_sort(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141e850)
Location: block/elevator.c:377
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_dispatch
  - block/cfq-iosched.c:cfq_dispatch_insert
```
**Symbols:**

```
ffffffff8141e850-ffffffff8141e938: elv_dispatch_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void elv_dispatch_sort(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81448e70)
Location: block/elevator.c:394
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_dispatch
  - block/cfq-iosched.c:cfq_dispatch_insert
```
**Symbols:**

```
ffffffff81448e70-ffffffff81448f58: elv_dispatch_sort (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void elv_dispatch_sort(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147bea0)
Location: block/elevator.c:363
Inline: False
Direct callers:
  - block/noop-iosched.c:noop_dispatch
  - block/cfq-iosched.c:cfq_dispatch_insert
```
**Symbols:**

```
ffffffff8147bea0-ffffffff8147bf82: elv_dispatch_sort (STB_GLOBAL)
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
