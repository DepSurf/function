# Function: <code>ext4_bh_delay_or_unwritten</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_bh_delay_or_unwritten(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81295c80)
Location: fs/ext4/inode.c:1527
Inline: False
```
**Symbols:**

```
ffffffff81295c80-ffffffff81295ca6: ext4_bh_delay_or_unwritten (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffff812c8b32)
Location: fs/ext4/inode.c:1684
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff812de71e)
Location: fs/ext4/inode.c:1713
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff8130270f)
Location: fs/ext4/inode.c:1767
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff8132709f)
Location: fs/ext4/inode.c:1775
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff813568b9)
Location: fs/ext4/inode.c:1778
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff8136ebd9)
Location: fs/ext4/inode.c:1763
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff8139856b)
Location: fs/ext4/inode.c:1779
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff813b0fb8)
Location: fs/ext4/inode.c:1755
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff813fcc33)
Location: fs/ext4/inode.c:1606
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff8140f3b6)
Location: fs/ext4/inode.c:1623
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff81415736)
Location: fs/ext4/inode.c:1622
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff81468c76)
Location: fs/ext4/inode.c:1610
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff814e8974)
Location: fs/ext4/inode.c:1632
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_bh_delay_or_unwritten(handle_t *handle, struct inode *inode, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81578b60)
Location: fs/ext4/inode.c:1652
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage
```
**Symbols:**

```
ffffffff81578b60-ffffffff81578b8e: ext4_bh_delay_or_unwritten (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In fs/ext4/inode.c (ffff80001048590c)
Location: fs/ext4/inode.c:1755
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (c06474c0)
Location: fs/ext4/inode.c:1755
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (c0000000005ab218)
Location: fs/ext4/inode.c:1755
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffe00030daf4)
Location: fs/ext4/inode.c:1755
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff813a9598)
Location: fs/ext4/inode.c:1755
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff8139a028)
Location: fs/ext4/inode.c:1755
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff813a6df8)
Location: fs/ext4/inode.c:1755
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
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
In fs/ext4/inode.c (ffffffff813bb5e8)
Location: fs/ext4/inode.c:1755
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_writepage
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
