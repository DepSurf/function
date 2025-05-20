# Function: <code>jbd2_journal_file_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff812e96b0)
Location: fs/jbd2/transaction.c:2479
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_block_zero_page_range
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/move_extent.c:move_extent_per_page
```
**Symbols:**

```
ffffffff812e96b0-ffffffff812e97a2: jbd2_journal_file_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81315160)
Location: fs/jbd2/transaction.c:2464
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_add_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_add_write
```
**Symbols:**

```
ffffffff81315160-ffffffff81315278: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8132b160)
Location: fs/jbd2/transaction.c:2469
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_add_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_add_write
```
**Symbols:**

```
ffffffff8132b160-ffffffff8132b278: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81340390)
Location: fs/jbd2/transaction.c:2487
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_add_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_add_write
```
**Symbols:**

```
ffffffff81340390-ffffffff8134049b: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813649a0)
Location: fs/jbd2/transaction.c:2490
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_add_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_add_write
```
**Symbols:**

```
ffffffff813649a0-ffffffff81364aab: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81393110)
Location: fs/jbd2/transaction.c:2493
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_add_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_add_write
```
**Symbols:**

```
ffffffff81393110-ffffffff81393220: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813abe30)
Location: fs/jbd2/transaction.c:2533
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_add_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_add_write
```
**Symbols:**

```
ffffffff813abe30-ffffffff813abf40: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d6080)
Location: fs/jbd2/transaction.c:2567
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write
  - fs/jbd2/transaction.c:jbd2_journal_inode_add_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_add_write
```
**Symbols:**

```
ffffffff813d6080-ffffffff813d61bd: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813f00b0)
Location: fs/jbd2/transaction.c:2576
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write
```
**Symbols:**

```
ffffffff813f00b0-ffffffff813f01ed: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8143d790)
Location: fs/jbd2/transaction.c:2644
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write
```
**Symbols:**

```
ffffffff8143d790-ffffffff8143d8cd: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81459ae0)
Location: fs/jbd2/transaction.c:2642
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write
```
**Symbols:**

```
ffffffff81459ae0-ffffffff81459c1d: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8145f3a0)
Location: fs/jbd2/transaction.c:2647
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write
```
**Symbols:**

```
ffffffff8145f3a0-ffffffff8145f4ca: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff814b4850)
Location: fs/jbd2/transaction.c:2647
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write
```
**Symbols:**

```
ffffffff814b4850-ffffffff814b497d: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8153ce40)
Location: fs/jbd2/transaction.c:2665
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write
```
**Symbols:**

```
ffffffff8153ce40-ffffffff8153cf7a: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff815db610)
Location: fs/jbd2/transaction.c:2673
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write
```
**Symbols:**

```
ffffffff815db610-ffffffff815db74a: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff816130d0)
Location: fs/jbd2/transaction.c:2652
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write
```
**Symbols:**

```
ffffffff816130d0-ffffffff8161320a: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8164bed0)
Location: fs/jbd2/transaction.c:2662
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write
```
**Symbols:**

```
ffffffff8164bed0-ffffffff8164c007: jbd2_journal_file_inode (STB_LOCAL)
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
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffff8000104c8c10)
Location: fs/jbd2/transaction.c:2576
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write
```
**Symbols:**

```
ffff8000104c8c10-ffff8000104c8da8: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c068c594)
Location: fs/jbd2/transaction.c:2576
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write
```
**Symbols:**

```
c068c594-c068c718: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c0000000006013d0)
Location: fs/jbd2/transaction.c:2576
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write
```
**Symbols:**

```
c0000000006013d0-c000000000601620: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffe000342e9a)
Location: fs/jbd2/transaction.c:2576
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write
```
**Symbols:**

```
ffffffe000342e9a-ffffffe000342fd4: jbd2_journal_file_inode (STB_LOCAL)
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
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e8690)
Location: fs/jbd2/transaction.c:2576
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write
```
**Symbols:**

```
ffffffff813e8690-ffffffff813e87cd: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d9110)
Location: fs/jbd2/transaction.c:2576
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write
```
**Symbols:**

```
ffffffff813d9110-ffffffff813d924d: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e5a10)
Location: fs/jbd2/transaction.c:2576
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write
```
**Symbols:**

```
ffffffff813e5a10-ffffffff813e5b4d: jbd2_journal_file_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int jbd2_journal_file_inode(handle_t *handle, struct jbd2_inode *jinode, long unsigned int flags, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813fa280)
Location: fs/jbd2/transaction.c:2576
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_wait
  - fs/jbd2/transaction.c:jbd2_journal_inode_ranged_write
```
**Symbols:**

```
ffffffff813fa280-ffffffff813fa3bb: jbd2_journal_file_inode (STB_LOCAL)
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
<code>long unsigned int flags</code>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>loff_t start_byte</code>
</li>
<li>
<b>Param added. </b>
<code>loff_t end_byte</code>
</li>
</ul>
</details>
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
