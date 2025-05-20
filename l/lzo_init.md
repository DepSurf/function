# Function: <code>lzo_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int lzo_init(struct crypto_tfm *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff813ab950)
Location: crypto/lzo.c:30
Inline: False
```
**Symbols:**

```
ffffffff813ab950-ffffffff813ab99c: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (ffffffff81326370)
Location: fs/squashfs/lzo_wrapper.c:41
Inline: False
```
```
In crypto/lzo.c (ffffffff813eb1b0)
Location: crypto/lzo.c:30
Inline: False
```
**Symbols:**

```
ffffffff81326370-ffffffff81326404: lzo_init (STB_LOCAL)
ffffffff813eb1b0-ffffffff813eb1fc: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (ffffffff8133c120)
Location: fs/squashfs/lzo_wrapper.c:41
Inline: False
```
```
In crypto/lzo.c (ffffffff81404a00)
Location: crypto/lzo.c:44
Inline: False
```
**Symbols:**

```
ffffffff8133c120-ffffffff8133c1b4: lzo_init (STB_LOCAL)
ffffffff81404a00-ffffffff81404a28: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (ffffffff81350c20)
Location: fs/squashfs/lzo_wrapper.c:41
Inline: False
```
```
In crypto/lzo.c (ffffffff81412130)
Location: crypto/lzo.c:42
Inline: False
```
**Symbols:**

```
ffffffff81350c20-ffffffff81350cb4: lzo_init (STB_LOCAL)
ffffffff81412130-ffffffff81412178: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (ffffffff813753e0)
Location: fs/squashfs/lzo_wrapper.c:41
Inline: False
```
```
In crypto/lzo.c (ffffffff8143c8a0)
Location: crypto/lzo.c:42
Inline: False
```
**Symbols:**

```
ffffffff813753e0-ffffffff81375474: lzo_init (STB_LOCAL)
ffffffff8143c8a0-ffffffff8143c8e8: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Transformation ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (0)
Location: fs/squashfs/lzo_wrapper.c:41
Inline: False
```
```
In crypto/lzo.c (ffffffff8146f6e0)
Location: crypto/lzo.c:42
Inline: False
```
**Symbols:**

```
ffffffff813a3dd0-ffffffff813a3e54: lzo_init (STB_LOCAL)
ffffffff813a3e54-ffffffff813a3e74: lzo_init.cold.2 (STB_LOCAL)
ffffffff8146f6e0-ffffffff8146f727: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Transformation ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (0)
Location: fs/squashfs/lzo_wrapper.c:41
Inline: False
```
```
In crypto/lzo.c (ffffffff8148d090)
Location: crypto/lzo.c:42
Inline: False
```
**Symbols:**

```
ffffffff813bcbd0-ffffffff813bcc54: lzo_init (STB_LOCAL)
ffffffff813bcc54-ffffffff813bcc74: lzo_init.cold.1 (STB_LOCAL)
ffffffff8148d090-ffffffff8148d0d7: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (0)
Location: fs/squashfs/lzo_wrapper.c:28
Inline: False
```
```
In crypto/lzo.c (ffffffff814ba780)
Location: crypto/lzo.c:29
Inline: False
```
**Symbols:**

```
ffffffff813e7480-ffffffff813e7508: lzo_init (STB_LOCAL)
ffffffff813e7508-ffffffff813e7528: lzo_init.cold (STB_LOCAL)
ffffffff814ba780-ffffffff814ba7ca: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Transformation ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (0)
Location: fs/squashfs/lzo_wrapper.c:28
Inline: False
```
```
In crypto/lzo.c (ffffffff814d3550)
Location: crypto/lzo.c:29
Inline: False
```
**Symbols:**

```
ffffffff81401500-ffffffff81401588: lzo_init (STB_LOCAL)
ffffffff81401588-ffffffff814015a8: lzo_init.cold (STB_LOCAL)
ffffffff814d3550-ffffffff814d359a: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (0)
Location: fs/squashfs/lzo_wrapper.c:28
Inline: False
```
```
In crypto/lzo.c (ffffffff81532810)
Location: crypto/lzo.c:29
Inline: False
```
**Symbols:**

```
ffffffff8144f090-ffffffff8144f118: lzo_init (STB_LOCAL)
ffffffff8144f118-ffffffff8144f138: lzo_init.cold (STB_LOCAL)
ffffffff81532810-ffffffff81532860: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (0)
Location: fs/squashfs/lzo_wrapper.c:28
Inline: False
```
```
In crypto/lzo.c (ffffffff8154f760)
Location: crypto/lzo.c:29
Inline: False
```
**Symbols:**

```
ffffffff8146b650-ffffffff8146b6d8: lzo_init (STB_LOCAL)
ffffffff81bed651-ffffffff81bed671: lzo_init.cold (STB_LOCAL)
ffffffff8154f760-ffffffff8154f7b0: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (0)
Location: fs/squashfs/lzo_wrapper.c:28
Inline: False
```
```
In crypto/lzo.c (ffffffff81557fd0)
Location: crypto/lzo.c:29
Inline: False
```
**Symbols:**

```
ffffffff81470d10-ffffffff81470d8f: lzo_init (STB_LOCAL)
ffffffff81bdf754-ffffffff81bdf774: lzo_init.cold (STB_LOCAL)
ffffffff81557fd0-ffffffff8155802d: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (0)
Location: fs/squashfs/lzo_wrapper.c:28
Inline: False
```
```
In crypto/lzo.c (ffffffff815b9280)
Location: crypto/lzo.c:29
Inline: False
```
**Symbols:**

```
ffffffff814c7780-ffffffff814c77ff: lzo_init (STB_LOCAL)
ffffffff81ccf283-ffffffff81ccf2a3: lzo_init.cold (STB_LOCAL)
ffffffff815b9280-ffffffff815b92dd: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (0)
Location: fs/squashfs/lzo_wrapper.c:28
Inline: False
```
```
In crypto/lzo.c (ffffffff81662780)
Location: crypto/lzo.c:29
Inline: False
```
**Symbols:**

```
ffffffff81552b80-ffffffff81552c07: lzo_init (STB_LOCAL)
ffffffff81e82330-ffffffff81e82350: lzo_init.cold (STB_LOCAL)
ffffffff81662780-ffffffff816627d7: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (ffffffff815f4160)
Location: fs/squashfs/lzo_wrapper.c:28
Inline: False
```
```
In crypto/lzo.c (ffffffff8171c890)
Location: crypto/lzo.c:29
Inline: False
```
**Symbols:**

```
ffffffff815f4160-ffffffff815f41f8: lzo_init (STB_LOCAL)
ffffffff8171c890-ffffffff8171c8e7: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (ffffffff8162c250)
Location: fs/squashfs/lzo_wrapper.c:28
Inline: False
```
```
In crypto/lzo.c (ffffffff81758030)
Location: crypto/lzo.c:29
Inline: False
```
**Symbols:**

```
ffffffff8162c250-ffffffff8162c2e8: lzo_init (STB_LOCAL)
ffffffff81758030-ffffffff81758087: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (ffffffff81665650)
Location: fs/squashfs/lzo_wrapper.c:28
Inline: False
```
```
In crypto/lzo.c (ffffffff81799f30)
Location: crypto/lzo.c:29
Inline: False
```
**Symbols:**

```
ffffffff81665650-ffffffff81665716: lzo_init (STB_LOCAL)
ffffffff81799f30-ffffffff81799f87: lzo_init (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (ffff8000104df460)
Location: fs/squashfs/lzo_wrapper.c:28
Inline: False
```
```
In crypto/lzo.c (ffff8000105cfdc8)
Location: crypto/lzo.c:29
Inline: False
```
**Symbols:**

```
ffff8000104df460-ffff8000104df4fc: lzo_init (STB_LOCAL)
ffff8000105cfdc8-ffff8000105cfe2c: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (c06a1028)
Location: fs/squashfs/lzo_wrapper.c:28
Inline: False
```
```
In crypto/lzo.c (c077d938)
Location: crypto/lzo.c:29
Inline: False
```
**Symbols:**

```
c06a1028-c06a10bc: lzo_init (STB_LOCAL)
c077d938-c077d988: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (c00000000061b9b0)
Location: fs/squashfs/lzo_wrapper.c:28
Inline: False
```
```
In crypto/lzo.c (c00000000075be70)
Location: crypto/lzo.c:29
Inline: False
```
**Symbols:**

```
c00000000061b9b0-c00000000061ba88: lzo_init (STB_LOCAL)
c00000000075be70-c00000000075bf08: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (ffffffe000353c24)
Location: fs/squashfs/lzo_wrapper.c:28
Inline: False
```
```
In crypto/lzo.c (ffffffe000414bde)
Location: crypto/lzo.c:29
Inline: False
```
**Symbols:**

```
ffffffe000414bde-ffffffe000414c2e: lzo_init (STB_LOCAL)
ffffffe000353c24-ffffffe000353cb6: lzo_init (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Transformation ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (0)
Location: fs/squashfs/lzo_wrapper.c:28
Inline: False
```
```
In crypto/lzo.c (ffffffff814cbb30)
Location: crypto/lzo.c:29
Inline: False
```
**Symbols:**

```
ffffffff813f9ae0-ffffffff813f9b68: lzo_init (STB_LOCAL)
ffffffff813f9b68-ffffffff813f9b88: lzo_init.cold (STB_LOCAL)
ffffffff814cbb30-ffffffff814cbb7a: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Transformation ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (0)
Location: fs/squashfs/lzo_wrapper.c:28
Inline: False
```
```
In crypto/lzo.c (ffffffff814bc550)
Location: crypto/lzo.c:29
Inline: False
```
**Symbols:**

```
ffffffff813ea560-ffffffff813ea5e8: lzo_init (STB_LOCAL)
ffffffff813ea5e8-ffffffff813ea608: lzo_init.cold (STB_LOCAL)
ffffffff814bc550-ffffffff814bc59a: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Transformation ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (0)
Location: fs/squashfs/lzo_wrapper.c:28
Inline: False
```
```
In crypto/lzo.c (ffffffff814c7bc0)
Location: crypto/lzo.c:29
Inline: False
```
**Symbols:**

```
ffffffff813f6e60-ffffffff813f6ee8: lzo_init (STB_LOCAL)
ffffffff813f6ee8-ffffffff813f6f08: lzo_init.cold (STB_LOCAL)
ffffffff814c7bc0-ffffffff814c7c0a: lzo_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Transformation ⚠️</summary>

```c
void *lzo_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/lzo_wrapper.c (0)
Location: fs/squashfs/lzo_wrapper.c:28
Inline: False
```
```
In crypto/lzo.c (ffffffff814e0690)
Location: crypto/lzo.c:29
Inline: False
```
**Symbols:**

```
ffffffff8140caf0-ffffffff8140cb78: lzo_init (STB_LOCAL)
ffffffff8140cb78-ffffffff8140cb98: lzo_init.cold (STB_LOCAL)
ffffffff814e0690-ffffffff814e06da: lzo_init (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct squashfs_sb_info *msblk</code>
</li>
<li>
<b>Param added. </b>
<code>void *buff</code>
</li>
<li>
<b>Param removed. </b>
<code>struct crypto_tfm *tfm</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void *</code>
</li>
</ul>
</details>
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
