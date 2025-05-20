# Function: <code>ext4_mb_new_blocks_simple</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:5149
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff8141daa0-ffffffff8141dcad: ext4_mb_new_blocks_simple.constprop.0 (STB_LOCAL)
ffffffff81bec47f-ffffffff81bec499: ext4_mb_new_blocks_simple.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:5682
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff81424210-ffffffff81424437: ext4_mb_new_blocks_simple.constprop.0 (STB_LOCAL)
ffffffff81bde531-ffffffff81bde54b: ext4_mb_new_blocks_simple.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:5749
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff81477e90-ffffffff814780d4: ext4_mb_new_blocks_simple.constprop.0 (STB_LOCAL)
ffffffff81ccc37b-ffffffff81ccc395: ext4_mb_new_blocks_simple.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:5804
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff814fa410-ffffffff814fa691: ext4_mb_new_blocks_simple.constprop.0 (STB_LOCAL)
ffffffff81e7f3a1-ffffffff81e7f3b9: ext4_mb_new_blocks_simple.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81594c50)
Location: fs/ext4/mballoc.c:5773
Inline: True
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff81594c50-ffffffff81594ecc: ext4_mb_new_blocks_simple.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ext4_fsblk_t ext4_mb_new_blocks_simple(struct ext4_allocation_request *ar, int *errp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:6096
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff815cbc30-ffffffff815cbea0: ext4_mb_new_blocks_simple (STB_LOCAL)
ffffffff820ef483-ffffffff820ef4ba: ext4_mb_new_blocks_simple.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ext4_fsblk_t ext4_mb_new_blocks_simple(struct ext4_allocation_request *ar, int *errp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:6056
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_new_blocks
```
**Symbols:**

```
ffffffff816046e0-ffffffff81604950: ext4_mb_new_blocks_simple (STB_LOCAL)
ffffffff821cc597-ffffffff821cc5ce: ext4_mb_new_blocks_simple.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
