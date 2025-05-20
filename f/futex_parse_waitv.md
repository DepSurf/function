# Function: <code>futex_parse_waitv</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex/syscalls.c (ffffffff811b39b5)
Location: kernel/futex/syscalls.c:197
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex/syscalls.c (ffffffff811f49c5)
Location: kernel/futex/syscalls.c:197
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex/syscalls.c (ffffffff81209155)
Location: kernel/futex/syscalls.c:197
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int futex_parse_waitv(struct futex_vector *futexv, struct futex_waitv *uwaitv, unsigned int nr_futexes, futex_wake_fn *wake, void *wake_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/syscalls.c (ffffffff81220eb0)
Location: kernel/futex/syscalls.c:192
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:__do_sys_futex_requeue
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - io_uring/futex.c:io_futexv_prep
```
**Symbols:**

```
ffffffff81220eb0-ffffffff812210a4: futex_parse_waitv (STB_GLOBAL)
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
</ul>
