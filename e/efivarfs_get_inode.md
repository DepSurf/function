# Function: <code>efivarfs_get_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81320d20)
Location: fs/efivarfs/inode.c:17
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81320d20-ffffffff81320dda: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81356380)
Location: fs/efivarfs/inode.c:18
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81356380-ffffffff8135643c: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff8136c7a0)
Location: fs/efivarfs/inode.c:18
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff8136c7a0-ffffffff8136c854: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81380ce0)
Location: fs/efivarfs/inode.c:18
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81380ce0-ffffffff81380d9a: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff813a5cf0)
Location: fs/efivarfs/inode.c:18
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff813a5cf0-ffffffff813a5daa: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff813d4fb0)
Location: fs/efivarfs/inode.c:18
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff813d4fb0-ffffffff813d506e: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff813ef5f0)
Location: fs/efivarfs/inode.c:18
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff813ef5f0-ffffffff813ef6ae: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff8141b8d0)
Location: fs/efivarfs/inode.c:15
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff8141b8d0-ffffffff8141b997: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81435720)
Location: fs/efivarfs/inode.c:15
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81435720-ffffffff814357e7: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81485430)
Location: fs/efivarfs/inode.c:15
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81485430-ffffffff814854f7: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff814a2a60)
Location: fs/efivarfs/inode.c:16
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff814a2a60-ffffffff814a2b27: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff814a8c40)
Location: fs/efivarfs/inode.c:19
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff814a8c40-ffffffff814a8d12: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81500f70)
Location: fs/efivarfs/inode.c:19
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81500f70-ffffffff81501042: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff815922c0)
Location: fs/efivarfs/inode.c:19
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff815922c0-ffffffff815923a9: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81639bf0)
Location: fs/efivarfs/inode.c:19
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81639bf0-ffffffff81639cd9: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81672050)
Location: fs/efivarfs/inode.c:19
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81672050-ffffffff81672139: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff816ae030)
Location: fs/efivarfs/inode.c:19
Inline: False
Direct callers:
  - fs/efivarfs/inode.c:efivarfs_create
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff816ae030-ffffffff816ae11e: efivarfs_get_inode (STB_GLOBAL)
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
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffff80001051b618)
Location: fs/efivarfs/inode.c:15
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffff80001051b618-ffff80001051b6fc: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (c06d8030)
Location: fs/efivarfs/inode.c:15
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
c06d8030-c06d8128: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff8142dd00)
Location: fs/efivarfs/inode.c:15
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff8142dd00-ffffffff8142ddc7: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff8141e780)
Location: fs/efivarfs/inode.c:15
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff8141e780-ffffffff8141e847: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81429ea0)
Location: fs/efivarfs/inode.c:15
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81429ea0-ffffffff81429f67: efivarfs_get_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *efivarfs_get_inode(struct super_block *sb, const struct inode *dir, int mode, dev_t dev, bool is_removable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/inode.c (ffffffff81440d60)
Location: fs/efivarfs/inode.c:15
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_fill_super
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81440d60-ffffffff81440e27: efivarfs_get_inode (STB_GLOBAL)
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
