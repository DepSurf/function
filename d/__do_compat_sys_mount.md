# Function: <code>__do_compat_sys_mount</code>

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
In fs/compat.c (ffffffff81301896)
Location: fs/compat.c:92
Inline: True
Inline callers:
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
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
In fs/compat.c (ffffffff81317386)
Location: fs/compat.c:92
Inline: True
Inline callers:
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
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
In fs/compat.c (ffffffff8133ec32)
Location: fs/compat.c:89
Inline: True
Inline callers:
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
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
In fs/compat.c (ffffffff81357222)
Location: fs/compat.c:89
Inline: True
Inline callers:
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
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
In fs/compat.c (ffffffff8139e4d2)
Location: fs/compat.c:89
Inline: True
Inline callers:
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
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
In fs/compat.c (ffff800010419f34)
Location: fs/compat.c:89
Inline: True
Inline callers:
  - fs/compat.c:__arm64_compat_sys_mount
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
In fs/compat.c (c0000000005298e4)
Location: fs/compat.c:89
Inline: True
Inline callers:
  - fs/compat.c:__se_compat_sys_mount
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
In fs/compat.c (ffffffff8134f802)
Location: fs/compat.c:89
Inline: True
Inline callers:
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
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
In fs/compat.c (ffffffff813404e2)
Location: fs/compat.c:89
Inline: True
Inline callers:
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
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
In fs/compat.c (ffffffff8134d2d2)
Location: fs/compat.c:89
Inline: True
Inline callers:
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
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
In fs/compat.c (ffffffff81360852)
Location: fs/compat.c:89
Inline: True
Inline callers:
  - fs/compat.c:__x32_compat_sys_mount
  - fs/compat.c:__ia32_compat_sys_mount
```
</details>
</li>
</ul>

## Differences
