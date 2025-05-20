# Function: <code>debugfs_read_file_str</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t debugfs_read_file_str(struct file *file, char *user_buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a5e00)
Location: fs/debugfs/file.c:867
Inline: False
```
**Symbols:**

```
ffffffff814a5e00-ffffffff814a5ede: debugfs_read_file_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t debugfs_read_file_str(struct file *file, char *user_buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814fe140)
Location: fs/debugfs/file.c:852
Inline: False
```
**Symbols:**

```
ffffffff814fe140-ffffffff814fe21e: debugfs_read_file_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t debugfs_read_file_str(struct file *file, char *user_buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8158edb0)
Location: fs/debugfs/file.c:852
Inline: False
```
**Symbols:**

```
ffffffff8158edb0-ffffffff8158ee9c: debugfs_read_file_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t debugfs_read_file_str(struct file *file, char *user_buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81635ec0)
Location: fs/debugfs/file.c:868
Inline: False
```
**Symbols:**

```
ffffffff81635ec0-ffffffff81635fac: debugfs_read_file_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t debugfs_read_file_str(struct file *file, char *user_buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8166e200)
Location: fs/debugfs/file.c:868
Inline: False
```
**Symbols:**

```
ffffffff8166e200-ffffffff8166e35b: debugfs_read_file_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t debugfs_read_file_str(struct file *file, char *user_buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff816a89f0)
Location: fs/debugfs/file.c:960
Inline: False
```
**Symbols:**

```
ffffffff816a89f0-ffffffff816a8b4b: debugfs_read_file_str (STB_GLOBAL)
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
