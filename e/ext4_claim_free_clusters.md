# Function: <code>ext4_claim_free_clusters</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8128f520)
Location: fs/ext4/balloc.c:582
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff8128f520-ffffffff8128f55e: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812bca30)
Location: fs/ext4/balloc.c:585
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff812bca30-ffffffff812bca6e: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812d2080)
Location: fs/ext4/balloc.c:585
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff812d2080-ffffffff812d20be: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff812e36f0)
Location: fs/ext4/balloc.c:585
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff812e36f0-ffffffff812e372e: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813080e0)
Location: fs/ext4/balloc.c:586
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff813080e0-ffffffff8130811e: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81335fe0)
Location: fs/ext4/balloc.c:595
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff81335fe0-ffffffff8133601e: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8134d260)
Location: fs/ext4/balloc.c:595
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff8134d260-ffffffff8134d29e: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81375c60)
Location: fs/ext4/balloc.c:595
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff81375c60-ffffffff81375c9e: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8138ded0)
Location: fs/ext4/balloc.c:603
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff8138ded0-ffffffff8138df0e: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813d93f0)
Location: fs/ext4/balloc.c:605
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff813d93f0-ffffffff813d942e: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813eb080)
Location: fs/ext4/balloc.c:617
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff813eb080-ffffffff813eb0be: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813f15b0)
Location: fs/ext4/balloc.c:617
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff813f15b0-ffffffff813f15ee: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff814435b0)
Location: fs/ext4/balloc.c:617
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff814435b0-ffffffff814435ee: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff814bf3f0)
Location: fs/ext4/balloc.c:618
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff814bf3f0-ffffffff814bf438: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81557340)
Location: fs/ext4/balloc.c:618
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff81557340-ffffffff81557388: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff8158f1c0)
Location: fs/ext4/balloc.c:660
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff8158f1c0-ffffffff8158f208: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff815c7ed0)
Location: fs/ext4/balloc.c:668
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff815c7ed0-ffffffff815c7f18: ext4_claim_free_clusters (STB_GLOBAL)
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
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffff80001045ffe0)
Location: fs/ext4/balloc.c:603
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffff80001045ffe0-ffff800010460048: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c06207e4)
Location: fs/ext4/balloc.c:603
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
c06207e4-c0620850: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (c00000000057c360)
Location: fs/ext4/balloc.c:603
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
c00000000057c360-c00000000057c3d8: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffe0002ef69e)
Location: fs/ext4/balloc.c:603
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffe0002ef69e-ffffffe0002ef6f6: ext4_claim_free_clusters (STB_GLOBAL)
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
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff813864b0)
Location: fs/ext4/balloc.c:603
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff813864b0-ffffffff813864ee: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81376f40)
Location: fs/ext4/balloc.c:603
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff81376f40-ffffffff81376f7e: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81383f80)
Location: fs/ext4/balloc.c:603
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff81383f80-ffffffff81383fbe: ext4_claim_free_clusters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_claim_free_clusters(struct ext4_sb_info *sbi, s64 nclusters, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/balloc.c (ffffffff81397ae0)
Location: fs/ext4/balloc.c:603
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_reserve_space
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff81397ae0-ffffffff81397b1e: ext4_claim_free_clusters (STB_GLOBAL)
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
