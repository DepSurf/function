# Function: <code>fuse_writepage_add_to_bucket</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fuse_writepage_add_to_bucket(struct fuse_conn *fc, struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814ede80)
Location: fs/fuse/file.c:1890
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff814ede80-ffffffff814edebd: fuse_writepage_add_to_bucket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fuse_writepage_add_to_bucket(struct fuse_conn *fc, struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8157d260)
Location: fs/fuse/file.c:1904
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8157d260-ffffffff8157d2c5: fuse_writepage_add_to_bucket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fuse_writepage_add_to_bucket(struct fuse_conn *fc, struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81622ec0)
Location: fs/fuse/file.c:1939
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81622ec0-ffffffff81622f25: fuse_writepage_add_to_bucket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fuse_writepage_add_to_bucket(struct fuse_conn *fc, struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165b340)
Location: fs/fuse/file.c:1916
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff8165b340-ffffffff8165b3a5: fuse_writepage_add_to_bucket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fuse_writepage_add_to_bucket(struct fuse_conn *fc, struct fuse_writepage_args *wpa);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81695010)
Location: fs/fuse/file.c:1936
Inline: True
Direct callers:
  - fs/fuse/file.c:fuse_writepages_fill
  - fs/fuse/file.c:fuse_writepage_locked
```
**Symbols:**

```
ffffffff81695010-ffffffff81695075: fuse_writepage_add_to_bucket (STB_LOCAL)
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
