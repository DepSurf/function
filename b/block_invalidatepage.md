# Function: <code>block_invalidatepage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812442a0)
Location: fs/buffer.c:1533
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff812442a0-ffffffff812443c5: block_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8126bf00)
Location: fs/buffer.c:1523
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff8126bf00-ffffffff8126c038: block_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8127f270)
Location: fs/buffer.c:1523
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff8127f270-ffffffff8127f3a8: block_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8128cc80)
Location: fs/buffer.c:1518
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff8128cc80-ffffffff8128cdb7: block_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812af720)
Location: fs/buffer.c:1478
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff812af720-ffffffff812af855: block_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d70e0)
Location: fs/buffer.c:1449
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff812d70e0-ffffffff812d721c: block_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ec580)
Location: fs/buffer.c:1457
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff812ec580-ffffffff812ec6bc: block_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130dcf0)
Location: fs/buffer.c:1458
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff8130dcf0-ffffffff8130de33: block_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81320cf0)
Location: fs/buffer.c:1458
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81320cf0-ffffffff81320e33: block_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8135adf0)
Location: fs/buffer.c:1502
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff8135adf0-ffffffff8135af3f: block_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81368c30)
Location: fs/buffer.c:1501
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81368c30-ffffffff81368d7f: block_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8136f2f0)
Location: fs/buffer.c:1521
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff8136f2f0-ffffffff8136f43f: block_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813bdef0)
Location: fs/buffer.c:1500
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff813bdef0-ffffffff813be03f: block_invalidatepage (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d9b38)
Location: fs/buffer.c:1458
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffff8000103d9b38-ffff8000103d9d64: block_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b2a68)
Location: fs/buffer.c:1458
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
c05b2a68-c05b2c58: block_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004de500)
Location: fs/buffer.c:1458
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_invalidatepage
  - fs/ext4/inode.c:mpage_release_unused_pages
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
c0000000004de500-c0000000004de758: block_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe0002923e0)
Location: fs/buffer.c:1458
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffe0002923e0-ffffffe000292534: block_invalidatepage (STB_GLOBAL)
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
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813192d0)
Location: fs/buffer.c:1458
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff813192d0-ffffffff81319413: block_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81309e90)
Location: fs/buffer.c:1458
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81309e90-ffffffff81309fd3: block_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81316da0)
Location: fs/buffer.c:1458
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81316da0-ffffffff81316ee3: block_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void block_invalidatepage(struct page *page, unsigned int offset, unsigned int length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81328e00)
Location: fs/buffer.c:1458
Inline: False
Direct callers:
  - fs/ext4/inode.c:mpage_release_unused_pages
```
**Symbols:**

```
ffffffff81328e00-ffffffff81328f38: block_invalidatepage (STB_GLOBAL)
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
