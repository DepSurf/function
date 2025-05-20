# Function: <code>__locks_insert_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812603d0)
Location: fs/locks.c:635
Inline: True
Direct callers:
  - fs/locks.c:locks_insert_block
  - fs/locks.c:__posix_lock_file
```
**Symbols:**

```
ffffffff812603d0-ffffffff81260478: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128c5b0)
Location: fs/locks.c:662
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_insert_block
```
**Symbols:**

```
ffffffff8128c5b0-ffffffff8128c65b: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a1360)
Location: fs/locks.c:682
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_insert_block
```
**Symbols:**

```
ffffffff812a1360-ffffffff812a140b: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812b0080)
Location: fs/locks.c:682
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_insert_block
```
**Symbols:**

```
ffffffff812b0080-ffffffff812b012b: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d3620)
Location: fs/locks.c:699
Inline: True
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_insert_block
```
**Symbols:**

```
ffffffff812d3620-ffffffff812d36cf: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812fdbf0)
Location: fs/locks.c:699
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff812fdbf0-ffffffff812fdc9f: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81313660)
Location: fs/locks.c:798
Inline: True
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81313660-ffffffff81313770: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133ace0)
Location: fs/locks.c:794
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8133ace0-ffffffff8133adce: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81353200)
Location: fs/locks.c:818
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81353200-ffffffff813532ee: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81399f10)
Location: fs/locks.c:818
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81399f10-ffffffff81399ffe: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813aba00)
Location: fs/locks.c:818
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff813aba00-ffffffff813abaee: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813b2f50)
Location: fs/locks.c:818
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff813b2f50-ffffffff813b303e: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81402c40)
Location: fs/locks.c:818
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81402c40-ffffffff81402d30: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81477780)
Location: fs/locks.c:768
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81477780-ffffffff8147787f: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81509fe0)
Location: fs/locks.c:754
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81509fe0-ffffffff8150a0df: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81541760)
Location: fs/locks.c:755
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81541760-ffffffff8154185f: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff81576c40)
Location: fs/locks.c:754
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff81576c40-ffffffff81576d3f: __locks_insert_block (STB_LOCAL)
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
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffff800010414cc8)
Location: fs/locks.c:818
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffff800010414cc8-ffff800010414df4: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e18e4)
Location: fs/locks.c:818
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_insert_block
```
**Symbols:**

```
c05e18e4-c05e19dc: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000524060)
Location: fs/locks.c:818
Inline: False
Direct callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_insert_block
```
**Symbols:**

```
c000000000524060-c00000000052421c: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffe0002bc924)
Location: fs/locks.c:818
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffe0002bc924-ffffffe0002bca00: __locks_insert_block (STB_LOCAL)
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
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8134b7e0)
Location: fs/locks.c:818
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8134b7e0-ffffffff8134b8ce: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8133c4c0)
Location: fs/locks.c:818
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8133c4c0-ffffffff8133c5ae: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff813492b0)
Location: fs/locks.c:818
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff813492b0-ffffffff8134939e: __locks_insert_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __locks_insert_block(struct file_lock *blocker, struct file_lock *waiter, bool (*conflict)(struct file_lock *, struct file_lock *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8135c790)
Location: fs/locks.c:818
Inline: False
Direct callers:
  - fs/locks.c:__break_lease
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:flock_lock_inode
```
**Symbols:**

```
ffffffff8135c790-ffffffff8135c87e: __locks_insert_block (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool (*conflict)(struct file_lock *, struct file_lock *)</code>
</li>
</ul>
</details>
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
