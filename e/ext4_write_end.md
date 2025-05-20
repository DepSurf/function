# Function: <code>ext4_write_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8129dc20)
Location: fs/ext4/inode.c:1138
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff8129dc20-ffffffff8129df70: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812cc0d0)
Location: fs/ext4/inode.c:1304
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff812cc0d0-ffffffff812cc44f: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812e1e90)
Location: fs/ext4/inode.c:1318
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff812e1e90-ffffffff812e2255: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813061e0)
Location: fs/ext4/inode.c:1371
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff813061e0-ffffffff8130652f: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8132ad40)
Location: fs/ext4/inode.c:1381
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff8132ad40-ffffffff8132b0f5: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81359260)
Location: fs/ext4/inode.c:1382
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff81359260-ffffffff8135962c: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81371580)
Location: fs/ext4/inode.c:1382
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff81371580-ffffffff8137194c: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8139aab0)
Location: fs/ext4/inode.c:1398
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff8139aab0-ffffffff8139aebf: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b3570)
Location: fs/ext4/inode.c:1410
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff813b3570-ffffffff813b3971: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813fe850)
Location: fs/ext4/inode.c:1259
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff813fe850-ffffffff813fec83: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81411070)
Location: fs/ext4/inode.c:1276
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff81411070-ffffffff81411466: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81417430)
Location: fs/ext4/inode.c:1275
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff81417430-ffffffff8141783e: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8146a7f0)
Location: fs/ext4/inode.c:1278
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff8146a7f0-ffffffff8146aba9: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814ea7e0)
Location: fs/ext4/inode.c:1291
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff814ea7e0-ffffffff814eabf7: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81584330)
Location: fs/ext4/inode.c:1304
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff81584330-ffffffff81584776: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815bac70)
Location: fs/ext4/inode.c:1257
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff815bac70-ffffffff815bb085: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815f39e0)
Location: fs/ext4/inode.c:1269
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff815f39e0-ffffffff815f3df2: ext4_write_end (STB_LOCAL)
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
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010487dd0)
Location: fs/ext4/inode.c:1410
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffff800010487dd0-ffff8000104881e4: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0649f94)
Location: fs/ext4/inode.c:1410
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
c0649f94-c064a458: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005ae4f0)
Location: fs/ext4/inode.c:1410
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
c0000000005ae4f0-c0000000005aea90: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030f9be)
Location: fs/ext4/inode.c:1410
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffe00030f9be-ffffffe00030fcd2: ext4_write_end (STB_LOCAL)
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
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813abb50)
Location: fs/ext4/inode.c:1410
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff813abb50-ffffffff813abf51: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8139c5e0)
Location: fs/ext4/inode.c:1410
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff8139c5e0-ffffffff8139c9e1: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a93b0)
Location: fs/ext4/inode.c:1410
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff813a93b0-ffffffff813a97b1: ext4_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813bdc90)
Location: fs/ext4/inode.c:1410
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
```
**Symbols:**

```
ffffffff813bdc90-ffffffff813be0aa: ext4_write_end (STB_LOCAL)
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
