# Function: <code>clone_verify_area</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int clone_verify_area(struct file *file, loff_t pos, u64 len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81231cb0)
Location: fs/read_write.c:1625
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff81231cb0-ffffffff81231d3d: clone_verify_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int clone_verify_area(struct file *file, loff_t pos, u64 len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81244260)
Location: fs/read_write.c:1669
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff81244260-ffffffff812442ed: clone_verify_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int clone_verify_area(struct file *file, loff_t pos, u64 len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8124f9f0)
Location: fs/read_write.c:1685
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff8124f9f0-ffffffff8124fa7e: clone_verify_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int clone_verify_area(struct file *file, loff_t pos, u64 len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81271940)
Location: fs/read_write.c:1688
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff81271940-ffffffff812719ce: clone_verify_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int clone_verify_area(struct file *file, loff_t pos, u64 len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812977b0)
Location: fs/read_write.c:1715
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff812977b0-ffffffff8129783d: clone_verify_area (STB_LOCAL)
```
</details>
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
