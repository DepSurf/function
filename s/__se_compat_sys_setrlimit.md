# Function: <code>__se_compat_sys_setrlimit</code>

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
In kernel/sys.c (ffffffff810a7c1e)
Location: kernel/sys.c:1411
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
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
In kernel/sys.c (ffffffff810b092e)
Location: kernel/sys.c:1412
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
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
In kernel/sys.c (ffffffff810b63ce)
Location: kernel/sys.c:1412
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
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
In kernel/sys.c (ffffffff810bc98e)
Location: kernel/sys.c:1412
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
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
In kernel/sys.c (ffffffff810c431e)
Location: kernel/sys.c:1428
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
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
In kernel/sys.c (ffffffff810bf71e)
Location: kernel/sys.c:1429
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
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
In kernel/sys.c (ffffffff810c114f)
Location: kernel/sys.c:1446
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
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
In kernel/sys.c (ffffffff810d3c3f)
Location: kernel/sys.c:1455
Inline: True
Inline callers:
  - kernel/sys.c:__x64_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
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
In kernel/sys.c (ffffffff810e901c)
Location: kernel/sys.c:1524
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_setrlimit
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
In kernel/sys.c (ffffffff811098cc)
Location: kernel/sys.c:1529
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_setrlimit
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
In kernel/sys.c (ffffffff81115c5c)
Location: kernel/sys.c:1547
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_setrlimit
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
In kernel/sys.c (ffffffff8111f64c)
Location: kernel/sys.c:1547
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_setrlimit
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
In kernel/sys.c (ffff800010119020)
Location: kernel/sys.c:1412
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_compat_sys_setrlimit
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
long int __se_compat_sys_setrlimit(long int resource, long int rlim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c000000000160b00)
Location: kernel/sys.c:1412
Inline: False
```
**Symbols:**

```
c000000000160b00-c000000000160bd0: __se_compat_sys_setrlimit (STB_GLOBAL)
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
In kernel/sys.c (ffffffff810b6cfe)
Location: kernel/sys.c:1412
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
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
In kernel/sys.c (ffffffff810a563e)
Location: kernel/sys.c:1412
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
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
In kernel/sys.c (ffffffff810b625e)
Location: kernel/sys.c:1412
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
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
In kernel/sys.c (ffffffff810be5ce)
Location: kernel/sys.c:1412
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_setrlimit
  - kernel/sys.c:__ia32_compat_sys_setrlimit
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
