# Function: <code>iomap_dio_bio_actor</code>

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
loff_t iomap_dio_bio_actor(struct inode *inode, loff_t pos, loff_t length, struct iomap_dio *dio, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81323890)
Location: fs/iomap.c:1604
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff81323890-ffffffff81323c75: iomap_dio_bio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
loff_t iomap_dio_bio_actor(struct inode *inode, loff_t pos, loff_t length, struct iomap_dio *dio, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8134d7c0)
Location: fs/iomap/direct-io.c:202
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff8134d7c0-ffffffff8134db88: iomap_dio_bio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
loff_t iomap_dio_bio_actor(struct inode *inode, loff_t pos, loff_t length, struct iomap_dio *dio, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff81365a80)
Location: fs/iomap/direct-io.c:198
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff81365a80-ffffffff81365e46: iomap_dio_bio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
loff_t iomap_dio_bio_actor(struct inode *inode, loff_t pos, loff_t length, struct iomap_dio *dio, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813acf00)
Location: fs/iomap/direct-io.c:203
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff813acf00-ffffffff813ad2c9: iomap_dio_bio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
loff_t iomap_dio_bio_actor(struct inode *inode, loff_t pos, loff_t length, struct iomap_dio *dio, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813be5f0)
Location: fs/iomap/direct-io.c:205
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff813be5f0-ffffffff813be9b6: iomap_dio_bio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
loff_t iomap_dio_bio_actor(struct inode *inode, loff_t pos, loff_t length, struct iomap_dio *dio, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813c5be0)
Location: fs/iomap/direct-io.c:233
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff813c5be0-ffffffff813c6028: iomap_dio_bio_actor (STB_LOCAL)
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
loff_t iomap_dio_bio_actor(struct inode *inode, loff_t pos, loff_t length, struct iomap_dio *dio, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffff80001042c920)
Location: fs/iomap/direct-io.c:198
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
**Symbols:**

```
ffff80001042c920-ffff80001042cce4: iomap_dio_bio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
loff_t iomap_dio_bio_actor(struct inode *inode, loff_t pos, loff_t length, struct iomap_dio *dio, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (c05f551c)
Location: fs/iomap/direct-io.c:198
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
**Symbols:**

```
c05f551c-c05f5a44: iomap_dio_bio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
loff_t iomap_dio_bio_actor(struct inode *inode, loff_t pos, loff_t length, struct iomap_dio *dio, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (c00000000053dfb0)
Location: fs/iomap/direct-io.c:198
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
  - fs/iomap/direct-io.c:iomap_dio_actor
```
**Symbols:**

```
c00000000053dfb0-c00000000053e4b0: iomap_dio_bio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
loff_t iomap_dio_bio_actor(struct inode *inode, loff_t pos, loff_t length, struct iomap_dio *dio, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffe0002c9d20)
Location: fs/iomap/direct-io.c:198
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
**Symbols:**

```
ffffffe0002c9d20-ffffffe0002ca098: iomap_dio_bio_actor (STB_LOCAL)
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
loff_t iomap_dio_bio_actor(struct inode *inode, loff_t pos, loff_t length, struct iomap_dio *dio, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8135e060)
Location: fs/iomap/direct-io.c:198
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff8135e060-ffffffff8135e426: iomap_dio_bio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
loff_t iomap_dio_bio_actor(struct inode *inode, loff_t pos, loff_t length, struct iomap_dio *dio, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8134ed00)
Location: fs/iomap/direct-io.c:198
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff8134ed00-ffffffff8134f0c6: iomap_dio_bio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
loff_t iomap_dio_bio_actor(struct inode *inode, loff_t pos, loff_t length, struct iomap_dio *dio, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8135bb30)
Location: fs/iomap/direct-io.c:198
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff8135bb30-ffffffff8135bef6: iomap_dio_bio_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
loff_t iomap_dio_bio_actor(struct inode *inode, loff_t pos, loff_t length, struct iomap_dio *dio, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8136f280)
Location: fs/iomap/direct-io.c:198
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff8136f280-ffffffff8136f646: iomap_dio_bio_actor (STB_LOCAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
