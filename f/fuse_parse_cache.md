# Function: <code>fuse_parse_cache</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff813ea745)
Location: fs/fuse/readdir.c:363
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
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
In fs/fuse/readdir.c (ffffffff81416b47)
Location: fs/fuse/readdir.c:363
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
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
In fs/fuse/readdir.c (ffffffff81430a78)
Location: fs/fuse/readdir.c:377
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum fuse_parse_result fuse_parse_cache(struct fuse_file *ff, void *addr, unsigned int size, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8147fa80)
Location: fs/fuse/readdir.c:377
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
**Symbols:**

```
ffffffff8147fa80-ffffffff8147fbd1: fuse_parse_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum fuse_parse_result fuse_parse_cache(struct fuse_file *ff, void *addr, unsigned int size, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff8149b160)
Location: fs/fuse/readdir.c:377
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
**Symbols:**

```
ffffffff8149b160-ffffffff8149b2b1: fuse_parse_cache (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum fuse_parse_result fuse_parse_cache(struct fuse_file *ff, void *addr, unsigned int size, struct dir_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/readdir.c (ffffffff814a0400)
Location: fs/fuse/readdir.c:380
Inline: False
Direct callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
**Symbols:**

```
ffffffff814a0400-ffffffff814a0551: fuse_parse_cache (STB_LOCAL)
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
In fs/fuse/readdir.c (ffffffff814f8cf9)
Location: fs/fuse/readdir.c:380
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
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
In fs/fuse/readdir.c (ffffffff81589349)
Location: fs/fuse/readdir.c:380
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
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
In fs/fuse/readdir.c (ffffffff8162f9d5)
Location: fs/fuse/readdir.c:382
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
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
In fs/fuse/readdir.c (ffffffff81667c14)
Location: fs/fuse/readdir.c:382
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
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
In fs/fuse/readdir.c (ffffffff816a1f3f)
Location: fs/fuse/readdir.c:390
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
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
In fs/fuse/readdir.c (ffff800010515588)
Location: fs/fuse/readdir.c:377
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
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
In fs/fuse/readdir.c (c06d0318)
Location: fs/fuse/readdir.c:377
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
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
In fs/fuse/readdir.c (c00000000065ddd4)
Location: fs/fuse/readdir.c:377
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
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
In fs/fuse/readdir.c (ffffffe00037eedc)
Location: fs/fuse/readdir.c:377
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
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
In fs/fuse/readdir.c (ffffffff81429058)
Location: fs/fuse/readdir.c:377
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
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
In fs/fuse/readdir.c (ffffffff81419ad8)
Location: fs/fuse/readdir.c:377
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
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
In fs/fuse/readdir.c (ffffffff814251f8)
Location: fs/fuse/readdir.c:377
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
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
In fs/fuse/readdir.c (ffffffff8143c0c8)
Location: fs/fuse/readdir.c:377
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
