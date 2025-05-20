# Function: <code>get_write_access</code>

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
In fs/open.c (ffffffff81209904)
Location: include/linux/fs.h:2507
Inline: True
Inline callers:
  - fs/open.c:vfs_truncate
  - fs/open.c:do_dentry_open
```
```
In fs/namei.c (ffffffff8121ab6c)
Location: include/linux/fs.h:2507
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
In fs/open.c (ffffffff8122fde6)
Location: include/linux/fs.h:2622
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812423b9)
Location: include/linux/fs.h:2622
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
In fs/open.c (ffffffff81242386)
Location: include/linux/fs.h:2591
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff8125528e)
Location: include/linux/fs.h:2591
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
In fs/open.c (ffffffff8124d8c8)
Location: include/linux/fs.h:2716
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812612d6)
Location: include/linux/fs.h:2716
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
In fs/open.c (ffffffff8126f92e)
Location: include/linux/fs.h:2777
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff81283a09)
Location: include/linux/fs.h:2777
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
In fs/open.c (ffffffff81295562)
Location: include/linux/fs.h:2799
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812aab92)
Location: include/linux/fs.h:2799
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
In fs/open.c (ffffffff812aa037)
Location: include/linux/fs.h:2870
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812bf957)
Location: include/linux/fs.h:2870
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
In fs/open.c (ffffffff812c67f3)
Location: include/linux/fs.h:2876
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812dcaeb)
Location: include/linux/fs.h:2876
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
In fs/open.c (ffffffff812d81f7)
Location: include/linux/fs.h:2938
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812ee63a)
Location: include/linux/fs.h:2938
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
In fs/open.c (ffffffff8130e299)
Location: include/linux/fs.h:2980
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff813213e7)
Location: include/linux/fs.h:2980
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
In fs/open.c (ffffffff8131a37c)
Location: include/linux/fs.h:2815
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff8132c987)
Location: include/linux/fs.h:2815
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
In fs/open.c (ffffffff8132045c)
Location: include/linux/fs.h:3068
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff813367a6)
Location: include/linux/fs.h:3068
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
In fs/open.c (ffffffff8136da15)
Location: include/linux/fs.h:3056
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff81384186)
Location: include/linux/fs.h:3056
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
In fs/open.c (ffffffff813ebb4c)
Location: include/linux/fs.h:2822
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff814052d5)
Location: include/linux/fs.h:2822
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
In fs/open.c (ffffffff81473fbe)
Location: include/linux/fs.h:2976
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff8148f722)
Location: include/linux/fs.h:2976
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
In fs/open.c (ffffffff814a8866)
Location: include/linux/fs.h:2590
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff814c1f0e)
Location: include/linux/fs.h:2590
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
In fs/open.c (ffffffff814d9961)
Location: include/linux/fs.h:2874
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff814f43ce)
Location: include/linux/fs.h:2874
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
In fs/open.c (ffff80001037dd30)
Location: include/linux/fs.h:2938
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffff8000103982b0)
Location: include/linux/fs.h:2938
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
In fs/open.c (c056784c)
Location: include/linux/fs.h:2938
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (c057e8a0)
Location: include/linux/fs.h:2938
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
In fs/open.c (c000000000472a14)
Location: include/linux/fs.h:2938
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (c0000000004921b8)
Location: include/linux/fs.h:2938
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
In fs/open.c (ffffffe0002538e6)
Location: include/linux/fs.h:2938
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffe000265ed4)
Location: include/linux/fs.h:2938
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
In fs/open.c (ffffffff812d07d7)
Location: include/linux/fs.h:2938
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812e6c1a)
Location: include/linux/fs.h:2938
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
In fs/open.c (ffffffff812c1457)
Location: include/linux/fs.h:2938
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812d785a)
Location: include/linux/fs.h:2938
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
In fs/open.c (ffffffff812ce5e7)
Location: include/linux/fs.h:2938
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812e4a2a)
Location: include/linux/fs.h:2938
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
In fs/open.c (ffffffff812df3f7)
Location: include/linux/fs.h:2938
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
  - fs/open.c:vfs_truncate
```
```
In fs/namei.c (ffffffff812f59aa)
Location: include/linux/fs.h:2938
Inline: True
Inline callers:
  - fs/namei.c:do_last
```
</details>
</li>
</ul>

## Differences
