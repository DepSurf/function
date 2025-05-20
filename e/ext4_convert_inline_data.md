# Function: <code>ext4_convert_inline_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812e2b70)
Location: fs/ext4/inline.c:1985
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/crypto_policy.c:ext4_process_policy
```
**Symbols:**

```
ffffffff812e2b70-ffffffff812e2c95: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81312b20)
Location: fs/ext4/inline.c:1983
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_prepare_context
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff81312b20-ffffffff81312c4b: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81328aa0)
Location: fs/ext4/inline.c:2000
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_prepare_context
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff81328aa0-ffffffff81328bf7: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812fca80)
Location: fs/ext4/inline.c:2005
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/super.c:ext4_set_context
```
**Symbols:**

```
ffffffff812fca80-ffffffff812fcbd5: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813212e0)
Location: fs/ext4/inline.c:2028
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/super.c:ext4_set_context
```
**Symbols:**

```
ffffffff813212e0-ffffffff81321435: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8134f2f0)
Location: fs/ext4/inline.c:1997
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/super.c:ext4_set_context
```
**Symbols:**

```
ffffffff8134f2f0-ffffffff8134f43d: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813674a0)
Location: fs/ext4/inline.c:2000
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/super.c:ext4_set_context
```
**Symbols:**

```
ffffffff813674a0-ffffffff813675ed: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81390870)
Location: fs/ext4/inline.c:1997
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/super.c:ext4_set_context
```
**Symbols:**

```
ffffffff81390870-ffffffff813909c9: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a92d0)
Location: fs/ext4/inline.c:1997
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813a92d0-ffffffff813a9429: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813f5210)
Location: fs/ext4/inline.c:1959
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813f5210-ffffffff813f5374: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814079b0)
Location: fs/ext4/inline.c:1960
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff814079b0-ffffffff81407b14: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8140de20)
Location: fs/ext4/inline.c:1971
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff8140de20-ffffffff8140df84: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81460ce0)
Location: fs/ext4/inline.c:2006
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff81460ce0-ffffffff81460e44: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814df6a0)
Location: fs/ext4/inline.c:2029
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/verity.c:ext4_begin_enable_verity
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff814df6a0-ffffffff814df87e: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815787e0)
Location: fs/ext4/inline.c:2028
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/verity.c:ext4_begin_enable_verity
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff815787e0-ffffffff815789c2: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815afd80)
Location: fs/ext4/inline.c:2003
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/verity.c:ext4_begin_enable_verity
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff815afd80-ffffffff815aff62: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815e8b30)
Location: fs/ext4/inline.c:2002
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/verity.c:ext4_begin_enable_verity
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff815e8b30-ffffffff815e8d12: ext4_convert_inline_data (STB_GLOBAL)
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
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffff80001047cb98)
Location: fs/ext4/inline.c:1997
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffff80001047cb98-ffff80001047cd74: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c063e670)
Location: fs/ext4/inline.c:1997
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
c063e670-c063e7dc: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c0000000005a06f0)
Location: fs/ext4/inline.c:1997
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
c0000000005a06f0-c0000000005a0928: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffe000306a74)
Location: fs/ext4/inline.c:1997
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffe000306a74-ffffffe000306b9a: ext4_convert_inline_data (STB_GLOBAL)
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
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a18b0)
Location: fs/ext4/inline.c:1997
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813a18b0-ffffffff813a1a09: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81392340)
Location: fs/ext4/inline.c:1997
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff81392340-ffffffff81392499: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139f110)
Location: fs/ext4/inline.c:1997
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff8139f110-ffffffff8139f269: ext4_convert_inline_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_convert_inline_data(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813b3680)
Location: fs/ext4/inline.c:1997
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/inode.c:ext4_page_mkwrite
  - fs/ext4/inode.c:ext4_punch_hole
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_begin_enable_verity
```
**Symbols:**

```
ffffffff813b3680-ffffffff813b37d9: ext4_convert_inline_data (STB_GLOBAL)
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
