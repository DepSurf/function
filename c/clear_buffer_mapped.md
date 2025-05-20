# Function: <code>clear_buffer_mapped</code>

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
In fs/mpage.c (ffffffff8124e0f1)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff812e926d)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff812eb127)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff81276a1e)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff81316e5d)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff81318b83)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff8128a71f)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff8132ce51)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff8132eb7a)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff812976d5)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff8134201a)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff81343b6c)
Location: include/linux/buffer_head.h:122
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff812ba95a)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff8136664a)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813681bf)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff812e33e7)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff81394db1)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813969f2)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff812f809b)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff813adb21)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813af75b)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff813186e0)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff813d7e64)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813d9ca9)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff8132b53e)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff813f1f34)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813f3d47)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff813651d4)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff8143f268)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff81441187)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff8137213a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff8145b4c8)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff8145d388)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff81378243)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff81460e08)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff81462cb1)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff813c4a22)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff814b62eb)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff814b81a7)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff8144b86e)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff8153fbda)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff81541c2e)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff814d9f62)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff815de74a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff815e087a)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff8150dd3b)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff816161ae)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff81618182)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff81542971)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff8164efcb)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (ffffffff816510bb)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffff8000103e6ae8)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffff8000104cc428)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffff8000104cf35c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (c05be544)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (c068fbdc)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (c0692038)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (c0000000004ecf40)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (c0000000006057f8)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
```
```
In fs/jbd2/commit.c (c00000000060802c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffe00029bd42)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffe000344fb4)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffe000346dcc)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff81323b1e)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff813ea514)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813ec327)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff813146be)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff813daf94)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813dcda7)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff813215ee)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff813e7894)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813e96a7)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
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
In fs/mpage.c (ffffffff81333342)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/mpage.c:do_mpage_readpage
  - fs/mpage.c:do_mpage_readpage
```
```
In fs/jbd2/transaction.c (ffffffff813fd05b)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
```
```
In fs/jbd2/commit.c (ffffffff813fef9d)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
</details>
</li>
</ul>

## Differences
