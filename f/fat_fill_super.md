# Function: <code>fat_fill_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff812fccf0)
Location: fs/fat/inode.c:1486
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff812fccf0-ffffffff812fdaed: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff813309b0)
Location: fs/fat/inode.c:1576
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff813309b0-ffffffff813317ef: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81346700)
Location: fs/fat/inode.c:1586
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff81346700-ffffffff81347581: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8135b110)
Location: fs/fat/inode.c:1586
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff8135b110-ffffffff8135bfb7: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8137fe10)
Location: fs/fat/inode.c:1586
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff8137fe10-ffffffff81380cba: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1608
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff813afdbb-ffffffff813b0086: fat_fill_super.cold.30 (STB_LOCAL)
ffffffff813ae690-ffffffff813af2c2: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1600
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff813c9208-ffffffff813c94cb: fat_fill_super.cold.33 (STB_LOCAL)
ffffffff813c7880-ffffffff813c8497: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1595
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff813f3d7f-ffffffff813f406e: fat_fill_super.cold (STB_LOCAL)
ffffffff813f2440-ffffffff813f3047: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1597
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff8140dc5f-ffffffff8140df40: fat_fill_super.cold (STB_LOCAL)
ffffffff8140c340-ffffffff8140cf2b: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1603
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff8145bb63-ffffffff8145bd1f: fat_fill_super.cold (STB_LOCAL)
ffffffff8145a3f0-ffffffff8145ac5c: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1602
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff81bedaaa-ffffffff81bedc66: fat_fill_super.cold (STB_LOCAL)
ffffffff81476740-ffffffff81476fa9: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1602
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff81bdfbb1-ffffffff81bdfd70: fat_fill_super.cold (STB_LOCAL)
ffffffff8147c1b0-ffffffff8147ca19: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1603
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff81cd0149-ffffffff81cd0308: fat_fill_super.cold (STB_LOCAL)
ffffffff814d38b0-ffffffff814d4130: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1604
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff81e833d4-ffffffff81e83592: fat_fill_super.cold (STB_LOCAL)
ffffffff81560aa0-ffffffff81561380: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff81602d60)
Location: fs/fat/inode.c:1599
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff81602d60-ffffffff816038bd: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff8163ac80)
Location: fs/fat/inode.c:1599
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff8163ac80-ffffffff8163b7da: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffff816741b0)
Location: fs/fat/inode.c:1607
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff816741b0-ffffffff81674d39: fat_fill_super (STB_GLOBAL)
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
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffff8000104ed200)
Location: fs/fat/inode.c:1597
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffff8000104ed200-ffff8000104ede3c: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c06aad80)
Location: fs/fat/inode.c:1597
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
c06aad80-c06abbc4: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (c00000000062bd50)
Location: fs/fat/inode.c:1597
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
c00000000062bd50-c00000000062cc2c: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/inode.c (ffffffe00035d63c)
Location: fs/fat/inode.c:1597
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffe00035d63c-ffffffe00035e2e4: fat_fill_super (STB_GLOBAL)
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
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1597
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff8140623f-ffffffff81406520: fat_fill_super.cold (STB_LOCAL)
ffffffff81404920-ffffffff8140550b: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1597
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff813f6cbf-ffffffff813f6fa0: fat_fill_super.cold (STB_LOCAL)
ffffffff813f53a0-ffffffff813f5f8b: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1597
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff814035bf-ffffffff814038a0: fat_fill_super.cold (STB_LOCAL)
ffffffff81401ca0-ffffffff8140288b: fat_fill_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fat_fill_super(struct super_block *sb, void *data, int silent, int isvfat, void (*setup)(struct super_block *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/inode.c (0)
Location: fs/fat/inode.c:1597
Inline: False
Direct callers:
  - fs/fat/namei_vfat.c:vfat_fill_super
```
**Symbols:**

```
ffffffff8141926f-ffffffff81419550: fat_fill_super.cold (STB_LOCAL)
ffffffff81417c70-ffffffff8141885b: fat_fill_super (STB_GLOBAL)
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
