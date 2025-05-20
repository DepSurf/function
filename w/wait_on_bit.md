# Function: <code>wait_on_bit</code>

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
In kernel/ptrace.c (ffffffff8108af08)
Location: include/linux/wait.h:985
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff811e468e)
Location: include/linux/wait.h:985
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff81228399)
Location: include/linux/wait.h:985
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:ilookup5
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:insert_inode_locked
```
```
In security/keys/gc.c (ffffffff8132f39b)
Location: include/linux/wait.h:985
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff81334a15)
Location: include/linux/wait.h:985
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff816a45ac)
Location: include/linux/wait.h:985
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_resume
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
In kernel/ptrace.c (ffffffff8108defa)
Location: include/linux/wait.h:1049
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff81202fcb)
Location: include/linux/wait.h:1049
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff81250ac7)
Location: include/linux/wait.h:1049
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
```
```
In security/keys/gc.c (ffffffff8136409b)
Location: include/linux/wait.h:1049
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff813699c9)
Location: include/linux/wait.h:1049
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff8170483c)
Location: include/linux/wait.h:1049
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff81093670)
Location: include/linux/wait.h:1040
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff81214eab)
Location: include/linux/wait.h:1040
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff81263b67)
Location: include/linux/wait.h:1040
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
```
```
In security/keys/gc.c (ffffffff8137a8bb)
Location: include/linux/wait.h:1040
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff813801d9)
Location: include/linux/wait.h:1040
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff81736709)
Location: include/linux/wait.h:1040
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff81090755)
Location: include/linux/wait_bit.h:75
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/backing-dev.c (ffffffff811e0b7c)
Location: include/linux/wait_bit.h:75
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/ksm.c (ffffffff8122063b)
Location: include/linux/wait_bit.h:75
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff812714a4)
Location: include/linux/wait_bit.h:75
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
```
```
In security/keys/gc.c (ffffffff8138e4ab)
Location: include/linux/wait_bit.h:75
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff81394059)
Location: include/linux/wait_bit.h:75
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff8174fb39)
Location: include/linux/wait_bit.h:75
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff810975c5)
Location: include/linux/wait_bit.h:79
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/backing-dev.c (ffffffff811f6b6c)
Location: include/linux/wait_bit.h:79
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_shutdown
```
```
In mm/ksm.c (ffffffff8123b87b)
Location: include/linux/wait_bit.h:79
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff81293dc6)
Location: include/linux/wait_bit.h:79
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
```
```
In security/keys/gc.c (ffffffff813b395e)
Location: include/linux/wait_bit.h:79
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff813b9329)
Location: include/linux/wait_bit.h:79
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff817c1d07)
Location: include/linux/wait_bit.h:79
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff8109aaf1)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff8125ee1b)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff812ba3d8)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (ffffffff813e40ce)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff813ea09d)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff8180a467)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff810a2d21)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff8127358b)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff812cf724)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (ffffffff813fe8be)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff81404acd)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff81836467)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff810a79e3)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff8128ed7e)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff812ec674)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (ffffffff8142af0e)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff8143198e)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff8187902b)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff810ae003)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff8129eaee)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff812fe1c4)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (ffffffff81444c5e)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff8144b6ee)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff818aae6b)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff810b5ae3)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff812d30be)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff81337504)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (ffffffff81495c8e)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff8149d6da)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff8197affb)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff810b0cd3)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff812dea6e)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff81342e44)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (ffffffff814b36ee)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff814bb1ff)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff8197f81b)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff810b2273)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff812e624e)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff813490f4)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (ffffffff814b951e)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff814c10c1)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff81963937)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff810c40dc)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff8132e16e)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff81396e3e)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (ffffffff81511d4e)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff81519b31)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff81a0b8d7)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff810db709)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff8139e4ce)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff81418b18)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (ffffffff815a40ee)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff815ac7a2)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff81b73d55)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff810fb7c9)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff8141dbfe)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff814a4438)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (ffffffff8164ddce)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff81656c87)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff81d10ca5)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff81107869)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff8145253e)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff814d95af)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (ffffffff8168658e)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff8168f507)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff81d7a135)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff811111c7)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff8148cbce)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff8150bd5a)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (ffffffff816c29fe)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff816cba97)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff81e312d5)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffff800010108100)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In fs/inode.c (ffff8000103aeb5c)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (ffff80001052d97c)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffff8000105354f0)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffff800010b00f80)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (c0362670)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
```
```
In fs/inode.c (c058e8d8)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (c06e60c4)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (c06ed460)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (c0be0870)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (c00000000014f528)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (c000000000419d2c)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (c0000000004a9f44)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (c000000000679bd8)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (c000000000684714)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (c000000000bf0290)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffe0000cc502)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:__se_sys_ptrace
```
```
In fs/inode.c (ffffffe000273960)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (ffffffe00038f5bc)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffe000395afc)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffe0006f10a0)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff810a8373)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff812970ce)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff812f67a4)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (ffffffff8143d23e)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff81443cce)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff81850ceb)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff81096d28)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff81288cde)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff812e73c4)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (ffffffff8142dcae)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff8143471e)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff818182fb)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff810a78d3)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff81294ede)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff812f45b4)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (ffffffff814393de)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff8143ff3e)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff818a031b)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
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
In kernel/ptrace.c (ffffffff810af9e8)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
```
```
In mm/ksm.c (ffffffff812a4d5e)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - mm/ksm.c:wait_while_offlining
```
```
In fs/inode.c (ffffffff813054fb)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
```
```
In security/keys/gc.c (ffffffff8145051e)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/gc.c:key_gc_keytype
```
```
In security/keys/request_key.c (ffffffff81457011)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - security/keys/request_key.c:wait_for_key_construction
```
```
In drivers/md/dm.c (ffffffff818bc56b)
Location: include/linux/wait_bit.h:71
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:dm_suspend
  - drivers/md/dm.c:dm_suspend
```
</details>
</li>
</ul>

## Differences
