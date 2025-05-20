# Function: <code>__se_compat_sys_get_robust_list</code>

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
In kernel/futex_compat.c (ffffffff8112bdbc)
Location: kernel/futex_compat.c:136
Inline: True
Inline callers:
  - kernel/futex_compat.c:__x32_compat_sys_get_robust_list
  - kernel/futex_compat.c:__ia32_compat_sys_get_robust_list
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
In kernel/futex.c (ffffffff8113388c)
Location: kernel/futex.c:3789
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
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
In kernel/futex.c (ffffffff8113e8ec)
Location: kernel/futex.c:3827
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
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
In kernel/futex.c (ffffffff8114a45c)
Location: kernel/futex.c:4080
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
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
In kernel/futex.c (ffffffff8115af7c)
Location: kernel/futex.c:3993
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
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
In kernel/futex.c (ffffffff8115708e)
Location: kernel/futex.c:3919
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
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
In kernel/futex.c (ffffffff811584ae)
Location: kernel/futex.c:3925
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
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
In kernel/futex.c (ffffffff8117d2ee)
Location: kernel/futex.c:4162
Inline: True
Inline callers:
  - kernel/futex.c:__x64_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
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
In kernel/futex/syscalls.c (ffffffff811b36dc)
Location: kernel/futex/syscalls.c:318
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list
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
In kernel/futex/syscalls.c (ffffffff811f46cc)
Location: kernel/futex/syscalls.c:321
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list
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
In kernel/futex/syscalls.c (ffffffff81208e5c)
Location: kernel/futex/syscalls.c:321
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list
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
In kernel/futex/syscalls.c (ffffffff8121fcfc)
Location: kernel/futex/syscalls.c:454
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_compat_sys_get_robust_list
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
In kernel/futex.c (ffff8000101b726c)
Location: kernel/futex.c:4080
Inline: True
Inline callers:
  - kernel/futex.c:__arm64_compat_sys_get_robust_list
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
long int __se_compat_sys_get_robust_list(long int pid, long int head_ptr, long int len_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021c5a0)
Location: kernel/futex.c:4080
Inline: False
```
**Symbols:**

```
c00000000021c5a0-c00000000021c768: __se_compat_sys_get_robust_list (STB_GLOBAL)
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
In kernel/futex.c (ffffffff81142a7c)
Location: kernel/futex.c:4080
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
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
In kernel/futex.c (ffffffff81135ddc)
Location: kernel/futex.c:4080
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
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
In kernel/futex.c (ffffffff8114092c)
Location: kernel/futex.c:4080
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
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
In kernel/futex.c (ffffffff8114db6e)
Location: kernel/futex.c:4080
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_get_robust_list
  - kernel/futex.c:__ia32_compat_sys_get_robust_list
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
