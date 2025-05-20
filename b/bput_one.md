# Function: <code>bput_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bput_one(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81295cd0)
Location: fs/ext4/inode.c:1721
Inline: False
```
**Symbols:**

```
ffffffff81295cd0-ffffffff81295ce1: bput_one (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffff812c8e9f)
Location: fs/ext4/inode.c:1878
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
In fs/ext4/inode.c (ffffffff812dea99)
Location: fs/ext4/inode.c:1907
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
In fs/ext4/inode.c (ffffffff81302bbe)
Location: fs/ext4/inode.c:1961
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
In fs/ext4/inode.c (ffffffff81327586)
Location: fs/ext4/inode.c:1969
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
In fs/ext4/inode.c (ffffffff81356c0f)
Location: fs/ext4/inode.c:1972
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
In fs/ext4/inode.c (ffffffff8136eea5)
Location: fs/ext4/inode.c:2002
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
In fs/ext4/inode.c (ffffffff813983c5)
Location: fs/ext4/inode.c:2018
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
In fs/ext4/inode.c (ffffffff813b0e05)
Location: fs/ext4/inode.c:1994
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
In fs/ext4/inode.c (ffffffff813fc892)
Location: fs/ext4/inode.c:1844
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
In fs/ext4/inode.c (ffffffff8140f092)
Location: fs/ext4/inode.c:1861
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
In fs/ext4/inode.c (ffffffff81415412)
Location: fs/ext4/inode.c:1860
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
In fs/ext4/inode.c (ffff800010485760)
Location: fs/ext4/inode.c:1994
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
In fs/ext4/inode.c (c0647244)
Location: fs/ext4/inode.c:1994
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
In fs/ext4/inode.c (c0000000005aae08)
Location: fs/ext4/inode.c:1994
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
In fs/ext4/inode.c (ffffffe00030d92c)
Location: fs/ext4/inode.c:1994
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
In fs/ext4/inode.c (ffffffff813a93e5)
Location: fs/ext4/inode.c:1994
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
In fs/ext4/inode.c (ffffffff81399e75)
Location: fs/ext4/inode.c:1994
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
In fs/ext4/inode.c (ffffffff813a6c45)
Location: fs/ext4/inode.c:1994
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
In fs/ext4/inode.c (ffffffff813bb431)
Location: fs/ext4/inode.c:1994
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
