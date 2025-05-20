# Function: <code>futex_init_timeout</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8115bd8b)
Location: kernel/futex.c:3772
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81180ddb)
Location: kernel/futex.c:4009
Inline: True
Inline callers:
  - kernel/futex.c:__ia32_sys_futex_time32
  - kernel/futex.c:__x64_sys_futex_time32
  - kernel/futex.c:__ia32_sys_futex
  - kernel/futex.c:__x64_sys_futex
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex/syscalls.c (ffffffff811b418d)
Location: kernel/futex/syscalls.c:151
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
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
In kernel/futex/syscalls.c (ffffffff811f51ed)
Location: kernel/futex/syscalls.c:151
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
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
In kernel/futex/syscalls.c (ffffffff812099a4)
Location: kernel/futex/syscalls.c:151
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:__do_sys_futex_waitv
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/futex/syscalls.c (ffffffff81220924)
Location: kernel/futex/syscalls.c:147
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_sys_futex_time32
  - kernel/futex/syscalls.c:__x64_sys_futex_time32
  - kernel/futex/syscalls.c:futex2_setup_timeout
  - kernel/futex/syscalls.c:__ia32_sys_futex
  - kernel/futex/syscalls.c:__x64_sys_futex
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
