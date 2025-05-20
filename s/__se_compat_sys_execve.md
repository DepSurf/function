# Function: <code>__se_compat_sys_execve</code>

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
In fs/exec.c (ffffffff812a3265)
Location: fs/exec.c:1992
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
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
In fs/exec.c (ffffffff812b8355)
Location: fs/exec.c:1992
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
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
In fs/exec.c (ffffffff812d47b5)
Location: fs/exec.c:1990
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
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
In fs/exec.c (ffffffff812e6335)
Location: fs/exec.c:1990
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
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
In fs/exec.c (ffffffff8131db05)
Location: fs/exec.c:2098
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
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
In fs/exec.c (ffffffff81329065)
Location: fs/exec.c:2084
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
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
In fs/exec.c (ffffffff8132ee25)
Location: fs/exec.c:2084
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
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
In fs/exec.c (ffffffff8137c665)
Location: fs/exec.c:2084
Inline: True
Inline callers:
  - fs/exec.c:__x64_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
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
In fs/exec.c (ffffffff813fc7f5)
Location: fs/exec.c:2111
Inline: True
Inline callers:
  - fs/exec.c:__ia32_compat_sys_execve
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
In fs/exec.c (ffffffff814862f5)
Location: fs/exec.c:2121
Inline: True
Inline callers:
  - fs/exec.c:__ia32_compat_sys_execve
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
In fs/exec.c (ffffffff814bae65)
Location: fs/exec.c:2128
Inline: True
Inline callers:
  - fs/exec.c:__ia32_compat_sys_execve
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
In fs/exec.c (ffffffff814ed3d5)
Location: fs/exec.c:2149
Inline: True
Inline callers:
  - fs/exec.c:__ia32_compat_sys_execve
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
In fs/exec.c (ffff80001038e4c8)
Location: fs/exec.c:1990
Inline: True
Inline callers:
  - fs/exec.c:__arm64_compat_sys_execve
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
long int __se_compat_sys_execve(long int filename, long int argv, long int envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c000000000486920)
Location: fs/exec.c:1990
Inline: False
```
**Symbols:**

```
c000000000486920-c000000000486980: __se_compat_sys_execve (STB_GLOBAL)
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
In fs/exec.c (ffffffff812de915)
Location: fs/exec.c:1990
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
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
In fs/exec.c (ffffffff812cfc45)
Location: fs/exec.c:1990
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
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
In fs/exec.c (ffffffff812dc725)
Location: fs/exec.c:1990
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
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
In fs/exec.c (ffffffff812ed4e5)
Location: fs/exec.c:1990
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
