# Function: <code>__do_compat_sys_pselect6_time32</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812e50dd)
Location: fs/select.c:1350
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
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
In fs/select.c (ffffffff812f6afd)
Location: fs/select.c:1350
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
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
In fs/select.c (ffffffff8132eaad)
Location: fs/select.c:1373
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
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
In fs/select.c (ffffffff8133a37d)
Location: fs/select.c:1379
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
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
In fs/select.c (ffffffff813408ac)
Location: fs/select.c:1379
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
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
In fs/select.c (ffffffff8138e27c)
Location: fs/select.c:1382
Inline: True
Inline callers:
  - fs/select.c:__x64_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
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
In fs/select.c (ffffffff8140f569)
Location: fs/select.c:1383
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
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
In fs/select.c (ffffffff8149a169)
Location: fs/select.c:1383
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
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
In fs/select.c (ffffffff814cf238)
Location: fs/select.c:1383
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
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
In fs/select.c (ffffffff81501b78)
Location: fs/select.c:1383
Inline: True
Inline callers:
  - fs/select.c:__ia32_compat_sys_pselect6_time32
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
In fs/select.c (ffff8000103a4074)
Location: fs/select.c:1350
Inline: True
Inline callers:
  - fs/select.c:__arm64_compat_sys_pselect6_time32
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
In fs/select.c (c00000000049dce8)
Location: fs/select.c:1350
Inline: True
Inline callers:
  - fs/select.c:__se_compat_sys_pselect6_time32
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
In fs/select.c (ffffffff812ef0dd)
Location: fs/select.c:1350
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
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
In fs/select.c (ffffffff812dfd0d)
Location: fs/select.c:1350
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
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
In fs/select.c (ffffffff812eceed)
Location: fs/select.c:1350
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
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
In fs/select.c (ffffffff812fdeed)
Location: fs/select.c:1350
Inline: True
Inline callers:
  - fs/select.c:__x32_compat_sys_pselect6_time32
  - fs/select.c:__ia32_compat_sys_pselect6_time32
```
</details>
</li>
</ul>

## Differences
