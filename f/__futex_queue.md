# Function: <code>__futex_queue</code>

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
void __futex_queue(struct futex_q *q, struct futex_hash_bucket *hb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b32e0)
Location: kernel/futex/core.c:543
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/waitwake.c:futex_wait_multiple_setup
  - kernel/futex/waitwake.c:futex_wait_queue
```
**Symbols:**

```
ffffffff811b32e0-ffffffff811b333f: __futex_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __futex_queue(struct futex_q *q, struct futex_hash_bucket *hb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811f4230)
Location: kernel/futex/core.c:543
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/waitwake.c:futex_wait_multiple_setup
  - kernel/futex/waitwake.c:futex_wait_queue
```
**Symbols:**

```
ffffffff811f4230-ffffffff811f428f: __futex_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __futex_queue(struct futex_q *q, struct futex_hash_bucket *hb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff812089c0)
Location: kernel/futex/core.c:543
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/waitwake.c:futex_wait_multiple_setup
  - kernel/futex/waitwake.c:futex_wait_queue
```
**Symbols:**

```
ffffffff812089c0-ffffffff81208a1f: __futex_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __futex_queue(struct futex_q *q, struct futex_hash_bucket *hb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff8121f850)
Location: kernel/futex/core.c:556
Inline: False
Direct callers:
  - kernel/futex/pi.c:futex_lock_pi
  - kernel/futex/waitwake.c:futex_wait_multiple_setup
  - kernel/futex/waitwake.c:futex_wait_queue
  - io_uring/futex.c:io_futex_wait
```
**Symbols:**

```
ffffffff8121f850-ffffffff8121f8af: __futex_queue (STB_GLOBAL)
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
