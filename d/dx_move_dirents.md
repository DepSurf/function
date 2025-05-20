# Function: <code>dx_move_dirents</code>

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
In fs/ext4/namei.c (ffffffff812a33f3)
Location: fs/ext4/namei.c:1633
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (ffffffff812d233e)
Location: fs/ext4/namei.c:1660
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (ffffffff812e809e)
Location: fs/ext4/namei.c:1664
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (ffffffff81317936)
Location: fs/ext4/namei.c:1626
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (ffffffff8133c1a6)
Location: fs/ext4/namei.c:1621
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (ffffffff8136a805)
Location: fs/ext4/namei.c:1623
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (ffffffff81382cc5)
Location: fs/ext4/namei.c:1624
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (ffffffff813abfcc)
Location: fs/ext4/namei.c:1761
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (ffffffff813c4efc)
Location: fs/ext4/namei.c:1762
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (ffffffff81411480)
Location: fs/ext4/namei.c:1768
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (ffffffff81424730)
Location: fs/ext4/namei.c:1758
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (ffffffff8142b230)
Location: fs/ext4/namei.c:1844
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (ffffffff8147f229)
Location: fs/ext4/namei.c:1845
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ext4_dir_entry_2 *dx_move_dirents(struct inode *dir, char *from, char *to, struct dx_map_entry *map, int count, unsigned int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81500080)
Location: fs/ext4/namei.c:1891
Inline: False
Direct callers:
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff81500080-ffffffff815001a7: dx_move_dirents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ext4_dir_entry_2 *dx_move_dirents(struct inode *dir, char *from, char *to, struct dx_map_entry *map, int count, unsigned int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8159aa50)
Location: fs/ext4/namei.c:1896
Inline: False
Direct callers:
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff8159aa50-ffffffff8159ab77: dx_move_dirents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ext4_dir_entry_2 *dx_move_dirents(struct inode *dir, char *from, char *to, struct dx_map_entry *map, int count, unsigned int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d12f0)
Location: fs/ext4/namei.c:1911
Inline: False
Direct callers:
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff815d12f0-ffffffff815d1410: dx_move_dirents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ext4_dir_entry_2 *dx_move_dirents(struct inode *dir, char *from, char *to, struct dx_map_entry *map, int count, unsigned int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81609a90)
Location: fs/ext4/namei.c:1915
Inline: False
Direct callers:
  - fs/ext4/namei.c:do_split
```
**Symbols:**

```
ffffffff81609a90-ffffffff81609bb0: dx_move_dirents (STB_LOCAL)
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
In fs/ext4/namei.c (ffff80001049cb08)
Location: fs/ext4/namei.c:1762
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (c065e8c0)
Location: fs/ext4/namei.c:1762
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (c0000000005c7c50)
Location: fs/ext4/namei.c:1762
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (ffffffe00031fab0)
Location: fs/ext4/namei.c:1762
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (ffffffff813bd4dc)
Location: fs/ext4/namei.c:1762
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (ffffffff813adf6c)
Location: fs/ext4/namei.c:1762
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (ffffffff813baebc)
Location: fs/ext4/namei.c:1762
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
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
In fs/ext4/namei.c (ffffffff813cfa5c)
Location: fs/ext4/namei.c:1762
Inline: True
Inline callers:
  - fs/ext4/namei.c:do_split
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
