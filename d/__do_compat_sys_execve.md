# Function: <code>__do_compat_sys_execve</code>

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
In fs/exec.c (ffffffff812a3274)
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
In fs/exec.c (ffffffff812b8364)
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
In fs/exec.c (ffffffff812d47c4)
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
In fs/exec.c (ffffffff812e6344)
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
In fs/exec.c (ffffffff8131db16)
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
In fs/exec.c (ffffffff81329076)
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
In fs/exec.c (ffffffff8132ee34)
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
In fs/exec.c (ffffffff8137c674)
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
In fs/exec.c (ffffffff813fc803)
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
In fs/exec.c (ffffffff81486303)
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
In fs/exec.c (ffffffff814bae73)
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
In fs/exec.c (ffffffff814ed3e3)
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
In fs/exec.c (ffff80001038e4d0)
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
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (c00000000048693c)
Location: fs/exec.c:1990
Inline: True
Inline callers:
  - fs/exec.c:__se_compat_sys_execve
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
In fs/exec.c (ffffffff812de924)
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
In fs/exec.c (ffffffff812cfc54)
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
In fs/exec.c (ffffffff812dc734)
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
In fs/exec.c (ffffffff812ed4f4)
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
