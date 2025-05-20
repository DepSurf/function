# Function: <code>ext4_da_update_reserve_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81298890)
Location: fs/ext4/inode.c:326
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff81298890-ffffffff81298a43: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c5a40)
Location: fs/ext4/inode.c:329
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff812c5a40-ffffffff812c5bee: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812db270)
Location: fs/ext4/inode.c:336
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff812db270-ffffffff812db41e: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812ffb30)
Location: fs/ext4/inode.c:342
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff812ffb30-ffffffff812ffcd0: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81324340)
Location: fs/ext4/inode.c:352
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81324340-ffffffff813244e2: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81352580)
Location: fs/ext4/inode.c:353
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_handle_unwritten_extents
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81352580-ffffffff81352711: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136a6a0)
Location: fs/ext4/inode.c:353
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8136a6a0-ffffffff8136a832: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81393ba0)
Location: fs/ext4/inode.c:353
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81393ba0-ffffffff81393d48: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ac540)
Location: fs/ext4/inode.c:362
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813ac540-ffffffff813ac6dc: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f87f0)
Location: fs/ext4/inode.c:344
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813f87f0-ffffffff813f89a5: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140aef0)
Location: fs/ext4/inode.c:355
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8140aef0-ffffffff8140b072: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814110b0)
Location: fs/ext4/inode.c:356
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff814110b0-ffffffff81411232: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:355
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81ccaaab-ffffffff81ccab2b: ext4_da_update_reserve_space.cold (STB_LOCAL)
ffffffff81463eb0-ffffffff81464068: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:354
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81e7d8ac-ffffffff81e7d92c: ext4_da_update_reserve_space.cold (STB_LOCAL)
ffffffff814e33c0-ffffffff814e35ad: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:360
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8206de16-ffffffff8206de96: ext4_da_update_reserve_space.cold (STB_LOCAL)
ffffffff8157c8a0-ffffffff8157ca8d: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:332
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff820edb05-ffffffff820edb85: ext4_da_update_reserve_space.cold (STB_LOCAL)
ffffffff815b3ca0-ffffffff815b3e8d: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:332
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/indirect.c:ext4_ind_map_blocks
```
**Symbols:**

```
ffffffff821cac34-ffffffff821cacb4: ext4_da_update_reserve_space.cold (STB_LOCAL)
ffffffff815ecab0-ffffffff815ecc8e: ext4_da_update_reserve_space (STB_GLOBAL)
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
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010480c68)
Location: fs/ext4/inode.c:362
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffff800010480c68-ffff800010480e74: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0641d30)
Location: fs/ext4/inode.c:362
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
c0641d30-c0641f5c: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a5020)
Location: fs/ext4/inode.c:362
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
c0000000005a5020-c0000000005a52ac: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe000309a20)
Location: fs/ext4/inode.c:362
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffe000309a20-ffffffe000309bc8: ext4_da_update_reserve_space (STB_GLOBAL)
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
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a4b20)
Location: fs/ext4/inode.c:362
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813a4b20-ffffffff813a4cbc: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813955b0)
Location: fs/ext4/inode.c:362
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813955b0-ffffffff8139574c: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a2380)
Location: fs/ext4/inode.c:362
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813a2380-ffffffff813a251c: ext4_da_update_reserve_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_da_update_reserve_space(struct inode *inode, int used, int quota_claim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b6a50)
Location: fs/ext4/inode.c:362
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/extents.c:ext4_ext_map_blocks
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813b6a50-ffffffff813b6bf8: ext4_da_update_reserve_space (STB_GLOBAL)
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
