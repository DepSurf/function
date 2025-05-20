# Function: <code>ext4_delete_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812a6840)
Location: fs/ext4/namei.c:2339
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff812a6840-ffffffff812a69a6: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d58b0)
Location: fs/ext4/namei.c:2363
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
```
**Symbols:**

```
ffffffff812d58b0-ffffffff812d5a19: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812eb5b0)
Location: fs/ext4/namei.c:2365
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
```
**Symbols:**

```
ffffffff812eb5b0-ffffffff812eb719: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8131b260)
Location: fs/ext4/namei.c:2341
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
```
**Symbols:**

```
ffffffff8131b260-ffffffff8131b397: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8133f980)
Location: fs/ext4/namei.c:2336
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
```
**Symbols:**

```
ffffffff8133f980-ffffffff8133fab7: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8136d8a0)
Location: fs/ext4/namei.c:2338
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
```
**Symbols:**

```
ffffffff8136d8a0-ffffffff8136d9ca: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81385d20)
Location: fs/ext4/namei.c:2339
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
```
**Symbols:**

```
ffffffff81385d20-ffffffff81385e4a: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813afd00)
Location: fs/ext4/namei.c:2479
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
```
**Symbols:**

```
ffffffff813afd00-ffffffff813afe2a: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c8cc0)
Location: fs/ext4/namei.c:2487
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
```
**Symbols:**

```
ffffffff813c8cc0-ffffffff813c8dea: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81414780)
Location: fs/ext4/namei.c:2507
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_delete
  - fs/ext4/namei.c:ext4_rename_delete
```
**Symbols:**

```
ffffffff81414780-ffffffff814148ac: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81427dd0)
Location: fs/ext4/namei.c:2494
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename_delete
  - fs/ext4/namei.c:ext4_rename_delete
  - fs/ext4/namei.c:__ext4_unlink
```
**Symbols:**

```
ffffffff81427dd0-ffffffff81427ef8: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142ea60)
Location: fs/ext4/namei.c:2620
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_unlink
```
**Symbols:**

```
ffffffff8142ea60-ffffffff8142eb88: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81483200)
Location: fs/ext4/namei.c:2627
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:__ext4_unlink
```
**Symbols:**

```
ffffffff81483200-ffffffff8148332e: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81506240)
Location: fs/ext4/namei.c:2677
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
```
**Symbols:**

```
ffffffff81506240-ffffffff8150638c: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815a0ce0)
Location: fs/ext4/namei.c:2690
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
```
**Symbols:**

```
ffffffff815a0ce0-ffffffff815a0e2c: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d7660)
Location: fs/ext4/namei.c:2710
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_rmdir
```
**Symbols:**

```
ffffffff815d7660-ffffffff815d77a6: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8160fcd0)
Location: fs/ext4/namei.c:2711
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_rmdir
```
**Symbols:**

```
ffffffff8160fcd0-ffffffff8160fe16: ext4_delete_entry (STB_LOCAL)
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
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff8000104a0708)
Location: fs/ext4/namei.c:2487
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
```
**Symbols:**

```
ffff8000104a0708-ffff8000104a0898: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0662844)
Location: fs/ext4/namei.c:2487
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
```
**Symbols:**

```
c0662844-c06629fc: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005ccba0)
Location: fs/ext4/namei.c:2487
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
```
**Symbols:**

```
c0000000005ccba0-c0000000005ccd74: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe000322a20)
Location: fs/ext4/namei.c:2487
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
```
**Symbols:**

```
ffffffe000322a20-ffffffe000322b28: ext4_delete_entry (STB_LOCAL)
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
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c12a0)
Location: fs/ext4/namei.c:2487
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
```
**Symbols:**

```
ffffffff813c12a0-ffffffff813c13ca: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813b1d30)
Location: fs/ext4/namei.c:2487
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
```
**Symbols:**

```
ffffffff813b1d30-ffffffff813b1e5a: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813be750)
Location: fs/ext4/namei.c:2487
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
```
**Symbols:**

```
ffffffff813be750-ffffffff813be87a: ext4_delete_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_delete_entry(handle_t *handle, struct inode *dir, struct ext4_dir_entry_2 *de_del, struct buffer_head *bh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d3830)
Location: fs/ext4/namei.c:2487
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_find_delete_entry
```
**Symbols:**

```
ffffffff813d3830-ffffffff813d395a: ext4_delete_entry (STB_LOCAL)
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
