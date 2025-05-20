# Function: <code>__do_compat_sys_sendfile</code>

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
In fs/read_write.c (ffffffff81299f7f)
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
In fs/read_write.c (ffffffff812aeeaf)
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
In fs/read_write.c (ffffffff812cbb5f)
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
In fs/read_write.c (ffffffff812dd4df)
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
In fs/read_write.c (ffffffff8131455f)
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
In fs/read_write.c (ffffffff8131fc4f)
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
In fs/read_write.c (ffffffff8132564d)
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
In fs/read_write.c (ffffffff813732bd)
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
In fs/read_write.c (ffffffff813f182d)
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
In fs/read_write.c (ffffffff81479b6d)
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
In fs/read_write.c (ffffffff814ae63d)
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
In fs/read_write.c (ffffffff814dfd5d)
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
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c0000000004796d0)
Location: fs/read_write.c:1555
Inline: True
Inline callers:
  - fs/read_write.c:__se_compat_sys_sendfile
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
In fs/read_write.c (ffffffff812d5abf)
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
In fs/read_write.c (ffffffff812c673f)
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
In fs/read_write.c (ffffffff812d38cf)
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
In fs/read_write.c (ffffffff812e472f)
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
