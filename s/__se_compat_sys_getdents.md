# Function: <code>__se_compat_sys_getdents</code>

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
In fs/readdir.c (ffffffff812b0fb0)
Location: fs/readdir.c:466
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
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
In fs/readdir.c (ffffffff812c61b0)
Location: fs/readdir.c:466
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
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
In fs/readdir.c (ffffffff812e2c60)
Location: fs/readdir.c:466
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
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
In fs/readdir.c (ffffffff812f49d0)
Location: fs/readdir.c:525
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
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
In fs/readdir.c (ffffffff8132d0b7)
Location: fs/readdir.c:523
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
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
In fs/readdir.c (ffffffff81338897)
Location: fs/readdir.c:516
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
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
In fs/readdir.c (ffffffff8133eefc)
Location: fs/readdir.c:522
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
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
In fs/readdir.c (ffffffff8138c88c)
Location: fs/readdir.c:522
Inline: True
Inline callers:
  - fs/readdir.c:__x64_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
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
In fs/readdir.c (ffffffff8140d162)
Location: fs/readdir.c:522
Inline: True
Inline callers:
  - fs/readdir.c:__ia32_compat_sys_getdents
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
In fs/readdir.c (ffffffff81497c12)
Location: fs/readdir.c:522
Inline: True
Inline callers:
  - fs/readdir.c:__ia32_compat_sys_getdents
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
In fs/readdir.c (ffffffff814ccb82)
Location: fs/readdir.c:558
Inline: True
Inline callers:
  - fs/readdir.c:__ia32_compat_sys_getdents
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
In fs/readdir.c (ffffffff814ff7a2)
Location: fs/readdir.c:562
Inline: True
Inline callers:
  - fs/readdir.c:__ia32_compat_sys_getdents
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
In fs/readdir.c (ffff80001039fb44)
Location: fs/readdir.c:525
Inline: True
Inline callers:
  - fs/readdir.c:__arm64_compat_sys_getdents
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
long int __se_compat_sys_getdents(long int fd, long int dirent, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/readdir.c (c000000000499da0)
Location: fs/readdir.c:525
Inline: False
```
**Symbols:**

```
c000000000499da0-c000000000499fa8: __se_compat_sys_getdents (STB_GLOBAL)
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
In fs/readdir.c (ffffffff812ecfb0)
Location: fs/readdir.c:525
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
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
In fs/readdir.c (ffffffff812ddbe0)
Location: fs/readdir.c:525
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
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
In fs/readdir.c (ffffffff812eadc0)
Location: fs/readdir.c:525
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
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
In fs/readdir.c (ffffffff812fbdb0)
Location: fs/readdir.c:525
Inline: True
Inline callers:
  - fs/readdir.c:__x32_compat_sys_getdents
  - fs/readdir.c:__ia32_compat_sys_getdents
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
