# Function: <code>__se_compat_sys_sendfile</code>

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
In fs/read_write.c (ffffffff81299f77)
Location: fs/read_write.c:1531
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
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
In fs/read_write.c (ffffffff812aeea7)
Location: fs/read_write.c:1527
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
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
In fs/read_write.c (ffffffff812cbb57)
Location: fs/read_write.c:1555
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
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
In fs/read_write.c (ffffffff812dd4d7)
Location: fs/read_write.c:1555
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
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
In fs/read_write.c (ffffffff81314557)
Location: fs/read_write.c:1639
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
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
In fs/read_write.c (ffffffff8131fc47)
Location: fs/read_write.c:1324
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
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
In fs/read_write.c (ffffffff81325647)
Location: fs/read_write.c:1329
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
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
In fs/read_write.c (ffffffff813732b7)
Location: fs/read_write.c:1320
Inline: True
Inline callers:
  - fs/read_write.c:__x64_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
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
In fs/read_write.c (ffffffff813f1827)
Location: fs/read_write.c:1334
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_compat_sys_sendfile
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
In fs/read_write.c (ffffffff81479b67)
Location: fs/read_write.c:1327
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_compat_sys_sendfile
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
In fs/read_write.c (ffffffff814ae637)
Location: fs/read_write.c:1326
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_compat_sys_sendfile
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
In fs/read_write.c (ffffffff814dfd57)
Location: fs/read_write.c:1366
Inline: True
Inline callers:
  - fs/read_write.c:__ia32_compat_sys_sendfile
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
In fs/read_write.c (ffff8000103830c8)
Location: fs/read_write.c:1555
Inline: True
Inline callers:
  - fs/read_write.c:__arm64_compat_sys_sendfile
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
long int __se_compat_sys_sendfile(long int out_fd, long int in_fd, long int offset, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c0000000004796a0)
Location: fs/read_write.c:1555
Inline: False
```
**Symbols:**

```
c0000000004796a0-c000000000479874: __se_compat_sys_sendfile (STB_GLOBAL)
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
In fs/read_write.c (ffffffff812d5ab7)
Location: fs/read_write.c:1555
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
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
In fs/read_write.c (ffffffff812c6737)
Location: fs/read_write.c:1555
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
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
In fs/read_write.c (ffffffff812d38c7)
Location: fs/read_write.c:1555
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
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
In fs/read_write.c (ffffffff812e4727)
Location: fs/read_write.c:1555
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_sendfile
  - fs/read_write.c:__ia32_compat_sys_sendfile
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
