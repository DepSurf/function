# Function: <code>remap_verify_area</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int remap_verify_area(struct file *file, loff_t pos, loff_t len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ac480)
Location: fs/read_write.c:1715
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
```
**Symbols:**

```
ffffffff812ac480-ffffffff812ac513: remap_verify_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int remap_verify_area(struct file *file, loff_t pos, loff_t len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c8be0)
Location: fs/read_write.c:1778
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
```
**Symbols:**

```
ffffffff812c8be0-ffffffff812c8c72: remap_verify_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int remap_verify_area(struct file *file, loff_t pos, loff_t len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812da5f0)
Location: fs/read_write.c:1778
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff812da5f0-ffffffff812da682: remap_verify_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int remap_verify_area(struct file *file, loff_t pos, loff_t len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81310af0)
Location: fs/read_write.c:1862
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
```
**Symbols:**

```
ffffffff81310af0-ffffffff81310b82: remap_verify_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int remap_verify_area(struct file *file, loff_t pos, loff_t len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff81365ff0)
Location: fs/remap_range.c:99
Inline: False
Direct callers:
  - fs/remap_range.c:vfs_dedupe_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
**Symbols:**

```
ffffffff81365ff0-ffffffff81366082: remap_verify_area (STB_LOCAL)
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
In fs/remap_range.c (ffffffff8136cc65)
Location: fs/remap_range.c:99
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
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
In fs/remap_range.c (ffffffff813bb925)
Location: fs/remap_range.c:99
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
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
In fs/remap_range.c (ffffffff81441b79)
Location: fs/remap_range.c:100
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
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
In fs/remap_range.c (ffffffff814d0e59)
Location: fs/remap_range.c:101
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
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
In fs/remap_range.c (ffffffff8150798f)
Location: fs/remap_range.c:102
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_dedupe_file_range
  - fs/remap_range.c:do_clone_file_range
  - fs/remap_range.c:do_clone_file_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int remap_verify_area(struct file *file, loff_t pos, loff_t len, bool write);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff8153bd80)
Location: fs/remap_range.c:102
Inline: True
Direct callers:
  - fs/remap_range.c:vfs_dedupe_file_range
  - fs/remap_range.c:vfs_clone_file_range
  - fs/remap_range.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff8153bd80-ffffffff8153be80: remap_verify_area (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int remap_verify_area(struct file *file, loff_t pos, loff_t len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff80001037fbf8)
Location: fs/read_write.c:1778
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffff80001037fbf8-ffff80001037fcc4: remap_verify_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int remap_verify_area(struct file *file, loff_t pos, loff_t len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056a228)
Location: fs/read_write.c:1778
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
  - fs/read_write.c:do_clone_file_range
  - fs/read_write.c:do_clone_file_range
```
**Symbols:**

```
c056a228-c056a2fc: remap_verify_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int remap_verify_area(struct file *file, loff_t pos, loff_t len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000475af0)
Location: fs/read_write.c:1778
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
c000000000475af0-c000000000475bf4: remap_verify_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int remap_verify_area(struct file *file, loff_t pos, loff_t len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe0002555ac)
Location: fs/read_write.c:1778
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffe0002555ac-ffffffe00025565a: remap_verify_area (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int remap_verify_area(struct file *file, loff_t pos, loff_t len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d2bd0)
Location: fs/read_write.c:1778
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff812d2bd0-ffffffff812d2c62: remap_verify_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int remap_verify_area(struct file *file, loff_t pos, loff_t len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c3850)
Location: fs/read_write.c:1778
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff812c3850-ffffffff812c38e2: remap_verify_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int remap_verify_area(struct file *file, loff_t pos, loff_t len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d09e0)
Location: fs/read_write.c:1778
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff812d09e0-ffffffff812d0a72: remap_verify_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int remap_verify_area(struct file *file, loff_t pos, loff_t len, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e1810)
Location: fs/read_write.c:1778
Inline: False
Direct callers:
  - fs/read_write.c:vfs_dedupe_file_range
```
**Symbols:**

```
ffffffff812e1810-ffffffff812e18a2: remap_verify_area (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
