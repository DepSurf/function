# Function: <code>bit_waitqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
wait_queue_head_t *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c36a0)
Location: kernel/sched/wait.c:486
Inline: False
Direct callers:
  - kernel/sched/wait.c:wake_up_bit
  - kernel/sched/wait.c:wake_up_atomic_t
  - kernel/sched/wait.c:out_of_line_wait_on_bit
  - kernel/sched/wait.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait.c:out_of_line_wait_on_atomic_t
  - fs/inode.c:__wait_on_freeing_inode
  - fs/inode.c:inode_dio_wait
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff810c36a0-ffffffff810c3737: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
wait_queue_head_t *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c7020)
Location: kernel/sched/wait.c:486
Inline: False
Direct callers:
  - kernel/sched/wait.c:wake_up_atomic_t
  - kernel/sched/wait.c:out_of_line_wait_on_atomic_t
  - kernel/sched/wait.c:wake_up_bit
  - kernel/sched/wait.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait.c:out_of_line_wait_on_bit
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff810c7020-ffffffff810c70c5: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
wait_queue_head_t *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae190)
Location: kernel/sched/core.c:7534
Inline: False
Direct callers:
  - kernel/sched/wait.c:wake_up_atomic_t
  - kernel/sched/wait.c:out_of_line_wait_on_atomic_t
  - kernel/sched/wait.c:wake_up_bit
  - kernel/sched/wait.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait.c:out_of_line_wait_on_bit
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff810ae190-ffffffff810ae1c3: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810c9cc5)
Location: kernel/sched/wait_bit.c:14
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_atomic_t
  - kernel/sched/wait_bit.c:out_of_line_wait_on_atomic_t
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff810c9b60-ffffffff810c9b93: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810d14e5)
Location: kernel/sched/wait_bit.c:14
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_atomic_t
  - kernel/sched/wait_bit.c:out_of_line_wait_on_atomic_t
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff810d1380-ffffffff810d13b3: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810d9a65)
Location: kernel/sched/wait_bit.c:11
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff810d98d0-ffffffff810d9903: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810e3565)
Location: kernel/sched/wait_bit.c:11
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:blkdev_get
```
**Symbols:**

```
ffffffff810e33d0-ffffffff810e3403: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ea175)
Location: kernel/sched/wait_bit.c:12
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
ffffffff810e9fe0-ffffffff810ea013: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810f5b45)
Location: kernel/sched/wait_bit.c:12
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
ffffffff810f59b0-ffffffff810f59e3: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81bc8f9c)
Location: kernel/sched/wait_bit.c:12
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
ffffffff810ff0f0-ffffffff810ff123: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81c41d8c)
Location: kernel/sched/wait_bit.c:12
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:bd_prepare_to_claim
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
```
**Symbols:**

```
ffffffff810fdbf0-ffffffff810fdc23: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81c33cfc)
Location: kernel/sched/wait_bit.c:12
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:bd_prepare_to_claim
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
```
**Symbols:**

```
ffffffff810fffd0-ffffffff81100003: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81d526bc)
Location: kernel/sched/wait_bit.c:12
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - block/bdev.c:bd_prepare_to_claim
```
**Symbols:**

```
ffffffff8111c070-ffffffff8111c0a3: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81f22b5c)
Location: kernel/sched/wait_bit.c:12
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_bit
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - block/bdev.c:bd_prepare_to_claim
```
**Symbols:**

```
ffffffff8113b830-ffffffff8113b86b: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff820cd4bc)
Location: kernel/sched/wait_bit.c:12
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_bit
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - block/bdev.c:bd_prepare_to_claim
```
**Symbols:**

```
ffffffff81166250-ffffffff8116628b: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8215193c)
Location: kernel/sched/wait_bit.c:12
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_bit
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - block/bdev.c:bd_prepare_to_claim
```
**Symbols:**

```
ffffffff811766c0-ffffffff811766fb: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8223477c)
Location: kernel/sched/wait_bit.c:12
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_bit
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/ext4/fast_commit.c:ext4_fc_wait_committing_inode
  - block/bdev.c:bd_prepare_to_claim
```
**Symbols:**

```
ffffffff81184940-ffffffff8118497b: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffff80001015915c)
Location: kernel/sched/wait_bit.c:12
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
ffff800010158e48-ffff800010158ea0: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c03a64d0)
Location: kernel/sched/wait_bit.c:12
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
c03a627c-c03a62b8: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c0000000001ad680)
Location: kernel/sched/wait_bit.c:12
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
c0000000001ad3f0-c0000000001ad438: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffe0000ff264)
Location: kernel/sched/wait_bit.c:12
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
ffffffe0000ff01c-ffffffe0000ff06a: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810eef45)
Location: kernel/sched/wait_bit.c:12
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
ffffffff810eedb0-ffffffff810eede3: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810defc5)
Location: kernel/sched/wait_bit.c:12
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
ffffffff810dee30-ffffffff810dee63: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ec075)
Location: kernel/sched/wait_bit.c:12
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
ffffffff810ebee0-ffffffff810ebf13: bit_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct wait_queue_head *bit_waitqueue(void *word, int bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810f70c5)
Location: kernel/sched/wait_bit.c:12
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
Direct callers:
  - fs/inode.c:inode_dio_wait
  - fs/inode.c:__wait_on_freeing_inode
  - fs/fs-writeback.c:inode_sleep_on_writeback
  - fs/fs-writeback.c:__inode_wait_for_writeback
  - fs/block_dev.c:bd_start_claiming
```
**Symbols:**

```
ffffffff810f6f30-ffffffff810f6f63: bit_waitqueue (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>wait_queue_head_t *</code> ➡️ <code>struct wait_queue_head *</code>
</li>
</ul>
</details>
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
