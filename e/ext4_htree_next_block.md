# Function: <code>ext4_htree_next_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812a2940)
Location: fs/ext4/namei.c:884
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_find_entry
```
**Symbols:**

```
ffffffff812a2940-ffffffff812a2a52: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d1880)
Location: fs/ext4/namei.c:885
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff812d1880-ffffffff812d199f: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812e7600)
Location: fs/ext4/namei.c:887
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff812e7600-ffffffff812e771f: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81316f70)
Location: fs/ext4/namei.c:901
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff81316f70-ffffffff8131709c: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8133b7e0)
Location: fs/ext4/namei.c:902
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff8133b7e0-ffffffff8133b90c: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81369ec0)
Location: fs/ext4/namei.c:903
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff81369ec0-ffffffff81369fdf: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81382380)
Location: fs/ext4/namei.c:904
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff81382380-ffffffff8138249f: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ab5c0)
Location: fs/ext4/namei.c:922
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff813ab5c0-ffffffff813ab6d3: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c44f0)
Location: fs/ext4/namei.c:922
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff813c44f0-ffffffff813c4603: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81410c60)
Location: fs/ext4/namei.c:929
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff81410c60-ffffffff81410d77: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81424120)
Location: fs/ext4/namei.c:918
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff81424120-ffffffff81424237: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142ab30)
Location: fs/ext4/namei.c:951
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff8142ab30-ffffffff8142ac47: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8147eb10)
Location: fs/ext4/namei.c:952
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff8147eb10-ffffffff8147ec27: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81501820)
Location: fs/ext4/namei.c:991
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff81501820-ffffffff8150196a: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8159c3a0)
Location: fs/ext4/namei.c:996
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff8159c3a0-ffffffff8159c4ea: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d2bc0)
Location: fs/ext4/namei.c:1004
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff815d2bc0-ffffffff815d2d0a: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8160b350)
Location: fs/ext4/namei.c:1006
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff8160b350-ffffffff8160b49a: ext4_htree_next_block (STB_LOCAL)
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
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049bfe0)
Location: fs/ext4/namei.c:922
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffff80001049bfe0-ffff80001049c130: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c065dd18)
Location: fs/ext4/namei.c:922
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
c065dd18-c065de54: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005c6dc0)
Location: fs/ext4/namei.c:922
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
c0000000005c6dc0-c0000000005c6fa4: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe00031f246)
Location: fs/ext4/namei.c:922
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffe00031f246-ffffffe00031f34c: ext4_htree_next_block (STB_LOCAL)
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
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bcad0)
Location: fs/ext4/namei.c:922
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff813bcad0-ffffffff813bcbe3: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ad560)
Location: fs/ext4/namei.c:922
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff813ad560-ffffffff813ad673: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ba4b0)
Location: fs/ext4/namei.c:922
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff813ba4b0-ffffffff813ba5c3: ext4_htree_next_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_htree_next_block(struct inode *dir, __u32 hash, struct dx_frame *frame, struct dx_frame *frames, __u32 *start_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813cf050)
Location: fs/ext4/namei.c:922
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_dx_find_entry
  - fs/ext4/namei.c:ext4_htree_fill_tree
```
**Symbols:**

```
ffffffff813cf050-ffffffff813cf163: ext4_htree_next_block (STB_LOCAL)
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
