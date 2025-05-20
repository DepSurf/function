# Function: <code>ext4_ext_zeroout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_ext_zeroout(struct inode *inode, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c2710)
Location: fs/ext4/extents.c:3118
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
```
**Symbols:**

```
ffffffff812c2710-ffffffff812c2785: ext4_ext_zeroout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_ext_zeroout(struct inode *inode, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f2080)
Location: fs/ext4/extents.c:3140
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
```
**Symbols:**

```
ffffffff812f2080-ffffffff812f20b1: ext4_ext_zeroout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_ext_zeroout(struct inode *inode, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81308050)
Location: fs/ext4/extents.c:3140
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
```
**Symbols:**

```
ffffffff81308050-ffffffff81308081: ext4_ext_zeroout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_ext_zeroout(struct inode *inode, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812e6810)
Location: fs/ext4/extents.c:3141
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
```
**Symbols:**

```
ffffffff812e6810-ffffffff812e6841: ext4_ext_zeroout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_ext_zeroout(struct inode *inode, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130b220)
Location: fs/ext4/extents.c:3141
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
```
**Symbols:**

```
ffffffff8130b220-ffffffff8130b251: ext4_ext_zeroout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_ext_zeroout(struct inode *inode, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813391d0)
Location: fs/ext4/extents.c:3135
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
```
**Symbols:**

```
ffffffff813391d0-ffffffff81339201: ext4_ext_zeroout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_ext_zeroout(struct inode *inode, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81350490)
Location: fs/ext4/extents.c:3197
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
```
**Symbols:**

```
ffffffff81350490-ffffffff813504c1: ext4_ext_zeroout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_ext_zeroout(struct inode *inode, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81379150)
Location: fs/ext4/extents.c:3217
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
```
**Symbols:**

```
ffffffff81379150-ffffffff81379181: ext4_ext_zeroout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_ext_zeroout(struct inode *inode, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81391500)
Location: fs/ext4/extents.c:3263
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
```
**Symbols:**

```
ffffffff81391500-ffffffff81391531: ext4_ext_zeroout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813e2d22)
Location: fs/ext4/extents.c:3100
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f458b)
Location: fs/ext4/extents.c:3099
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
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
In fs/ext4/extents.c (ffffffff813fa7ca)
Location: fs/ext4/extents.c:3102
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
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
In fs/ext4/extents.c (ffffffff8144ce10)
Location: fs/ext4/extents.c:3140
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
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
In fs/ext4/extents.c (ffffffff814c9698)
Location: fs/ext4/extents.c:3139
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
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
In fs/ext4/extents.c (ffffffff81561d08)
Location: fs/ext4/extents.c:3144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
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
In fs/ext4/extents.c (ffffffff81599a76)
Location: fs/ext4/extents.c:3144
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815d28f6)
Location: fs/ext4/extents.c:3120
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
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
int ext4_ext_zeroout(struct inode *inode, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff800010464140)
Location: fs/ext4/extents.c:3263
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
```
**Symbols:**

```
ffff800010464140-ffff800010464190: ext4_ext_zeroout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_ext_zeroout(struct inode *inode, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c0625104)
Location: fs/ext4/extents.c:3263
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
```
**Symbols:**

```
c0625104-c0625144: ext4_ext_zeroout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_ext_zeroout(struct inode *inode, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c000000000582190)
Location: fs/ext4/extents.c:3263
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
```
**Symbols:**

```
c000000000582190-c0000000005821e8: ext4_ext_zeroout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_ext_zeroout(struct inode *inode, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f2f9c)
Location: fs/ext4/extents.c:3263
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
```
**Symbols:**

```
ffffffe0002f2f9c-ffffffe0002f2fec: ext4_ext_zeroout (STB_LOCAL)
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
int ext4_ext_zeroout(struct inode *inode, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81389ae0)
Location: fs/ext4/extents.c:3263
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
```
**Symbols:**

```
ffffffff81389ae0-ffffffff81389b11: ext4_ext_zeroout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_ext_zeroout(struct inode *inode, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137a570)
Location: fs/ext4/extents.c:3263
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
```
**Symbols:**

```
ffffffff8137a570-ffffffff8137a5a1: ext4_ext_zeroout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_ext_zeroout(struct inode *inode, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81387440)
Location: fs/ext4/extents.c:3263
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
```
**Symbols:**

```
ffffffff81387440-ffffffff81387471: ext4_ext_zeroout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_ext_zeroout(struct inode *inode, struct ext4_extent *ex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139b120)
Location: fs/ext4/extents.c:3263
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_ext_convert_to_initialized
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
  - fs/ext4/extents.c:ext4_split_extent_at
```
**Symbols:**

```
ffffffff8139b120-ffffffff8139b151: ext4_ext_zeroout (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
