# Function: <code>locks_verify_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811c76c9)
Location: include/linux/fs.h:2080
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (ffffffff8121ab98)
Location: include/linux/fs.h:2080
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811e3d62)
Location: include/linux/fs.h:2170
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (ffffffff812423d5)
Location: include/linux/fs.h:2170
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811f3d42)
Location: include/linux/fs.h:2151
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (ffffffff812552a2)
Location: include/linux/fs.h:2151
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff811fed1f)
Location: include/linux/fs.h:2204
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (ffffffff812612ea)
Location: include/linux/fs.h:2204
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81217362)
Location: include/linux/fs.h:2249
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (ffffffff81283a1d)
Location: include/linux/fs.h:2249
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81238427)
Location: include/linux/fs.h:2265
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (ffffffff812aabae)
Location: include/linux/fs.h:2265
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8124be05)
Location: include/linux/fs.h:2351
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (ffffffff812bf982)
Location: include/linux/fs.h:2351
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8125e293)
Location: include/linux/fs.h:2345
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (ffffffff812dcb09)
Location: include/linux/fs.h:2345
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8126ca87)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (ffffffff812ee658)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff8129c753)
Location: include/linux/fs.h:2413
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (ffffffff81321405)
Location: include/linux/fs.h:2413
Inline: True
Inline callers:
  - fs/namei.c:handle_truncate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812a7a83)
Location: include/linux/fs.h:2367
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (ffffffff8132c9a5)
Location: include/linux/fs.h:2367
Inline: True
Inline callers:
  - fs/namei.c:handle_truncate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (0)
Location: include/linux/fs.h:2644
Inline: True
```
```
In fs/namei.c (0)
Location: include/linux/fs.h:2644
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffff800010303b88)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (ffff8000103982e0)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c05224ac)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (c057e8e0)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (c0000000003d08d8)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (c000000000492200)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffe000210596)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (ffffffe000265efa)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812650d7)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (ffffffff812e6c38)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff812574f7)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (ffffffff812d7878)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81262e77)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (ffffffff812e4a48)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmap.c (ffffffff81272837)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - mm/mmap.c:do_mmap
```
```
In fs/namei.c (ffffffff812f59c8)
Location: include/linux/fs.h:2380
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
</details>
</li>
</ul>

## Differences
