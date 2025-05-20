# Function: <code>ext4_dx_find_entry</code>

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
In fs/ext4/namei.c (ffffffff812a421f)
Location: fs/ext4/namei.c:1501
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff812d313a)
Location: fs/ext4/namei.c:1511
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff812e8e8a)
Location: fs/ext4/namei.c:1513
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81318200)
Location: fs/ext4/namei.c:1483
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff81318200-ffffffff81318372: ext4_dx_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8133ca60)
Location: fs/ext4/namei.c:1488
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff8133ca60-ffffffff8133cbd2: ext4_dx_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8136afa0)
Location: fs/ext4/namei.c:1490
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff8136afa0-ffffffff8136b129: ext4_dx_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81383460)
Location: fs/ext4/namei.c:1491
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff81383460-ffffffff813835e9: ext4_dx_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813acc70)
Location: fs/ext4/namei.c:1622
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff813acc70-ffffffff813acdfb: ext4_dx_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c5bb0)
Location: fs/ext4/namei.c:1623
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff813c5bb0-ffffffff813c5d3b: ext4_dx_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81411fe0)
Location: fs/ext4/namei.c:1629
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff81411fe0-ffffffff814121ac: ext4_dx_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81425480)
Location: fs/ext4/namei.c:1619
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff81425480-ffffffff8142564c: ext4_dx_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142c090)
Location: fs/ext4/namei.c:1706
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff8142c090-ffffffff8142c25c: ext4_dx_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:1707
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff8147ff30-ffffffff81480105: ext4_dx_find_entry (STB_LOCAL)
ffffffff81cccc59-ffffffff81cccc80: ext4_dx_find_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:1753
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff81502e30-ffffffff8150301e: ext4_dx_find_entry (STB_LOCAL)
ffffffff81e7fb36-ffffffff81e7fb5f: ext4_dx_find_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:1758
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff8159d960-ffffffff8159db4e: ext4_dx_find_entry (STB_LOCAL)
ffffffff8206fff6-ffffffff8207001f: ext4_dx_find_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:1773
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff815d41c0-ffffffff815d43ae: ext4_dx_find_entry (STB_LOCAL)
ffffffff820efb8f-ffffffff820efbb8: ext4_dx_find_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:1777
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff8160c870-ffffffff8160ca5e: ext4_dx_find_entry (STB_LOCAL)
ffffffff821ccc67-ffffffff821ccc90: ext4_dx_find_entry.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049d6a8)
Location: fs/ext4/namei.c:1623
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffff80001049d6a8-ffff80001049d834: ext4_dx_find_entry (STB_LOCAL)
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
In fs/ext4/namei.c (c065f6f8)
Location: fs/ext4/namei.c:1623
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005c8ca0)
Location: fs/ext4/namei.c:1623
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
c0000000005c8ca0-c0000000005c8eac: ext4_dx_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe0003203da)
Location: fs/ext4/namei.c:1623
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffe0003203da-ffffffe00032051c: ext4_dx_find_entry (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813be190)
Location: fs/ext4/namei.c:1623
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff813be190-ffffffff813be31b: ext4_dx_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813aec20)
Location: fs/ext4/namei.c:1623
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff813aec20-ffffffff813aedab: ext4_dx_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bb790)
Location: fs/ext4/namei.c:1623
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff813bb790-ffffffff813bb91b: ext4_dx_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct buffer_head *ext4_dx_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d0720)
Location: fs/ext4/namei.c:1623
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
```
**Symbols:**

```
ffffffff813d0720-ffffffff813d08ab: ext4_dx_find_entry (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
