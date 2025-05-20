# Function: <code>ext4_set_inode_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81299bc0)
Location: fs/ext4/inode.c:4026
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81299bc0-ffffffff81299c27: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c72b0)
Location: fs/ext4/inode.c:4334
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
**Symbols:**

```
ffffffff812c72b0-ffffffff812c7325: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dcdb0)
Location: fs/ext4/inode.c:4463
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
```
**Symbols:**

```
ffffffff812dcdb0-ffffffff812dce8d: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81301640)
Location: fs/ext4/inode.c:4587
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inline.c:ext4_destroy_inline_data_nolock
  - fs/ext4/inline.c:ext4_create_inline_data
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
**Symbols:**

```
ffffffff81301640-ffffffff8130171d: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81325fe0)
Location: fs/ext4/inode.c:4651
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
**Symbols:**

```
ffffffff81325fe0-ffffffff813260d8: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81354390)
Location: fs/ext4/inode.c:4700
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
**Symbols:**

```
ffffffff81354390-ffffffff81354488: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136c600)
Location: fs/ext4/inode.c:4730
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
**Symbols:**

```
ffffffff8136c600-ffffffff8136c6f8: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81395bc0)
Location: fs/ext4/inode.c:4742
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
```
**Symbols:**

```
ffffffff81395bc0-ffffffff81395cc6: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ae590)
Location: fs/ext4/inode.c:4733
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff813ae590-ffffffff813ae6b9: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode, bool init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813fa5b0)
Location: fs/ext4/inode.c:4440
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff813fa5b0-ffffffff813fa70f: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode, bool init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140cc10)
Location: fs/ext4/inode.c:4498
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff8140cc10-ffffffff8140cd6f: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode, bool init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81412d90)
Location: fs/ext4/inode.c:4497
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff81412d90-ffffffff81412eef: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode, bool init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814660c0)
Location: fs/ext4/inode.c:4418
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff814660c0-ffffffff8146621f: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode, bool init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e5b80)
Location: fs/ext4/inode.c:4639
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/crypto.c:ext4_set_context
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff814e5b80-ffffffff814e5cf1: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode, bool init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157f2e0)
Location: fs/ext4/inode.c:4734
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/crypto.c:ext4_set_context
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff8157f2e0-ffffffff8157f451: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode, bool init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b6790)
Location: fs/ext4/inode.c:4519
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/crypto.c:ext4_set_context
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff815b6790-ffffffff815b6901: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode, bool init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815ef530)
Location: fs/ext4/inode.c:4538
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/verity.c:ext4_end_enable_verity
  - fs/ext4/crypto.c:ext4_set_context
  - fs/ext4/crypto.c:ext4_set_context
```
**Symbols:**

```
ffffffff815ef530-ffffffff815ef6a1: ext4_set_inode_flags (STB_GLOBAL)
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
void ext4_set_inode_flags(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010483120)
Location: fs/ext4/inode.c:4733
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffff800010483120-ffff800010483234: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c06444d8)
Location: fs/ext4/inode.c:4733
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
c06444d8-c064453c: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a7ee0)
Location: fs/ext4/inode.c:4733
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
c0000000005a7ee0-c0000000005a8060: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030b82e)
Location: fs/ext4/inode.c:4733
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffe00030b82e-ffffffe00030b950: ext4_set_inode_flags (STB_GLOBAL)
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
void ext4_set_inode_flags(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a6b70)
Location: fs/ext4/inode.c:4733
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff813a6b70-ffffffff813a6c99: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81397600)
Location: fs/ext4/inode.c:4733
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff81397600-ffffffff81397729: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a43d0)
Location: fs/ext4/inode.c:4733
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff813a43d0-ffffffff813a44f9: ext4_set_inode_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_set_inode_flags(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b8ad0)
Location: fs/ext4/inode.c:4733
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/super.c:ext4_set_context
  - fs/ext4/verity.c:ext4_end_enable_verity
```
**Symbols:**

```
ffffffff813b8ad0-ffffffff813b8bf9: ext4_set_inode_flags (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool init</code>
</li>
</ul>
</details>
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
