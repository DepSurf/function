# Function: <code>move_cursor</code>

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
void move_cursor(struct dentry *cursor, struct list_head *after);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8125bd00)
Location: fs/libfs.c:122
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff8125bd00-ffffffff8125bde7: move_cursor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void move_cursor(struct dentry *cursor, struct list_head *after);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8126f2b0)
Location: fs/libfs.c:122
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff8126f2b0-ffffffff8126f397: move_cursor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void move_cursor(struct dentry *cursor, struct list_head *after);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8127caa0)
Location: fs/libfs.c:123
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff8127caa0-ffffffff8127cb80: move_cursor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void move_cursor(struct dentry *cursor, struct list_head *after);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8129f540)
Location: fs/libfs.c:123
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff8129f540-ffffffff8129f620: move_cursor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void move_cursor(struct dentry *cursor, struct list_head *after);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812c6f60)
Location: fs/libfs.c:123
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff812c6f60-ffffffff812c7040: move_cursor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void move_cursor(struct dentry *cursor, struct list_head *after);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812dc240)
Location: fs/libfs.c:123
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff812dc240-ffffffff812dc320: move_cursor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void move_cursor(struct dentry *cursor, struct list_head *after);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812fa8f0)
Location: fs/libfs.c:126
Inline: False
Direct callers:
  - fs/libfs.c:dcache_readdir
  - fs/libfs.c:dcache_dir_lseek
```
**Symbols:**

```
ffffffff812fa8f0-ffffffff812fa9d3: move_cursor (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
