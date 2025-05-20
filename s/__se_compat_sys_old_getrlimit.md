# Function: <code>__se_compat_sys_old_getrlimit</code>

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
In kernel/sys.c (ffffffff810a4cc2)
Location: kernel/sys.c:1481
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
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
In kernel/sys.c (ffffffff810ad972)
Location: kernel/sys.c:1482
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
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
In kernel/sys.c (ffffffff810b37c2)
Location: kernel/sys.c:1482
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
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
In kernel/sys.c (ffffffff810b9db2)
Location: kernel/sys.c:1482
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
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
In kernel/sys.c (ffffffff810c1cc2)
Location: kernel/sys.c:1498
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
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
In kernel/sys.c (ffffffff810bcfb2)
Location: kernel/sys.c:1499
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
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
In kernel/sys.c (ffffffff810bf162)
Location: kernel/sys.c:1516
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
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
In kernel/sys.c (ffffffff810d1b06)
Location: kernel/sys.c:1525
Inline: True
Inline callers:
  - kernel/sys.c:__x64_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
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
In kernel/sys.c (ffffffff810e7736)
Location: kernel/sys.c:1594
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
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
In kernel/sys.c (ffffffff811083c6)
Location: kernel/sys.c:1599
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
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
In kernel/sys.c (ffffffff811146d6)
Location: kernel/sys.c:1617
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
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
In kernel/sys.c (ffffffff8111e0c6)
Location: kernel/sys.c:1617
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_compat_sys_old_getrlimit(long int resource, long int rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c00000000015dc00)
Location: kernel/sys.c:1482
Inline: False
```
**Symbols:**

```
c00000000015dc00-c00000000015de28: __se_compat_sys_old_getrlimit (STB_GLOBAL)
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
In kernel/sys.c (ffffffff810b4122)
Location: kernel/sys.c:1482
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
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
In kernel/sys.c (ffffffff810a2a52)
Location: kernel/sys.c:1482
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
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
In kernel/sys.c (ffffffff810b3682)
Location: kernel/sys.c:1482
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
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
In kernel/sys.c (ffffffff810bbfb4)
Location: kernel/sys.c:1482
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_old_getrlimit
  - kernel/sys.c:__ia32_compat_sys_old_getrlimit
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
