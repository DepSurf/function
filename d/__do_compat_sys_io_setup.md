# Function: <code>__do_compat_sys_io_setup</code>

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
In fs/aio.c (ffffffff812f5b16)
Location: fs/aio.c:1311
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
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
In fs/aio.c (ffffffff8130ac06)
Location: fs/aio.c:1343
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
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
In fs/aio.c (ffffffff8132ce68)
Location: fs/aio.c:1343
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
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
In fs/aio.c (ffffffff8133fcb8)
Location: fs/aio.c:1343
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
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
In fs/aio.c (ffffffff813795b8)
Location: fs/aio.c:1343
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
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
In fs/aio.c (ffffffff81387408)
Location: fs/aio.c:1345
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
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
In fs/aio.c (ffffffff8138e3e8)
Location: fs/aio.c:1342
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
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
In fs/aio.c (ffffffff813dbd48)
Location: fs/aio.c:1343
Inline: True
Inline callers:
  - fs/aio.c:__x64_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
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
In fs/aio.c (ffffffff81463d76)
Location: fs/aio.c:1369
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_setup
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
In fs/aio.c (ffffffff814f4066)
Location: fs/aio.c:1370
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_setup
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
In fs/aio.c (ffffffff8152ae36)
Location: fs/aio.c:1362
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_setup
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
In fs/aio.c (ffffffff8155fd06)
Location: fs/aio.c:1419
Inline: True
Inline callers:
  - fs/aio.c:__ia32_compat_sys_io_setup
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
In fs/aio.c (ffff8000103ff3f0)
Location: fs/aio.c:1343
Inline: True
Inline callers:
  - fs/aio.c:__arm64_compat_sys_io_setup
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
In fs/aio.c (c000000000508e94)
Location: fs/aio.c:1343
Inline: True
Inline callers:
  - fs/aio.c:__se_compat_sys_io_setup
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
In fs/aio.c (ffffffff81338298)
Location: fs/aio.c:1343
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
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
In fs/aio.c (ffffffff81328fc8)
Location: fs/aio.c:1343
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
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
In fs/aio.c (ffffffff81335d68)
Location: fs/aio.c:1343
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
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
In fs/aio.c (ffffffff81348e18)
Location: fs/aio.c:1343
Inline: True
Inline callers:
  - fs/aio.c:__x32_compat_sys_io_setup
  - fs/aio.c:__ia32_compat_sys_io_setup
```
</details>
</li>
</ul>

## Differences
