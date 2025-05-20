# Function: <code>__d_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81225770)
Location: fs/dcache.c:1546
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_make_root
  - fs/dcache.c:__d_obtain_alias
  - fs/libfs.c:mount_pseudo
```
**Symbols:**

```
ffffffff81225770-ffffffff812258e2: __d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124d860)
Location: fs/dcache.c:1557
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
  - fs/libfs.c:mount_pseudo
```
**Symbols:**

```
ffffffff8124d860-ffffffff8124da2f: __d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81260940)
Location: fs/dcache.c:1566
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
  - fs/libfs.c:mount_pseudo_xattr
```
**Symbols:**

```
ffffffff81260940-ffffffff81260b0f: __d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126e110)
Location: fs/dcache.c:1597
Inline: False
Direct callers:
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
  - fs/libfs.c:mount_pseudo_xattr
```
**Symbols:**

```
ffffffff8126e110-ffffffff8126e2dd: __d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81290a30)
Location: fs/dcache.c:1609
Inline: False
Direct callers:
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
  - fs/libfs.c:mount_pseudo_xattr
```
**Symbols:**

```
ffffffff81290a30-ffffffff81290c00: __d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b71b0)
Location: fs/dcache.c:1608
Inline: False
Direct callers:
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
  - fs/libfs.c:mount_pseudo_xattr
```
**Symbols:**

```
ffffffff812b71b0-ffffffff812b73f2: __d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812cc390)
Location: fs/dcache.c:1617
Inline: False
Direct callers:
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
  - fs/libfs.c:mount_pseudo_xattr
```
**Symbols:**

```
ffffffff812cc390-ffffffff812cc55d: __d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e8f70)
Location: fs/dcache.c:1683
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
```
**Symbols:**

```
ffffffff812e8f70-ffffffff812e9156: __d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812fab10)
Location: fs/dcache.c:1683
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
```
**Symbols:**

```
ffffffff812fab10-ffffffff812facf6: __d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813308d0)
Location: fs/dcache.c:1704
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
```
**Symbols:**

```
ffffffff813308d0-ffffffff81330ab6: __d_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133c240)
Location: fs/dcache.c:1711
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
```
**Symbols:**

```
ffffffff8133c240-ffffffff8133c426: __d_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813426d0)
Location: fs/dcache.c:1738
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
```
**Symbols:**

```
ffffffff813426d0-ffffffff813428b6: __d_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8138fff0)
Location: fs/dcache.c:1739
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
```
**Symbols:**

```
ffffffff8138fff0-ffffffff813901d6: __d_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81411be0)
Location: fs/dcache.c:1763
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_name
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
```
**Symbols:**

```
ffffffff81411be0-ffffffff81411dc0: __d_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149c940)
Location: fs/dcache.c:1763
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_name
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
```
**Symbols:**

```
ffffffff8149c940-ffffffff8149cb20: __d_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:1763
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_name
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
```
**Symbols:**

```
ffffffff814d1ce0-ffffffff814d1f38: __d_alloc (STB_LOCAL)
ffffffff820e822b-ffffffff820e8250: __d_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:1618
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
```
**Symbols:**

```
ffffffff815046b0-ffffffff81504902: __d_alloc (STB_LOCAL)
ffffffff821c4f68-ffffffff821c4f8d: __d_alloc.cold (STB_LOCAL)
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
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a9dd0)
Location: fs/dcache.c:1683
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
```
**Symbols:**

```
ffff8000103a9dd0-ffff8000103a9f88: __d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c058ae4c)
Location: fs/dcache.c:1683
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
```
**Symbols:**

```
c058ae4c-c058b000: __d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a4b20)
Location: fs/dcache.c:1683
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
```
**Symbols:**

```
c0000000004a4b20-c0000000004a4dac: __d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026fbec)
Location: fs/dcache.c:1683
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
```
**Symbols:**

```
ffffffe00026fbec-ffffffe00026fd82: __d_alloc (STB_GLOBAL)
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
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f30f0)
Location: fs/dcache.c:1683
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
```
**Symbols:**

```
ffffffff812f30f0-ffffffff812f32d6: __d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e3d20)
Location: fs/dcache.c:1683
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
```
**Symbols:**

```
ffffffff812e3d20-ffffffff812e3f06: __d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f0f00)
Location: fs/dcache.c:1683
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
```
**Symbols:**

```
ffffffff812f0f00-ffffffff812f10e6: __d_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *__d_alloc(struct super_block *sb, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813020c0)
Location: fs/dcache.c:1683
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:d_make_root
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:d_alloc_cursor
  - fs/dcache.c:d_alloc
```
**Symbols:**

```
ffffffff813020c0-ffffffff813022a6: __d_alloc (STB_GLOBAL)
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
