# Function: <code>ecryptfs_readpage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff81304030)
Location: fs/ecryptfs/mmap.c:194
Inline: False
```
**Symbols:**

```
ffffffff81304030-ffffffff81304136: ecryptfs_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff81338050)
Location: fs/ecryptfs/mmap.c:193
Inline: False
```
**Symbols:**

```
ffffffff81338050-ffffffff8133816b: ecryptfs_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff8134de20)
Location: fs/ecryptfs/mmap.c:194
Inline: False
```
**Symbols:**

```
ffffffff8134de20-ffffffff8134df3b: ecryptfs_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff813629f0)
Location: fs/ecryptfs/mmap.c:194
Inline: False
```
**Symbols:**

```
ffffffff813629f0-ffffffff81362b0b: ecryptfs_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff81387650)
Location: fs/ecryptfs/mmap.c:194
Inline: False
```
**Symbols:**

```
ffffffff81387650-ffffffff8138776b: ecryptfs_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:194
Inline: False
```
**Symbols:**

```
ffffffff813b6450-ffffffff813b6546: ecryptfs_readpage (STB_LOCAL)
ffffffff813b6c4f-ffffffff813b6c7c: ecryptfs_readpage.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:194
Inline: False
```
**Symbols:**

```
ffffffff813cf9a0-ffffffff813cfa96: ecryptfs_readpage (STB_LOCAL)
ffffffff813d019f-ffffffff813d01cc: ecryptfs_readpage.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:180
Inline: False
```
**Symbols:**

```
ffffffff813fa590-ffffffff813fa68e: ecryptfs_readpage (STB_LOCAL)
ffffffff813fad94-ffffffff813fadc1: ecryptfs_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:180
Inline: False
```
**Symbols:**

```
ffffffff81414460-ffffffff8141455e: ecryptfs_readpage (STB_LOCAL)
ffffffff81414c64-ffffffff81414c91: ecryptfs_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:180
Inline: False
```
**Symbols:**

```
ffffffff81462790-ffffffff8146288e: ecryptfs_readpage (STB_LOCAL)
ffffffff81462eff-ffffffff81462f2c: ecryptfs_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:180
Inline: False
```
**Symbols:**

```
ffffffff8147e1e0-ffffffff8147e2de: ecryptfs_readpage (STB_LOCAL)
ffffffff81bee3fb-ffffffff81bee428: ecryptfs_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:181
Inline: False
```
**Symbols:**

```
ffffffff81483cc0-ffffffff81483db6: ecryptfs_readpage (STB_LOCAL)
ffffffff81be045b-ffffffff81be0488: ecryptfs_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:181
Inline: False
```
**Symbols:**

```
ffffffff814db660-ffffffff814db756: ecryptfs_readpage (STB_LOCAL)
ffffffff81cd0d0f-ffffffff81cd0d3c: ecryptfs_readpage.cold (STB_LOCAL)
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
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffff8000104f59e8)
Location: fs/ecryptfs/mmap.c:180
Inline: False
```
**Symbols:**

```
ffff8000104f59e8-ffff8000104f5b6c: ecryptfs_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (c06b31d0)
Location: fs/ecryptfs/mmap.c:180
Inline: False
```
**Symbols:**

```
c06b31d0-c06b3314: ecryptfs_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (c000000000636600)
Location: fs/ecryptfs/mmap.c:180
Inline: False
```
**Symbols:**

```
c000000000636600-c000000000636810: ecryptfs_readpage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffe0003648d6)
Location: fs/ecryptfs/mmap.c:180
Inline: False
```
**Symbols:**

```
ffffffe0003648d6-ffffffe0003649f4: ecryptfs_readpage (STB_LOCAL)
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
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:180
Inline: False
```
**Symbols:**

```
ffffffff8140ca40-ffffffff8140cb3e: ecryptfs_readpage (STB_LOCAL)
ffffffff8140d244-ffffffff8140d271: ecryptfs_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:180
Inline: False
```
**Symbols:**

```
ffffffff813fd4c0-ffffffff813fd5be: ecryptfs_readpage (STB_LOCAL)
ffffffff813fdcc4-ffffffff813fdcf1: ecryptfs_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:180
Inline: False
```
**Symbols:**

```
ffffffff81409dc0-ffffffff81409ebe: ecryptfs_readpage (STB_LOCAL)
ffffffff8140a5c4-ffffffff8140a5f1: ecryptfs_readpage.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_readpage(struct file *file, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:180
Inline: False
```
**Symbols:**

```
ffffffff8141fa90-ffffffff8141fb8e: ecryptfs_readpage (STB_LOCAL)
ffffffff814202c3-ffffffff814202f0: ecryptfs_readpage.cold (STB_LOCAL)
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
