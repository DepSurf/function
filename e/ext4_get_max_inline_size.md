# Function: <code>ext4_get_max_inline_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812e0660)
Location: fs/ext4/inline.c:97
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
```
**Symbols:**

```
ffffffff812e0660-ffffffff812e0717: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81310350)
Location: fs/ext4/inline.c:97
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
**Symbols:**

```
ffffffff81310350-ffffffff8131040a: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81326150)
Location: fs/ext4/inline.c:97
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
**Symbols:**

```
ffffffff81326150-ffffffff8132620a: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812fa110)
Location: fs/ext4/inline.c:97
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff812fa110-ffffffff812fa1ca: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8131e740)
Location: fs/ext4/inline.c:98
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff8131e740-ffffffff8131e7fa: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8134c750)
Location: fs/ext4/inline.c:91
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff8134c750-ffffffff8134c80a: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81364890)
Location: fs/ext4/inline.c:91
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81364890-ffffffff8136494a: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138e0d0)
Location: fs/ext4/inline.c:91
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffffffff8138e0d0-ffffffff8138e196: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a6b30)
Location: fs/ext4/inline.c:91
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffffffff813a6b30-ffffffff813a6bf6: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff813f375d)
Location: fs/ext4/inline.c:91
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffffffff813f16f0-ffffffff813f17af: ext4_get_max_inline_size.part.0 (STB_LOCAL)
ffffffff813f2d60-ffffffff813f2d7d: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff81405eed)
Location: fs/ext4/inline.c:91
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffffffff81403dd0-ffffffff81403e8f: ext4_get_max_inline_size.part.0 (STB_LOCAL)
ffffffff814054b0-ffffffff814054cd: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff8140c246)
Location: fs/ext4/inline.c:91
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffffffff8140a290-ffffffff8140a34f: ext4_get_max_inline_size.part.0 (STB_LOCAL)
ffffffff8140b7f0-ffffffff8140b80d: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (ffffffff8145f142)
Location: fs/ext4/inline.c:92
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffffffff8145d030-ffffffff8145d0ef: ext4_get_max_inline_size.part.0 (STB_LOCAL)
ffffffff8145e470-ffffffff8145e48d: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814dca10)
Location: fs/ext4/inline.c:96
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffffffff814dca10-ffffffff814dcaf8: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815759f0)
Location: fs/ext4/inline.c:96
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffffffff815759f0-ffffffff81575ad8: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815ad3f0)
Location: fs/ext4/inline.c:106
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
**Symbols:**

```
ffffffff815ad3f0-ffffffff815ad4d8: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815e61a0)
Location: fs/ext4/inline.c:106
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
```
**Symbols:**

```
ffffffff815e61a0-ffffffff815e6288: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffff80001047a280)
Location: fs/ext4/inline.c:91
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffff80001047a280-ffff80001047a35c: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c063bd0c)
Location: fs/ext4/inline.c:91
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
c063bd0c-c063be00: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c00000000059d070)
Location: fs/ext4/inline.c:91
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
c00000000059d070-c00000000059d1bc: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffe000304c3a)
Location: fs/ext4/inline.c:91
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffffffe000304c3a-ffffffe000304ce2: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139f110)
Location: fs/ext4/inline.c:91
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffffffff8139f110-ffffffff8139f1d6: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138fba0)
Location: fs/ext4/inline.c:91
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffffffff8138fba0-ffffffff8138fc66: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139c970)
Location: fs/ext4/inline.c:91
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffffffff8139c970-ffffffff8139ca36: ext4_get_max_inline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_get_max_inline_size(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813b0e80)
Location: fs/ext4/inline.c:91
Inline: True
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_begin
  - fs/ext4/inline.c:ext4_try_to_write_inline_data
  - fs/ext4/inline.c:ext4_prepare_inline_data
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
**Symbols:**

```
ffffffff813b0e80-ffffffff813b0f46: ext4_get_max_inline_size (STB_GLOBAL)
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
