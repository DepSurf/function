# Function: <code>__do_compat_sys_pselect6_time64</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812c8581)
Location: fs/select.c:1360
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
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
In fs/select.c (ffffffff812e516d)
Location: fs/select.c:1328
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
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
In fs/select.c (ffffffff812f6b8d)
Location: fs/select.c:1328
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
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
In fs/select.c (ffffffff8132eb3d)
Location: fs/select.c:1358
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
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
In fs/select.c (ffffffff8133a41d)
Location: fs/select.c:1364
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
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
In fs/select.c (ffffffff8134092c)
Location: fs/select.c:1364
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
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
In fs/select.c (ffffffff8138e2fc)
Location: fs/select.c:1367
Inline: True
Inline callers:
  - fs/select.c:__x64_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
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
In fs/select.c (ffffffff8140f4c9)
Location: fs/select.c:1368
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time64
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
In fs/select.c (ffffffff8149a0b9)
Location: fs/select.c:1368
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time64
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
In fs/select.c (ffffffff814cf188)
Location: fs/select.c:1368
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time64
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
In fs/select.c (ffffffff81501ac8)
Location: fs/select.c:1368
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time64
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
In fs/select.c (ffff8000103a3d7c)
Location: fs/select.c:1328
Inline: True
Inline callers:
  - fs/select.c:__arm64_compat_sys_pselect6_time64
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
In fs/select.c (c00000000049dbb8)
Location: fs/select.c:1328
Inline: True
Inline callers:
  - fs/select.c:__se_compat_sys_pselect6_time64
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
In fs/select.c (ffffffff812ef16d)
Location: fs/select.c:1328
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
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
In fs/select.c (ffffffff812dfd9d)
Location: fs/select.c:1328
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
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
In fs/select.c (ffffffff812ecf7d)
Location: fs/select.c:1328
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
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
In fs/select.c (ffffffff812fdf7d)
Location: fs/select.c:1328
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time64
  - fs/select.c:__ia32_compat_sys_pselect6_time64
```
</details>
</li>
</ul>

## Differences
