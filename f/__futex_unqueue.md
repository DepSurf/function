# Function: <code>__futex_unqueue</code>

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
void __futex_unqueue(struct futex_q *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b3210)
Location: kernel/futex/core.c:499
Inline: False
Direct callers:
  - kernel/futex/core.c:futex_unqueue_pi
  - kernel/futex/core.c:futex_unqueue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wake_mark
```
**Symbols:**

```
ffffffff811b3210-ffffffff811b3263: __futex_unqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __futex_unqueue(struct futex_q *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811f4130)
Location: kernel/futex/core.c:499
Inline: False
Direct callers:
  - kernel/futex/core.c:futex_unqueue_pi
  - kernel/futex/core.c:futex_unqueue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wake_mark
```
**Symbols:**

```
ffffffff811f4130-ffffffff811f4183: __futex_unqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __futex_unqueue(struct futex_q *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff812088c0)
Location: kernel/futex/core.c:499
Inline: False
Direct callers:
  - kernel/futex/core.c:futex_unqueue_pi
  - kernel/futex/core.c:futex_unqueue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
```
**Symbols:**

```
ffffffff812088c0-ffffffff81208913: __futex_unqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __futex_unqueue(struct futex_q *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff8121f750)
Location: kernel/futex/core.c:512
Inline: False
Direct callers:
  - kernel/futex/core.c:futex_unqueue_pi
  - kernel/futex/core.c:futex_unqueue
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wake_mark
```
**Symbols:**

```
ffffffff8121f750-ffffffff8121f7a3: __futex_unqueue (STB_GLOBAL)
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
