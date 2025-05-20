# Function: <code>ext4_free_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff812d8b10)
Location: fs/ext4/indirect.c:1008
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
```
**Symbols:**

```
ffffffff812d8b10-ffffffff812d8c67: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813088b0)
Location: fs/ext4/indirect.c:896
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff813088b0-ffffffff81308a06: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8131e8c0)
Location: fs/ext4/indirect.c:896
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
```
**Symbols:**

```
ffffffff8131e8c0-ffffffff8131ea16: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff812f74a0)
Location: fs/ext4/indirect.c:897
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff812f74a0-ffffffff812f7600: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8131bae0)
Location: fs/ext4/indirect.c:898
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff8131bae0-ffffffff8131bc40: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813499e0)
Location: fs/ext4/indirect.c:904
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff813499e0-ffffffff81349b40: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81361ba0)
Location: fs/ext4/indirect.c:904
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff81361ba0-ffffffff81361d00: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8138af90)
Location: fs/ext4/indirect.c:898
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff8138af90-ffffffff8138b104: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813a39e0)
Location: fs/ext4/indirect.c:898
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff813a39e0-ffffffff813a3b54: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813efc20)
Location: fs/ext4/indirect.c:902
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff813efc20-ffffffff813efd98: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81402380)
Location: fs/ext4/indirect.c:903
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff81402380-ffffffff814024f8: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81408780)
Location: fs/ext4/indirect.c:903
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff81408780-ffffffff814088f8: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8145b1e0)
Location: fs/ext4/indirect.c:906
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff8145b1e0-ffffffff8145b362: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff814d8fa0)
Location: fs/ext4/indirect.c:906
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff814d8fa0-ffffffff814d9129: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81571dd0)
Location: fs/ext4/indirect.c:913
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff81571dd0-ffffffff81571f59: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff815a9b60)
Location: fs/ext4/indirect.c:921
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff815a9b60-ffffffff815a9ce9: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff815e2900)
Location: fs/ext4/indirect.c:921
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff815e2900-ffffffff815e2a89: ext4_free_data (STB_LOCAL)
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
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffff800010477050)
Location: fs/ext4/indirect.c:898
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffff800010477050-ffff8000104771d4: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (c0638b3c)
Location: fs/ext4/indirect.c:898
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
c0638b3c-c0638d44: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (c000000000599140)
Location: fs/ext4/indirect.c:898
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
c000000000599140-c00000000059936c: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffe0003024f0)
Location: fs/ext4/indirect.c:898
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffe0003024f0-ffffffe00030260a: ext4_free_data (STB_LOCAL)
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
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8139bfc0)
Location: fs/ext4/indirect.c:898
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff8139bfc0-ffffffff8139c134: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff8138ca50)
Location: fs/ext4/indirect.c:898
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff8138ca50-ffffffff8138cbc4: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81399820)
Location: fs/ext4/indirect.c:898
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff81399820-ffffffff81399994: ext4_free_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_free_data(handle_t *handle, struct inode *inode, struct buffer_head *this_bh, __le32 *first, __le32 *last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813ad910)
Location: fs/ext4/indirect.c:898
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_remove_space
  - fs/ext4/indirect.c:ext4_ind_truncate
  - fs/ext4/indirect.c:ext4_free_branches
```
**Symbols:**

```
ffffffff813ad910-ffffffff813ada84: ext4_free_data (STB_LOCAL)
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
