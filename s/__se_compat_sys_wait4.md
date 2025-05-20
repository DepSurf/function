# Function: <code>__se_compat_sys_wait4</code>

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
In kernel/exit.c (ffffffff81094265)
Location: kernel/exit.c:1700
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
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
In kernel/exit.c (ffffffff8109c605)
Location: kernel/exit.c:1702
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
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
In kernel/exit.c (ffffffff810a0c25)
Location: kernel/exit.c:1706
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
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
In kernel/exit.c (ffffffff810a7205)
Location: kernel/exit.c:1652
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
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
In kernel/exit.c (ffffffff810ae955)
Location: kernel/exit.c:1656
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
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
In kernel/exit.c (ffffffff810a9fa5)
Location: kernel/exit.c:1681
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
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
In kernel/exit.c (ffffffff810aafd5)
Location: kernel/exit.c:1728
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
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
In kernel/exit.c (ffffffff810bcaf5)
Location: kernel/exit.c:1728
Inline: True
Inline callers:
  - kernel/exit.c:__x64_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
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
In kernel/exit.c (ffffffff810d3925)
Location: kernel/exit.c:1732
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_compat_sys_wait4
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
In kernel/exit.c (ffffffff810f2635)
Location: kernel/exit.c:1826
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_compat_sys_wait4
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
In kernel/exit.c (ffffffff810fe5b5)
Location: kernel/exit.c:1831
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_compat_sys_wait4
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
In kernel/exit.c (ffffffff81107c65)
Location: kernel/exit.c:1834
Inline: True
Inline callers:
  - kernel/exit.c:__ia32_compat_sys_wait4
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
In kernel/exit.c (ffff8000100fe2d8)
Location: kernel/exit.c:1652
Inline: True
Inline callers:
  - kernel/exit.c:__arm64_compat_sys_wait4
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
long int __se_compat_sys_wait4(long int pid, long int stat_addr, long int options, long int ru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c000000000145310)
Location: kernel/exit.c:1652
Inline: False
```
**Symbols:**

```
c000000000145310-c00000000014532c: __se_compat_sys_wait4 (STB_GLOBAL)
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
In kernel/exit.c (ffffffff810a0b25)
Location: kernel/exit.c:1652
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
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
In kernel/exit.c (ffffffff8108f545)
Location: kernel/exit.c:1652
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
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
In kernel/exit.c (ffffffff810a0ad5)
Location: kernel/exit.c:1652
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
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
In kernel/exit.c (ffffffff810a8a55)
Location: kernel/exit.c:1652
Inline: True
Inline callers:
  - kernel/exit.c:__x32_compat_sys_wait4
  - kernel/exit.c:__ia32_compat_sys_wait4
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
