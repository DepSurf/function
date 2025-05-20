# Function: <code>ext4_get_next_extent</code>

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
int ext4_get_next_extent(struct inode *inode, ext4_lblk_t lblk, unsigned int map_len, struct extent_status *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812cdda0)
Location: fs/ext4/inode.c:5758
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff812cdda0-ffffffff812cdf6a: ext4_get_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_get_next_extent(struct inode *inode, ext4_lblk_t lblk, unsigned int map_len, struct extent_status *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812e3b90)
Location: fs/ext4/inode.c:5909
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff812e3b90-ffffffff812e3d5a: ext4_get_next_extent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_get_next_extent(struct inode *inode, ext4_lblk_t lblk, unsigned int map_len, struct extent_status *result);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81307d90)
Location: fs/ext4/inode.c:6140
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_llseek
  - fs/ext4/file.c:ext4_llseek
```
**Symbols:**

```
ffffffff81307d90-ffffffff81307f47: ext4_get_next_extent (STB_GLOBAL)
```
</details>
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
</ul>
