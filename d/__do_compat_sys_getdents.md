# Function: <code>__do_compat_sys_getdents</code>

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
In fs/readdir.c (ffffffff812b0fb4)
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
In fs/readdir.c (ffffffff812c61b4)
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
In fs/readdir.c (ffffffff812e2c64)
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
In fs/readdir.c (ffffffff812f49d4)
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
In fs/readdir.c (ffffffff8132d0bf)
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
In fs/readdir.c (ffffffff8133889f)
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
In fs/readdir.c (ffffffff8133ef03)
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
In fs/readdir.c (ffffffff8138c893)
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
In fs/readdir.c (ffff80001039fb60)
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
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/readdir.c (c000000000499dd4)
Location: fs/readdir.c:525
Inline: True
Inline callers:
  - fs/readdir.c:__se_compat_sys_getdents
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
In fs/readdir.c (ffffffff812ecfb4)
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
In fs/readdir.c (ffffffff812ddbe4)
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
In fs/readdir.c (ffffffff812eadc4)
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
In fs/readdir.c (ffffffff812fbdb4)
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
