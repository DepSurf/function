# Function: <code>ext4_bh_unmapped</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_bh_unmapped(handle_t *handle, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81295cf0)
Location: fs/ext4/inode.c:5289
Inline: False
```
**Symbols:**

```
ffffffff81295cf0-ffffffff81295d09: ext4_bh_unmapped (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffff812cdb0a)
Location: fs/ext4/inode.c:5642
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff812e38e6)
Location: fs/ext4/inode.c:5793
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff813079f0)
Location: fs/ext4/inode.c:6018
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff8132c640)
Location: fs/ext4/inode.c:6066
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff8135ac15)
Location: fs/ext4/inode.c:6158
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff81372ed5)
Location: fs/ext4/inode.c:6211
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff8139c31a)
Location: fs/ext4/inode.c:6203
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff813b4e2a)
Location: fs/ext4/inode.c:6232
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff814002ab)
Location: fs/ext4/inode.c:5958
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff81412aa5)
Location: fs/ext4/inode.c:6053
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff81418f05)
Location: fs/ext4/inode.c:6040
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff8146c139)
Location: fs/ext4/inode.c:5981
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff814ec154)
Location: fs/ext4/inode.c:6059
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff81585ebe)
Location: fs/ext4/inode.c:6203
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff815bc79b)
Location: fs/ext4/inode.c:6015
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff815f557a)
Location: fs/ext4/inode.c:6035
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffff8000104895c4)
Location: fs/ext4/inode.c:6232
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (c064bb0c)
Location: fs/ext4/inode.c:6232
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (c0000000005b0628)
Location: fs/ext4/inode.c:6232
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffe000310d70)
Location: fs/ext4/inode.c:6232
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff813ad40a)
Location: fs/ext4/inode.c:6232
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff8139de9a)
Location: fs/ext4/inode.c:6232
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff813aac6a)
Location: fs/ext4/inode.c:6232
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/ext4/inode.c (ffffffff813bf5b5)
Location: fs/ext4/inode.c:6232
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
