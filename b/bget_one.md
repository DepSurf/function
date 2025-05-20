# Function: <code>bget_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bget_one(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81295cb0)
Location: fs/ext4/inode.c:1715
Inline: False
```
**Symbols:**

```
ffffffff81295cb0-ffffffff81295cc1: bget_one (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffff812c8cee)
Location: fs/ext4/inode.c:1872
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
In fs/ext4/inode.c (ffffffff812de8d9)
Location: fs/ext4/inode.c:1901
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
In fs/ext4/inode.c (ffffffff813027dc)
Location: fs/ext4/inode.c:1955
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
In fs/ext4/inode.c (ffffffff8132716c)
Location: fs/ext4/inode.c:1963
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
In fs/ext4/inode.c (ffffffff81356a2a)
Location: fs/ext4/inode.c:1966
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
In fs/ext4/inode.c (ffffffff8136ecc0)
Location: fs/ext4/inode.c:1996
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
In fs/ext4/inode.c (ffffffff813980c6)
Location: fs/ext4/inode.c:2012
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
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
In fs/ext4/inode.c (ffffffff813b0b06)
Location: fs/ext4/inode.c:1988
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
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
In fs/ext4/inode.c (ffffffff813fc725)
Location: fs/ext4/inode.c:1838
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
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
In fs/ext4/inode.c (ffffffff8140ee26)
Location: fs/ext4/inode.c:1855
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
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
In fs/ext4/inode.c (ffffffff814151a6)
Location: fs/ext4/inode.c:1854
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
In fs/ext4/inode.c (ffff8000104855f8)
Location: fs/ext4/inode.c:1988
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
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
In fs/ext4/inode.c (c0646f48)
Location: fs/ext4/inode.c:1988
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
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
In fs/ext4/inode.c (c0000000005aab18)
Location: fs/ext4/inode.c:1988
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
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
In fs/ext4/inode.c (ffffffe00030d8f6)
Location: fs/ext4/inode.c:1988
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
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
In fs/ext4/inode.c (ffffffff813a90e6)
Location: fs/ext4/inode.c:1988
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
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
In fs/ext4/inode.c (ffffffff81399b76)
Location: fs/ext4/inode.c:1988
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
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
In fs/ext4/inode.c (ffffffff813a6946)
Location: fs/ext4/inode.c:1988
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
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
In fs/ext4/inode.c (ffffffff813bb131)
Location: fs/ext4/inode.c:1988
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_journalled_writepage
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
