# Function: <code>ext4_write_inline_data_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812e0f80)
Location: fs/ext4/inline.c:716
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
**Symbols:**

```
ffffffff812e0f80-ffffffff812e10f5: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81310d80)
Location: fs/ext4/inline.c:717
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
**Symbols:**

```
ffffffff81310d80-ffffffff81310f05: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81326c20)
Location: fs/ext4/inline.c:728
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
**Symbols:**

```
ffffffff81326c20-ffffffff81326dcd: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff812fab40)
Location: fs/ext4/inline.c:731
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff812fab40-ffffffff812faccc: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8131f230)
Location: fs/ext4/inline.c:722
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8131f230-ffffffff8131f3bc: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8134d300)
Location: fs/ext4/inline.c:726
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8134d300-ffffffff8134d496: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81365490)
Location: fs/ext4/inline.c:729
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff81365490-ffffffff81365626: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8138e7d0)
Location: fs/ext4/inline.c:729
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8138e7d0-ffffffff8138e96a: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a7230)
Location: fs/ext4/inline.c:729
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff813a7230-ffffffff813a73ca: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813f33d0)
Location: fs/ext4/inline.c:729
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff813f33d0-ffffffff813f356a: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81405b60)
Location: fs/ext4/inline.c:729
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff81405b60-ffffffff81405cfa: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8140be90)
Location: fs/ext4/inline.c:729
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8140be90-ffffffff8140c031: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8145ea70)
Location: fs/ext4/inline.c:734
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8145ea70-ffffffff8145ef3b: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff814dd1a0)
Location: fs/ext4/inline.c:737
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff814dd1a0-ffffffff814dd725: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815761d0)
Location: fs/ext4/inline.c:736
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff815761d0-ffffffff81576750: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815adad0)
Location: fs/ext4/inline.c:743
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff815adad0-ffffffff815ade86: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct folio *folio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff815e6890)
Location: fs/ext4/inline.c:742
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff815e6890-ffffffff815e6c46: ext4_write_inline_data_end (STB_GLOBAL)
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
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffff80001047aa00)
Location: fs/ext4/inline.c:729
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffff80001047aa00-ffff80001047ac24: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c063c3f4)
Location: fs/ext4/inline.c:729
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
c063c3f4-c063c5a4: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c00000000059da40)
Location: fs/ext4/inline.c:729
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
c00000000059da40-c00000000059dcd0: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffe0003051e0)
Location: fs/ext4/inline.c:729
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffe0003051e0-ffffffe00030534c: ext4_write_inline_data_end (STB_GLOBAL)
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
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139f810)
Location: fs/ext4/inline.c:729
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8139f810-ffffffff8139f9aa: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813902a0)
Location: fs/ext4/inline.c:729
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff813902a0-ffffffff8139043a: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139d070)
Location: fs/ext4/inline.c:729
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff8139d070-ffffffff8139d20a: ext4_write_inline_data_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_write_inline_data_end(struct inode *inode, loff_t pos, unsigned int len, unsigned int copied, struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813b15a0)
Location: fs/ext4/inline.c:729
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
**Symbols:**

```
ffffffff813b15a0-ffffffff813b1758: ext4_write_inline_data_end (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct folio *folio</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *page</code>
</li>
</ul>
</details>
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
