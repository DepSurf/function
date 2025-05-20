# Function: <code>__do_compat_sys_times</code>

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
In kernel/sys.c (ffffffff810a4e73)
Location: kernel/sys.c:975
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
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
In kernel/sys.c (ffffffff810add23)
Location: kernel/sys.c:975
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
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
In kernel/sys.c (ffffffff810b38a3)
Location: kernel/sys.c:975
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
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
In kernel/sys.c (ffffffff810b9e93)
Location: kernel/sys.c:975
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
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
In kernel/sys.c (ffffffff810c1b93)
Location: kernel/sys.c:989
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
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
In kernel/sys.c (ffffffff810bce83)
Location: kernel/sys.c:990
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
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
In kernel/sys.c (ffffffff810beeb3)
Location: kernel/sys.c:1007
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
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
In kernel/sys.c (ffffffff810d1853)
Location: kernel/sys.c:1016
Inline: True
Inline callers:
  - kernel/sys.c:__x64_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
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
In kernel/sys.c (ffffffff810e7c63)
Location: kernel/sys.c:1023
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_times
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
In kernel/sys.c (ffffffff81108963)
Location: kernel/sys.c:1024
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_times
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
In kernel/sys.c (ffffffff81114c73)
Location: kernel/sys.c:1042
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_times
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
In kernel/sys.c (ffffffff8111e663)
Location: kernel/sys.c:1042
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_compat_sys_times
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
In kernel/sys.c (ffff800010116ffc)
Location: kernel/sys.c:975
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_compat_sys_times
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
In kernel/sys.c (c00000000015c5b8)
Location: kernel/sys.c:975
Inline: True
Inline callers:
  - kernel/sys.c:__se_compat_sys_times
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
In kernel/sys.c (ffffffff810b4203)
Location: kernel/sys.c:975
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
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
In kernel/sys.c (ffffffff810a2b33)
Location: kernel/sys.c:975
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
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
In kernel/sys.c (ffffffff810b3763)
Location: kernel/sys.c:975
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
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
In kernel/sys.c (ffffffff810bc193)
Location: kernel/sys.c:975
Inline: True
Inline callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
```
</details>
</li>
</ul>

## Differences
