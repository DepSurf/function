# Function: <code>iomap_bmap</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130fc90)
Location: fs/iomap.c:1443
Inline: False
```
**Symbols:**

```
ffffffff8130fc90-ffffffff8130fd06: iomap_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81326c20)
Location: fs/iomap.c:2158
Inline: False
```
**Symbols:**

```
ffffffff81326c20-ffffffff81326c97: iomap_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff8134dd50)
Location: fs/iomap/fiemap.c:130
Inline: False
```
**Symbols:**

```
ffffffff8134dd50-ffffffff8134ddc8: iomap_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff81366040)
Location: fs/iomap/fiemap.c:130
Inline: False
```
**Symbols:**

```
ffffffff81366040-ffffffff813660b8: iomap_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff813add20)
Location: fs/iomap/fiemap.c:122
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bmap
```
**Symbols:**

```
ffffffff813add20-ffffffff813addb1: iomap_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff813bf390)
Location: fs/iomap/fiemap.c:122
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bmap
```
**Symbols:**

```
ffffffff813bf390-ffffffff813bf421: iomap_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff813c64d0)
Location: fs/iomap/fiemap.c:122
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bmap
```
**Symbols:**

```
ffffffff813c64d0-ffffffff813c6561: iomap_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/fiemap.c (0)
Location: fs/iomap/fiemap.c:97
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bmap
```
**Symbols:**

```
ffffffff81cc7b56-ffffffff81cc7bc4: iomap_bmap.cold (STB_LOCAL)
ffffffff81416230-ffffffff81416357: iomap_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/fiemap.c (0)
Location: fs/iomap/fiemap.c:98
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bmap
```
**Symbols:**

```
ffffffff81e7a74a-ffffffff81e7a7ba: iomap_bmap.cold (STB_LOCAL)
ffffffff8148daf0-ffffffff8148dc24: iomap_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/fiemap.c (0)
Location: fs/iomap/fiemap.c:98
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bmap
```
**Symbols:**

```
ffffffff8206b6fb-ffffffff8206b76b: iomap_bmap.cold (STB_LOCAL)
ffffffff815212d0-ffffffff81521404: iomap_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/fiemap.c (0)
Location: fs/iomap/fiemap.c:98
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bmap
```
**Symbols:**

```
ffffffff820eb61a-ffffffff820eb68a: iomap_bmap.cold (STB_LOCAL)
ffffffff81559310-ffffffff81559444: iomap_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/fiemap.c (0)
Location: fs/iomap/fiemap.c:98
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_bmap
```
**Symbols:**

```
ffffffff821c8844-ffffffff821c88b4: iomap_bmap.cold (STB_LOCAL)
ffffffff8158faa0-ffffffff8158fbd4: iomap_bmap (STB_GLOBAL)
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
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffff80001042d6f8)
Location: fs/iomap/fiemap.c:130
Inline: False
```
**Symbols:**

```
ffff80001042d6f8-ffff80001042d788: iomap_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (c05f660c)
Location: fs/iomap/fiemap.c:130
Inline: False
```
**Symbols:**

```
c05f660c-c05f66b4: iomap_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (c00000000053e790)
Location: fs/iomap/fiemap.c:130
Inline: False
```
**Symbols:**

```
c00000000053e790-c00000000053e864: iomap_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffe0002ca210)
Location: fs/iomap/fiemap.c:130
Inline: False
```
**Symbols:**

```
ffffffe0002ca210-ffffffe0002ca29c: iomap_bmap (STB_GLOBAL)
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
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff8135e620)
Location: fs/iomap/fiemap.c:130
Inline: False
```
**Symbols:**

```
ffffffff8135e620-ffffffff8135e698: iomap_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff8134f2c0)
Location: fs/iomap/fiemap.c:130
Inline: False
```
**Symbols:**

```
ffffffff8134f2c0-ffffffff8134f338: iomap_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff8135c0f0)
Location: fs/iomap/fiemap.c:130
Inline: False
```
**Symbols:**

```
ffffffff8135c0f0-ffffffff8135c168: iomap_bmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
sector_t iomap_bmap(struct address_space *mapping, sector_t bno, const struct iomap_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/fiemap.c (ffffffff8136f840)
Location: fs/iomap/fiemap.c:130
Inline: False
```
**Symbols:**

```
ffffffff8136f840-ffffffff8136f8b8: iomap_bmap (STB_GLOBAL)
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
