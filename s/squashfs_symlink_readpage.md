# Function: <code>squashfs_symlink_readpage</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/symlink.c (ffffffff81324800)
Location: fs/squashfs/symlink.c:46
Inline: False
```
**Symbols:**

```
ffffffff81324800-ffffffff81324ae5: squashfs_symlink_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/symlink.c (ffffffff8133a680)
Location: fs/squashfs/symlink.c:46
Inline: False
```
**Symbols:**

```
ffffffff8133a680-ffffffff8133a94a: squashfs_symlink_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/symlink.c (ffffffff8134f380)
Location: fs/squashfs/symlink.c:46
Inline: False
```
**Symbols:**

```
ffffffff8134f380-ffffffff8134f5b2: squashfs_symlink_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/symlink.c (ffffffff81373a30)
Location: fs/squashfs/symlink.c:46
Inline: False
```
**Symbols:**

```
ffffffff81373a30-ffffffff81373c66: squashfs_symlink_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/symlink.c (0)
Location: fs/squashfs/symlink.c:46
Inline: False
```
**Symbols:**

```
ffffffff813a2460-ffffffff813a26c4: squashfs_symlink_readpage (STB_LOCAL)
ffffffff813a26c4-ffffffff813a2711: squashfs_symlink_readpage.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/symlink.c (0)
Location: fs/squashfs/symlink.c:46
Inline: False
```
**Symbols:**

```
ffffffff813bb240-ffffffff813bb4a4: squashfs_symlink_readpage (STB_LOCAL)
ffffffff813bb4a4-ffffffff813bb4f2: squashfs_symlink_readpage.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/symlink.c (0)
Location: fs/squashfs/symlink.c:33
Inline: False
```
**Symbols:**

```
ffffffff813e5af0-ffffffff813e5d4c: squashfs_symlink_readpage (STB_LOCAL)
ffffffff813e5d4c-ffffffff813e5d9e: squashfs_symlink_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/symlink.c (0)
Location: fs/squashfs/symlink.c:33
Inline: False
```
**Symbols:**

```
ffffffff813ffb40-ffffffff813ffd9c: squashfs_symlink_readpage (STB_LOCAL)
ffffffff813ffd9c-ffffffff813ffdfe: squashfs_symlink_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/symlink.c (0)
Location: fs/squashfs/symlink.c:33
Inline: False
```
**Symbols:**

```
ffffffff8144d500-ffffffff8144d75a: squashfs_symlink_readpage (STB_LOCAL)
ffffffff8144d75a-ffffffff8144d7bc: squashfs_symlink_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/symlink.c (0)
Location: fs/squashfs/symlink.c:33
Inline: False
```
**Symbols:**

```
ffffffff81469b40-ffffffff81469d9a: squashfs_symlink_readpage (STB_LOCAL)
ffffffff81bed593-ffffffff81bed5f5: squashfs_symlink_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/symlink.c (0)
Location: fs/squashfs/symlink.c:33
Inline: False
```
**Symbols:**

```
ffffffff8146f240-ffffffff8146f496: squashfs_symlink_readpage (STB_LOCAL)
ffffffff81bdf675-ffffffff81bdf6d7: squashfs_symlink_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/symlink.c (0)
Location: fs/squashfs/symlink.c:33
Inline: False
```
**Symbols:**

```
ffffffff814c5c30-ffffffff814c5e86: squashfs_symlink_readpage (STB_LOCAL)
ffffffff81ccf185-ffffffff81ccf1e7: squashfs_symlink_readpage.cold (STB_LOCAL)
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
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/symlink.c (ffff8000104ddb68)
Location: fs/squashfs/symlink.c:33
Inline: False
```
**Symbols:**

```
ffff8000104ddb68-ffff8000104dddd0: squashfs_symlink_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/symlink.c (c069f768)
Location: fs/squashfs/symlink.c:33
Inline: False
```
**Symbols:**

```
c069f768-c069fa00: squashfs_symlink_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/symlink.c (c0000000006196d0)
Location: fs/squashfs/symlink.c:33
Inline: False
```
**Symbols:**

```
c0000000006196d0-c000000000619a30: squashfs_symlink_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/symlink.c (ffffffe000352628)
Location: fs/squashfs/symlink.c:33
Inline: False
```
**Symbols:**

```
ffffffe000352628-ffffffe000352844: squashfs_symlink_readpage (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/symlink.c (0)
Location: fs/squashfs/symlink.c:33
Inline: False
```
**Symbols:**

```
ffffffff813f8120-ffffffff813f837c: squashfs_symlink_readpage (STB_LOCAL)
ffffffff813f837c-ffffffff813f83de: squashfs_symlink_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/symlink.c (0)
Location: fs/squashfs/symlink.c:33
Inline: False
```
**Symbols:**

```
ffffffff813e8ba0-ffffffff813e8dfc: squashfs_symlink_readpage (STB_LOCAL)
ffffffff813e8dfc-ffffffff813e8e5e: squashfs_symlink_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/symlink.c (0)
Location: fs/squashfs/symlink.c:33
Inline: False
```
**Symbols:**

```
ffffffff813f54a0-ffffffff813f56fc: squashfs_symlink_readpage (STB_LOCAL)
ffffffff813f56fc-ffffffff813f575e: squashfs_symlink_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int squashfs_symlink_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/symlink.c (0)
Location: fs/squashfs/symlink.c:33
Inline: False
```
**Symbols:**

```
ffffffff8140b0d0-ffffffff8140b34a: squashfs_symlink_readpage (STB_LOCAL)
ffffffff8140b34a-ffffffff8140b3ac: squashfs_symlink_readpage.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
