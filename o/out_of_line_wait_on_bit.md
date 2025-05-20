# Function: <code>out_of_line_wait_on_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff818207d0)
Location: kernel/sched/wait.c:402
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:insert_inode_locked
  - fs/buffer.c:unmap_underlying_metadata
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:__block_write_begin
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_resume
```
**Symbols:**

```
ffffffff818207d0-ffffffff81820873: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8189ac30)
Location: kernel/sched/wait.c:402
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:unmap_underlying_metadata
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff8189ac30-ffffffff8189acd3: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff818cf300)
Location: kernel/sched/wait.c:390
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff818cf300-ffffffff818cf3a3: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81906830)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/backing-dev.c:wb_shutdown
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81906830-ffffffff819068d6: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff819908a0)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/backing-dev.c:wb_shutdown
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff819908a0-ffffffff81990946: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff819ed060)
Location: kernel/sched/wait_bit.c:57
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff819ed060-ffffffff819ed106: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81a28290)
Location: kernel/sched/wait_bit.c:57
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81a28290-ffffffff81a28336: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81a98a80)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81a98a80-ffffffff81a98b23: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81ad03d0)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81ad03d0-ffffffff81ad0473: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81bc8d50)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:osync_buffers_list
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81bc8d50-ffffffff81bc8df3: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81c41b40)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:osync_buffers_list
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81c41b40-ffffffff81c41be3: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81c33ab0)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81c33ab0-ffffffff81c33b53: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81d52470)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81d52470-ffffffff81d52513: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81f22d10)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:bh_submit_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81f22d10-ffffffff81f22dbe: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff820cd690)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff820cd690-ffffffff820cd73e: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82151b00)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff82151b00-ffffffff82151bae: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82234940)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:__bh_read
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff82234940-ffffffff822349ee: out_of_line_wait_on_bit (STB_GLOBAL)
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
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffff800010da21f8)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffff800010da21f8-ffff800010da22c4: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c0e9a300)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:fsync_buffers_list
  - fs/buffer.c:fsync_buffers_list
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
c0e9a300-c0e9a3bc: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c000000000ee36c0)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:__sync_dirty_buffer
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
c000000000ee36c0-c000000000ee378c: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffe0008c5890)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffe0008c5890-ffffffe0008c5928: out_of_line_wait_on_bit (STB_GLOBAL)
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
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81a6f240)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81a6f240-ffffffff81a6f2e3: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81a2b670)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81a2b670-ffffffff81a2b713: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81adb650)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81adb650-ffffffff81adb6f3: out_of_line_wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int out_of_line_wait_on_bit(void *word, int bit, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81ae7bf0)
Location: kernel/sched/wait_bit.c:58
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_attach
  - mm/ksm.c:wait_while_offlining
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/buffer.c:block_truncate_page
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:clean_bdev_aliases
  - fs/buffer.c:__bread_gfp
  - fs/buffer.c:sync_mapping_buffers
  - fs/buffer.c:sync_mapping_buffers
  - fs/jbd2/transaction.c:do_get_write_access
  - security/keys/gc.c:key_gc_keytype
  - security/keys/request_key.c:wait_for_key_construction
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
```
**Symbols:**

```
ffffffff81ae7bf0-ffffffff81ae7c93: out_of_line_wait_on_bit (STB_GLOBAL)
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
