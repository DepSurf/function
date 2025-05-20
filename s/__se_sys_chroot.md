# Function: <code>__se_sys_chroot</code>

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
In fs/open.c (ffffffff812964c5)
Location: fs/open.c:534
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
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
In fs/open.c (ffffffff812ab2b5)
Location: fs/open.c:523
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
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
In fs/open.c (ffffffff812c7ab5)
Location: fs/open.c:543
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
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
In fs/open.c (ffffffff812d94c5)
Location: fs/open.c:543
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
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
In fs/open.c (ffffffff8130f285)
Location: fs/open.c:572
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
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
In fs/open.c (ffffffff81319b8b)
Location: fs/open.c:534
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
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
In fs/open.c (ffffffff8131fcab)
Location: fs/open.c:535
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
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
In fs/open.c (ffffffff8136d24b)
Location: fs/open.c:532
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
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
In fs/open.c (ffffffff813eb602)
Location: fs/open.c:556
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
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
In fs/open.c (ffffffff81473972)
Location: fs/open.c:556
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
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
In fs/open.c (ffffffff814a8172)
Location: fs/open.c:593
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
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
In fs/open.c (ffffffff814d9202)
Location: fs/open.c:598
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
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
In fs/open.c (ffff80001037e830)
Location: fs/open.c:543
Inline: True
Inline callers:
  - fs/open.c:__arm64_sys_chroot
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_chroot(long int filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c05691ec)
Location: fs/open.c:543
Inline: False
```
**Symbols:**

```
c05691ec-c0569208: __se_sys_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_chroot(long int filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (c0000000004743f0)
Location: fs/open.c:543
Inline: False
```
**Symbols:**

```
c0000000004743f0-c000000000474420: __se_sys_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_chroot(long int filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe0002544da)
Location: fs/open.c:543
Inline: False
```
**Symbols:**

```
ffffffe0002544da-ffffffe000254504: __se_sys_chroot (STB_GLOBAL)
```
</details>
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
In fs/open.c (ffffffff812d1aa5)
Location: fs/open.c:543
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
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
In fs/open.c (ffffffff812c2725)
Location: fs/open.c:543
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
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
In fs/open.c (ffffffff812cf8b5)
Location: fs/open.c:543
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
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
In fs/open.c (ffffffff812e06c5)
Location: fs/open.c:543
Inline: True
Inline callers:
  - fs/open.c:__ia32_sys_chroot
  - fs/open.c:__x64_sys_chroot
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
