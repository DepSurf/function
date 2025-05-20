# Function: <code>__se_compat_sys_vmsplice</code>

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
In fs/splice.c (ffffffff812d1695)
Location: fs/splice.c:1371
Inline: True
Inline callers:
  - fs/splice.c:__x32_compat_sys_vmsplice
  - fs/splice.c:__ia32_compat_sys_vmsplice
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
In fs/splice.c (ffffffff812e6af5)
Location: fs/splice.c:1375
Inline: True
Inline callers:
  - fs/splice.c:__x32_compat_sys_vmsplice
  - fs/splice.c:__ia32_compat_sys_vmsplice
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
In fs/splice.c (ffffffff81305775)
Location: fs/splice.c:1381
Inline: True
Inline callers:
  - fs/splice.c:__x32_compat_sys_vmsplice
  - fs/splice.c:__ia32_compat_sys_vmsplice
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
In fs/splice.c (ffffffff81318805)
Location: fs/splice.c:1389
Inline: True
Inline callers:
  - fs/splice.c:__x32_compat_sys_vmsplice
  - fs/splice.c:__ia32_compat_sys_vmsplice
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
In fs/splice.c (ffffffff81351745)
Location: fs/splice.c:1377
Inline: True
Inline callers:
  - fs/splice.c:__x32_compat_sys_vmsplice
  - fs/splice.c:__ia32_compat_sys_vmsplice
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
In fs/splice.c (ffff8000103ce8d8)
Location: fs/splice.c:1389
Inline: True
Inline callers:
  - fs/splice.c:__arm64_compat_sys_vmsplice
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
long int __se_compat_sys_vmsplice(long int fd, long int iov32, long int nr_segs, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c0000000004d1da0)
Location: fs/splice.c:1389
Inline: False
```
**Symbols:**

```
c0000000004d1da0-c0000000004d1dc0: __se_compat_sys_vmsplice (STB_GLOBAL)
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
In fs/splice.c (ffffffff81310de5)
Location: fs/splice.c:1389
Inline: True
Inline callers:
  - fs/splice.c:__x32_compat_sys_vmsplice
  - fs/splice.c:__ia32_compat_sys_vmsplice
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
In fs/splice.c (ffffffff813019f5)
Location: fs/splice.c:1389
Inline: True
Inline callers:
  - fs/splice.c:__x32_compat_sys_vmsplice
  - fs/splice.c:__ia32_compat_sys_vmsplice
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
In fs/splice.c (ffffffff8130ebd5)
Location: fs/splice.c:1389
Inline: True
Inline callers:
  - fs/splice.c:__x32_compat_sys_vmsplice
  - fs/splice.c:__ia32_compat_sys_vmsplice
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
In fs/splice.c (ffffffff813203d5)
Location: fs/splice.c:1389
Inline: True
Inline callers:
  - fs/splice.c:__x32_compat_sys_vmsplice
  - fs/splice.c:__ia32_compat_sys_vmsplice
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
