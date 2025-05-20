# Function: <code>fuse_insert_writeback</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fuse_writepage_args *fuse_insert_writeback(struct rb_root *root, struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81475940)
Location: fs/fuse/file.c:1678
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff81475940-ffffffff81475a02: fuse_insert_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fuse_writepage_args *fuse_insert_writeback(struct rb_root *root, struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81490650)
Location: fs/fuse/file.c:1718
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff81490650-ffffffff81490712: fuse_insert_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fuse_writepage_args *fuse_insert_writeback(struct rb_root *root, struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81496080)
Location: fs/fuse/file.c:1720
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepage_add
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff81496080-ffffffff81496142: fuse_insert_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fuse_writepage_args *fuse_insert_writeback(struct rb_root *root, struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814edb40)
Location: fs/fuse/file.c:1726
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff814edb40-ffffffff814edc02: fuse_insert_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fuse_writepage_args *fuse_insert_writeback(struct rb_root *root, struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8157ce10)
Location: fs/fuse/file.c:1741
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff8157ce10-ffffffff8157cefc: fuse_insert_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fuse_writepage_args *fuse_insert_writeback(struct rb_root *root, struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81622970)
Location: fs/fuse/file.c:1776
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff81622970-ffffffff81622a5c: fuse_insert_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fuse_writepage_args *fuse_insert_writeback(struct rb_root *root, struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165adb0)
Location: fs/fuse/file.c:1753
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff8165adb0-ffffffff8165ae9c: fuse_insert_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fuse_writepage_args *fuse_insert_writeback(struct rb_root *root, struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81694a80)
Location: fs/fuse/file.c:1773
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
  - fs/fuse/file.c:fuse_writepage_end
```
**Symbols:**

```
ffffffff81694a80-ffffffff81694b6c: fuse_insert_writeback (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
