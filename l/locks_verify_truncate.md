# Function: <code>locks_verify_truncate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8120996a)
Location: include/linux/fs.h:2087
Inline: True
Inline callers:
  - fs/open.c:vfs_truncate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8122f778)
Location: include/linux/fs.h:2177
Inline: True
Inline callers:
  - fs/open.c:vfs_truncate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81241d01)
Location: include/linux/fs.h:2158
Inline: True
Inline callers:
  - fs/open.c:vfs_truncate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124d327)
Location: include/linux/fs.h:2211
Inline: True
Inline callers:
  - fs/open.c:vfs_truncate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8126f29a)
Location: include/linux/fs.h:2256
Inline: True
Inline callers:
  - fs/open.c:vfs_truncate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81295d72)
Location: include/linux/fs.h:2272
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
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
In fs/open.c (ffffffff812aab62)
Location: include/linux/fs.h:2358
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
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
In fs/open.c (ffffffff812c733f)
Location: include/linux/fs.h:2352
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
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
In fs/open.c (ffffffff812d8d4f)
Location: include/linux/fs.h:2387
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
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
In fs/open.c (ffffffff8130eb8f)
Location: include/linux/fs.h:2420
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
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
In fs/open.c (ffffffff8131ae79)
Location: include/linux/fs.h:2374
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
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
In fs/open.c (0)
Location: include/linux/fs.h:2649
Inline: True
```
</details>
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
In fs/open.c (ffff80001037e0d8)
Location: include/linux/fs.h:2387
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (c0568a58)
Location: include/linux/fs.h:2387
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (c000000000473af0)
Location: include/linux/fs.h:2387
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffe000253e60)
Location: include/linux/fs.h:2387
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
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
In fs/open.c (ffffffff812d132f)
Location: include/linux/fs.h:2387
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
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
In fs/open.c (ffffffff812c1faf)
Location: include/linux/fs.h:2387
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
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
In fs/open.c (ffffffff812cf13f)
Location: include/linux/fs.h:2387
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
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
In fs/open.c (ffffffff812dff4f)
Location: include/linux/fs.h:2387
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:do_sys_ftruncate
  - fs/open.c:vfs_truncate
  - fs/open.c:vfs_truncate
```
</details>
</li>
</ul>

## Differences
