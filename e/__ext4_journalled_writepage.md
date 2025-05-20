# Function: <code>__ext4_journalled_writepage</code>

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
In fs/ext4/inode.c (ffffffff8129ac1d)
Location: fs/ext4/inode.c:1727
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff812c8a61)
Location: fs/ext4/inode.c:1884
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff812de63f)
Location: fs/ext4/inode.c:1913
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff81302773)
Location: fs/ext4/inode.c:1967
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff81327103)
Location: fs/ext4/inode.c:1975
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff813569ce)
Location: fs/ext4/inode.c:1978
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff8136ec64)
Location: fs/ext4/inode.c:2008
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __ext4_journalled_writepage(struct page *page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81398050)
Location: fs/ext4/inode.c:2024
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81398050-ffffffff813984b6: __ext4_journalled_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __ext4_journalled_writepage(struct page *page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b0a90)
Location: fs/ext4/inode.c:2000
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff813b0a90-ffffffff813b0ef6: __ext4_journalled_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ext4_journalled_writepage(struct page *page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813fc6b0)
Location: fs/ext4/inode.c:1850
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff813fc6b0-ffffffff813fcb8c: __ext4_journalled_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ext4_journalled_writepage(struct page *page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140edb0)
Location: fs/ext4/inode.c:1867
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff8140edb0-ffffffff8140f309: __ext4_journalled_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ext4_journalled_writepage(struct page *page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81415130)
Location: fs/ext4/inode.c:1866
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81415130-ffffffff81415689: __ext4_journalled_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ext4_journalled_writepage(struct page *page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814686f0)
Location: fs/ext4/inode.c:1848
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff814686f0-ffffffff81468bc3: __ext4_journalled_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ext4_journalled_writepage(struct page *page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e8290)
Location: fs/ext4/inode.c:1870
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff814e8290-ffffffff814e886a: __ext4_journalled_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ext4_journalled_writepage(struct page *page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81581010)
Location: fs/ext4/inode.c:1890
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81581010-ffffffff815815f0: __ext4_journalled_writepage (STB_LOCAL)
```
</details>
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
int __ext4_journalled_writepage(struct page *page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010485390)
Location: fs/ext4/inode.c:2000
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffff800010485390-ffff800010485844: __ext4_journalled_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ext4_journalled_writepage(struct page *page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0646e90)
Location: fs/ext4/inode.c:2000
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
c0646e90-c06473ec: __ext4_journalled_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __ext4_journalled_writepage(struct page *page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005aaa60)
Location: fs/ext4/inode.c:2000
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
c0000000005aaa60-c0000000005ab14c: __ext4_journalled_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ext4_journalled_writepage(struct page *page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030d6d0)
Location: fs/ext4/inode.c:2000
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffe00030d6d0-ffffffe00030da66: __ext4_journalled_writepage (STB_LOCAL)
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
int __ext4_journalled_writepage(struct page *page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a9070)
Location: fs/ext4/inode.c:2000
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff813a9070-ffffffff813a94d6: __ext4_journalled_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __ext4_journalled_writepage(struct page *page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81399b00)
Location: fs/ext4/inode.c:2000
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81399b00-ffffffff81399f66: __ext4_journalled_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __ext4_journalled_writepage(struct page *page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a68d0)
Location: fs/ext4/inode.c:2000
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff813a68d0-ffffffff813a6d36: __ext4_journalled_writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __ext4_journalled_writepage(struct page *page, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813bb0c0)
Location: fs/ext4/inode.c:2000
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff813bb0c0-ffffffff813bb527: __ext4_journalled_writepage (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
