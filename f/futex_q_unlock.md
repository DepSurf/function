# Function: <code>futex_q_unlock</code>

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
void futex_q_unlock(struct futex_hash_bucket *hb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b32b0)
Location: kernel/futex/core.c:536
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/waitwake.c:futex_wait_setup
  - kernel/futex/waitwake.c:futex_wait_setup
  - kernel/futex/waitwake.c:futex_wait_multiple_setup
  - kernel/futex/waitwake.c:futex_wait_multiple_setup
```
**Symbols:**

```
ffffffff811b32b0-ffffffff811b32d5: futex_q_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void futex_q_unlock(struct futex_hash_bucket *hb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811f41f0)
Location: kernel/futex/core.c:536
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/waitwake.c:futex_wait_setup
  - kernel/futex/waitwake.c:futex_wait_setup
  - kernel/futex/waitwake.c:futex_wait_multiple_setup
  - kernel/futex/waitwake.c:futex_wait_multiple_setup
```
**Symbols:**

```
ffffffff811f41f0-ffffffff811f4215: futex_q_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void futex_q_unlock(struct futex_hash_bucket *hb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff81208980)
Location: kernel/futex/core.c:536
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/waitwake.c:futex_wait_setup
  - kernel/futex/waitwake.c:futex_wait_setup
  - kernel/futex/waitwake.c:futex_wait_multiple_setup
  - kernel/futex/waitwake.c:futex_wait_multiple_setup
```
**Symbols:**

```
ffffffff81208980-ffffffff812089a5: futex_q_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void futex_q_unlock(struct futex_hash_bucket *hb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff8121f810)
Location: kernel/futex/core.c:549
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/requeue.c:futex_wait_requeue_pi
  - kernel/futex/waitwake.c:futex_wait_setup
  - kernel/futex/waitwake.c:futex_wait_setup
  - kernel/futex/waitwake.c:futex_wait_multiple_setup
  - kernel/futex/waitwake.c:futex_wait_multiple_setup
```
**Symbols:**

```
ffffffff8121f810-ffffffff8121f835: futex_q_unlock (STB_GLOBAL)
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
