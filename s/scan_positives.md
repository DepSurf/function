# Function: <code>scan_positives</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *scan_positives(struct dentry *cursor, struct list_head *p, loff_t count, struct dentry *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8130ca20)
Location: fs/libfs.c:99
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff8130ca20-ffffffff8130cba8: scan_positives (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *scan_positives(struct dentry *cursor, struct list_head *p, loff_t count, struct dentry *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81346440)
Location: fs/libfs.c:99
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff81346440-ffffffff813465c8: scan_positives (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *scan_positives(struct dentry *cursor, struct list_head *p, loff_t count, struct dentry *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81352930)
Location: fs/libfs.c:101
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff81352930-ffffffff81352ab8: scan_positives (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *scan_positives(struct dentry *cursor, struct list_head *p, loff_t count, struct dentry *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81359720)
Location: fs/libfs.c:102
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff81359720-ffffffff813598a2: scan_positives (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *scan_positives(struct dentry *cursor, struct list_head *p, loff_t count, struct dentry *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813a7bc0)
Location: fs/libfs.c:102
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff813a7bc0-ffffffff813a7d42: scan_positives (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *scan_positives(struct dentry *cursor, struct list_head *p, loff_t count, struct dentry *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8142a840)
Location: fs/libfs.c:102
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff8142a840-ffffffff8142a9bc: scan_positives (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *scan_positives(struct dentry *cursor, struct list_head *p, loff_t count, struct dentry *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b8fc0)
Location: fs/libfs.c:103
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff814b8fc0-ffffffff814b913f: scan_positives (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *scan_positives(struct dentry *cursor, struct list_head *p, loff_t count, struct dentry *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814ecb00)
Location: fs/libfs.c:103
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff814ecb00-ffffffff814ecc7f: scan_positives (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *scan_positives(struct dentry *cursor, struct hlist_node **p, loff_t count, struct dentry *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81520a50)
Location: fs/libfs.c:106
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff81520a50-ffffffff81520bed: scan_positives (STB_LOCAL)
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
struct dentry *scan_positives(struct dentry *cursor, struct list_head *p, loff_t count, struct dentry *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffff8000103c1418)
Location: fs/libfs.c:99
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffff8000103c1418-ffff8000103c166c: scan_positives (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *scan_positives(struct dentry *cursor, struct list_head *p, loff_t count, struct dentry *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c059cb0c)
Location: fs/libfs.c:99
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
c059cb0c-c059ccbc: scan_positives (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *scan_positives(struct dentry *cursor, struct list_head *p, loff_t count, struct dentry *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c0000000004be720)
Location: fs/libfs.c:99
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
c0000000004be720-c0000000004be9a4: scan_positives (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *scan_positives(struct dentry *cursor, struct list_head *p, loff_t count, struct dentry *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffe00028176c)
Location: fs/libfs.c:99
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffe00028176c-ffffffe000281944: scan_positives (STB_LOCAL)
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
struct dentry *scan_positives(struct dentry *cursor, struct list_head *p, loff_t count, struct dentry *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81305000)
Location: fs/libfs.c:99
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff81305000-ffffffff81305188: scan_positives (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *scan_positives(struct dentry *cursor, struct list_head *p, loff_t count, struct dentry *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f5c20)
Location: fs/libfs.c:99
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff812f5c20-ffffffff812f5da8: scan_positives (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *scan_positives(struct dentry *cursor, struct list_head *p, loff_t count, struct dentry *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81302df0)
Location: fs/libfs.c:99
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff81302df0-ffffffff81302f78: scan_positives (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *scan_positives(struct dentry *cursor, struct list_head *p, loff_t count, struct dentry *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81313e80)
Location: fs/libfs.c:99
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff81313e80-ffffffff81313fe9: scan_positives (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct list_head *p</code> ➡️ <code>struct hlist_node **p</code>
</li>
</ul>
</details>
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
