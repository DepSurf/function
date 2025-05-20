# Function: <code>locks_wake_up_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8125fa00)
Location: fs/locks.c:659
Inline: False
Direct callers:
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:__posix_lock_file
  - fs/locks.c:__posix_lock_file
  - fs/locks.c:time_out_leases
```
**Symbols:**

```
ffffffff8125fa00-ffffffff8125fac9: locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff8128bba0)
Location: fs/locks.c:686
Inline: False
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
```
**Symbols:**

```
ffffffff8128bba0-ffffffff8128bc73: locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812a0900)
Location: fs/locks.c:706
Inline: False
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
```
**Symbols:**

```
ffffffff812a0900-ffffffff812a09d3: locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812af6b0)
Location: fs/locks.c:706
Inline: False
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
```
**Symbols:**

```
ffffffff812af6b0-ffffffff812af780: locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812d3130)
Location: fs/locks.c:723
Inline: False
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
```
**Symbols:**

```
ffffffff812d3130-ffffffff812d3200: locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void locks_wake_up_blocks(struct file_lock *blocker);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/locks.c (ffffffff812fe820)
Location: fs/locks.c:723
Inline: False
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
```
**Symbols:**

```
ffffffff812fe820-ffffffff812fe8f3: locks_wake_up_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff81314293)
Location: fs/locks.c:840
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
```
**Symbols:**

```
ffffffff81313fa0-ffffffff81313fd2: locks_wake_up_blocks.part.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8133bbcd)
Location: fs/locks.c:836
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
```
**Symbols:**

```
ffffffff8133b890-ffffffff8133b8c4: locks_wake_up_blocks.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8135411d)
Location: fs/locks.c:860
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
```
**Symbols:**

```
ffffffff81353de0-ffffffff81353e14: locks_wake_up_blocks.part.0 (STB_LOCAL)
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
In fs/locks.c (ffffffff8139ae39)
Location: fs/locks.c:860
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_unlink_lock_ctx
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
In fs/locks.c (ffffffff813acb18)
Location: fs/locks.c:860
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_unlink_lock_ctx
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
In fs/locks.c (ffffffff813b3fa8)
Location: fs/locks.c:860
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_unlink_lock_ctx
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
In fs/locks.c (ffffffff81403cb5)
Location: fs/locks.c:860
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_unlink_lock_ctx
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
In fs/locks.c (ffffffff814780a2)
Location: fs/locks.c:810
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_unlink_lock_ctx
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
In fs/locks.c (ffffffff8150a9b2)
Location: fs/locks.c:796
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_unlink_lock_ctx
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
In fs/locks.c (ffffffff81542112)
Location: fs/locks.c:797
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_unlink_lock_ctx
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
In fs/locks.c (ffffffff81577632)
Location: fs/locks.c:796
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
  - fs/locks.c:locks_unlink_lock_ctx
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffff800010416878)
Location: fs/locks.c:860
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
```
**Symbols:**

```
ffff8000104161f8-ffff8000104162a4: locks_wake_up_blocks.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (c05e36f8)
Location: fs/locks.c:860
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
```
**Symbols:**

```
c05e1f90-c05e1fdc: locks_wake_up_blocks.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (c000000000525754)
Location: fs/locks.c:860
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
```
**Symbols:**

```
c000000000524970-c000000000524a2c: locks_wake_up_blocks.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffe0002bd7da)
Location: fs/locks.c:860
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
```
**Symbols:**

```
ffffffe0002bd43e-ffffffe0002bd4bc: locks_wake_up_blocks.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8134c6fd)
Location: fs/locks.c:860
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
```
**Symbols:**

```
ffffffff8134c3c0-ffffffff8134c3f4: locks_wake_up_blocks.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8133d3dd)
Location: fs/locks.c:860
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
```
**Symbols:**

```
ffffffff8133d0a0-ffffffff8133d0d4: locks_wake_up_blocks.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8134a1cd)
Location: fs/locks.c:860
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
```
**Symbols:**

```
ffffffff81349e90-ffffffff81349ec4: locks_wake_up_blocks.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/locks.c (ffffffff8135e0ad)
Location: fs/locks.c:860
Inline: True
Inline callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
Direct callers:
  - fs/locks.c:time_out_leases
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:locks_unlink_lock_ctx
```
**Symbols:**

```
ffffffff8135cc20-ffffffff8135cc52: locks_wake_up_blocks.part.0 (STB_LOCAL)
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
</ul>
