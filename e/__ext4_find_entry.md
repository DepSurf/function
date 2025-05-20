# Function: <code>__ext4_find_entry</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct buffer_head *__ext4_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ace00)
Location: fs/ext4/namei.c:1439
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff813ace00-ffffffff813ad23c: __ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct buffer_head *__ext4_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c5d40)
Location: fs/ext4/namei.c:1439
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff813c5d40-ffffffff813c6178: __ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct buffer_head *__ext4_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814121b0)
Location: fs/ext4/namei.c:1443
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff814121b0-ffffffff8141260f: __ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct buffer_head *__ext4_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81425650)
Location: fs/ext4/namei.c:1432
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff81425650-ffffffff81425aaf: __ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct buffer_head *__ext4_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142c260)
Location: fs/ext4/namei.c:1519
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff8142c260-ffffffff8142c6bb: __ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__ext4_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:1520
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff81480110-ffffffff814805c0: __ext4_find_entry (STB_LOCAL)
ffffffff81cccc80-ffffffff81cccd05: __ext4_find_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__ext4_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:1566
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff81503020-ffffffff815034ec: __ext4_find_entry (STB_LOCAL)
ffffffff81e7fb5f-ffffffff81e7fbe4: __ext4_find_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__ext4_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:1571
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff8159db60-ffffffff8159e01c: __ext4_find_entry (STB_LOCAL)
ffffffff8207001f-ffffffff820700a4: __ext4_find_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__ext4_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:1587
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff815d43c0-ffffffff815d492f: __ext4_find_entry (STB_LOCAL)
ffffffff820efbb8-ffffffff820efc14: __ext4_find_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct buffer_head *__ext4_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:1591
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff8160ca70-ffffffff8160cfdf: __ext4_find_entry (STB_LOCAL)
ffffffff821ccc90-ffffffff821cccec: __ext4_find_entry.cold (STB_LOCAL)
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
struct buffer_head *__ext4_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049d838)
Location: fs/ext4/namei.c:1439
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffff80001049d838-ffff80001049dc78: __ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct buffer_head *__ext4_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c065f350)
Location: fs/ext4/namei.c:1439
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
c065f350-c065f908: __ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct buffer_head *__ext4_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005c8eb0)
Location: fs/ext4/namei.c:1439
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
c0000000005c8eb0-c0000000005c94f4: __ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct buffer_head *__ext4_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe00032051c)
Location: fs/ext4/namei.c:1439
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffe00032051c-ffffffe000320860: __ext4_find_entry (STB_LOCAL)
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
struct buffer_head *__ext4_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813be320)
Location: fs/ext4/namei.c:1439
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff813be320-ffffffff813be758: __ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct buffer_head *__ext4_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813aedb0)
Location: fs/ext4/namei.c:1439
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff813aedb0-ffffffff813af1e8: __ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct buffer_head *__ext4_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bb920)
Location: fs/ext4/namei.c:1439
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff813bb920-ffffffff813bbd58: __ext4_find_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct buffer_head *__ext4_find_entry(struct inode *dir, struct ext4_filename *fname, struct ext4_dir_entry_2 **res_dir, int *inlined);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d08b0)
Location: fs/ext4/namei.c:1439
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff813d08b0-ffffffff813d0ce6: __ext4_find_entry (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
