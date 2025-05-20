# Function: <code>ext4_commit_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812b7f50)
Location: fs/ext4/super.c:4315
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_error
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff812b7f50-ffffffff812b81d5: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812e6c50)
Location: fs/ext4/super.c:4477
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff812e6c50-ffffffff812e6ee0: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812fc800)
Location: fs/ext4/super.c:4602
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff812fc800-ffffffff812fcab7: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81331450)
Location: fs/ext4/super.c:4710
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff81331450-ffffffff8133170c: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81355910)
Location: fs/ext4/super.c:4720
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff81355910-ffffffff81355bbd: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81383ce0)
Location: fs/ext4/super.c:4831
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff81383ce0-ffffffff81383f97: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8139c7c0)
Location: fs/ext4/super.c:4894
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff8139c7c0-ffffffff8139ca7a: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c6a20)
Location: fs/ext4/super.c:4984
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff813c6a20-ffffffff813c6ce1: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813dfde0)
Location: fs/ext4/super.c:5015
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff813dfde0-ffffffff813e00a1: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8142c6a0)
Location: fs/ext4/super.c:5199
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff8142c6a0-ffffffff8142c95d: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814454d0)
Location: fs/ext4/super.c:5559
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_handle_error
```
**Symbols:**

```
ffffffff814454d0-ffffffff814455f5: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144adf0)
Location: fs/ext4/super.c:5605
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_handle_error
```
**Symbols:**

```
ffffffff8144adf0-ffffffff8144af2d: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8149ed00)
Location: fs/ext4/super.c:5460
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_handle_error
```
**Symbols:**

```
ffffffff8149ed00-ffffffff8149ee44: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81525490)
Location: fs/ext4/super.c:5906
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_handle_error
```
**Symbols:**

```
ffffffff81525490-ffffffff815255d3: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c2af0)
Location: fs/ext4/super.c:6058
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_handle_error
```
**Symbols:**

```
ffffffff815c2af0-ffffffff815c2c3a: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815fa250)
Location: fs/ext4/super.c:6145
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:ext4_handle_error
```
**Symbols:**

```
ffffffff815fa250-ffffffff815fa39a: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81632e50)
Location: fs/ext4/super.c:6173
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_freeze
  - fs/ext4/super.c:ext4_freeze
  - fs/ext4/super.c:ext4_freeze
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:update_super_work
  - fs/ext4/super.c:ext4_handle_error
```
**Symbols:**

```
ffffffff81632e50-ffffffff81632f9a: ext4_commit_super (STB_LOCAL)
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
int ext4_commit_super(struct super_block *sb, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104b8e30)
Location: fs/ext4/super.c:5015
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffff8000104b8e30-ffff8000104b9184: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067c46c)
Location: fs/ext4/super.c:5015
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_clear_journal_err
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
c067c46c-c067c7e0: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005edf00)
Location: fs/ext4/super.c:5015
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
c0000000005edf00-c0000000005ee320: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000335774)
Location: fs/ext4/super.c:5015
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffe000335774-ffffffe000335a00: ext4_commit_super (STB_LOCAL)
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
int ext4_commit_super(struct super_block *sb, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d83c0)
Location: fs/ext4/super.c:5015
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff813d83c0-ffffffff813d8681: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c8e40)
Location: fs/ext4/super.c:5015
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff813c8e40-ffffffff813c9101: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d5850)
Location: fs/ext4/super.c:5015
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff813d5850-ffffffff813d5b11: ext4_commit_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_commit_super(struct super_block *sb, int sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813eaad0)
Location: fs/ext4/super.c:5015
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_unfreeze
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_setup_super
  - fs/ext4/super.c:ext4_put_super
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_grp_locked_error
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_abort
  - fs/ext4/super.c:__ext4_std_error
  - fs/ext4/super.c:__ext4_error_file
  - fs/ext4/super.c:__ext4_error_inode
  - fs/ext4/super.c:__ext4_error
```
**Symbols:**

```
ffffffff813eaad0-ffffffff813ead8c: ext4_commit_super (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int sync</code>
</li>
</ul>
</details>
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
