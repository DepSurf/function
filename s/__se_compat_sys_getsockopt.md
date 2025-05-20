# Function: <code>__se_compat_sys_getsockopt</code>

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
In net/compat.c (ffffffff818c92b5)
Location: net/compat.c:542
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_getsockopt
  - net/compat.c:__ia32_compat_sys_getsockopt
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
In net/compat.c (ffffffff818f4175)
Location: net/compat.c:547
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_getsockopt
  - net/compat.c:__ia32_compat_sys_getsockopt
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
In net/compat.c (ffffffff819539f5)
Location: net/compat.c:428
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_getsockopt
  - net/compat.c:__ia32_compat_sys_getsockopt
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
In net/compat.c (ffffffff81989f45)
Location: net/compat.c:428
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_getsockopt
  - net/compat.c:__ia32_compat_sys_getsockopt
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
In net/compat.c (ffffffff81a62305)
Location: net/compat.c:447
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_getsockopt
  - net/compat.c:__ia32_compat_sys_getsockopt
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In net/compat.c (ffff800010c32728)
Location: net/compat.c:428
Inline: True
Inline callers:
  - net/compat.c:__arm64_compat_sys_getsockopt
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
long int __se_compat_sys_getsockopt(long int fd, long int level, long int optname, long int optval, long int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (c000000000d2ba20)
Location: net/compat.c:428
Inline: False
```
**Symbols:**

```
c000000000d2ba20-c000000000d2ba5c: __se_compat_sys_getsockopt (STB_GLOBAL)
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
In net/compat.c (ffffffff81929db5)
Location: net/compat.c:428
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_getsockopt
  - net/compat.c:__ia32_compat_sys_getsockopt
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
In net/compat.c (ffffffff818e3b65)
Location: net/compat.c:428
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_getsockopt
  - net/compat.c:__ia32_compat_sys_getsockopt
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
In net/compat.c (ffffffff8197af45)
Location: net/compat.c:428
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_getsockopt
  - net/compat.c:__ia32_compat_sys_getsockopt
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
In net/compat.c (ffffffff8199d495)
Location: net/compat.c:428
Inline: True
Inline callers:
  - net/compat.c:__x32_compat_sys_getsockopt
  - net/compat.c:__ia32_compat_sys_getsockopt
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
