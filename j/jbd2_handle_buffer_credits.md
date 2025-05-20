# Function: <code>jbd2_handle_buffer_credits</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int jbd2_handle_buffer_credits(handle_t *handle);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813dcbd1)
Location: include/linux/jbd2.h:1633
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/xattr.c (ffffffff8143a1bf)
Location: include/linux/jbd2.h:1633
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/jbd2/transaction.c (ffffffff8143ed5c)
Location: include/linux/jbd2.h:1633
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
```
**Symbols:**

```
ffffffff813dc1a0-ffffffff813dc1c7: jbd2_handle_buffer_credits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int jbd2_handle_buffer_credits(handle_t *handle);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813ee611)
Location: include/linux/jbd2.h:1768
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/xattr.c (ffffffff81452cda)
Location: include/linux/jbd2.h:1768
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/jbd2/transaction.c (ffffffff8145afbc)
Location: include/linux/jbd2.h:1768
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
```
**Symbols:**

```
ffffffff813edc30-ffffffff813edc57: jbd2_handle_buffer_credits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int jbd2_handle_buffer_credits(handle_t *handle);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813f4bd5)
Location: include/linux/jbd2.h:1777
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/xattr.c (ffffffff8145850a)
Location: include/linux/jbd2.h:1777
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/jbd2/transaction.c (ffffffff814608fc)
Location: include/linux/jbd2.h:1777
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
```
**Symbols:**

```
ffffffff81bde341-ffffffff81bde368: jbd2_handle_buffer_credits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int jbd2_handle_buffer_credits(handle_t *handle);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81446e25)
Location: include/linux/jbd2.h:1816
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/xattr.c (ffffffff814ac60a)
Location: include/linux/jbd2.h:1816
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/jbd2/transaction.c (ffffffff814b5d8c)
Location: include/linux/jbd2.h:1816
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
```
**Symbols:**

```
ffffffff81cc8e09-ffffffff81cc8e30: jbd2_handle_buffer_credits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int jbd2_handle_buffer_credits(handle_t *handle);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff814c311c)
Location: include/linux/jbd2.h:1808
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/xattr.c (ffffffff815345c7)
Location: include/linux/jbd2.h:1808
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/jbd2/transaction.c (ffffffff8153f662)
Location: include/linux/jbd2.h:1808
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
```
**Symbols:**

```
ffffffff814c24a0-ffffffff814c24ce: jbd2_handle_buffer_credits (STB_LOCAL)
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
In fs/ext4/ext4_jbd2.c (ffffffff8155b52d)
Location: include/linux/jbd2.h:1806
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
```
In fs/ext4/xattr.c (ffffffff815d2ae7)
Location: include/linux/jbd2.h:1806
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/jbd2/transaction.c (ffffffff815de082)
Location: include/linux/jbd2.h:1806
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
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
In fs/ext4/ext4_jbd2.c (ffffffff81593348)
Location: include/linux/jbd2.h:1807
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
```
In fs/ext4/xattr.c (ffffffff8160a5fa)
Location: include/linux/jbd2.h:1807
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/jbd2/transaction.c (ffffffff81615b02)
Location: include/linux/jbd2.h:1807
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
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
In fs/ext4/ext4_jbd2.c (ffffffff815cc038)
Location: include/linux/jbd2.h:1820
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
  - fs/ext4/ext4_jbd2.c:__ext4_journal_ensure_credits
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
```
In fs/ext4/xattr.c (ffffffff816433bb)
Location: include/linux/jbd2.h:1820
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
```
In fs/jbd2/transaction.c (ffffffff8164e932)
Location: include/linux/jbd2.h:1820
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_dirty_metadata
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
