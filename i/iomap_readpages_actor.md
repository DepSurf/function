# Function: <code>iomap_readpages_actor</code>

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
loff_t iomap_readpages_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81324f50)
Location: fs/iomap.c:434
Inline: False
```
**Symbols:**

```
ffffffff81324f50-ffffffff8132515a: iomap_readpages_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
loff_t iomap_readpages_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134bbf0)
Location: fs/iomap/buffered-io.c:353
Inline: False
```
**Symbols:**

```
ffffffff8134bbf0-ffffffff8134be02: iomap_readpages_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
loff_t iomap_readpages_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81363ec0)
Location: fs/iomap/buffered-io.c:353
Inline: False
```
**Symbols:**

```
ffffffff81363ec0-ffffffff813640d2: iomap_readpages_actor (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
loff_t iomap_readpages_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042c218)
Location: fs/iomap/buffered-io.c:353
Inline: False
```
**Symbols:**

```
ffff80001042c218-ffff80001042c414: iomap_readpages_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
loff_t iomap_readpages_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f3b90)
Location: fs/iomap/buffered-io.c:353
Inline: False
```
**Symbols:**

```
c05f3b90-c05f3e0c: iomap_readpages_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
loff_t iomap_readpages_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053b650)
Location: fs/iomap/buffered-io.c:353
Inline: False
```
**Symbols:**

```
c00000000053b650-c00000000053b9a0: iomap_readpages_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
loff_t iomap_readpages_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c85ca)
Location: fs/iomap/buffered-io.c:353
Inline: False
```
**Symbols:**

```
ffffffe0002c85ca-ffffffe0002c875c: iomap_readpages_actor (STB_LOCAL)
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
loff_t iomap_readpages_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135c4a0)
Location: fs/iomap/buffered-io.c:353
Inline: False
```
**Symbols:**

```
ffffffff8135c4a0-ffffffff8135c6b2: iomap_readpages_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
loff_t iomap_readpages_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134d140)
Location: fs/iomap/buffered-io.c:353
Inline: False
```
**Symbols:**

```
ffffffff8134d140-ffffffff8134d352: iomap_readpages_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
loff_t iomap_readpages_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81359f70)
Location: fs/iomap/buffered-io.c:353
Inline: False
```
**Symbols:**

```
ffffffff81359f70-ffffffff8135a182: iomap_readpages_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
loff_t iomap_readpages_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136d6a0)
Location: fs/iomap/buffered-io.c:353
Inline: False
```
**Symbols:**

```
ffffffff8136d6a0-ffffffff8136d8b2: iomap_readpages_actor (STB_LOCAL)
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
