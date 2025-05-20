# Function: <code>ecryptfs_write_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff81304140)
Location: fs/ecryptfs/mmap.c:278
Inline: False
```
**Symbols:**

```
ffffffff81304140-ffffffff8130446d: ecryptfs_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff81338170)
Location: fs/ecryptfs/mmap.c:277
Inline: False
```
**Symbols:**

```
ffffffff81338170-ffffffff81338521: ecryptfs_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff8134df40)
Location: fs/ecryptfs/mmap.c:278
Inline: False
```
**Symbols:**

```
ffffffff8134df40-ffffffff8134e2eb: ecryptfs_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff81362b10)
Location: fs/ecryptfs/mmap.c:278
Inline: False
```
**Symbols:**

```
ffffffff81362b10-ffffffff81362e64: ecryptfs_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff81387770)
Location: fs/ecryptfs/mmap.c:278
Inline: False
```
**Symbols:**

```
ffffffff81387770-ffffffff81387b04: ecryptfs_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:278
Inline: False
```
**Symbols:**

```
ffffffff813b6550-ffffffff813b67cc: ecryptfs_write_begin (STB_LOCAL)
ffffffff813b6c7c-ffffffff813b6d9e: ecryptfs_write_begin.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:278
Inline: False
```
**Symbols:**

```
ffffffff813cfaa0-ffffffff813cfd1c: ecryptfs_write_begin (STB_LOCAL)
ffffffff813d01cc-ffffffff813d02ee: ecryptfs_write_begin.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:264
Inline: False
```
**Symbols:**

```
ffffffff813fa690-ffffffff813fa90b: ecryptfs_write_begin (STB_LOCAL)
ffffffff813fadc1-ffffffff813faeed: ecryptfs_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:264
Inline: False
```
**Symbols:**

```
ffffffff81414560-ffffffff814147db: ecryptfs_write_begin (STB_LOCAL)
ffffffff81414c91-ffffffff81414dbd: ecryptfs_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:264
Inline: False
```
**Symbols:**

```
ffffffff81462890-ffffffff81462b0d: ecryptfs_write_begin (STB_LOCAL)
ffffffff81462f2c-ffffffff81463058: ecryptfs_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:264
Inline: False
```
**Symbols:**

```
ffffffff8147e2e0-ffffffff8147e609: ecryptfs_write_begin (STB_LOCAL)
ffffffff81bee428-ffffffff81bee543: ecryptfs_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:265
Inline: False
```
**Symbols:**

```
ffffffff81483dc0-ffffffff814840dd: ecryptfs_write_begin (STB_LOCAL)
ffffffff81be0488-ffffffff81be059f: ecryptfs_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:265
Inline: False
```
**Symbols:**

```
ffffffff814db480-ffffffff814db655: ecryptfs_write_begin (STB_LOCAL)
ffffffff81cd0be9-ffffffff81cd0d0f: ecryptfs_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:266
Inline: False
```
**Symbols:**

```
ffffffff815690f0-ffffffff815692f2: ecryptfs_write_begin (STB_LOCAL)
ffffffff81e83e4e-ffffffff81e83f9e: ecryptfs_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff8160cac0)
Location: fs/ecryptfs/mmap.c:266
Inline: False
```
**Symbols:**

```
ffffffff8160cac0-ffffffff8160ce79: ecryptfs_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff81644910)
Location: fs/ecryptfs/mmap.c:266
Inline: False
```
**Symbols:**

```
ffffffff81644910-ffffffff81644d27: ecryptfs_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffff8167de40)
Location: fs/ecryptfs/mmap.c:265
Inline: False
```
**Symbols:**

```
ffffffff8167de40-ffffffff8167e24b: ecryptfs_write_begin (STB_LOCAL)
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
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffff8000104f5b70)
Location: fs/ecryptfs/mmap.c:264
Inline: False
```
**Symbols:**

```
ffff8000104f5b70-ffff8000104f5ec0: ecryptfs_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (c06b3314)
Location: fs/ecryptfs/mmap.c:264
Inline: False
```
**Symbols:**

```
c06b3314-c06b3738: ecryptfs_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (c000000000636810)
Location: fs/ecryptfs/mmap.c:264
Inline: False
```
**Symbols:**

```
c000000000636810-c000000000636cb8: ecryptfs_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/mmap.c (ffffffe0003649f4)
Location: fs/ecryptfs/mmap.c:264
Inline: False
```
**Symbols:**

```
ffffffe0003649f4-ffffffe000364cde: ecryptfs_write_begin (STB_LOCAL)
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
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:264
Inline: False
```
**Symbols:**

```
ffffffff8140cb40-ffffffff8140cdbb: ecryptfs_write_begin (STB_LOCAL)
ffffffff8140d271-ffffffff8140d39d: ecryptfs_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:264
Inline: False
```
**Symbols:**

```
ffffffff813fd5c0-ffffffff813fd83b: ecryptfs_write_begin (STB_LOCAL)
ffffffff813fdcf1-ffffffff813fde1d: ecryptfs_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:264
Inline: False
```
**Symbols:**

```
ffffffff81409ec0-ffffffff8140a13b: ecryptfs_write_begin (STB_LOCAL)
ffffffff8140a5f1-ffffffff8140a71d: ecryptfs_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/mmap.c (0)
Location: fs/ecryptfs/mmap.c:264
Inline: False
```
**Symbols:**

```
ffffffff8141fb90-ffffffff8141fe37: ecryptfs_write_begin (STB_LOCAL)
ffffffff814202f0-ffffffff8142040e: ecryptfs_write_begin.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>file, mapping, pos, len, flags, pagep, fsdata</code> ➡️ <code>file, mapping, pos, len, pagep, fsdata</code>
</li>
</ul>
</details>
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
