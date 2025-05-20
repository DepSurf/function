# Function: <code>ext4_convert_inline_data_to_extent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812e0a76)
Location: fs/ext4/inline.c:520
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8131079c)
Location: fs/ext4/inline.c:520
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813265cc)
Location: fs/ext4/inline.c:531
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812fa555)
Location: fs/ext4/inline.c:534
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8131eb85)
Location: fs/ext4/inline.c:525
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8134cb71)
Location: fs/ext4/inline.c:525
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81364cb1)
Location: fs/ext4/inline.c:525
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138d570)
Location: fs/ext4/inline.c:525
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff8138d570-ffffffff8138da58: ext4_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a5fd0)
Location: fs/ext4/inline.c:525
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff813a5fd0-ffffffff813a64b8: ext4_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813f28f0)
Location: fs/ext4/inline.c:525
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff813f28f0-ffffffff813f2d5e: ext4_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81405040)
Location: fs/ext4/inline.c:525
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff81405040-ffffffff814054a8: ext4_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8140b380)
Location: fs/ext4/inline.c:525
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff8140b380-ffffffff8140b7e6: ext4_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8145e000)
Location: fs/ext4/inline.c:529
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff8145e000-ffffffff8145e46b: ext4_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814dc4a0)
Location: fs/ext4/inline.c:533
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff814dc4a0-ffffffff814dca09: ext4_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81575460)
Location: fs/ext4/inline.c:532
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff81575460-ffffffff815759d6: ext4_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815acfe0)
Location: fs/ext4/inline.c:542
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff815acfe0-ffffffff815ad3d6: ext4_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815e5d90)
Location: fs/ext4/inline.c:541
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff815e5d90-ffffffff815e6186: ext4_convert_inline_data_to_extent (STB_LOCAL)
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
int ext4_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffff800010479688)
Location: fs/ext4/inline.c:525
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffff800010479688-ffff800010479b68: ext4_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c063b12c)
Location: fs/ext4/inline.c:525
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
c063b12c-c063b62c: ext4_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c00000000059c6f0)
Location: fs/ext4/inline.c:525
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
c00000000059c6f0-c00000000059cdd8: ext4_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffe00030482e)
Location: fs/ext4/inline.c:525
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffe00030482e-ffffffe000304c3a: ext4_convert_inline_data_to_extent (STB_LOCAL)
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
int ext4_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139e5b0)
Location: fs/ext4/inline.c:525
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff8139e5b0-ffffffff8139ea98: ext4_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138f040)
Location: fs/ext4/inline.c:525
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff8138f040-ffffffff8138f528: ext4_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139be10)
Location: fs/ext4/inline.c:525
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff8139be10-ffffffff8139c2f8: ext4_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813b0330)
Location: fs/ext4/inline.c:525
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
```
**Symbols:**

```
ffffffff813b0330-ffffffff813b0818: ext4_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
