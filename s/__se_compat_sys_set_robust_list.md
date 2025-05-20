# Function: <code>__se_compat_sys_set_robust_list</code>

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
In kernel/futex_compat.c (ffffffff8112bb35)
Location: kernel/futex_compat.c:121
Inline: True
Inline callers:
  - kernel/futex_compat.c:__x32_compat_sys_set_robust_list
  - kernel/futex_compat.c:__ia32_compat_sys_set_robust_list
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
In kernel/futex.c (ffffffff81133445)
Location: kernel/futex.c:3774
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_set_robust_list
  - kernel/futex.c:__ia32_compat_sys_set_robust_list
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
In kernel/futex.c (ffffffff8113e305)
Location: kernel/futex.c:3812
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_set_robust_list
  - kernel/futex.c:__ia32_compat_sys_set_robust_list
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
In kernel/futex.c (ffffffff81149e95)
Location: kernel/futex.c:4065
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_set_robust_list
  - kernel/futex.c:__ia32_compat_sys_set_robust_list
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
In kernel/futex.c (ffffffff8115a705)
Location: kernel/futex.c:3978
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_set_robust_list
  - kernel/futex.c:__ia32_compat_sys_set_robust_list
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
In kernel/futex.c (ffffffff81156755)
Location: kernel/futex.c:3904
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_set_robust_list
  - kernel/futex.c:__ia32_compat_sys_set_robust_list
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
In kernel/futex.c (ffffffff81157b55)
Location: kernel/futex.c:3910
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_set_robust_list
  - kernel/futex.c:__ia32_compat_sys_set_robust_list
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
In kernel/futex.c (ffffffff8117c9d5)
Location: kernel/futex.c:4147
Inline: True
Inline callers:
  - kernel/futex.c:__x64_compat_sys_set_robust_list
  - kernel/futex.c:__ia32_compat_sys_set_robust_list
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
In kernel/futex/syscalls.c (ffffffff811b35b5)
Location: kernel/futex/syscalls.c:306
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_compat_sys_set_robust_list
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
In kernel/futex/syscalls.c (ffffffff811f4585)
Location: kernel/futex/syscalls.c:309
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_compat_sys_set_robust_list
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
In kernel/futex/syscalls.c (ffffffff81208d15)
Location: kernel/futex/syscalls.c:309
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_compat_sys_set_robust_list
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
In kernel/futex/syscalls.c (ffffffff8121fbb5)
Location: kernel/futex/syscalls.c:442
Inline: True
Inline callers:
  - kernel/futex/syscalls.c:__ia32_compat_sys_set_robust_list
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
In kernel/futex.c (ffff8000101b6568)
Location: kernel/futex.c:4065
Inline: True
Inline callers:
  - kernel/futex.c:__arm64_compat_sys_set_robust_list
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
long int __se_compat_sys_set_robust_list(long int head, long int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021bcf0)
Location: kernel/futex.c:4065
Inline: False
```
**Symbols:**

```
c00000000021bcf0-c00000000021bd48: __se_compat_sys_set_robust_list (STB_GLOBAL)
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
In kernel/futex.c (ffffffff811424b5)
Location: kernel/futex.c:4065
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_set_robust_list
  - kernel/futex.c:__ia32_compat_sys_set_robust_list
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
In kernel/futex.c (ffffffff81135815)
Location: kernel/futex.c:4065
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_set_robust_list
  - kernel/futex.c:__ia32_compat_sys_set_robust_list
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
In kernel/futex.c (ffffffff81140365)
Location: kernel/futex.c:4065
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_set_robust_list
  - kernel/futex.c:__ia32_compat_sys_set_robust_list
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
In kernel/futex.c (ffffffff8114ce95)
Location: kernel/futex.c:4065
Inline: True
Inline callers:
  - kernel/futex.c:__x32_compat_sys_set_robust_list
  - kernel/futex.c:__ia32_compat_sys_set_robust_list
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
