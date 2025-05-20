# Function: <code>__se_compat_sys_readv</code>

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
In fs/read_write.c (ffffffff81298c25)
Location: fs/read_write.c:1221
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_readv
  - fs/read_write.c:__ia32_compat_sys_readv
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
In fs/read_write.c (ffffffff812adaa5)
Location: fs/read_write.c:1218
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_readv
  - fs/read_write.c:__ia32_compat_sys_readv
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
In fs/read_write.c (ffffffff812ca735)
Location: fs/read_write.c:1240
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_readv
  - fs/read_write.c:__ia32_compat_sys_readv
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
In fs/read_write.c (ffffffff812dc155)
Location: fs/read_write.c:1240
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_readv
  - fs/read_write.c:__ia32_compat_sys_readv
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
In fs/read_write.c (ffffffff81312d45)
Location: fs/read_write.c:1324
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_readv
  - fs/read_write.c:__ia32_compat_sys_readv
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
In fs/read_write.c (ffff800010381c18)
Location: fs/read_write.c:1240
Inline: True
Inline callers:
  - fs/read_write.c:__arm64_compat_sys_readv
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
long int __se_compat_sys_readv(long int fd, long int vec, long int vlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000478160)
Location: fs/read_write.c:1240
Inline: False
```
**Symbols:**

```
c000000000478160-c000000000478180: __se_compat_sys_readv (STB_GLOBAL)
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
In fs/read_write.c (ffffffff812d4735)
Location: fs/read_write.c:1240
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_readv
  - fs/read_write.c:__ia32_compat_sys_readv
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
In fs/read_write.c (ffffffff812c53b5)
Location: fs/read_write.c:1240
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_readv
  - fs/read_write.c:__ia32_compat_sys_readv
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
In fs/read_write.c (ffffffff812d2545)
Location: fs/read_write.c:1240
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_readv
  - fs/read_write.c:__ia32_compat_sys_readv
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
In fs/read_write.c (ffffffff812e33a5)
Location: fs/read_write.c:1240
Inline: True
Inline callers:
  - fs/read_write.c:__x32_compat_sys_readv
  - fs/read_write.c:__ia32_compat_sys_readv
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
