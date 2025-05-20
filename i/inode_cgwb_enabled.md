# Function: <code>inode_cgwb_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8119a461)
Location: include/linux/backing-dev.h:265
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff8123aa8b)
Location: include/linux/backing-dev.h:265
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811aed71)
Location: include/linux/backing-dev.h:266
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff8126292b)
Location: include/linux/backing-dev.h:266
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811bf421)
Location: include/linux/backing-dev.h:266
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff81275d7b)
Location: include/linux/backing-dev.h:266
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c723d)
Location: include/linux/backing-dev.h:241
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff81283217)
Location: include/linux/backing-dev.h:241
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811dc04d)
Location: include/linux/backing-dev.h:246
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff812a5d87)
Location: include/linux/backing-dev.h:246
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:247
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff812cd245)
Location: include/linux/backing-dev.h:247
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:247
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff812e2565)
Location: include/linux/backing-dev.h:247
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:248
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff813005b5)
Location: include/linux/backing-dev.h:248
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:254
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff81312bf5)
Location: include/linux/backing-dev.h:254
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:250
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff81349d73)
Location: include/linux/backing-dev.h:250
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:192
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff81356c79)
Location: include/linux/backing-dev.h:192
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:192
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff8135f495)
Location: include/linux/backing-dev.h:192
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:192
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff813abdb5)
Location: include/linux/backing-dev.h:192
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812feb4a)
Location: include/linux/backing-dev.h:170
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff81433015)
Location: include/linux/backing-dev.h:170
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813692c5)
Location: include/linux/backing-dev.h:174
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In fs/fs-writeback.c (ffffffff814c1005)
Location: include/linux/backing-dev.h:174
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8139b465)
Location: include/linux/backing-dev.h:174
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In fs/fs-writeback.c (ffffffff814f62b5)
Location: include/linux/backing-dev.h:174
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813c53d5)
Location: include/linux/backing-dev.h:173
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited_flags
```
```
In fs/fs-writeback.c (ffffffff8152a9f5)
Location: include/linux/backing-dev.h:173
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:254
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffff8000103c84dc)
Location: include/linux/backing-dev.h:254
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:254
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (c05a4d74)
Location: include/linux/backing-dev.h:254
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:254
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (c0000000004c98a8)
Location: include/linux/backing-dev.h:254
Inline: True
Inline callers:
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffe0001df140)
Location: include/linux/backing-dev.h:254
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffe000286b2a)
Location: include/linux/backing-dev.h:254
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:254
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff8130b1d5)
Location: include/linux/backing-dev.h:254
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:254
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff812fbdf5)
Location: include/linux/backing-dev.h:254
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:254
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff81308fc5)
Location: include/linux/backing-dev.h:254
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (0)
Location: include/linux/backing-dev.h:254
Inline: True
Inline callers:
  - mm/page-writeback.c:balance_dirty_pages_ratelimited
```
```
In fs/fs-writeback.c (ffffffff8131acc5)
Location: include/linux/backing-dev.h:254
Inline: True
Inline callers:
  - fs/fs-writeback.c:wbc_attach_and_unlock_inode
  - fs/fs-writeback.c:__inode_attach_wb
```
</details>
</li>
</ul>

## Differences
