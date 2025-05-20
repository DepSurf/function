# Function: <code>inode_add_lru</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff81227ab0)
Location: fs/inode.c:405
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81227ab0-ffffffff81227ae5: inode_add_lru.part.18 (STB_LOCAL)
ffffffff81228bf0-ffffffff81228c18: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff812500d0)
Location: fs/inode.c:413
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff812500d0-ffffffff81250105: inode_add_lru.part.16 (STB_LOCAL)
ffffffff812512f0-ffffffff81251318: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/inode.c (ffffffff81263170)
Location: fs/inode.c:415
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81263170-ffffffff812631a5: inode_add_lru.part.19 (STB_LOCAL)
ffffffff812643f0-ffffffff81264418: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81271184)
Location: fs/inode.c:415
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81271da0-ffffffff81271dd3: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81293ab0)
Location: fs/inode.c:415
Inline: True
Direct callers:
  - fs/fs-writeback.c:inode_sync_complete
```
**Symbols:**

```
ffffffff812946c0-ffffffff812946f3: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b9e32)
Location: fs/inode.c:421
Inline: True
Direct callers:
  - fs/fs-writeback.c:inode_sync_complete
```
**Symbols:**

```
ffffffff812ba7d0-ffffffff812ba802: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ceda2)
Location: fs/inode.c:421
Inline: True
Direct callers:
  - fs/fs-writeback.c:inode_sync_complete
```
**Symbols:**

```
ffffffff812cfb10-ffffffff812cfb42: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ebca5)
Location: fs/inode.c:434
Inline: True
Direct callers:
  - fs/fs-writeback.c:inode_sync_complete
```
**Symbols:**

```
ffffffff812eca60-ffffffff812eca92: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fd7f2)
Location: fs/inode.c:438
Inline: True
Direct callers:
  - fs/fs-writeback.c:inode_sync_complete
```
**Symbols:**

```
ffffffff812fe5b0-ffffffff812fe5e2: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81336830)
Location: fs/inode.c:439
Inline: True
Direct callers:
  - fs/inode.c:iput_final
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81336830-ffffffff81336893: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81342190)
Location: fs/inode.c:440
Inline: True
Direct callers:
  - fs/inode.c:iput_final
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81342190-ffffffff813421f3: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81348590)
Location: fs/inode.c:440
Inline: True
Direct callers:
  - fs/inode.c:iput_final
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81348590-ffffffff813485f3: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81396260)
Location: fs/inode.c:444
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81396260-ffffffff813962c3: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81418ec0)
Location: fs/inode.c:477
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:clear_shadow_entry
  - mm/vmscan.c:__remove_mapping
  - mm/workingset.c:shadow_lru_isolate
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff81418ec0-ffffffff81418f4e: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a47e0)
Location: fs/inode.c:476
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:clear_shadow_entry
  - mm/vmscan.c:__remove_mapping
  - mm/workingset.c:shadow_lru_isolate
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff814a47e0-ffffffff814a486e: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d9970)
Location: fs/inode.c:476
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:clear_shadow_entry
  - mm/vmscan.c:__remove_mapping
  - mm/workingset.c:shadow_lru_isolate
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff814d9970-ffffffff814d99fe: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8150c120)
Location: fs/inode.c:477
Inline: False
Direct callers:
  - mm/filemap.c:delete_from_page_cache_batch
  - mm/filemap.c:filemap_remove_folio
  - mm/truncate.c:invalidate_inode_pages2_range
  - mm/truncate.c:clear_shadow_entry
  - mm/vmscan.c:__remove_mapping
  - mm/workingset.c:shadow_lru_isolate
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffff8150c120-ffffffff8150c1ae: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ae2a8)
Location: fs/inode.c:438
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffff8000103af390-ffff8000103af3e4: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058e440)
Location: fs/inode.c:438
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
c058f1b4-c058f1fc: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a932c)
Location: fs/inode.c:438
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
c0000000004aae00-c0000000004aae3c: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000272bb4)
Location: fs/inode.c:438
Inline: True
Direct callers:
  - fs/fs-writeback.c:writeback_sb_inodes
  - fs/fs-writeback.c:writeback_single_inode
```
**Symbols:**

```
ffffffe000273e4c-ffffffe000273e98: inode_add_lru (STB_GLOBAL)
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
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f5dd2)
Location: fs/inode.c:438
Inline: True
Direct callers:
  - fs/fs-writeback.c:inode_sync_complete
```
**Symbols:**

```
ffffffff812f6b90-ffffffff812f6bc2: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e69f2)
Location: fs/inode.c:438
Inline: True
Direct callers:
  - fs/fs-writeback.c:inode_sync_complete
```
**Symbols:**

```
ffffffff812e77b0-ffffffff812e77e2: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f3be2)
Location: fs/inode.c:438
Inline: True
Direct callers:
  - fs/fs-writeback.c:inode_sync_complete
```
**Symbols:**

```
ffffffff812f49a0-ffffffff812f49d2: inode_add_lru (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void inode_add_lru(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8130501a)
Location: fs/inode.c:438
Inline: True
Direct callers:
  - fs/fs-writeback.c:inode_sync_complete
```
**Symbols:**

```
ffffffff81305b40-ffffffff81305b72: inode_add_lru (STB_GLOBAL)
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
