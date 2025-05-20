# Function: <code>iomap_zero_range_actor</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8129c660)
Location: fs/iomap.c:282
Inline: True
```
**Symbols:**

```
ffffffff8129c660-ffffffff8129c89e: iomap_zero_range_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812b1380)
Location: fs/iomap.c:365
Inline: True
```
**Symbols:**

```
ffffffff812b1380-ffffffff812b15b8: iomap_zero_range_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812be830)
Location: fs/iomap.c:361
Inline: True
```
**Symbols:**

```
ffffffff812be830-ffffffff812be9dd: iomap_zero_range_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812e2200)
Location: fs/iomap.c:361
Inline: True
```
**Symbols:**

```
ffffffff812e2200-ffffffff812e23a8: iomap_zero_range_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130eb60)
Location: fs/iomap.c:368
Inline: True
```
**Symbols:**

```
ffffffff8130eb60-ffffffff8130ed08: iomap_zero_range_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff813255b0)
Location: fs/iomap.c:997
Inline: True
```
**Symbols:**

```
ffffffff813255b0-ffffffff8132575b: iomap_zero_range_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134c750)
Location: fs/iomap/buffered-io.c:944
Inline: True
```
**Symbols:**

```
ffffffff8134c750-ffffffff8134c907: iomap_zero_range_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81364a20)
Location: fs/iomap/buffered-io.c:944
Inline: True
```
**Symbols:**

```
ffffffff81364a20-ffffffff81364bd7: iomap_zero_range_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813ac660)
Location: fs/iomap/buffered-io.c:948
Inline: True
```
**Symbols:**

```
ffffffff813ac7f0-ffffffff813ac814: iomap_zero_range_actor (STB_LOCAL)
ffffffff813ac660-ffffffff813ac7ec: iomap_zero_range_actor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bdc20)
Location: fs/iomap/buffered-io.c:921
Inline: True
```
**Symbols:**

```
ffffffff813bdd60-ffffffff813bdd84: iomap_zero_range_actor (STB_LOCAL)
ffffffff813bdc20-ffffffff813bdd58: iomap_zero_range_actor.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c4df0)
Location: fs/iomap/buffered-io.c:921
Inline: True
```
**Symbols:**

```
ffffffff813c4df0-ffffffff813c4f4f: iomap_zero_range_actor (STB_LOCAL)
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
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042b8d8)
Location: fs/iomap/buffered-io.c:944
Inline: True
```
**Symbols:**

```
ffff80001042b8d8-ffff80001042babc: iomap_zero_range_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f48f0)
Location: fs/iomap/buffered-io.c:944
Inline: True
```
**Symbols:**

```
c05f48f0-c05f4ad0: iomap_zero_range_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053cac0)
Location: fs/iomap/buffered-io.c:944
Inline: True
```
**Symbols:**

```
c00000000053cac0-c00000000053cd90: iomap_zero_range_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c9120)
Location: fs/iomap/buffered-io.c:944
Inline: True
```
**Symbols:**

```
ffffffe0002c9120-ffffffe0002c92d0: iomap_zero_range_actor (STB_LOCAL)
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
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135d000)
Location: fs/iomap/buffered-io.c:944
Inline: True
```
**Symbols:**

```
ffffffff8135d000-ffffffff8135d1b7: iomap_zero_range_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134dca0)
Location: fs/iomap/buffered-io.c:944
Inline: True
```
**Symbols:**

```
ffffffff8134dca0-ffffffff8134de57: iomap_zero_range_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135aad0)
Location: fs/iomap/buffered-io.c:944
Inline: True
```
**Symbols:**

```
ffffffff8135aad0-ffffffff8135ac87: iomap_zero_range_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_zero_range_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136e240)
Location: fs/iomap/buffered-io.c:944
Inline: True
```
**Symbols:**

```
ffffffff8136e240-ffffffff8136e40e: iomap_zero_range_actor (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>loff_t length</code>
</li>
<li>
<b>Param removed. </b>
<code>loff_t count</code>
</li>
</ul>
</details>
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
