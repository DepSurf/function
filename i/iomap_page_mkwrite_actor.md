# Function: <code>iomap_page_mkwrite_actor</code>

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
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8129c100)
Location: fs/iomap.c:351
Inline: False
```
**Symbols:**

```
ffffffff8129c100-ffffffff8129c141: iomap_page_mkwrite_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812b0a50)
Location: fs/iomap.c:434
Inline: False
```
**Symbols:**

```
ffffffff812b0a50-ffffffff812b0a8b: iomap_page_mkwrite_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812bddc0)
Location: fs/iomap.c:430
Inline: False
```
**Symbols:**

```
ffffffff812bddc0-ffffffff812bddfb: iomap_page_mkwrite_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812e1690)
Location: fs/iomap.c:430
Inline: False
```
**Symbols:**

```
ffffffff812e1690-ffffffff812e16cb: iomap_page_mkwrite_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130da30)
Location: fs/iomap.c:437
Inline: False
```
**Symbols:**

```
ffffffff8130da30-ffffffff8130da6b: iomap_page_mkwrite_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81324920)
Location: fs/iomap.c:1066
Inline: True
```
**Symbols:**

```
ffffffff81324920-ffffffff81324994: iomap_page_mkwrite_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134bb70)
Location: fs/iomap/buffered-io.c:1013
Inline: True
```
**Symbols:**

```
ffffffff8134bb70-ffffffff8134bbe4: iomap_page_mkwrite_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81363e40)
Location: fs/iomap/buffered-io.c:1013
Inline: True
```
**Symbols:**

```
ffffffff81363e40-ffffffff81363eb4: iomap_page_mkwrite_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813aa8a0)
Location: fs/iomap/buffered-io.c:1018
Inline: True
```
**Symbols:**

```
ffffffff813aa8a0-ffffffff813aa93c: iomap_page_mkwrite_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bd410)
Location: fs/iomap/buffered-io.c:987
Inline: True
```
**Symbols:**

```
ffffffff813bd410-ffffffff813bd484: iomap_page_mkwrite_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c4560)
Location: fs/iomap/buffered-io.c:987
Inline: True
```
**Symbols:**

```
ffffffff813c4560-ffffffff813c45dc: iomap_page_mkwrite_actor (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042a5f0)
Location: fs/iomap/buffered-io.c:1013
Inline: True
```
**Symbols:**

```
ffff80001042a5f0-ffff80001042a6d8: iomap_page_mkwrite_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f2fd8)
Location: fs/iomap/buffered-io.c:1013
Inline: True
```
**Symbols:**

```
c05f2fd8-c05f30c8: iomap_page_mkwrite_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053b550)
Location: fs/iomap/buffered-io.c:1013
Inline: True
```
**Symbols:**

```
c00000000053b550-c00000000053b648: iomap_page_mkwrite_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c8528)
Location: fs/iomap/buffered-io.c:1013
Inline: True
```
**Symbols:**

```
ffffffe0002c8528-ffffffe0002c85ca: iomap_page_mkwrite_actor (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135c420)
Location: fs/iomap/buffered-io.c:1013
Inline: True
```
**Symbols:**

```
ffffffff8135c420-ffffffff8135c494: iomap_page_mkwrite_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134d0c0)
Location: fs/iomap/buffered-io.c:1013
Inline: True
```
**Symbols:**

```
ffffffff8134d0c0-ffffffff8134d134: iomap_page_mkwrite_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81359ef0)
Location: fs/iomap/buffered-io.c:1013
Inline: True
```
**Symbols:**

```
ffffffff81359ef0-ffffffff81359f64: iomap_page_mkwrite_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_page_mkwrite_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136d620)
Location: fs/iomap/buffered-io.c:1013
Inline: True
```
**Symbols:**

```
ffffffff8136d620-ffffffff8136d694: iomap_page_mkwrite_actor (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iomap *srcmap</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
