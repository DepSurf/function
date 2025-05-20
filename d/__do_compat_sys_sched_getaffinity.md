# Function: <code>__do_compat_sys_sched_getaffinity</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8113b0ed)
Location: kernel/compat.c:299
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8114695d)
Location: kernel/compat.c:299
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81151aad)
Location: kernel/compat.c:232
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8115d6fd)
Location: kernel/compat.c:232
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116e13d)
Location: kernel/compat.c:144
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116a74d)
Location: kernel/compat.c:144
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8116b3ad)
Location: kernel/compat.c:144
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
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
In kernel/compat.c (ffffffff81190fad)
Location: kernel/compat.c:144
Inline: True
Inline callers:
  - kernel/compat.c:__x64_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
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
In kernel/compat.c (ffffffff811c069c)
Location: kernel/compat.c:144
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
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
In kernel/compat.c (ffffffff81202a9c)
Location: kernel/compat.c:144
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
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
In kernel/compat.c (ffffffff81217e5c)
Location: kernel/compat.c:144
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
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
In kernel/compat.c (ffffffff8122fa1c)
Location: kernel/compat.c:144
Inline: True
Inline callers:
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffff8000101cdcec)
Location: kernel/compat.c:232
Inline: True
Inline callers:
  - kernel/compat.c:__arm64_compat_sys_sched_getaffinity
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_compat_sys_sched_getaffinity(compat_pid_t pid, unsigned int len, compat_ulong_t *user_mask_ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (c0000000002375a0)
Location: kernel/compat.c:232
Inline: False
Direct callers:
  - kernel/compat.c:__se_compat_sys_sched_getaffinity
```
**Symbols:**

```
c0000000002375a0-c0000000002376e0: __do_compat_sys_sched_getaffinity (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81155d1d)
Location: kernel/compat.c:232
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8114903d)
Location: kernel/compat.c:232
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81153aed)
Location: kernel/compat.c:232
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811609ed)
Location: kernel/compat.c:232
Inline: True
Inline callers:
  - kernel/compat.c:__x32_compat_sys_sched_getaffinity
  - kernel/compat.c:__ia32_compat_sys_sched_getaffinity
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
