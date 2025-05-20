# Function: <code>squashfs_readpage</code>

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
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff81322630)
Location: fs/squashfs/file.c:453
Inline: False
```
**Symbols:**

```
ffffffff81322630-ffffffff81322e47: squashfs_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff813384c0)
Location: fs/squashfs/file.c:453
Inline: False
```
**Symbols:**

```
ffffffff813384c0-ffffffff81338cd4: squashfs_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff8134d160)
Location: fs/squashfs/file.c:453
Inline: False
```
**Symbols:**

```
ffffffff8134d160-ffffffff8134d9b3: squashfs_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffff81371810)
Location: fs/squashfs/file.c:453
Inline: False
```
**Symbols:**

```
ffffffff81371810-ffffffff81372063: squashfs_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:460
Inline: False
```
**Symbols:**

```
ffffffff813a00b0-ffffffff813a08cb: squashfs_readpage (STB_LOCAL)
ffffffff813a0906-ffffffff813a094a: squashfs_readpage.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:460
Inline: False
```
**Symbols:**

```
ffffffff813b8e30-ffffffff813b964d: squashfs_readpage (STB_LOCAL)
ffffffff813b9688-ffffffff813b96cc: squashfs_readpage.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:447
Inline: False
```
**Symbols:**

```
ffffffff813e3c60-ffffffff813e3ef2: squashfs_readpage (STB_LOCAL)
ffffffff813e3f5a-ffffffff813e3f73: squashfs_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:447
Inline: False
```
**Symbols:**

```
ffffffff813fdc90-ffffffff813fdf43: squashfs_readpage (STB_LOCAL)
ffffffff813fdfab-ffffffff813fdfc4: squashfs_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:447
Inline: False
```
**Symbols:**

```
ffffffff8144b6f0-ffffffff8144b900: squashfs_readpage (STB_LOCAL)
ffffffff8144b954-ffffffff8144b96d: squashfs_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:447
Inline: False
```
**Symbols:**

```
ffffffff81467dd0-ffffffff81467fe0: squashfs_readpage (STB_LOCAL)
ffffffff81bed4a6-ffffffff81bed4bf: squashfs_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:447
Inline: False
```
**Symbols:**

```
ffffffff8146d3d0-ffffffff8146d690: squashfs_readpage (STB_LOCAL)
ffffffff81bdf58a-ffffffff81bdf5a3: squashfs_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:447
Inline: False
```
**Symbols:**

```
ffffffff814c3c50-ffffffff814c3f1f: squashfs_readpage (STB_LOCAL)
ffffffff81ccf01a-ffffffff81ccf082: squashfs_readpage.cold (STB_LOCAL)
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
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffff8000104dbd48)
Location: fs/squashfs/file.c:447
Inline: False
```
**Symbols:**

```
ffff8000104dbd48-ffff8000104dc024: squashfs_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (c069d4c0)
Location: fs/squashfs/file.c:447
Inline: False
```
**Symbols:**

```
c069d4c0-c069d92c: squashfs_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (c000000000616fd0)
Location: fs/squashfs/file.c:447
Inline: False
```
**Symbols:**

```
c000000000616fd0-c000000000617390: squashfs_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file.c (ffffffe0003509d8)
Location: fs/squashfs/file.c:447
Inline: False
```
**Symbols:**

```
ffffffe0003509d8-ffffffe000350c80: squashfs_readpage (STB_LOCAL)
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
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:447
Inline: False
```
**Symbols:**

```
ffffffff813f6270-ffffffff813f6523: squashfs_readpage (STB_LOCAL)
ffffffff813f658b-ffffffff813f65a4: squashfs_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:447
Inline: False
```
**Symbols:**

```
ffffffff813e6cf0-ffffffff813e6fa3: squashfs_readpage (STB_LOCAL)
ffffffff813e700b-ffffffff813e7024: squashfs_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:447
Inline: False
```
**Symbols:**

```
ffffffff813f35f0-ffffffff813f38a3: squashfs_readpage (STB_LOCAL)
ffffffff813f390b-ffffffff813f3924: squashfs_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file.c (0)
Location: fs/squashfs/file.c:447
Inline: False
```
**Symbols:**

```
ffffffff81409200-ffffffff814094d1: squashfs_readpage (STB_LOCAL)
ffffffff81409539-ffffffff81409552: squashfs_readpage.cold (STB_LOCAL)
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
