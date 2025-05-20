# Function: <code>futex_wait_multiple</code>

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
int futex_wait_multiple(struct futex_vector *vs, unsigned int count, struct hrtimer_sleeper *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff811b72a0)
Location: kernel/futex/waitwake.c:524
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
```
**Symbols:**

```
ffffffff811b72a0-ffffffff811b74ab: futex_wait_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int futex_wait_multiple(struct futex_vector *vs, unsigned int count, struct hrtimer_sleeper *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff811f8410)
Location: kernel/futex/waitwake.c:524
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
```
**Symbols:**

```
ffffffff811f8410-ffffffff811f8619: futex_wait_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int futex_wait_multiple(struct futex_vector *vs, unsigned int count, struct hrtimer_sleeper *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff8120cbd0)
Location: kernel/futex/waitwake.c:524
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
```
**Symbols:**

```
ffffffff8120cbd0-ffffffff8120cdd9: futex_wait_multiple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int futex_wait_multiple(struct futex_vector *vs, unsigned int count, struct hrtimer_sleeper *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/waitwake.c (ffffffff812242c0)
Location: kernel/futex/waitwake.c:539
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
```
**Symbols:**

```
ffffffff812242c0-ffffffff812244c7: futex_wait_multiple (STB_GLOBAL)
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
