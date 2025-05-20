# Function: <code>__se_compat_sys_getrlimit</code>

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
In kernel/sys.c (ffffffff810a7cc0)
Location: kernel/sys.c:1431
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
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
In kernel/sys.c (ffffffff810b09d0)
Location: kernel/sys.c:1432
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
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
In kernel/sys.c (ffffffff810b6479)
Location: kernel/sys.c:1432
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
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
In kernel/sys.c (ffffffff810bca39)
Location: kernel/sys.c:1432
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
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
In kernel/sys.c (ffffffff810c43c9)
Location: kernel/sys.c:1448
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
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
In kernel/sys.c (ffffffff810bf7c9)
Location: kernel/sys.c:1449
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
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
In kernel/sys.c (ffffffff810c11f8)
Location: kernel/sys.c:1466
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
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
In kernel/sys.c (ffffffff810d3ce8)
Location: kernel/sys.c:1475
Inline: True
Inline callers:
  - kernel/sys.c:__x64_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
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
In kernel/sys.c (ffffffff810eb572)
Location: kernel/sys.c:1544
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_getrlimit
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
In kernel/sys.c (ffffffff8110c752)
Location: kernel/sys.c:1549
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_getrlimit
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
In kernel/sys.c (ffffffff81118912)
Location: kernel/sys.c:1567
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_getrlimit
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
In kernel/sys.c (ffffffff81122302)
Location: kernel/sys.c:1567
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_getrlimit
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
In kernel/sys.c (ffff800010119208)
Location: kernel/sys.c:1432
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_compat_sys_getrlimit
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
long int __se_compat_sys_getrlimit(long int resource, long int rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c000000000160bd0)
Location: kernel/sys.c:1432
Inline: False
```
**Symbols:**

```
c000000000160bd0-c000000000160d14: __se_compat_sys_getrlimit (STB_GLOBAL)
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
In kernel/sys.c (ffffffff810b6da9)
Location: kernel/sys.c:1432
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
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
In kernel/sys.c (ffffffff810a56e9)
Location: kernel/sys.c:1432
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
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
In kernel/sys.c (ffffffff810b6309)
Location: kernel/sys.c:1432
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
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
In kernel/sys.c (ffffffff810be679)
Location: kernel/sys.c:1432
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_getrlimit
  - kernel/sys.c:__ia32_compat_sys_getrlimit
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
