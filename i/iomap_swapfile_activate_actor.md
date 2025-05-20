# Function: <code>iomap_swapfile_activate_actor</code>

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
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
loff_t iomap_swapfile_activate_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap.c (0)
Location: fs/iomap.c:1322
Inline: False
```
**Symbols:**

```
ffffffff8130e670-ffffffff8130e75b: iomap_swapfile_activate_actor (STB_LOCAL)
ffffffff8130fd06-ffffffff8130fd66: iomap_swapfile_activate_actor.cold.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
loff_t iomap_swapfile_activate_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap.c (0)
Location: fs/iomap.c:2037
Inline: False
```
**Symbols:**

```
ffffffff81323ea0-ffffffff81323fa3: iomap_swapfile_activate_actor (STB_LOCAL)
ffffffff81326c97-ffffffff81326cf7: iomap_swapfile_activate_actor.cold.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
loff_t iomap_swapfile_activate_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/swapfile.c (0)
Location: fs/iomap/swapfile.c:78
Inline: False
```
**Symbols:**

```
ffffffff8134e720-ffffffff8134e811: iomap_swapfile_activate_actor (STB_LOCAL)
ffffffff8134e811-ffffffff8134e88f: iomap_swapfile_activate_actor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
loff_t iomap_swapfile_activate_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/swapfile.c (0)
Location: fs/iomap/swapfile.c:78
Inline: False
```
**Symbols:**

```
ffffffff81366a10-ffffffff81366b01: iomap_swapfile_activate_actor (STB_LOCAL)
ffffffff81366b01-ffffffff81366b7f: iomap_swapfile_activate_actor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
loff_t iomap_swapfile_activate_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/swapfile.c (0)
Location: fs/iomap/swapfile.c:78
Inline: False
```
**Symbols:**

```
ffffffff813ae570-ffffffff813ae664: iomap_swapfile_activate_actor (STB_LOCAL)
ffffffff813ae664-ffffffff813ae6e2: iomap_swapfile_activate_actor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
loff_t iomap_swapfile_activate_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/swapfile.c (0)
Location: fs/iomap/swapfile.c:78
Inline: False
```
**Symbols:**

```
ffffffff813bfbe0-ffffffff813bfcd4: iomap_swapfile_activate_actor (STB_LOCAL)
ffffffff81bebb94-ffffffff81bebc12: iomap_swapfile_activate_actor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
loff_t iomap_swapfile_activate_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffff813c6a40)
Location: fs/iomap/swapfile.c:91
Inline: True
```
**Symbols:**

```
ffffffff813c6a40-ffffffff813c6b86: iomap_swapfile_activate_actor (STB_LOCAL)
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
loff_t iomap_swapfile_activate_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffff80001042e258)
Location: fs/iomap/swapfile.c:78
Inline: False
```
**Symbols:**

```
ffff80001042e258-ffff80001042e3a8: iomap_swapfile_activate_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
loff_t iomap_swapfile_activate_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (c05f74b4)
Location: fs/iomap/swapfile.c:78
Inline: False
```
**Symbols:**

```
c05f74b4-c05f7634: iomap_swapfile_activate_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
loff_t iomap_swapfile_activate_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (c00000000053f690)
Location: fs/iomap/swapfile.c:78
Inline: False
```
**Symbols:**

```
c00000000053f690-c00000000053f86c: iomap_swapfile_activate_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
loff_t iomap_swapfile_activate_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/swapfile.c (ffffffe0002cab2c)
Location: fs/iomap/swapfile.c:78
Inline: False
```
**Symbols:**

```
ffffffe0002cab2c-ffffffe0002cac36: iomap_swapfile_activate_actor (STB_LOCAL)
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
loff_t iomap_swapfile_activate_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/swapfile.c (0)
Location: fs/iomap/swapfile.c:78
Inline: False
```
**Symbols:**

```
ffffffff8135eff0-ffffffff8135f0e1: iomap_swapfile_activate_actor (STB_LOCAL)
ffffffff8135f0e1-ffffffff8135f15f: iomap_swapfile_activate_actor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
loff_t iomap_swapfile_activate_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/swapfile.c (0)
Location: fs/iomap/swapfile.c:78
Inline: False
```
**Symbols:**

```
ffffffff8134fc90-ffffffff8134fd81: iomap_swapfile_activate_actor (STB_LOCAL)
ffffffff8134fd81-ffffffff8134fdff: iomap_swapfile_activate_actor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
loff_t iomap_swapfile_activate_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/swapfile.c (0)
Location: fs/iomap/swapfile.c:78
Inline: False
```
**Symbols:**

```
ffffffff8135cac0-ffffffff8135cbb1: iomap_swapfile_activate_actor (STB_LOCAL)
ffffffff8135cbb1-ffffffff8135cc2f: iomap_swapfile_activate_actor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
loff_t iomap_swapfile_activate_actor(struct inode *inode, loff_t pos, loff_t count, void *data, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/swapfile.c (0)
Location: fs/iomap/swapfile.c:78
Inline: False
```
**Symbols:**

```
ffffffff81370230-ffffffff81370321: iomap_swapfile_activate_actor (STB_LOCAL)
ffffffff81370321-ffffffff8137039f: iomap_swapfile_activate_actor.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
