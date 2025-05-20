# Function: <code>inode_reserved_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
qsize_t *inode_reserved_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81270e50)
Location: fs/quota/dquot.c:1562
Inline: True
Direct callers:
  - fs/quota/dquot.c:inode_get_rsv_space
  - fs/quota/dquot.c:inode_add_rsv_space
  - fs/quota/dquot.c:inode_sub_rsv_space
  - fs/quota/dquot.c:inode_claim_rsv_space
  - fs/quota/dquot.c:inode_reclaim_rsv_space
```
**Symbols:**

```
ffffffff81270e50-ffffffff81270e70: inode_reserved_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
qsize_t *inode_reserved_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8129d340)
Location: fs/quota/dquot.c:1570
Inline: True
Direct callers:
  - fs/quota/dquot.c:inode_get_rsv_space
  - fs/quota/dquot.c:inode_sub_rsv_space
  - fs/quota/dquot.c:inode_reclaim_rsv_space
  - fs/quota/dquot.c:inode_claim_rsv_space
  - fs/quota/dquot.c:inode_add_rsv_space
```
**Symbols:**

```
ffffffff8129d340-ffffffff8129d360: inode_reserved_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
qsize_t *inode_reserved_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812b2c80)
Location: fs/quota/dquot.c:1567
Inline: True
Direct callers:
  - fs/quota/dquot.c:inode_get_rsv_space
  - fs/quota/dquot.c:inode_sub_rsv_space
  - fs/quota/dquot.c:inode_reclaim_rsv_space
  - fs/quota/dquot.c:inode_claim_rsv_space
  - fs/quota/dquot.c:inode_add_rsv_space
```
**Symbols:**

```
ffffffff812b2c80-ffffffff812b2ca0: inode_reserved_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
qsize_t *inode_reserved_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812c02e0)
Location: fs/quota/dquot.c:1593
Inline: True
Direct callers:
  - fs/quota/dquot.c:inode_sub_rsv_space
  - fs/quota/dquot.c:inode_reclaim_rsv_space
  - fs/quota/dquot.c:inode_claim_rsv_space
  - fs/quota/dquot.c:inode_add_rsv_space
```
**Symbols:**

```
ffffffff812c02e0-ffffffff812c0300: inode_reserved_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
qsize_t *inode_reserved_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812e3c90)
Location: fs/quota/dquot.c:1602
Inline: True
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffffffff812e3c90-ffffffff812e3cb3: inode_reserved_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
qsize_t *inode_reserved_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81310380)
Location: fs/quota/dquot.c:1599
Inline: True
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffffffff81310380-ffffffff813103a3: inode_reserved_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
qsize_t *inode_reserved_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81327310)
Location: fs/quota/dquot.c:1599
Inline: True
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffffffff81327310-ffffffff81327333: inode_reserved_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
qsize_t *inode_reserved_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8134eeb0)
Location: fs/quota/dquot.c:1609
Inline: True
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffffffff8134eeb0-ffffffff8134eed3: inode_reserved_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
qsize_t *inode_reserved_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813671c0)
Location: fs/quota/dquot.c:1611
Inline: True
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffffffff813671c0-ffffffff813671e3: inode_reserved_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813b23c4)
Location: fs/quota/dquot.c:1609
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c39a4)
Location: fs/quota/dquot.c:1610
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813ca66b)
Location: fs/quota/dquot.c:1608
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8141b13c)
Location: fs/quota/dquot.c:1613
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff814939a0)
Location: fs/quota/dquot.c:1623
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8152766f)
Location: fs/quota/dquot.c:1623
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8155fb50)
Location: fs/quota/dquot.c:1681
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81596240)
Location: fs/quota/dquot.c:1635
Inline: True
Inline callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
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
qsize_t *inode_reserved_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffff80001042e828)
Location: fs/quota/dquot.c:1611
Inline: True
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffff80001042e828-ffff80001042e868: inode_reserved_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
qsize_t *inode_reserved_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c05f8c08)
Location: fs/quota/dquot.c:1611
Inline: True
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
c05f8c08-c05f8c3c: inode_reserved_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
qsize_t *inode_reserved_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c0000000005401e0)
Location: fs/quota/dquot.c:1611
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
c0000000005401e0-c000000000540234: inode_reserved_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
qsize_t *inode_reserved_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffe0002cb236)
Location: fs/quota/dquot.c:1611
Inline: True
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffffffe0002cb236-ffffffe0002cb264: inode_reserved_space (STB_LOCAL)
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
qsize_t *inode_reserved_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8135f7a0)
Location: fs/quota/dquot.c:1611
Inline: True
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffffffff8135f7a0-ffffffff8135f7c3: inode_reserved_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
qsize_t *inode_reserved_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81350440)
Location: fs/quota/dquot.c:1611
Inline: True
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffffffff81350440-ffffffff81350463: inode_reserved_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
qsize_t *inode_reserved_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8135d270)
Location: fs/quota/dquot.c:1611
Inline: True
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffffffff8135d270-ffffffff8135d293: inode_reserved_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
qsize_t *inode_reserved_space(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81371210)
Location: fs/quota/dquot.c:1611
Inline: True
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_reclaim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:dquot_claim_space_nodirty
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
```
**Symbols:**

```
ffffffff81371210-ffffffff81371233: inode_reserved_space (STB_LOCAL)
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
