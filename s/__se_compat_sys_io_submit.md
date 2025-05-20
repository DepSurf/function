# Function: <code>__se_compat_sys_io_submit</code>

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
In fs/aio.c (ffffffff812f4e2d)
Location: fs/aio.c:1743
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
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
In fs/aio.c (ffffffff8130a00d)
Location: fs/aio.c:1958
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
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
In fs/aio.c (ffffffff8132be86)
Location: fs/aio.c:1933
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
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
In fs/aio.c (ffffffff8133ecd6)
Location: fs/aio.c:1949
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
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
In fs/aio.c (ffffffff813789af)
Location: fs/aio.c:1956
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
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
In fs/aio.c (ffffffff813866e1)
Location: fs/aio.c:1954
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
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
In fs/aio.c (ffffffff8138d846)
Location: fs/aio.c:1951
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
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
In fs/aio.c (ffffffff813daf96)
Location: fs/aio.c:2069
Inline: True
Inline callers:
  - fs/aio.c:__x64_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
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
In fs/aio.c (ffffffff81465701)
Location: fs/aio.c:2093
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_submit
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
In fs/aio.c (ffffffff814f5760)
Location: fs/aio.c:2094
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_submit
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
In fs/aio.c (ffffffff8152c4f1)
Location: fs/aio.c:2086
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_submit
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
In fs/aio.c (ffffffff815613d1)
Location: fs/aio.c:2129
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_submit
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
In fs/aio.c (ffff8000103fe52c)
Location: fs/aio.c:1949
Inline: True
Inline callers:
  - fs/aio.c:__arm64_compat_sys_io_submit
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
long int __se_compat_sys_io_submit(long int ctx_id, long int nr, long int iocbpp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c000000000507ca0)
Location: fs/aio.c:1949
Inline: False
```
**Symbols:**

```
c000000000507ca0-c000000000507fa8: __se_compat_sys_io_submit (STB_GLOBAL)
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
In fs/aio.c (ffffffff813372b6)
Location: fs/aio.c:1949
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
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
In fs/aio.c (ffffffff81327c26)
Location: fs/aio.c:1949
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
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
In fs/aio.c (ffffffff81334d86)
Location: fs/aio.c:1949
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
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
In fs/aio.c (ffffffff813472c6)
Location: fs/aio.c:1949
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_submit
  - fs/aio.c:__ia32_compat_sys_io_submit
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
