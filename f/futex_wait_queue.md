# Function: <code>futex_wait_queue</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void futex_wait_queue(struct futex_hash_bucket *hb, struct futex_q *q, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff811b71c0)
Location: kernel/futex/waitwake.c:328
Inline: False
Direct callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/waitwake.c:futex_wait
```
**Symbols:**

```
ffffffff811b71c0-ffffffff811b7296: futex_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void futex_wait_queue(struct futex_hash_bucket *hb, struct futex_q *q, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff811f8360)
Location: kernel/futex/waitwake.c:328
Inline: False
Direct callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/waitwake.c:futex_wait
```
**Symbols:**

```
ffffffff811f8360-ffffffff811f83f5: futex_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void futex_wait_queue(struct futex_hash_bucket *hb, struct futex_q *q, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff8120cb20)
Location: kernel/futex/waitwake.c:328
Inline: False
Direct callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/waitwake.c:futex_wait
```
**Symbols:**

```
ffffffff8120cb20-ffffffff8120cbb6: futex_wait_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void futex_wait_queue(struct futex_hash_bucket *hb, struct futex_q *q, struct hrtimer_sleeper *timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff81223ef0)
Location: kernel/futex/waitwake.c:343
Inline: False
Direct callers:
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/waitwake.c:__futex_wait
```
**Symbols:**

```
ffffffff81223ef0-ffffffff81223f86: futex_wait_queue (STB_GLOBAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
