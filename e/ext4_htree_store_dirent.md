# Function: <code>ext4_htree_store_dirent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct ext4_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81291720)
Location: fs/ext4/dir.c:418
Inline: False
Direct callers:
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
**Symbols:**

```
ffffffff81291720-ffffffff81291834: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff812bec80)
Location: fs/ext4/dir.c:434
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
**Symbols:**

```
ffffffff812bec80-ffffffff812bed95: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff812d42a0)
Location: fs/ext4/dir.c:435
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/inline.c:htree_inlinedir_to_tree
```
**Symbols:**

```
ffffffff812d42a0-ffffffff812d43b5: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff812e5ca0)
Location: fs/ext4/dir.c:435
Inline: False
Direct callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff812e5ca0-ffffffff812e5dab: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff8130a6b0)
Location: fs/ext4/dir.c:436
Inline: False
Direct callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff8130a6b0-ffffffff8130a7bb: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81338660)
Location: fs/ext4/dir.c:437
Inline: False
Direct callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81338660-ffffffff8133876b: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff8134f910)
Location: fs/ext4/dir.c:437
Inline: False
Direct callers:
  - fs/ext4/inline.c:htree_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff8134f910-ffffffff8134fa1b: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81378580)
Location: fs/ext4/dir.c:437
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81378580-ffffffff81378694: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81390940)
Location: fs/ext4/dir.c:444
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81390940-ffffffff81390a54: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813dbf40)
Location: fs/ext4/dir.c:443
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff813dbf40-ffffffff813dc046: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813ed9d0)
Location: fs/ext4/dir.c:441
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff813ed9d0-ffffffff813edad6: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813f4080)
Location: fs/ext4/dir.c:460
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff813f4080-ffffffff813f4186: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff814461c0)
Location: fs/ext4/dir.c:460
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff814461c0-ffffffff814462c6: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff814c22c0)
Location: fs/ext4/dir.c:459
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff814c22c0-ffffffff814c23d3: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff8155a530)
Location: fs/ext4/dir.c:459
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff8155a530-ffffffff8155a643: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/dir.c (0)
Location: fs/ext4/dir.c:459
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff820ec0a6-ffffffff820ec0cb: ext4_htree_store_dirent.cold (STB_LOCAL)
ffffffff815922d0-ffffffff81592467: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff815cb040)
Location: fs/ext4/dir.c:459
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff815cb040-ffffffff815cb181: ext4_htree_store_dirent (STB_GLOBAL)
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
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffff800010463258)
Location: fs/ext4/dir.c:444
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffff800010463258-ffff800010463398: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (c06239c4)
Location: fs/ext4/dir.c:444
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
c06239c4-c0623aec: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (c000000000580210)
Location: fs/ext4/dir.c:444
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
c000000000580210-c0000000005803cc: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffe0002f1d0c)
Location: fs/ext4/dir.c:444
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffe0002f1d0c-ffffffe0002f1e18: ext4_htree_store_dirent (STB_GLOBAL)
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
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81388f20)
Location: fs/ext4/dir.c:444
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81388f20-ffffffff81389034: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813799b0)
Location: fs/ext4/dir.c:444
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff813799b0-ffffffff81379ac4: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81386880)
Location: fs/ext4/dir.c:444
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff81386880-ffffffff81386994: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_htree_store_dirent(struct file *dir_file, __u32 hash, __u32 minor_hash, struct ext4_dir_entry_2 *dirent, struct fscrypt_str *ent_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff8139a560)
Location: fs/ext4/dir.c:444
Inline: False
Direct callers:
  - fs/ext4/inline.c:ext4_inlinedir_to_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:ext4_htree_fill_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
  - fs/ext4/namei.c:htree_dirblock_to_tree
```
**Symbols:**

```
ffffffff8139a560-ffffffff8139a674: ext4_htree_store_dirent (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ext4_str *ent_name</code> ➡️ <code>struct fscrypt_str *ent_name</code>
</li>
</ul>
</details>
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
