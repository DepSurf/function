# Function: <code>receive_fd_user</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff819f667b)
Location: include/linux/file.h:97
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffffffff81a6b300)
Location: include/linux/file.h:97
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff819dc7f2)
Location: include/linux/file.h:97
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffffffff81a53a2d)
Location: include/linux/file.h:97
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81a8ca32)
Location: include/linux/file.h:100
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffffffff81b0c73d)
Location: include/linux/file.h:100
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81c022f2)
Location: include/linux/file.h:98
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffffffff81c93039)
Location: include/linux/file.h:98
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81db1462)
Location: include/linux/file.h:98
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffffffff81e4e669)
Location: include/linux/file.h:98
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/scm.c (ffffffff81e2197f)
Location: include/linux/file.h:104
Inline: True
Inline callers:
  - net/core/scm.c:scm_detach_fds
```
```
In net/compat.c (ffffffff81ea9cd7)
Location: include/linux/file.h:104
Inline: True
Inline callers:
  - net/compat.c:scm_detach_fds_compat
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
