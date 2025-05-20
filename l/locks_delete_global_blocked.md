# Function: <code>locks_delete_global_blocked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8125f0dd)
Location: fs/locks.c:599
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_wake_up_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128aba3)
Location: fs/locks.c:626
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8129f933)
Location: fs/locks.c:646
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812ae7a3)
Location: fs/locks.c:646
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d218f)
Location: fs/locks.c:663
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
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
In fs/locks.c (ffffffff812fe63f)
Location: fs/locks.c:663
Inline: True
Inline callers:
  - fs/locks.c:posix_unblock_lock
  - fs/locks.c:locks_wake_up_blocks
  - fs/locks.c:locks_delete_block
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
In fs/locks.c (ffffffff8131433c)
Location: fs/locks.c:715
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
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
In fs/locks.c (ffffffff8133bc7c)
Location: fs/locks.c:711
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
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
In fs/locks.c (ffffffff813541db)
Location: fs/locks.c:712
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
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
In fs/locks.c (ffffffff8139a79e)
Location: fs/locks.c:712
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
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
In fs/locks.c (ffffffff813ac25e)
Location: fs/locks.c:712
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
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
In fs/locks.c (ffffffff813b390e)
Location: fs/locks.c:712
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
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
In fs/locks.c (ffffffff814035ee)
Location: fs/locks.c:712
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
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
In fs/locks.c (ffffffff814776fe)
Location: fs/locks.c:662
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
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
In fs/locks.c (ffffffff81509f4e)
Location: fs/locks.c:648
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
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
In fs/locks.c (ffffffff815416ce)
Location: fs/locks.c:649
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
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
In fs/locks.c (ffffffff81576bae)
Location: fs/locks.c:648
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
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
In fs/locks.c (ffff800010416490)
Location: fs/locks.c:712
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (c05e1864)
Location: fs/locks.c:712
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/locks.c (c000000000523fa4)
Location: fs/locks.c:712
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
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
In fs/locks.c (ffffffe0002bd89c)
Location: fs/locks.c:712
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
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
In fs/locks.c (ffffffff8134c7bb)
Location: fs/locks.c:712
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
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
In fs/locks.c (ffffffff8133d49b)
Location: fs/locks.c:712
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
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
In fs/locks.c (ffffffff8134a28b)
Location: fs/locks.c:712
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
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
In fs/locks.c (ffffffff8135c727)
Location: fs/locks.c:712
Inline: True
Inline callers:
  - fs/locks.c:locks_delete_block
  - fs/locks.c:__locks_wake_up_blocks
```
</details>
</li>
</ul>

## Differences
