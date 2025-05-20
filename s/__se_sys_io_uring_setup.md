# Function: <code>__se_sys_io_uring_setup</code>

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
In fs/io_uring.c (ffffffff81331695)
Location: fs/io_uring.c:3433
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
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
In fs/io_uring.c (ffffffff813452d5)
Location: fs/io_uring.c:4003
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
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
In fs/io_uring.c (ffffffff81385c25)
Location: fs/io_uring.c:8296
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
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
In fs/io_uring.c (ffffffff81396ef5)
Location: fs/io_uring.c:9855
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
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
In fs/io_uring.c (ffffffff8139a165)
Location: fs/io_uring.c:9777
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
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
In fs/io_uring.c (ffffffff813e9275)
Location: fs/io_uring.c:10450
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
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
In io_uring/io_uring.c (ffffffff816d68b5)
Location: io_uring/io_uring.c:12141
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_setup
  - io_uring/io_uring.c:__x64_sys_io_uring_setup
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
In io_uring/io_uring.c (ffffffff8178d0a5)
Location: io_uring/io_uring.c:3737
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_setup
  - io_uring/io_uring.c:__x64_sys_io_uring_setup
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
In io_uring/io_uring.c (ffffffff817ce1e5)
Location: io_uring/io_uring.c:4049
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_setup
  - io_uring/io_uring.c:__x64_sys_io_uring_setup
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
In io_uring/io_uring.c (ffffffff81816d45)
Location: io_uring/io_uring.c:4077
Inline: True
Inline callers:
  - io_uring/io_uring.c:__ia32_sys_io_uring_setup
  - io_uring/io_uring.c:__x64_sys_io_uring_setup
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
In fs/io_uring.c (ffff8000104040f0)
Location: fs/io_uring.c:4003
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_io_uring_setup(long int entries, long int params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d7638)
Location: fs/io_uring.c:4003
Inline: False
```
**Symbols:**

```
c05d7638-c05d7654: __se_sys_io_uring_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_io_uring_setup(long int entries, long int params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c000000000510080)
Location: fs/io_uring.c:4003
Inline: False
```
**Symbols:**

```
c000000000510080-c000000000510098: __se_sys_io_uring_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_io_uring_setup(long int entries, long int params);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002b1066)
Location: fs/io_uring.c:4003
Inline: False
```
**Symbols:**

```
ffffffe0002b1066-ffffffe0002b109a: __se_sys_io_uring_setup (STB_GLOBAL)
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
In fs/io_uring.c (ffffffff8133d8b5)
Location: fs/io_uring.c:4003
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
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
In fs/io_uring.c (ffffffff8132e575)
Location: fs/io_uring.c:4003
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
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
In fs/io_uring.c (ffffffff8133b385)
Location: fs/io_uring.c:4003
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
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
In fs/io_uring.c (ffffffff8134e535)
Location: fs/io_uring.c:4003
Inline: True
Inline callers:
  - fs/io_uring.c:__ia32_sys_io_uring_setup
  - fs/io_uring.c:__x64_sys_io_uring_setup
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
