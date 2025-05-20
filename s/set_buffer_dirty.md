# Function: <code>set_buffer_dirty</code>

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
In fs/buffer.c (ffffffff8124294d)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/buffer.c:__set_page_dirty_buffers
  - fs/buffer.c:create_empty_buffers
```
```
In fs/jbd2/commit.c (ffffffff812ea60a)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff812ed6c4)
Location: include/linux/buffer_head.h:117
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff812f2da5)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff8126b9fa)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/jbd2/commit.c (ffffffff813181c9)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff8131b0ea)
Location: include/linux/buffer_head.h:117
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff81320775)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff8127eb3a)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/jbd2/commit.c (ffffffff8132e1b6)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff813310ca)
Location: include/linux/buffer_head.h:117
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff81336618)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff8128ca26)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/jbd2/commit.c (ffffffff813433cc)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff8134602a)
Location: include/linux/buffer_head.h:117
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8134b2a8)
Location: include/linux/buffer_head.h:117
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff812aef79)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/jbd2/commit.c (ffffffff81367a11)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff8136a6bc)
Location: include/linux/buffer_head.h:118
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8136f94b)
Location: include/linux/buffer_head.h:118
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff812d743d)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/jbd2/commit.c (ffffffff813960aa)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff81398c26)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8139de4a)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff812ec94d)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/jbd2/commit.c (ffffffff813aee00)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff813b1996)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813b6bba)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff8130e114)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/jbd2/commit.c (ffffffff813d92ed)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff813dbfc4)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813e12a2)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff81321134)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/jbd2/commit.c (ffffffff813f32e6)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff813f6017)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813fb2f2)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff8135ac12)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/jbd2/commit.c (ffffffff81440991)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff81443497)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff81448a5e)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff81368a52)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/ext4/fast_commit.c (ffffffff81454294)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/jbd2/commit.c (ffffffff8145cbbf)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff8145f577)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8146565b)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff8136ff0f)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/ext4/fast_commit.c (ffffffff81459bc4)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/jbd2/commit.c (ffffffff81462258)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff81464de7)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8146adab)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff813bea72)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/ext4/fast_commit.c (ffffffff814adcb4)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/jbd2/commit.c (ffffffff814b774e)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff814ba737)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff814c15bb)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff8144540c)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:block_dirty_folio
```
```
In fs/ext4/fast_commit.c (ffffffff81535ba3)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/jbd2/commit.c (ffffffff815412a0)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff815444da)
Location: include/linux/buffer_head.h:120
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8154bf74)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff814d4c8c)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:block_dirty_folio
```
```
In fs/ext4/page-io.c (ffffffff815a4595)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
```
In fs/ext4/fast_commit.c (ffffffff815d4053)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/jbd2/commit.c (ffffffff815dfd59)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff815e350a)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff815ebd44)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff81509f20)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/buffer.c:folio_create_empty_buffers
  - fs/buffer.c:block_dirty_folio
```
```
In fs/ext4/page-io.c (ffffffff815daed9)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/fast_commit.c (ffffffff8160bc33)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/jbd2/commit.c (ffffffff81617700)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff8161acca)
Location: include/linux/buffer_head.h:124
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff81623824)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff8153ed4d)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:block_dirty_folio
```
```
In fs/ext4/page-io.c (ffffffff816136fd)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
```
In fs/ext4/fast_commit.c (ffffffff816449f3)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_submit_bh
```
```
In fs/jbd2/commit.c (ffffffff8165054c)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff81653bea)
Location: include/linux/buffer_head.h:122
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8165c7a9)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffff8000103d93fc)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/jbd2/commit.c (ffff8000104cec00)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffff8000104d21c8)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/jbd2/journal.c (ffff8000104d88f0)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (c05b216c)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/jbd2/commit.c (c0691500)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (c0694898)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/jbd2/journal.c (c069a7c4)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (c0000000004dbb18)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:attach_nobh_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/jbd2/commit.c (c00000000060758c)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (c00000000060b43c)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/jbd2/journal.c (c000000000613760)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffe00029287c)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/jbd2/commit.c (ffffffe000346564)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffe000349098)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/jbd2/journal.c (ffffffe00034e3c8)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff81319714)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/jbd2/commit.c (ffffffff813eb8c6)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff813ee5f7)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813f38d2)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff8130a2d4)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/jbd2/commit.c (ffffffff813dc346)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff813df077)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813e4352)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff813171e4)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/jbd2/commit.c (ffffffff813e8c46)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff813eb977)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813f0c52)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
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
In fs/buffer.c (ffffffff81328594)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__set_page_dirty_buffers
```
```
In fs/jbd2/commit.c (ffffffff813fe4af)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/revoke.c (ffffffff81401467)
Location: include/linux/buffer_head.h:121
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff81406715)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
</details>
</li>
</ul>

## Differences
