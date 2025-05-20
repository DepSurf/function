# Function: <code>generic_write_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81244600)
Location: fs/buffer.c:2090
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff81244600-ffffffff812446ae: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126c2c0)
Location: fs/buffer.c:2146
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff8126c2c0-ffffffff8126c39a: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127f610)
Location: fs/buffer.c:2187
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff8127f610-ffffffff8127f6ea: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128d6a0)
Location: fs/buffer.c:2184
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff8128d6a0-ffffffff8128d74e: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812b01f0)
Location: fs/buffer.c:2144
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff812b01f0-ffffffff812b02cb: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d7ab0)
Location: fs/buffer.c:2115
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff812d7ab0-ffffffff812d7b99: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ed670)
Location: fs/buffer.c:2158
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/iomap.c:iomap_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff812ed670-ffffffff812ed6aa: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130ec40)
Location: fs/buffer.c:2125
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff8130ec40-ffffffff8130ed27: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81321c60)
Location: fs/buffer.c:2125
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff81321c60-ffffffff81321d47: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135ce80)
Location: fs/buffer.c:2169
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff8135ce80-ffffffff8135cfdc: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81369020)
Location: fs/buffer.c:2168
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff81369020-ffffffff81369179: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136f560)
Location: fs/buffer.c:2189
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff8136f560-ffffffff8136f6bc: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813be3b0)
Location: fs/buffer.c:2168
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff813be3b0-ffffffff813be509: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81446f30)
Location: fs/buffer.c:2165
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff81446f30-ffffffff814470e4: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff814d5d20)
Location: fs/buffer.c:2150
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff814d5d20-ffffffff814d5ed4: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8150a8e0)
Location: fs/buffer.c:2286
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff8150a8e0-ffffffff8150aa0d: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8153f430)
Location: fs/buffer.c:2257
Inline: False
Direct callers:
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff8153f430-ffffffff8153f55a: generic_write_end (STB_GLOBAL)
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
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d97f0)
Location: fs/buffer.c:2125
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffff8000103d97f0-ffff8000103d9938: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b3c7c)
Location: fs/buffer.c:2125
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
c05b3c7c-c05b3dc4: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004df920)
Location: fs/buffer.c:2125
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
c0000000004df920-c0000000004dfac8: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000293426)
Location: fs/buffer.c:2125
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffe000293426-ffffffe00029350a: generic_write_end (STB_GLOBAL)
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
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8131a240)
Location: fs/buffer.c:2125
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff8131a240-ffffffff8131a327: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130ade0)
Location: fs/buffer.c:2125
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff8130ade0-ffffffff8130aec7: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81317d10)
Location: fs/buffer.c:2125
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff81317d10-ffffffff81317df7: generic_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int generic_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81329920)
Location: fs/buffer.c:2125
Inline: False
Direct callers:
  - fs/buffer.c:nobh_write_end
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/fat/inode.c:fat_write_end
```
**Symbols:**

```
ffffffff81329920-ffffffff81329a07: generic_write_end (STB_GLOBAL)
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
