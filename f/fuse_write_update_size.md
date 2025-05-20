# Function: <code>fuse_write_update_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813188c0)
Location: fs/fuse/file.c:970
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff813188c0-ffffffff81318927: fuse_write_update_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134d300)
Location: fs/fuse/file.c:983
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8134d300-ffffffff8134d367: fuse_write_update_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81362c10)
Location: fs/fuse/file.c:984
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81362c10-ffffffff81362c77: fuse_write_update_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813775a0)
Location: fs/fuse/file.c:979
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff813775a0-ffffffff81377607: fuse_write_update_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8139c340)
Location: fs/fuse/file.c:987
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8139c340-ffffffff8139c3a7: fuse_write_update_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813cb770)
Location: fs/fuse/file.c:988
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff813cb770-ffffffff813cb7d7: fuse_write_update_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e4820)
Location: fs/fuse/file.c:993
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/file.c:fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff813e4820-ffffffff813e4887: fuse_write_update_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814104f0)
Location: fs/fuse/file.c:1005
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff814104f0-ffffffff81410562: fuse_write_update_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8142a100)
Location: fs/fuse/file.c:1080
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8142a100-ffffffff8142a172: fuse_write_update_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8147a1b0)
Location: fs/fuse/file.c:1053
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8147a1b0-ffffffff8147a222: fuse_write_update_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81494ea0)
Location: fs/fuse/file.c:1076
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_direct_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff81494ea0-ffffffff81494f15: fuse_write_update_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81499f00)
Location: fs/fuse/file.c:1071
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff81499f00-ffffffff81499f75: fuse_write_update_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814f1920)
Location: fs/fuse/file.c:1075
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify_store
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
  - fs/fuse/dax.c:fuse_dax_write_iter
```
**Symbols:**

```
ffffffff814f1920-ffffffff814f1995: fuse_write_update_size (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050e0d8)
Location: fs/fuse/file.c:1080
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffff80001050e0d8-ffff80001050e1a8: fuse_write_update_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06c9704)
Location: fs/fuse/file.c:1080
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
c06c9704-c06c97c8: fuse_write_update_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c000000000654fe0)
Location: fs/fuse/file.c:1080
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
c000000000654fe0-c0000000006550e0: fuse_write_update_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe000378dc8)
Location: fs/fuse/file.c:1080
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffe000378dc8-ffffffe000378e62: fuse_write_update_size (STB_GLOBAL)
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
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814226e0)
Location: fs/fuse/file.c:1080
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff814226e0-ffffffff81422752: fuse_write_update_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81413160)
Location: fs/fuse/file.c:1080
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81413160-ffffffff814131d2: fuse_write_update_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141e880)
Location: fs/fuse/file.c:1080
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8141e880-ffffffff8141e8f2: fuse_write_update_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool fuse_write_update_size(struct inode *inode, loff_t pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814355f0)
Location: fs/fuse/file.c:1080
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/file.c:__fuse_copy_file_range
  - fs/fuse/file.c:fuse_file_fallocate
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_file_write_iter
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff814355f0-ffffffff81435660: fuse_write_update_size (STB_GLOBAL)
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
