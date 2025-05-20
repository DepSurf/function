# Function: <code>iomap_dio_actor</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
loff_t iomap_dio_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812b0c20)
Location: fs/iomap.c:735
Inline: False
```
**Symbols:**

```
ffffffff812b0c20-ffffffff812b0fdd: iomap_dio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
loff_t iomap_dio_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812be020)
Location: fs/iomap.c:824
Inline: False
```
**Symbols:**

```
ffffffff812be020-ffffffff812be394: iomap_dio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
loff_t iomap_dio_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812e1920)
Location: fs/iomap.c:848
Inline: False
```
**Symbols:**

```
ffffffff812e1920-ffffffff812e1ce0: iomap_dio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
loff_t iomap_dio_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130e030)
Location: fs/iomap.c:966
Inline: False
```
**Symbols:**

```
ffffffff8130e030-ffffffff8130e463: iomap_dio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
loff_t iomap_dio_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff813240e0)
Location: fs/iomap.c:1773
Inline: False
```
**Symbols:**

```
ffffffff813240e0-ffffffff81324296: iomap_dio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
loff_t iomap_dio_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8134db90)
Location: fs/iomap/direct-io.c:364
Inline: False
```
**Symbols:**

```
ffffffff8134db90-ffffffff8134dd46: iomap_dio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
loff_t iomap_dio_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff81365e50)
Location: fs/iomap/direct-io.c:362
Inline: False
```
**Symbols:**

```
ffffffff81365e50-ffffffff81366034: iomap_dio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
loff_t iomap_dio_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813ad9e0)
Location: fs/iomap/direct-io.c:372
Inline: False
```
**Symbols:**

```
ffffffff813ad9e0-ffffffff813ada55: iomap_dio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
loff_t iomap_dio_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (0)
Location: fs/iomap/direct-io.c:374
Inline: False
```
**Symbols:**

```
ffffffff813bf020-ffffffff813bf0cb: iomap_dio_actor (STB_LOCAL)
ffffffff81bebb4f-ffffffff81bebb7e: iomap_dio_actor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
loff_t iomap_dio_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (0)
Location: fs/iomap/direct-io.c:404
Inline: False
```
**Symbols:**

```
ffffffff813c6160-ffffffff813c620b: iomap_dio_actor (STB_LOCAL)
ffffffff81bddbb2-ffffffff81bddbe1: iomap_dio_actor.cold (STB_LOCAL)
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
loff_t iomap_dio_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffff80001042cce8)
Location: fs/iomap/direct-io.c:362
Inline: False
```
**Symbols:**

```
ffff80001042cce8-ffff80001042cf10: iomap_dio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
loff_t iomap_dio_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (c05f5a44)
Location: fs/iomap/direct-io.c:362
Inline: False
```
**Symbols:**

```
c05f5a44-c05f5d54: iomap_dio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
loff_t iomap_dio_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (c00000000053e4b0)
Location: fs/iomap/direct-io.c:362
Inline: False
```
**Symbols:**

```
c00000000053e4b0-c00000000053e788: iomap_dio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
loff_t iomap_dio_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffe0002ca098)
Location: fs/iomap/direct-io.c:362
Inline: False
```
**Symbols:**

```
ffffffe0002ca098-ffffffe0002ca210: iomap_dio_actor (STB_LOCAL)
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
loff_t iomap_dio_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8135e430)
Location: fs/iomap/direct-io.c:362
Inline: False
```
**Symbols:**

```
ffffffff8135e430-ffffffff8135e614: iomap_dio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
loff_t iomap_dio_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8134f0d0)
Location: fs/iomap/direct-io.c:362
Inline: False
```
**Symbols:**

```
ffffffff8134f0d0-ffffffff8134f2b4: iomap_dio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
loff_t iomap_dio_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8135bf00)
Location: fs/iomap/direct-io.c:362
Inline: False
```
**Symbols:**

```
ffffffff8135bf00-ffffffff8135c0e4: iomap_dio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
loff_t iomap_dio_actor(struct inode *inode, loff_t pos, loff_t length, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8136f650)
Location: fs/iomap/direct-io.c:362
Inline: False
```
**Symbols:**

```
ffffffff8136f650-ffffffff8136f834: iomap_dio_actor (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
