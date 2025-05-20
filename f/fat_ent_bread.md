# Function: <code>fat_ent_bread</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff812f96d0)
Location: fs/fat/fatent.c:99
Inline: True
```
**Symbols:**

```
ffffffff812f96d0-ffffffff812f978c: fat_ent_bread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff8132d300)
Location: fs/fat/fatent.c:99
Inline: True
```
**Symbols:**

```
ffffffff8132d300-ffffffff8132d3bc: fat_ent_bread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81343040)
Location: fs/fat/fatent.c:99
Inline: True
```
**Symbols:**

```
ffffffff81343040-ffffffff813430fc: fat_ent_bread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff81357ab0)
Location: fs/fat/fatent.c:99
Inline: True
```
**Symbols:**

```
ffffffff81357ab0-ffffffff81357b55: fat_ent_bread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff8137c4a0)
Location: fs/fat/fatent.c:99
Inline: False
```
**Symbols:**

```
ffffffff8137c4a0-ffffffff8137c54a: fat_ent_bread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:99
Inline: False
```
**Symbols:**

```
ffffffff813aae30-ffffffff813aaebe: fat_ent_bread (STB_LOCAL)
ffffffff813ac1c7-ffffffff813ac1ea: fat_ent_bread.cold.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:100
Inline: False
```
**Symbols:**

```
ffffffff813c3bb0-ffffffff813c3c3e: fat_ent_bread (STB_LOCAL)
ffffffff813c53f6-ffffffff813c5419: fat_ent_bread.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:100
Inline: False
```
**Symbols:**

```
ffffffff813ee470-ffffffff813ee500: fat_ent_bread (STB_LOCAL)
ffffffff813efe94-ffffffff813efed1: fat_ent_bread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (ffffffff81409df2)
Location: fs/fat/fatent.c:100
Inline: True
```
**Symbols:**

```
ffffffff814086a0-ffffffff81408730: fat_ent_bread (STB_LOCAL)
ffffffff81409df2-ffffffff81409e15: fat_ent_bread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:100
Inline: False
```
**Symbols:**

```
ffffffff81456160-ffffffff814561f0: fat_ent_bread (STB_LOCAL)
ffffffff81457a80-ffffffff81457aa3: fat_ent_bread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:100
Inline: False
```
**Symbols:**

```
ffffffff81472520-ffffffff814725b0: fat_ent_bread (STB_LOCAL)
ffffffff81bed82e-ffffffff81bed851: fat_ent_bread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:100
Inline: False
```
**Symbols:**

```
ffffffff81477f30-ffffffff81477fc0: fat_ent_bread (STB_LOCAL)
ffffffff81bdf92e-ffffffff81bdf951: fat_ent_bread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:101
Inline: False
```
**Symbols:**

```
ffffffff814cf0b0-ffffffff814cf140: fat_ent_bread (STB_LOCAL)
ffffffff81ccfb3f-ffffffff81ccfb62: fat_ent_bread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (0)
Location: fs/fat/fatent.c:102
Inline: False
```
**Symbols:**

```
ffffffff8155bba0-ffffffff8155bc60: fat_ent_bread (STB_LOCAL)
ffffffff81e82d67-ffffffff81e82d85: fat_ent_bread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff815fda10)
Location: fs/fat/fatent.c:102
Inline: False
```
**Symbols:**

```
ffffffff815fda10-ffffffff815fdae7: fat_ent_bread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff816359c0)
Location: fs/fat/fatent.c:102
Inline: False
```
**Symbols:**

```
ffffffff816359c0-ffffffff81635a97: fat_ent_bread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffff8166eea0)
Location: fs/fat/fatent.c:102
Inline: False
```
**Symbols:**

```
ffffffff8166eea0-ffffffff8166ef77: fat_ent_bread (STB_LOCAL)
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
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffff8000104e88d8)
Location: fs/fat/fatent.c:100
Inline: False
```
**Symbols:**

```
ffff8000104e88d8-ffff8000104e899c: fat_ent_bread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (c06a6bb8)
Location: fs/fat/fatent.c:100
Inline: True
```
**Symbols:**

```
c06a6bb8-c06a6c98: fat_ent_bread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (c0000000006262d0)
Location: fs/fat/fatent.c:100
Inline: False
```
**Symbols:**

```
c0000000006262d0-c0000000006263cc: fat_ent_bread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/fatent.c (ffffffe000359d1c)
Location: fs/fat/fatent.c:100
Inline: False
```
**Symbols:**

```
ffffffe000359d1c-ffffffe000359db4: fat_ent_bread (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (ffffffff814023d2)
Location: fs/fat/fatent.c:100
Inline: True
```
**Symbols:**

```
ffffffff81400c80-ffffffff81400d10: fat_ent_bread (STB_LOCAL)
ffffffff814023d2-ffffffff814023f5: fat_ent_bread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (ffffffff813f2e52)
Location: fs/fat/fatent.c:100
Inline: True
```
**Symbols:**

```
ffffffff813f1700-ffffffff813f1790: fat_ent_bread (STB_LOCAL)
ffffffff813f2e52-ffffffff813f2e75: fat_ent_bread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (ffffffff813ff752)
Location: fs/fat/fatent.c:100
Inline: True
```
**Symbols:**

```
ffffffff813fe000-ffffffff813fe090: fat_ent_bread (STB_LOCAL)
ffffffff813ff752-ffffffff813ff775: fat_ent_bread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fat_ent_bread(struct super_block *sb, struct fat_entry *fatent, int offset, sector_t blocknr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fat/fatent.c (ffffffff8141537d)
Location: fs/fat/fatent.c:100
Inline: True
```
**Symbols:**

```
ffffffff81413d60-ffffffff81413df0: fat_ent_bread (STB_LOCAL)
ffffffff8141537d-ffffffff814153a0: fat_ent_bread.cold (STB_LOCAL)
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
