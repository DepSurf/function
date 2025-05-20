# Function: <code>pagecache_read</code>

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
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/verity.c (ffffffff813eeee0)
Location: fs/ext4/verity.c:41
Inline: True
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff813eeee0-ffffffff813ef09d: pagecache_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pagecache_read(struct inode *inode, void *buf, size_t count, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff8143c2e0)
Location: fs/ext4/verity.c:41
Inline: False
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff8143c2e0-ffffffff8143c4a4: pagecache_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pagecache_read(struct inode *inode, void *buf, size_t count, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff81458630)
Location: fs/ext4/verity.c:41
Inline: False
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff81458630-ffffffff814587f1: pagecache_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pagecache_read(struct inode *inode, void *buf, size_t count, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff8145dfd0)
Location: fs/ext4/verity.c:41
Inline: False
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff8145dfd0-ffffffff8145e16d: pagecache_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pagecache_read(struct inode *inode, void *buf, size_t count, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff814b34f0)
Location: fs/ext4/verity.c:41
Inline: False
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff814b34f0-ffffffff814b368d: pagecache_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pagecache_read(struct inode *inode, void *buf, size_t count, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff8153c0c0)
Location: fs/ext4/verity.c:41
Inline: False
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff8153c0c0-ffffffff8153c2bc: pagecache_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pagecache_read(struct inode *inode, void *buf, size_t count, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff815da780)
Location: fs/ext4/verity.c:41
Inline: False
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff815da780-ffffffff815da97c: pagecache_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pagecache_read(struct inode *inode, void *buf, size_t count, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff81612560)
Location: fs/ext4/verity.c:41
Inline: False
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff81612560-ffffffff81612615: pagecache_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pagecache_read(struct inode *inode, void *buf, size_t count, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff8164b310)
Location: fs/ext4/verity.c:41
Inline: False
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff8164b310-ffffffff8164b3c5: pagecache_read (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/verity.c (ffff8000104c8278)
Location: fs/ext4/verity.c:41
Inline: True
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffff8000104c8278-ffff8000104c83bc: pagecache_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pagecache_read(struct inode *inode, void *buf, size_t count, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (c068bce4)
Location: fs/ext4/verity.c:41
Inline: False
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
c068bce4-c068bde0: pagecache_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pagecache_read(struct inode *inode, void *buf, size_t count, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (c000000000600820)
Location: fs/ext4/verity.c:41
Inline: False
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
c000000000600820-c000000000600a3c: pagecache_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pagecache_read(struct inode *inode, void *buf, size_t count, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffe000341d66)
Location: fs/ext4/verity.c:41
Inline: False
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffe000341d66-ffffffe000341e7a: pagecache_read (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/verity.c (ffffffff813e74c0)
Location: fs/ext4/verity.c:41
Inline: True
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff813e74c0-ffffffff813e767d: pagecache_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/verity.c (ffffffff813d7f40)
Location: fs/ext4/verity.c:41
Inline: True
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff813d7f40-ffffffff813d80fd: pagecache_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/verity.c (ffffffff813e4840)
Location: fs/ext4/verity.c:41
Inline: True
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff813e4840-ffffffff813e49fd: pagecache_read.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/verity.c (ffffffff813f9c70)
Location: fs/ext4/verity.c:41
Inline: True
Direct callers:
  - fs/ext4/verity.c:ext4_get_verity_descriptor
  - fs/ext4/verity.c:ext4_get_verity_descriptor
```
**Symbols:**

```
ffffffff813f9c70-ffffffff813f9e4b: pagecache_read.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
