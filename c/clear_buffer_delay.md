# Function: <code>clear_buffer_delay</code>

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
In fs/buffer.c (ffffffff81246be9)
Location: include/linux/buffer_head.h:126
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81296b01)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
```
In fs/jbd2/transaction.c (ffffffff812e927c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
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
In fs/buffer.c (ffffffff8126d2e6)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff812c4143)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
```
In fs/jbd2/transaction.c (ffffffff81316e6c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
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
In fs/buffer.c (ffffffff81280544)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff812d97f3)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
```
In fs/jbd2/transaction.c (ffffffff8132ce60)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
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
In fs/buffer.c (ffffffff8128dcfa)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff812fd70d)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
```
In fs/jbd2/transaction.c (ffffffff81342029)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
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
In fs/buffer.c (ffffffff812b08ed)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff81321f2a)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
```
In fs/jbd2/transaction.c (ffffffff81366659)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
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
In fs/buffer.c (ffffffff812d86f6)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff8134ff50)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
```
In fs/jbd2/transaction.c (ffffffff81394dc0)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
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
In fs/buffer.c (ffffffff812edbc6)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff81368143)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
```
In fs/jbd2/transaction.c (ffffffff813adb30)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
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
In fs/buffer.c (ffffffff8130f3a2)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff813916e2)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
```
In fs/jbd2/transaction.c (ffffffff813d7e76)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
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
In fs/buffer.c (ffffffff81322302)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff813aa072)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
```
In fs/jbd2/transaction.c (ffffffff813f1f46)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
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
In fs/buffer.c (ffffffff8135c54b)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff813f5fad)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page
```
```
In fs/jbd2/transaction.c (ffffffff8143f274)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
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
In fs/buffer.c (ffffffff8136a9c0)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff8140890d)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page
```
```
In fs/jbd2/transaction.c (ffffffff8145b4d4)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
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
In fs/buffer.c (ffffffff813700d4)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff8140e941)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
```
In fs/jbd2/transaction.c (ffffffff81460e14)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
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
In fs/buffer.c (ffffffff813bec62)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff814617b8)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page
```
```
In fs/jbd2/transaction.c (ffffffff814b62f7)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
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
In fs/buffer.c (ffffffff814473e5)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff814e03bb)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page
```
```
In fs/jbd2/transaction.c (ffffffff8153fbec)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
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
In fs/buffer.c (ffffffff814d601e)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff8157969b)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_page
```
```
In fs/jbd2/transaction.c (ffffffff815de75c)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
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
In fs/buffer.c (ffffffff8150b47c)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/ext4/inode.c (ffffffff815b147f)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_folio
```
```
In fs/jbd2/transaction.c (ffffffff816161c0)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
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
In fs/buffer.c (ffffffff815402aa)
Location: include/linux/buffer_head.h:131
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/ext4/inode.c (ffffffff815ea2af)
Location: include/linux/buffer_head.h:131
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_process_folio
```
```
In fs/jbd2/transaction.c (ffffffff8164efdd)
Location: include/linux/buffer_head.h:131
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
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
In fs/buffer.c (ffff8000103db088)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffff80001047e368)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
```
In fs/jbd2/transaction.c (ffff8000104cc458)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
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
In fs/buffer.c (c05b4498)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (c0645fa4)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_extent
```
```
In fs/jbd2/transaction.c (c068fc00)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
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
In fs/buffer.c (c0000000004e037c)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (c0000000005a1628)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
```
In fs/jbd2/transaction.c (c000000000605834)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
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
In fs/buffer.c (ffffffe000293af0)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffe0003077ce)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
```
In fs/jbd2/transaction.c (ffffffe000344fca)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
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
In fs/buffer.c (ffffffff8131a8e2)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff813a2652)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
```
In fs/jbd2/transaction.c (ffffffff813ea526)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
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
In fs/buffer.c (ffffffff8130b482)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff813930e2)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
```
In fs/jbd2/transaction.c (ffffffff813dafa6)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
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
In fs/buffer.c (ffffffff813183b2)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff8139feb2)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
```
In fs/jbd2/transaction.c (ffffffff813e78a6)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
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
In fs/buffer.c (ffffffff81329fd2)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
```
```
In fs/ext4/inode.c (ffffffff813b4b92)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/inode.c:mpage_map_and_submit_buffers
```
```
In fs/jbd2/transaction.c (ffffffff813fd06a)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
</details>
</li>
</ul>

## Differences
