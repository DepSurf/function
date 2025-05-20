# Function: <code>__se_sys_splice</code>

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
In fs/splice.c (ffffffff812d0e39)
Location: fs/splice.c:1397
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
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
In fs/splice.c (ffffffff812e6069)
Location: fs/splice.c:1401
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
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
In fs/splice.c (ffffffff81304c69)
Location: fs/splice.c:1407
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
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
In fs/splice.c (ffffffff81317cf9)
Location: fs/splice.c:1415
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
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
In fs/splice.c (ffffffff8135275a)
Location: fs/splice.c:1403
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
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
In fs/splice.c (ffffffff8135f03e)
Location: fs/splice.c:1327
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
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
In fs/splice.c (ffffffff8136593e)
Location: fs/splice.c:1332
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
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
In fs/splice.c (ffffffff813b422e)
Location: fs/splice.c:1334
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
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
In fs/splice.c (ffffffff8143959e)
Location: fs/splice.c:1330
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
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
In fs/splice.c (ffffffff814c78ae)
Location: fs/splice.c:1330
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
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
In fs/splice.c (ffffffff814fd8fe)
Location: fs/splice.c:1571
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
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
In fs/splice.c (ffffffff815324fe)
Location: fs/splice.c:1634
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
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
In fs/splice.c (0)
Location: fs/splice.c:1415
Inline: True
Inline callers:
  - fs/splice.c:__arm64_sys_splice
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_splice(long int fd_in, long int off_in, long int fd_out, long int off_out, long int len, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c05aaea0)
Location: fs/splice.c:1415
Inline: False
```
**Symbols:**

```
c05aaea0-c05aaf94: __se_sys_splice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_splice(long int fd_in, long int off_in, long int fd_out, long int off_out, long int len, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c0000000004d0de0)
Location: fs/splice.c:1415
Inline: False
```
**Symbols:**

```
c0000000004d0de0-c0000000004d0f8c: __se_sys_splice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_splice(long int fd_in, long int off_in, long int fd_out, long int off_out, long int len, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffe00028bed2)
Location: fs/splice.c:1415
Inline: False
```
**Symbols:**

```
ffffffe00028bed2-ffffffe00028bfb6: __se_sys_splice (STB_GLOBAL)
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
In fs/splice.c (ffffffff813102d9)
Location: fs/splice.c:1415
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
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
In fs/splice.c (ffffffff81300ee9)
Location: fs/splice.c:1415
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
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
In fs/splice.c (ffffffff8130e0c9)
Location: fs/splice.c:1415
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
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
In fs/splice.c (ffffffff8131f8c9)
Location: fs/splice.c:1415
Inline: True
Inline callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
