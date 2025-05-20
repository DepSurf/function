# Function: <code>iomap_file_unshare</code>

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
int iomap_file_unshare(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813a9da0)
Location: fs/iomap/buffered-io.c:913
Inline: False
```
**Symbols:**

```
ffffffff813a9da0-ffffffff813a9e0e: iomap_file_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iomap_file_unshare(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bb3f0)
Location: fs/iomap/buffered-io.c:885
Inline: False
```
**Symbols:**

```
ffffffff813bb3f0-ffffffff813bb45e: iomap_file_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iomap_file_unshare(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c2510)
Location: fs/iomap/buffered-io.c:885
Inline: False
```
**Symbols:**

```
ffffffff813c2510-ffffffff813c257e: iomap_file_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iomap_file_unshare(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81414540)
Location: fs/iomap/buffered-io.c:863
Inline: False
```
**Symbols:**

```
ffffffff81414540-ffffffff81414704: iomap_file_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iomap_file_unshare(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8148b820)
Location: fs/iomap/buffered-io.c:868
Inline: False
```
**Symbols:**

```
ffffffff8148b820-ffffffff8148b9f1: iomap_file_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iomap_file_unshare(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8151f870)
Location: fs/iomap/buffered-io.c:1127
Inline: False
```
**Symbols:**

```
ffffffff8151f870-ffffffff8151fa43: iomap_file_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iomap_file_unshare(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81557920)
Location: fs/iomap/buffered-io.c:1147
Inline: False
```
**Symbols:**

```
ffffffff81557920-ffffffff81557af3: iomap_file_unshare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int iomap_file_unshare(struct inode *inode, loff_t pos, loff_t len, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1315
Inline: False
```
**Symbols:**

```
ffffffff821c864f-ffffffff821c86e0: iomap_file_unshare.cold (STB_LOCAL)
ffffffff8158dec0-ffffffff8158e11d: iomap_file_unshare (STB_GLOBAL)
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
