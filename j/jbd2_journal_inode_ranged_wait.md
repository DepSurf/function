# Function: <code>jbd2_journal_inode_ranged_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_wait(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d82d0)
Location: fs/jbd2/transaction.c:2642
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813d82d0-ffffffff813d82ed: jbd2_journal_inode_ranged_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_wait(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813f2350)
Location: fs/jbd2/transaction.c:2639
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813f2350-ffffffff813f236d: jbd2_journal_inode_ranged_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_wait(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8143f6d0)
Location: fs/jbd2/transaction.c:2707
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8143f6d0-ffffffff8143f6ed: jbd2_journal_inode_ranged_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_wait(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8145b930)
Location: fs/jbd2/transaction.c:2705
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8145b930-ffffffff8145b94d: jbd2_journal_inode_ranged_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_wait(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81461270)
Location: fs/jbd2/transaction.c:2710
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81461270-ffffffff8146128d: jbd2_journal_inode_ranged_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_wait(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff814b6760)
Location: fs/jbd2/transaction.c:2710
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff814b6760-ffffffff814b677d: jbd2_journal_inode_ranged_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_wait(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81540170)
Location: fs/jbd2/transaction.c:2728
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81540170-ffffffff8154019c: jbd2_journal_inode_ranged_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_wait(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff815deca0)
Location: fs/jbd2/transaction.c:2736
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff815deca0-ffffffff815deccc: jbd2_journal_inode_ranged_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_wait(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81616700)
Location: fs/jbd2/transaction.c:2715
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff81616700-ffffffff8161672c: jbd2_journal_inode_ranged_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_wait(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8164f520)
Location: fs/jbd2/transaction.c:2725
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff8164f520-ffffffff8164f54c: jbd2_journal_inode_ranged_wait (STB_GLOBAL)
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
int jbd2_journal_inode_ranged_wait(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffff8000104ccb68)
Location: fs/jbd2/transaction.c:2639
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffff8000104ccb68-ffff8000104ccbbc: jbd2_journal_inode_ranged_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_wait(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c069041c)
Location: fs/jbd2/transaction.c:2639
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
c069041c-c0690464: jbd2_journal_inode_ranged_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_wait(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c000000000606260)
Location: fs/jbd2/transaction.c:2639
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
c000000000606260-c000000000606288: jbd2_journal_inode_ranged_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_wait(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffe000345478)
Location: fs/jbd2/transaction.c:2639
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffe000345478-ffffffe0003454c0: jbd2_journal_inode_ranged_wait (STB_GLOBAL)
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
int jbd2_journal_inode_ranged_wait(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813ea930)
Location: fs/jbd2/transaction.c:2639
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813ea930-ffffffff813ea94d: jbd2_journal_inode_ranged_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_wait(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813db3b0)
Location: fs/jbd2/transaction.c:2639
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813db3b0-ffffffff813db3cd: jbd2_journal_inode_ranged_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_wait(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e7cb0)
Location: fs/jbd2/transaction.c:2639
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813e7cb0-ffffffff813e7ccd: jbd2_journal_inode_ranged_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int jbd2_journal_inode_ranged_wait(handle_t *handle, struct jbd2_inode *jinode, loff_t start_byte, loff_t length);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813fd4d0)
Location: fs/jbd2/transaction.c:2639
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_map_blocks
```
**Symbols:**

```
ffffffff813fd4d0-ffffffff813fd4ed: jbd2_journal_inode_ranged_wait (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
