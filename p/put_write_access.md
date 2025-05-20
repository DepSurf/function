# Function: <code>put_write_access</code>

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
In fs/open.c (ffffffff81209948)
Location: include/linux/fs.h:2516
Inline: True
Inline callers:
  - fs/open.c:vfs_truncate
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff8120e560)
Location: include/linux/fs.h:2516
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff8121abdd)
Location: include/linux/fs.h:2516
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
In fs/open.c (ffffffff8122ff21)
Location: include/linux/fs.h:2631
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81234f83)
Location: include/linux/fs.h:2631
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff8124241a)
Location: include/linux/fs.h:2631
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
In fs/open.c (ffffffff812424c6)
Location: include/linux/fs.h:2600
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81247b30)
Location: include/linux/fs.h:2600
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812552f3)
Location: include/linux/fs.h:2600
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
In fs/open.c (ffffffff8124d7be)
Location: include/linux/fs.h:2725
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81253360)
Location: include/linux/fs.h:2725
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff81261320)
Location: include/linux/fs.h:2725
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
In fs/open.c (ffffffff8126f81e)
Location: include/linux/fs.h:2786
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81275463)
Location: include/linux/fs.h:2786
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff81283a57)
Location: include/linux/fs.h:2786
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
In fs/open.c (ffffffff812951df)
Location: include/linux/fs.h:2808
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff8129bd63)
Location: include/linux/fs.h:2808
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812aabe1)
Location: include/linux/fs.h:2808
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
In fs/open.c (ffffffff812a9fe7)
Location: include/linux/fs.h:2879
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812b0a25)
Location: include/linux/fs.h:2879
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812bf9c7)
Location: include/linux/fs.h:2879
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
In fs/open.c (ffffffff812c67b7)
Location: include/linux/fs.h:2885
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812cd3aa)
Location: include/linux/fs.h:2885
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812dcb39)
Location: include/linux/fs.h:2885
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
In fs/open.c (ffffffff812d81a7)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812dedca)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812ee688)
Location: include/linux/fs.h:2947
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
In fs/open.c (ffffffff8130e249)
Location: include/linux/fs.h:2989
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81315eda)
Location: include/linux/fs.h:2989
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff81321422)
Location: include/linux/fs.h:2989
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
In kernel/fork.c (ffffffff810a0cdf)
Location: include/linux/fs.h:2824
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff812a3895)
Location: include/linux/fs.h:2824
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_file
```
```
In fs/open.c (ffffffff8131a334)
Location: include/linux/fs.h:2824
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81321464)
Location: include/linux/fs.h:2824
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff8132c9c2)
Location: include/linux/fs.h:2824
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
In kernel/fork.c (ffffffff810a1a5b)
Location: include/linux/fs.h:3077
Inline: True
Inline callers:
  - kernel/fork.c:dup_mmap
```
```
In mm/mmap.c (ffffffff812a90c5)
Location: include/linux/fs.h:3077
Inline: True
Inline callers:
  - mm/mmap.c:__vma_link_file
```
```
In fs/open.c (ffffffff81320414)
Location: include/linux/fs.h:3077
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81327204)
Location: include/linux/fs.h:3077
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff813367d5)
Location: include/linux/fs.h:3077
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136d9d3)
Location: include/linux/fs.h:3065
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff81374aab)
Location: include/linux/fs.h:3065
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff813841b5)
Location: include/linux/fs.h:3065
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813eba27)
Location: include/linux/fs.h:2831
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff813f38a9)
Location: include/linux/fs.h:2831
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff81405301)
Location: include/linux/fs.h:2831
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81473f54)
Location: include/linux/fs.h:2985
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff8147c65f)
Location: include/linux/fs.h:2985
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff8148f751)
Location: include/linux/fs.h:2985
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a8794)
Location: include/linux/fs.h:2599
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff814b121d)
Location: include/linux/fs.h:2599
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff814c1f3d)
Location: include/linux/fs.h:2599
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814d9871)
Location: include/linux/fs.h:2883
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff814e2a54)
Location: include/linux/fs.h:2883
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff814f43fd)
Location: include/linux/fs.h:2883
Inline: True
Inline callers:
  - fs/namei.c:do_open
```
</details>
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
In fs/open.c (ffff80001037dcd4)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffff800010385598)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffff800010398314)
Location: include/linux/fs.h:2947
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
In fs/open.c (c05677cc)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (c056e370)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (c057e938)
Location: include/linux/fs.h:2947
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
In fs/open.c (c000000000472c40)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (c00000000047b560)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (c000000000492238)
Location: include/linux/fs.h:2947
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
In fs/open.c (ffffffe00025398e)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffe00025824e)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffe000265f28)
Location: include/linux/fs.h:2947
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
In fs/open.c (ffffffff812d0787)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812d73aa)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812e6c68)
Location: include/linux/fs.h:2947
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
In fs/open.c (ffffffff812c1407)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812c802a)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812d78a8)
Location: include/linux/fs.h:2947
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
In fs/open.c (ffffffff812ce597)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812d51ba)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812e4a78)
Location: include/linux/fs.h:2947
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
In fs/open.c (ffffffff812df3a7)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/file_table.c (ffffffff812e6000)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/file_table.c:__fput
```
```
In fs/namei.c (ffffffff812f59f8)
Location: include/linux/fs.h:2947
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
</details>
</li>
</ul>

## Differences
