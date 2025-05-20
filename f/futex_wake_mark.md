# Function: <code>futex_wake_mark</code>

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
void futex_wake_mark(struct wake_q_head *wake_q, struct futex_q *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff811b6c10)
Location: kernel/futex/waitwake.c:115
Inline: False
Direct callers:
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
```
**Symbols:**

```
ffffffff811b6c10-ffffffff811b6cb9: futex_wake_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void futex_wake_mark(struct wake_q_head *wake_q, struct futex_q *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff811f7d80)
Location: kernel/futex/waitwake.c:115
Inline: False
Direct callers:
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
```
**Symbols:**

```
ffffffff811f7d80-ffffffff811f7e29: futex_wake_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void futex_wake_mark(struct wake_q_head *wake_q, struct futex_q *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff8120c520)
Location: kernel/futex/waitwake.c:115
Inline: True
Direct callers:
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
```
**Symbols:**

```
ffffffff8120c520-ffffffff8120c5c9: futex_wake_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void futex_wake_mark(struct wake_q_head *wake_q, struct futex_q *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff81223890)
Location: kernel/futex/waitwake.c:134
Inline: False
```
**Symbols:**

```
ffffffff81223890-ffffffff81223992: futex_wake_mark (STB_GLOBAL)
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
