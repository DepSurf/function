# Function: <code>ext4_da_convert_inline_data_to_extent</code>

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
In fs/ext4/inline.c (ffffffff812e1282)
Location: fs/ext4/inline.c:786
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
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
In fs/ext4/inline.c (ffffffff8131107c)
Location: fs/ext4/inline.c:787
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
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
In fs/ext4/inline.c (ffffffff81326f5c)
Location: fs/ext4/inline.c:798
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
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
In fs/ext4/inline.c (ffffffff812fae32)
Location: fs/ext4/inline.c:801
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
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
In fs/ext4/inline.c (ffffffff8131f522)
Location: fs/ext4/inline.c:792
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
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
In fs/ext4/inline.c (ffffffff8134d74f)
Location: fs/ext4/inline.c:797
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
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
In fs/ext4/inline.c (ffffffff813658e6)
Location: fs/ext4/inline.c:800
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138eb48)
Location: fs/ext4/inline.c:800
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a75a8)
Location: fs/ext4/inline.c:800
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_da_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, unsigned int flags, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813f26d0)
Location: fs/ext4/inline.c:800
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
**Symbols:**

```
ffffffff813f26d0-ffffffff813f28e8: ext4_da_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_da_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, unsigned int flags, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81404e20)
Location: fs/ext4/inline.c:800
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
**Symbols:**

```
ffffffff81404e20-ffffffff81405032: ext4_da_convert_inline_data_to_extent (STB_LOCAL)
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
In fs/ext4/inline.c (ffffffff8140c286)
Location: fs/ext4/inline.c:806
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
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
In fs/ext4/inline.c (ffffffff8145f180)
Location: fs/ext4/inline.c:849
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_da_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814dc1a0)
Location: fs/ext4/inline.c:852
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
**Symbols:**

```
ffffffff814dc1a0-ffffffff814dc492: ext4_da_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_da_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81575150)
Location: fs/ext4/inline.c:851
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
**Symbols:**

```
ffffffff81575150-ffffffff81575442: ext4_da_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_da_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815ace40)
Location: fs/ext4/inline.c:834
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
**Symbols:**

```
ffffffff815ace40-ffffffff815acfc2: ext4_da_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_da_convert_inline_data_to_extent(struct address_space *mapping, struct inode *inode, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815e5bf0)
Location: fs/ext4/inline.c:833
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
**Symbols:**

```
ffffffff815e5bf0-ffffffff815e5d72: ext4_da_convert_inline_data_to_extent (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffff80001047ae5c)
Location: fs/ext4/inline.c:800
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c063c790)
Location: fs/ext4/inline.c:800
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c00000000059dfa4)
Location: fs/ext4/inline.c:800
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffe00030548c)
Location: fs/ext4/inline.c:800
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139fb88)
Location: fs/ext4/inline.c:800
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81390618)
Location: fs/ext4/inline.c:800
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139d3e8)
Location: fs/ext4/inline.c:800
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813b1958)
Location: fs/ext4/inline.c:800
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
