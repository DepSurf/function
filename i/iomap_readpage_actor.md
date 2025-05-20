# Function: <code>iomap_readpage_actor</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
loff_t iomap_readpage_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81324620)
Location: fs/iomap.c:292
Inline: False
Direct callers:
  - fs/iomap.c:iomap_readpages_actor
```
**Symbols:**

```
ffffffff81324620-ffffffff81324915: iomap_readpage_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
loff_t iomap_readpage_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134b830)
Location: fs/iomap/buffered-io.c:207
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpages_actor
```
**Symbols:**

```
ffffffff8134b830-ffffffff8134bb62: iomap_readpage_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
loff_t iomap_readpage_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81363b00)
Location: fs/iomap/buffered-io.c:207
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpages_actor
```
**Symbols:**

```
ffffffff81363b00-ffffffff81363e32: iomap_readpage_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
loff_t iomap_readpage_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813aadf0)
Location: fs/iomap/buffered-io.c:245
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readahead_actor
```
**Symbols:**

```
ffffffff813aadf0-ffffffff813ab19c: iomap_readpage_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
loff_t iomap_readpage_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bcc90)
Location: fs/iomap/buffered-io.c:237
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readahead_actor
```
**Symbols:**

```
ffffffff813bcc90-ffffffff813bcf84: iomap_readpage_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
loff_t iomap_readpage_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c3da0)
Location: fs/iomap/buffered-io.c:237
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readahead_actor
```
**Symbols:**

```
ffffffff813c3da0-ffffffff813c40b8: iomap_readpage_actor (STB_LOCAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
loff_t iomap_readpage_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042be80)
Location: fs/iomap/buffered-io.c:207
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpages_actor
```
**Symbols:**

```
ffff80001042be80-ffff80001042c214: iomap_readpage_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
loff_t iomap_readpage_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f370c)
Location: fs/iomap/buffered-io.c:207
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpages_actor
```
**Symbols:**

```
c05f370c-c05f3b90: iomap_readpage_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
loff_t iomap_readpage_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053b120)
Location: fs/iomap/buffered-io.c:207
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpages_actor
```
**Symbols:**

```
c00000000053b120-c00000000053b548: iomap_readpage_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
loff_t iomap_readpage_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c8158)
Location: fs/iomap/buffered-io.c:207
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpages_actor
```
**Symbols:**

```
ffffffe0002c8158-ffffffe0002c846a: iomap_readpage_actor (STB_LOCAL)
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
loff_t iomap_readpage_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135c0e0)
Location: fs/iomap/buffered-io.c:207
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpages_actor
```
**Symbols:**

```
ffffffff8135c0e0-ffffffff8135c412: iomap_readpage_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
loff_t iomap_readpage_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134cd80)
Location: fs/iomap/buffered-io.c:207
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpages_actor
```
**Symbols:**

```
ffffffff8134cd80-ffffffff8134d0b2: iomap_readpage_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
loff_t iomap_readpage_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81359bb0)
Location: fs/iomap/buffered-io.c:207
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpages_actor
```
**Symbols:**

```
ffffffff81359bb0-ffffffff81359ee2: iomap_readpage_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
loff_t iomap_readpage_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136d2c0)
Location: fs/iomap/buffered-io.c:207
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_readpages_actor
```
**Symbols:**

```
ffffffff8136d2c0-ffffffff8136d616: iomap_readpage_actor (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
