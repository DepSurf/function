# Function: <code>__do_compat_sys_ftruncate</code>

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
In fs/open.c (ffffffff81295ed5)
Location: fs/open.c:223
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_ftruncate
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
In fs/open.c (ffffffff812aacc5)
Location: fs/open.c:212
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_ftruncate
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
In fs/open.c (ffffffff812c74b5)
Location: fs/open.c:213
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_ftruncate
  - fs/open.c:__ia32_compat_sys_ftruncate
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
In fs/open.c (ffffffff812d8ec5)
Location: fs/open.c:213
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_ftruncate
  - fs/open.c:__ia32_compat_sys_ftruncate
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
In fs/open.c (ffffffff8130ece5)
Location: fs/open.c:210
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_ftruncate
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
In fs/open.c (ffffffff8131b025)
Location: fs/open.c:210
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_ftruncate
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
In fs/open.c (ffffffff81321135)
Location: fs/open.c:211
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_ftruncate
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
In fs/open.c (ffffffff8136e615)
Location: fs/open.c:208
Inline: True
Inline callers:
  - fs/open.c:__x64_compat_sys_ftruncate
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
In fs/open.c (0)
Location: fs/open.c:208
Inline: True
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
In fs/open.c (0)
Location: fs/open.c:208
Inline: True
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
In fs/open.c (0)
Location: fs/open.c:209
Inline: True
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
In fs/open.c (0)
Location: fs/open.c:209
Inline: True
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
In fs/open.c (ffff80001037e240)
Location: fs/open.c:213
Inline: True
Inline callers:
  - fs/open.c:__arm64_compat_sys_ftruncate
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
In fs/open.c (c000000000473c50)
Location: fs/open.c:213
Inline: True
Inline callers:
  - fs/open.c:__se_compat_sys_ftruncate
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
In fs/open.c (ffffffff812d14a5)
Location: fs/open.c:213
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_ftruncate
  - fs/open.c:__ia32_compat_sys_ftruncate
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
In fs/open.c (ffffffff812c2125)
Location: fs/open.c:213
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_ftruncate
  - fs/open.c:__ia32_compat_sys_ftruncate
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
In fs/open.c (ffffffff812cf2b5)
Location: fs/open.c:213
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_ftruncate
  - fs/open.c:__ia32_compat_sys_ftruncate
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
In fs/open.c (ffffffff812e00c5)
Location: fs/open.c:213
Inline: True
Inline callers:
  - fs/open.c:__x32_compat_sys_ftruncate
  - fs/open.c:__ia32_compat_sys_ftruncate
```
</details>
</li>
</ul>

## Differences
