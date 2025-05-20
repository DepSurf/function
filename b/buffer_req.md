# Function: <code>buffer_req</code>

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
In fs/ext4/inode.c (ffffffff8129a8fb)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812cbe16)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/jbd2/recovery.c (ffffffff812eb5cb)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/inode.c (ffffffff812c87e9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ext4_jbd2.c (ffffffff812fb746)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/jbd2/recovery.c (ffffffff8131902d)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/inode.c (ffffffff812de3b9)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/ext4/ext4_jbd2.c (ffffffff813116f6)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/jbd2/recovery.c (ffffffff8132f01d)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffff812e667e)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffff81302423)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffff813440a6)
Location: include/linux/buffer_head.h:120
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffff8130b08e)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffff81326db3)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffff81368746)
Location: include/linux/buffer_head.h:121
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffff81338f96)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffff813551f8)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffff81396fe1)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffff81350246)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffff8136d52b)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffff813afd51)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffff81378ee3)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffff81396b1c)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffff813da2ab)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffff813912a3)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffff813af54c)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffff813f42fb)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffff813dcb3b)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffff813fb5bc)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffff814417f5)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffff813ee57b)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffff8140dcfe)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffff8145d9e5)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffff813f4b3f)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffff81413ec2)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffff814632f5)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffff81446d8f)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffff8146722e)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffff814b8835)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffff814c30af)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffff814e6e07)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffff81542388)
Location: include/linux/buffer_head.h:123
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffff8155b448)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffff81580613)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffff815e0feb)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffff81593266)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffff815b7bd3)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffff816188db)
Location: include/linux/buffer_head.h:127
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffff815cbf56)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffff815f095c)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffff8165185a)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffff800010463e3c)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffff800010483e64)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffff8000104cfbf0)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (c0624410)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (c0645484)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (c06926a0)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (c000000000581148)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (c0000000005a8f24)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (c000000000608ac0)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffe0002f257a)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffe00030c416)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffe000347286)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffff81389883)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffff813a7b2c)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffff813ec8db)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffff8137a313)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffff813985bc)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffff813dd35b)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffff813871e3)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffff813a538c)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffff813e9c5b)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
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
In fs/ext4/ext4_jbd2.c (ffffffff8139aebd)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/ext4_jbd2.c:__ext4_handle_dirty_metadata
```
```
In fs/ext4/inode.c (ffffffff813b9acc)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_inode
```
```
In fs/jbd2/recovery.c (ffffffff813ff5ab)
Location: include/linux/buffer_head.h:124
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:jread
```
</details>
</li>
</ul>

## Differences
