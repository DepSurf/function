# Function: <code>futex_hash</code>

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
struct futex_hash_bucket *futex_hash(union futex_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b2250)
Location: kernel/futex/core.c:115
Inline: False
Direct callers:
  - kernel/futex/core.c:exit_pi_state_list
  - kernel/futex/core.c:futex_q_lock
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
```
**Symbols:**

```
ffffffff811b2250-ffffffff811b231e: futex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct futex_hash_bucket *futex_hash(union futex_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811f30c0)
Location: kernel/futex/core.c:115
Inline: False
Direct callers:
  - kernel/futex/core.c:exit_pi_state_list
  - kernel/futex/core.c:futex_q_lock
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
```
**Symbols:**

```
ffffffff811f30c0-ffffffff811f318e: futex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct futex_hash_bucket *futex_hash(union futex_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff81207840)
Location: kernel/futex/core.c:115
Inline: False
Direct callers:
  - kernel/futex/core.c:exit_pi_state_list
  - kernel/futex/core.c:futex_q_lock
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
```
**Symbols:**

```
ffffffff81207840-ffffffff8120790e: futex_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct futex_hash_bucket *futex_hash(union futex_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff8121ea50)
Location: kernel/futex/core.c:116
Inline: False
Direct callers:
  - kernel/futex/core.c:exit_pi_state_list
  - kernel/futex/core.c:futex_q_lock
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/requeue.c:futex_requeue
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake_op
  - kernel/futex/waitwake.c:futex_wake
```
**Symbols:**

```
ffffffff8121ea50-ffffffff8121eb1e: futex_hash (STB_GLOBAL)
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
