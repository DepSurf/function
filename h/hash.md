# Function: <code>hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff81f5c575)
Location: init/initramfs.c:63
Inline: True
```
```
In kernel/time/posix-timers.c (ffffffff810f09e6)
Location: kernel/time/posix-timers.c:150
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In fs/inode.c (ffffffff81226616)
Location: fs/inode.c:442
Inline: True
Inline callers:
  - fs/inode.c:__insert_inode_hash
  - fs/inode.c:iunique
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:ilookup
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:insert_inode_locked
```
```
In fs/block_dev.c (0)
Location: fs/block_dev.c:609
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: fs/jbd2/revoke.c:134
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff81f8452f)
Location: init/initramfs.c:63
Inline: True
```
```
In kernel/time/posix-timers.c (ffffffff810f7a06)
Location: kernel/time/posix-timers.c:150
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In fs/inode.c (ffffffff812509a8)
Location: fs/inode.c:450
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:__insert_inode_hash
```
```
In fs/block_dev.c (ffffffff812701cf)
Location: fs/block_dev.c:687
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/jbd2/revoke.c (ffffffff8131aeb1)
Location: fs/jbd2/revoke.c:134
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff81fbfab1)
Location: init/initramfs.c:63
Inline: True
```
```
In kernel/time/posix-timers.c (ffffffff811053a6)
Location: kernel/time/posix-timers.c:150
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:SyS_timer_create
```
```
In fs/inode.c (ffffffff81263a48)
Location: fs/inode.c:452
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:__insert_inode_hash
```
```
In fs/block_dev.c (ffffffff812833cf)
Location: fs/block_dev.c:939
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/jbd2/revoke.c (ffffffff81330e91)
Location: fs/jbd2/revoke.c:134
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8209f7f0)
Location: init/initramfs.c:64
Inline: True
```
```
In kernel/time/posix-timers.c (ffffffff81107364)
Location: kernel/time/posix-timers.c:141
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/inode.c (ffffffff812713d5)
Location: fs/inode.c:452
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:__insert_inode_hash
```
```
In fs/block_dev.c (ffffffff81290a9f)
Location: fs/block_dev.c:840
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/jbd2/revoke.c (ffffffff81345df1)
Location: fs/jbd2/revoke.c:134
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff826a57f0)
Location: init/initramfs.c:65
Inline: True
```
```
In kernel/time/posix-timers.c (ffffffff81112494)
Location: kernel/time/posix-timers.c:142
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/inode.c (ffffffff81293cf5)
Location: fs/inode.c:452
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked4
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:iget5_locked
  - fs/inode.c:__insert_inode_hash
```
```
In fs/block_dev.c (ffffffff812b377f)
Location: fs/block_dev.c:830
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/jbd2/revoke.c (ffffffff8136a481)
Location: fs/jbd2/revoke.c:134
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff826cec15)
Location: init/initramfs.c:65
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
```
```
In kernel/time/posix-timers.c (ffffffff8111de88)
Location: kernel/time/posix-timers.c:142
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/inode.c (ffffffff812ba31b)
Location: fs/inode.c:458
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/block_dev.c (ffffffff812dcb35)
Location: fs/block_dev.c:831
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/jbd2/revoke.c (ffffffff81398de4)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff82884c5a)
Location: init/initramfs.c:55
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
```
```
In kernel/time/posix-timers.c (ffffffff81129628)
Location: kernel/time/posix-timers.c:112
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/inode.c (ffffffff812cf65b)
Location: fs/inode.c:458
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/block_dev.c (ffffffff812f27f5)
Location: fs/block_dev.c:870
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/jbd2/revoke.c (ffffffff813b1b54)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289bc9c)
Location: init/initramfs.c:55
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
```
```
In kernel/time/posix-timers.c (ffffffff811340b5)
Location: kernel/time/posix-timers.c:112
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/inode.c (ffffffff812ec5ab)
Location: fs/inode.c:471
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/block_dev.c (ffffffff81314395)
Location: fs/block_dev.c:867
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/jbd2/revoke.c (ffffffff813dc194)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289ec81)
Location: init/initramfs.c:55
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
```
```
In kernel/time/posix-timers.c (ffffffff81140055)
Location: kernel/time/posix-timers.c:112
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/inode.c (ffffffff812fe0fb)
Location: fs/inode.c:475
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/block_dev.c (ffffffff81326d05)
Location: fs/block_dev.c:867
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/jbd2/revoke.c (ffffffff813f61e4)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff82cc4c06)
Location: init/initramfs.c:56
Inline: True
Inline callers:
  - init/initramfs.c:find_link
```
```
In kernel/time/posix-timers.c (ffffffff8114fcc5)
Location: kernel/time/posix-timers.c:113
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
```
```
In fs/inode.c (ffffffff8133743b)
Location: fs/inode.c:476
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_by_ino_rcu
  - fs/inode.c:find_inode_rcu
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/block_dev.c (ffffffff81360ea5)
Location: fs/block_dev.c:863
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
```
```
In fs/jbd2/revoke.c (ffffffff81443724)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff82fb0569)
Location: init/initramfs.c:59
Inline: True
Inline callers:
  - init/initramfs.c:find_link
```
```
In kernel/time/posix-timers.c (ffffffff8114bf49)
Location: kernel/time/posix-timers.c:113
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
```
```
In fs/inode.c (ffffffff81342d7b)
Location: fs/inode.c:477
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_by_ino_rcu
  - fs/inode.c:find_inode_rcu
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/jbd2/revoke.c (ffffffff8145f804)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff831ba5da)
Location: init/initramfs.c:71
Inline: True
Inline callers:
  - init/initramfs.c:find_link
```
```
In kernel/time/posix-timers.c (ffffffff8114d3fb)
Location: kernel/time/posix-timers.c:113
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/inode.c (ffffffff8134902b)
Location: fs/inode.c:477
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_by_ino_rcu
  - fs/inode.c:find_inode_rcu
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/jbd2/revoke.c (ffffffff81464ef4)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8329aab2)
Location: init/initramfs.c:72
Inline: True
Inline callers:
  - init/initramfs.c:find_link
```
```
In kernel/time/posix-timers.c (ffffffff81170bbb)
Location: kernel/time/posix-timers.c:113
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/inode.c (ffffffff81396d78)
Location: fs/inode.c:481
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_by_ino_rcu
  - fs/inode.c:find_inode_rcu
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/jbd2/revoke.c (ffffffff814ba86b)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff83449225)
Location: init/initramfs.c:83
Inline: True
Inline callers:
  - init/initramfs.c:find_link
```
```
In kernel/time/posix-timers.c (ffffffff811a51ed)
Location: kernel/time/posix-timers.c:113
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/bpf/bloom_filter.c (ffffffff812a4c9b)
Location: kernel/bpf/bloom_filter.c:30
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_peek_elem
```
```
In fs/inode.c (ffffffff814189f8)
Location: fs/inode.c:509
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_by_ino_rcu
  - fs/inode.c:find_inode_rcu
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/jbd2/revoke.c (ffffffff815446eb)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff83e62c25)
Location: init/initramfs.c:83
Inline: True
Inline callers:
  - init/initramfs.c:find_link
```
```
In kernel/time/posix-timers.c (ffffffff811e4b4d)
Location: kernel/time/posix-timers.c:113
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/bpf/bloom_filter.c (ffffffff81302a1b)
Location: kernel/bpf/bloom_filter.c:30
Inline: True
Inline callers:
  - kernel/bpf/bloom_filter.c:bloom_map_peek_elem
```
```
In fs/inode.c (ffffffff814a4318)
Location: fs/inode.c:508
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_by_ino_rcu
  - fs/inode.c:find_inode_rcu
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/jbd2/revoke.c (ffffffff815e374b)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int hash(int major, int minor, int ino);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff83683235)
Location: init/initramfs.c:77
Inline: True
Inline callers:
  - init/initramfs.c:find_link
```
```
In kernel/time/posix-timers.c (ffffffff811f91ad)
Location: kernel/time/posix-timers.c:70
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/bpf/bloom_filter.c (ffffffff81331180)
Location: kernel/bpf/bloom_filter.c:23
Inline: False
Direct callers:
  - kernel/bpf/bloom_filter.c:bloom_map_peek_elem
```
```
In fs/inode.c (ffffffff814d9498)
Location: fs/inode.c:508
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_by_ino_rcu
  - fs/inode.c:find_inode_rcu
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/jbd2/revoke.c (ffffffff8161af0b)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
**Symbols:**

```
ffffffff81331180-ffffffff813312b1: hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int hash(int major, int minor, int ino);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff838b2215)
Location: init/initramfs.c:77
Inline: True
Inline callers:
  - init/initramfs.c:find_link
```
```
In kernel/time/posix-timers.c (ffffffff8120f39d)
Location: kernel/time/posix-timers.c:70
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In kernel/bpf/bloom_filter.c (ffffffff81355720)
Location: kernel/bpf/bloom_filter.c:23
Inline: False
Direct callers:
  - kernel/bpf/bloom_filter.c:bloom_map_peek_elem
```
```
In fs/inode.c (ffffffff8150bc48)
Location: fs/inode.c:509
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_by_ino_rcu
  - fs/inode.c:find_inode_rcu
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/jbd2/revoke.c (ffffffff81653e2b)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
**Symbols:**

```
ffffffff81355720-ffffffff81355851: hash (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffff800011432f34)
Location: init/initramfs.c:55
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
```
```
In kernel/time/posix-timers.c (ffff8000101ab928)
Location: kernel/time/posix-timers.c:112
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/inode.c (ffff8000103ae92c)
Location: fs/inode.c:475
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/block_dev.c (ffff8000103e1c38)
Location: fs/block_dev.c:867
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/jbd2/revoke.c (ffff8000104d1f98)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (c1503038)
Location: init/initramfs.c:55
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
```
```
In kernel/time/posix-timers.c (c03f5778)
Location: kernel/time/posix-timers.c:112
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/inode.c (c058e7d0)
Location: fs/inode.c:475
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/block_dev.c (c05b7d64)
Location: fs/block_dev.c:867
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/jbd2/revoke.c (c06946e0)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (c000000001346a90)
Location: init/initramfs.c:55
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
```
```
In kernel/time/posix-timers.c (c00000000020dafc)
Location: kernel/time/posix-timers.c:112
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/inode.c (c0000000004a9d4c)
Location: fs/inode.c:475
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/block_dev.c (c0000000004e4aec)
Location: fs/block_dev.c:867
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/jbd2/revoke.c (c00000000060b778)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffe000002998)
Location: init/initramfs.c:55
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
```
```
In kernel/time/posix-timers.c (ffffffe000135804)
Location: kernel/time/posix-timers.c:112
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/inode.c (ffffffe0002737b6)
Location: fs/inode.c:475
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/block_dev.c (ffffffe000298112)
Location: fs/block_dev.c:867
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/jbd2/revoke.c (ffffffe000349284)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8288cc81)
Location: init/initramfs.c:55
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
```
```
In kernel/time/posix-timers.c (ffffffff81138805)
Location: kernel/time/posix-timers.c:112
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/inode.c (ffffffff812f66db)
Location: fs/inode.c:475
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/block_dev.c (ffffffff8131f2e5)
Location: fs/block_dev.c:867
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/jbd2/revoke.c (ffffffff813ee7c4)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8288abfe)
Location: init/initramfs.c:55
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
```
```
In kernel/time/posix-timers.c (ffffffff8112b255)
Location: kernel/time/posix-timers.c:112
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/inode.c (ffffffff812e72fb)
Location: fs/inode.c:475
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/block_dev.c (ffffffff8130fe85)
Location: fs/block_dev.c:867
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/jbd2/revoke.c (ffffffff813df244)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289fc81)
Location: init/initramfs.c:55
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
```
```
In kernel/time/posix-timers.c (ffffffff81136525)
Location: kernel/time/posix-timers.c:112
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/inode.c (ffffffff812f44eb)
Location: fs/inode.c:475
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/block_dev.c (ffffffff8131cdb5)
Location: fs/block_dev.c:867
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/jbd2/revoke.c (ffffffff813ebb44)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289fc86)
Location: init/initramfs.c:55
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
```
```
In kernel/time/posix-timers.c (ffffffff81143024)
Location: kernel/time/posix-timers.c:112
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:__lock_timer
  - kernel/time/posix-timers.c:do_timer_create
```
```
In fs/inode.c (ffffffff8130543b)
Location: fs/inode.c:475
Inline: True
Inline callers:
  - fs/inode.c:insert_inode_locked
  - fs/inode.c:find_inode_nowait
  - fs/inode.c:ilookup
  - fs/inode.c:ilookup5_nowait
  - fs/inode.c:iunique
  - fs/inode.c:iget_locked
  - fs/inode.c:inode_insert5
  - fs/inode.c:__insert_inode_hash
```
```
In fs/block_dev.c (ffffffff8132d195)
Location: fs/block_dev.c:867
Inline: True
Inline callers:
  - fs/block_dev.c:bdget
  - fs/block_dev.c:bdev_unhash_inode
```
```
In fs/jbd2/revoke.c (ffffffff814012b6)
Location: fs/jbd2/revoke.c:131
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
