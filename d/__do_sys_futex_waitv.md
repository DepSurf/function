# Function: <code>__do_sys_futex_waitv</code>

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
long int __do_sys_futex_waitv(struct futex_waitv *waiters, unsigned int nr_futexes, unsigned int flags, struct __kernel_timespec *timeout, clockid_t clockid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/syscalls.c (ffffffff811b3860)
Location: kernel/futex/syscalls.c:246
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_waitv
  - kernel/futex/syscalls.c:__x64_sys_futex_waitv
```
**Symbols:**

```
ffffffff811b3860-ffffffff811b3c1c: __do_sys_futex_waitv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_futex_waitv(struct futex_waitv *waiters, unsigned int nr_futexes, unsigned int flags, struct __kernel_timespec *timeout, clockid_t clockid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/syscalls.c (ffffffff811f4870)
Location: kernel/futex/syscalls.c:246
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_waitv
  - kernel/futex/syscalls.c:__x64_sys_futex_waitv
```
**Symbols:**

```
ffffffff811f4870-ffffffff811f4c2c: __do_sys_futex_waitv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_futex_waitv(struct futex_waitv *waiters, unsigned int nr_futexes, unsigned int flags, struct __kernel_timespec *timeout, clockid_t clockid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/syscalls.c (ffffffff81209000)
Location: kernel/futex/syscalls.c:246
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_waitv
  - kernel/futex/syscalls.c:__x64_sys_futex_waitv
```
**Symbols:**

```
ffffffff81209000-ffffffff812093bc: __do_sys_futex_waitv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_futex_waitv(struct futex_waitv *waiters, unsigned int nr_futexes, unsigned int flags, struct __kernel_timespec *timeout, clockid_t clockid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/syscalls.c (ffffffff812210c0)
Location: kernel/futex/syscalls.c:290
Inline: False
Direct callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_waitv
  - kernel/futex/syscalls.c:__x64_sys_futex_waitv
```
**Symbols:**

```
ffffffff812210c0-ffffffff81221219: __do_sys_futex_waitv (STB_LOCAL)
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
