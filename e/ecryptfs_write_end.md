# Function: <code>ecryptfs_write_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff81304680)
Location: fs/ecryptfs/mmap.c:478
Inline: False
```
**Symbols:**

```
ffffffff81304680-ffffffff813048ea: ecryptfs_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff81338760)
Location: fs/ecryptfs/mmap.c:479
Inline: False
```
**Symbols:**

```
ffffffff81338760-ffffffff81338a10: ecryptfs_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff8134e500)
Location: fs/ecryptfs/mmap.c:478
Inline: False
```
**Symbols:**

```
ffffffff8134e500-ffffffff8134e7af: ecryptfs_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff81363080)
Location: fs/ecryptfs/mmap.c:478
Inline: False
```
**Symbols:**

```
ffffffff81363080-ffffffff813632cd: ecryptfs_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff81387d10)
Location: fs/ecryptfs/mmap.c:476
Inline: False
```
**Symbols:**

```
ffffffff81387d10-ffffffff81387f91: ecryptfs_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:476
Inline: False
```
**Symbols:**

```
ffffffff813b6990-ffffffff813b6c08: ecryptfs_write_end (STB_LOCAL)
ffffffff813b6de1-ffffffff813b6df4: ecryptfs_write_end.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:476
Inline: False
```
**Symbols:**

```
ffffffff813cfee0-ffffffff813d0158: ecryptfs_write_end (STB_LOCAL)
ffffffff813d0331-ffffffff813d0344: ecryptfs_write_end.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:462
Inline: False
```
**Symbols:**

```
ffffffff813faad0-ffffffff813fad4d: ecryptfs_write_end (STB_LOCAL)
ffffffff813faf33-ffffffff813faf46: ecryptfs_write_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:462
Inline: False
```
**Symbols:**

```
ffffffff814149a0-ffffffff81414c1d: ecryptfs_write_end (STB_LOCAL)
ffffffff81414e03-ffffffff81414e16: ecryptfs_write_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:462
Inline: False
```
**Symbols:**

```
ffffffff81462c10-ffffffff81462e8d: ecryptfs_write_end (STB_LOCAL)
ffffffff81463073-ffffffff81463086: ecryptfs_write_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:462
Inline: False
```
**Symbols:**

```
ffffffff8147e710-ffffffff8147e8d1: ecryptfs_write_end (STB_LOCAL)
ffffffff81bee55e-ffffffff81bee571: ecryptfs_write_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:463
Inline: False
```
**Symbols:**

```
ffffffff814842a0-ffffffff81484465: ecryptfs_write_end (STB_LOCAL)
ffffffff81be05e5-ffffffff81be05f8: ecryptfs_write_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:463
Inline: False
```
**Symbols:**

```
ffffffff814db920-ffffffff814dbae2: ecryptfs_write_end (STB_LOCAL)
ffffffff81cd0d82-ffffffff81cd0d95: ecryptfs_write_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:464
Inline: False
```
**Symbols:**

```
ffffffff81569500-ffffffff81569760: ecryptfs_write_end (STB_LOCAL)
ffffffff81e83fe1-ffffffff81e83ff4: ecryptfs_write_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff8160d0e0)
Location: fs/ecryptfs/mmap.c:464
Inline: False
```
**Symbols:**

```
ffffffff8160d0e0-ffffffff8160d35b: ecryptfs_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff81644fa0)
Location: fs/ecryptfs/mmap.c:464
Inline: False
```
**Symbols:**

```
ffffffff81644fa0-ffffffff8164521b: ecryptfs_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff8167e4d0)
Location: fs/ecryptfs/mmap.c:463
Inline: False
```
**Symbols:**

```
ffffffff8167e4d0-ffffffff8167e745: ecryptfs_write_end (STB_LOCAL)
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
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffff8000104f6140)
Location: fs/ecryptfs/mmap.c:462
Inline: False
```
**Symbols:**

```
ffff8000104f6140-ffff8000104f63a0: ecryptfs_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (c06b3a84)
Location: fs/ecryptfs/mmap.c:462
Inline: False
```
**Symbols:**

```
c06b3a84-c06b3e64: ecryptfs_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (c000000000636fd0)
Location: fs/ecryptfs/mmap.c:462
Inline: False
```
**Symbols:**

```
c000000000636fd0-c000000000637360: ecryptfs_write_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffe000364f5c)
Location: fs/ecryptfs/mmap.c:462
Inline: False
```
**Symbols:**

```
ffffffe000364f5c-ffffffe0003651a4: ecryptfs_write_end (STB_LOCAL)
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
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:462
Inline: False
```
**Symbols:**

```
ffffffff8140cf80-ffffffff8140d1fd: ecryptfs_write_end (STB_LOCAL)
ffffffff8140d3e3-ffffffff8140d3f6: ecryptfs_write_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:462
Inline: False
```
**Symbols:**

```
ffffffff813fda00-ffffffff813fdc7d: ecryptfs_write_end (STB_LOCAL)
ffffffff813fde63-ffffffff813fde76: ecryptfs_write_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:462
Inline: False
```
**Symbols:**

```
ffffffff8140a300-ffffffff8140a57d: ecryptfs_write_end (STB_LOCAL)
ffffffff8140a763-ffffffff8140a776: ecryptfs_write_end.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_end(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int copied, struct page *page, void *fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:462
Inline: False
```
**Symbols:**

```
ffffffff8141fff0-ffffffff8142028b: ecryptfs_write_end (STB_LOCAL)
ffffffff81420454-ffffffff81420467: ecryptfs_write_end.cold (STB_LOCAL)
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
