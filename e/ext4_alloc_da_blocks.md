# Function: <code>ext4_alloc_da_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812998f0)
Location: fs/ext4/inode.c:2881
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/inode.c:ext4_change_inode_journal_flag
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/migrate.c:ext4_ind_migrate
```
**Symbols:**

```
ffffffff812998f0-ffffffff81299961: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c7010)
Location: fs/ext4/inode.c:3070
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/migrate.c:ext4_ind_migrate
```
**Symbols:**

```
ffffffff812c7010-ffffffff812c707a: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dcb00)
Location: fs/ext4/inode.c:3097
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/migrate.c:ext4_ind_migrate
```
**Symbols:**

```
ffffffff812dcb00-ffffffff812dcb6a: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81301380)
Location: fs/ext4/inode.c:3213
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff81301380-ffffffff813013ea: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81325d30)
Location: fs/ext4/inode.c:3206
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff81325d30-ffffffff81325d9d: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81353fd0)
Location: fs/ext4/inode.c:3207
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff81353fd0-ffffffff8135403d: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136c240)
Location: fs/ext4/inode.c:3238
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff8136c240-ffffffff8136c2ad: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81395810)
Location: fs/ext4/inode.c:3251
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff81395810-ffffffff8139587d: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ae1e0)
Location: fs/ext4/inode.c:3214
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff813ae1e0-ffffffff813ae24d: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813fa1b0)
Location: fs/ext4/inode.c:3107
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff813fa1b0-ffffffff813fa21d: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140c790)
Location: fs/ext4/inode.c:3127
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff8140c790-ffffffff8140c7ea: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81412910)
Location: fs/ext4/inode.c:3126
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff81412910-ffffffff8141296a: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81465c00)
Location: fs/ext4/inode.c:3049
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff81465c00-ffffffff81465c57: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e55b0)
Location: fs/ext4/inode.c:3093
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff814e55b0-ffffffff814e5626: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8157ec90)
Location: fs/ext4/inode.c:3181
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff8157ec90-ffffffff8157ed06: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b6150)
Location: fs/ext4/inode.c:2995
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff815b6150-ffffffff815b61c6: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815eeef0)
Location: fs/ext4/inode.c:3034
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff815eeef0-ffffffff815eef66: ext4_alloc_da_blocks (STB_GLOBAL)
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
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010482c48)
Location: fs/ext4/inode.c:3214
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffff800010482c48-ffff800010482ce8: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c06440d4)
Location: fs/ext4/inode.c:3214
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
c06440d4-c0644180: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a7910)
Location: fs/ext4/inode.c:3214
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_release_file
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
c0000000005a7910-c0000000005a79f4: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030b43c)
Location: fs/ext4/inode.c:3214
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffe00030b43c-ffffffe00030b4c8: ext4_alloc_da_blocks (STB_GLOBAL)
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
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a67c0)
Location: fs/ext4/inode.c:3214
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff813a67c0-ffffffff813a682d: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81397250)
Location: fs/ext4/inode.c:3214
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff81397250-ffffffff813972bd: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a4020)
Location: fs/ext4/inode.c:3214
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff813a4020-ffffffff813a408d: ext4_alloc_da_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_alloc_da_blocks(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b8700)
Location: fs/ext4/inode.c:3214
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/migrate.c:ext4_ind_migrate
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff813b8700-ffffffff813b8782: ext4_alloc_da_blocks (STB_GLOBAL)
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
