# Function: <code>locks_insert_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void locks_insert_block(struct file_lock *blocker, struct file_lock *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81260480)
Location: fs/locks.c:646
Inline: False
Direct callers:
  - fs/locks.c:flock_lock_inode
  - fs/locks.c:__break_lease
```
**Symbols:**

```
ffffffff81260480-ffffffff812604bc: locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void locks_insert_block(struct file_lock *blocker, struct file_lock *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128c660)
Location: fs/locks.c:673
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8128c660-ffffffff8128c69c: locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void locks_insert_block(struct file_lock *blocker, struct file_lock *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a1410)
Location: fs/locks.c:693
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff812a1410-ffffffff812a144c: locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void locks_insert_block(struct file_lock *blocker, struct file_lock *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b0130)
Location: fs/locks.c:693
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff812b0130-ffffffff812b016c: locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void locks_insert_block(struct file_lock *blocker, struct file_lock *waiter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d36d0)
Location: fs/locks.c:710
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff812d36d0-ffffffff812d370c: locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812ff873)
Location: fs/locks.c:710
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81314f23)
Location: fs/locks.c:825
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133c80e)
Location: fs/locks.c:821
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81354da4)
Location: fs/locks.c:845
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8139b9b7)
Location: fs/locks.c:845
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813ad3df)
Location: fs/locks.c:845
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b45e0)
Location: fs/locks.c:845
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff814042e0)
Location: fs/locks.c:845
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81478456)
Location: fs/locks.c:795
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8150ad76)
Location: fs/locks.c:781
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff815424d6)
Location: fs/locks.c:782
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff815779f6)
Location: fs/locks.c:781
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010416e4c)
Location: fs/locks.c:845
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e19dc)
Location: fs/locks.c:845
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
c05e19dc-c05e1a38: locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000524220)
Location: fs/locks.c:845
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
c000000000524220-c0000000005242ec: locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002be3ae)
Location: fs/locks.c:845
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134d384)
Location: fs/locks.c:845
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133e064)
Location: fs/locks.c:845
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134ae54)
Location: fs/locks.c:845
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135f775)
Location: fs/locks.c:845
Inline: True
Inline callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:flock_lock_inode
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
</ul>
<b>Arch</b>
<ul>
</ul>
