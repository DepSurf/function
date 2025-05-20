# Function: <code>dqput</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81271580)
Location: fs/quota/dquot.c:734
Inline: True
Direct callers:
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
```
**Symbols:**

```
ffffffff81271580-ffffffff81271760: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8129dd50)
Location: fs/quota/dquot.c:741
Inline: True
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff8129dd50-ffffffff8129df17: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812b3690)
Location: fs/quota/dquot.c:738
Inline: True
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff812b3690-ffffffff812b3857: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff812c1717)
Location: fs/quota/dquot.c:739
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff812c0920-ffffffff812c0ade: dqput.part.16 (STB_LOCAL)
ffffffff812c0ae0-ffffffff812c0af7: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff812e5518)
Location: fs/quota/dquot.c:750
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff812e4320-ffffffff812e44d5: dqput.part.13 (STB_LOCAL)
ffffffff812e44e0-ffffffff812e44f7: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff813128f5)
Location: fs/quota/dquot.c:747
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff81311a50-ffffffff81311c07: dqput.part.17 (STB_LOCAL)
ffffffff81311c10-ffffffff81311c26: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff81329475)
Location: fs/quota/dquot.c:747
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff813285d0-ffffffff81328787: dqput.part.17 (STB_LOCAL)
ffffffff81328790-ffffffff813287a6: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff81350f51)
Location: fs/quota/dquot.c:753
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff81350150-ffffffff81350307: dqput.part.0 (STB_LOCAL)
ffffffff81350310-ffffffff81350326: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff813692d1)
Location: fs/quota/dquot.c:754
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff81368460-ffffffff81368617: dqput.part.0 (STB_LOCAL)
ffffffff81368620-ffffffff81368636: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff813b12ae)
Location: fs/quota/dquot.c:752
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:remove_dquot_ref
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:invalidate_dquots
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:remove_dquot_ref
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:invalidate_dquots
```
**Symbols:**

```
ffffffff813b0750-ffffffff813b0907: dqput.part.0 (STB_LOCAL)
ffffffff813b0910-ffffffff813b0926: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c28ae)
Location: fs/quota/dquot.c:753
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:remove_dquot_ref
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:invalidate_dquots
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:remove_dquot_ref
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:invalidate_dquots
```
**Symbols:**

```
ffffffff813c1d50-ffffffff813c1f07: dqput.part.0 (STB_LOCAL)
ffffffff813c1f10-ffffffff813c1f26: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c947e)
Location: fs/quota/dquot.c:751
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:invalidate_dquots
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:invalidate_dquots
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff813c8910-ffffffff813c8ac7: dqput.part.0 (STB_LOCAL)
ffffffff813c8ad0-ffffffff813c8ae6: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff81419cfe)
Location: fs/quota/dquot.c:756
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:invalidate_dquots
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:invalidate_dquots
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff81419070-ffffffff8141924e: dqput.part.0 (STB_LOCAL)
ffffffff81cc7d18-ffffffff81cc7d65: dqput.part.0.cold (STB_LOCAL)
ffffffff81419250-ffffffff81419266: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff8149070d)
Location: fs/quota/dquot.c:766
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:invalidate_dquots
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:invalidate_dquots
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff8148fac0-ffffffff8148fca9: dqput.part.0 (STB_LOCAL)
ffffffff81e7a905-ffffffff81e7a94f: dqput.part.0.cold (STB_LOCAL)
ffffffff8148fcb0-ffffffff8148fcd2: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff8152429d)
Location: fs/quota/dquot.c:766
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:invalidate_dquots
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:invalidate_dquots
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff815235d0-ffffffff815237b9: dqput.part.0 (STB_LOCAL)
ffffffff8206b819-ffffffff8206b863: dqput.part.0.cold (STB_LOCAL)
ffffffff815237d0-ffffffff815237f2: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff8155c6bd)
Location: fs/quota/dquot.c:846
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:invalidate_dquots
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:invalidate_dquots
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff8155ba70-ffffffff8155bb8f: dqput.part.0 (STB_LOCAL)
ffffffff820eb71a-ffffffff820eb764: dqput.part.0.cold (STB_LOCAL)
ffffffff8155bba0-ffffffff8155bbc2: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff81592e7d)
Location: fs/quota/dquot.c:851
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:invalidate_dquots
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:invalidate_dquots
  - fs/ext4/ioctl.c:ext4_ioctl_setproject
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff815921e0-ffffffff8159230b: dqput.part.0 (STB_LOCAL)
ffffffff821c8944-ffffffff821c898e: dqput.part.0.cold (STB_LOCAL)
ffffffff81592320-ffffffff81592342: dqput (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffff800010430724)
Location: fs/quota/dquot.c:754
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffff80001042f9d0-ffff80001042fd30: dqput.part.0 (STB_LOCAL)
ffff80001042fd30-ffff80001042fd60: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (c05f9394)
Location: fs/quota/dquot.c:754
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
c05f87a8-c05f8a08: dqput.part.0 (STB_LOCAL)
c05f8a08-c05f8a2c: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (c000000000542c70)
Location: fs/quota/dquot.c:754
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
c000000000541450-c00000000054181c: dqput.part.0 (STB_LOCAL)
c000000000541820-c00000000054183c: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffe0002cd782)
Location: fs/quota/dquot.c:754
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffe0002cc70e-ffffffe0002cc9ce: dqput.part.0 (STB_LOCAL)
ffffffe0002cc9ce-ffffffe0002cc9fa: dqput (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff813618b1)
Location: fs/quota/dquot.c:754
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff81360a40-ffffffff81360bf7: dqput.part.0 (STB_LOCAL)
ffffffff81360c00-ffffffff81360c16: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff81352551)
Location: fs/quota/dquot.c:754
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff813516e0-ffffffff81351897: dqput.part.0 (STB_LOCAL)
ffffffff813518a0-ffffffff813518b6: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff8135f381)
Location: fs/quota/dquot.c:754
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff8135e510-ffffffff8135e6c7: dqput.part.0 (STB_LOCAL)
ffffffff8135e6d0-ffffffff8135e6e6: dqput (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dqput(struct dquot *dquot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (ffffffff81372179)
Location: fs/quota/dquot.c:754
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
Direct callers:
  - fs/quota/dquot.c:dquot_set_dqblk
  - fs/quota/dquot.c:dquot_get_dqblk
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_disable
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:dquot_transfer
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_drop
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:__dquot_initialize
  - fs/quota/dquot.c:dqget
  - fs/quota/dquot.c:dquot_writeback_dquots
  - fs/quota/dquot.c:dquot_scan_active
  - fs/quota/dquot.c:dquot_scan_active
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/super.c:ext4_statfs
```
**Symbols:**

```
ffffffff81370ed0-ffffffff81371084: dqput.part.0 (STB_LOCAL)
ffffffff81371090-ffffffff813710a6: dqput (STB_GLOBAL)
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
