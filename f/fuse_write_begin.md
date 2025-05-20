# Function: <code>fuse_write_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81316e00)
Location: fs/fuse/file.c:1924
Inline: False
```
**Symbols:**

```
ffffffff81316e00-ffffffff81316fa7: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134b090)
Location: fs/fuse/file.c:1937
Inline: False
```
**Symbols:**

```
ffffffff8134b090-ffffffff8134b2a9: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813609a0)
Location: fs/fuse/file.c:1938
Inline: False
```
**Symbols:**

```
ffffffff813609a0-ffffffff81360bb6: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813759d0)
Location: fs/fuse/file.c:1934
Inline: False
```
**Symbols:**

```
ffffffff813759d0-ffffffff81375b93: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8139a120)
Location: fs/fuse/file.c:1942
Inline: False
```
**Symbols:**

```
ffffffff8139a120-ffffffff8139a31c: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813caff0)
Location: fs/fuse/file.c:1943
Inline: False
```
**Symbols:**

```
ffffffff813caff0-ffffffff813cb1ef: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e29d0)
Location: fs/fuse/file.c:1956
Inline: False
```
**Symbols:**

```
ffffffff813e29d0-ffffffff813e2bcf: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:2021
Inline: False
```
**Symbols:**

```
ffffffff8140e6c0-ffffffff8140e8ba: fuse_write_begin (STB_LOCAL)
ffffffff814129d6-ffffffff814129f8: fuse_write_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814275f0)
Location: fs/fuse/file.c:2167
Inline: False
```
**Symbols:**

```
ffffffff814275f0-ffffffff814277f9: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81478110)
Location: fs/fuse/file.c:2184
Inline: False
```
**Symbols:**

```
ffffffff81478110-ffffffff81478343: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81492880)
Location: fs/fuse/file.c:2224
Inline: False
```
**Symbols:**

```
ffffffff81492880-ffffffff81492a09: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814979a0)
Location: fs/fuse/file.c:2235
Inline: False
```
**Symbols:**

```
ffffffff814979a0-ffffffff81497b2c: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814ef5b0)
Location: fs/fuse/file.c:2266
Inline: False
```
**Symbols:**

```
ffffffff814ef5b0-ffffffff814ef736: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8157f230)
Location: fs/fuse/file.c:2289
Inline: False
```
**Symbols:**

```
ffffffff8157f230-ffffffff8157f412: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81624f10)
Location: fs/fuse/file.c:2324
Inline: False
```
**Symbols:**

```
ffffffff81624f10-ffffffff816250f2: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165d2a0)
Location: fs/fuse/file.c:2301
Inline: False
```
**Symbols:**

```
ffffffff8165d2a0-ffffffff8165d48a: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81696ff0)
Location: fs/fuse/file.c:2321
Inline: False
```
**Symbols:**

```
ffffffff81696ff0-ffffffff816971d4: fuse_write_begin (STB_LOCAL)
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
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050c320)
Location: fs/fuse/file.c:2167
Inline: False
```
**Symbols:**

```
ffff80001050c320-ffff80001050c4b8: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c7234)
Location: fs/fuse/file.c:2167
Inline: False
```
**Symbols:**

```
c06c7234-c06c7404: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c000000000651c60)
Location: fs/fuse/file.c:2167
Inline: False
```
**Symbols:**

```
c000000000651c60-c000000000651ea8: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe000376a46)
Location: fs/fuse/file.c:2167
Inline: False
```
**Symbols:**

```
ffffffe000376a46-ffffffe000376ba4: fuse_write_begin (STB_LOCAL)
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
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141fbd0)
Location: fs/fuse/file.c:2167
Inline: False
```
**Symbols:**

```
ffffffff8141fbd0-ffffffff8141fdd9: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81410650)
Location: fs/fuse/file.c:2167
Inline: False
```
**Symbols:**

```
ffffffff81410650-ffffffff81410859: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141bd70)
Location: fs/fuse/file.c:2167
Inline: False
```
**Symbols:**

```
ffffffff8141bd70-ffffffff8141bf79: fuse_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fuse_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81432c00)
Location: fs/fuse/file.c:2167
Inline: False
```
**Symbols:**

```
ffffffff81432c00-ffffffff81432e1a: fuse_write_begin (STB_LOCAL)
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
