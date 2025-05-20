# Function: <code>configfs_create</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int configfs_create(struct dentry *dentry, umode_t mode, void (*init)(struct inode *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff812de150)
Location: fs/configfs/inode.c:181
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff812de150-ffffffff812de227: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int configfs_create(struct dentry *dentry, umode_t mode, void (*init)(struct inode *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81302a90)
Location: fs/configfs/inode.c:181
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff81302a90-ffffffff81302b69: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int configfs_create(struct dentry *dentry, umode_t mode, void (*init)(struct inode *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff813309e0)
Location: fs/configfs/inode.c:181
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff813309e0-ffffffff81330ab2: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int configfs_create(struct dentry *dentry, umode_t mode, void (*init)(struct inode *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81347dd0)
Location: fs/configfs/inode.c:181
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff81347dd0-ffffffff81347ea2: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int configfs_create(struct dentry *dentry, umode_t mode, void (*init)(struct inode *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81370260)
Location: fs/configfs/inode.c:167
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff81370260-ffffffff81370330: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *configfs_create(struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81388790)
Location: fs/configfs/inode.c:164
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff81388790-ffffffff81388818: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *configfs_create(struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff813d34d0)
Location: fs/configfs/inode.c:164
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff813d34d0-ffffffff813d3558: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *configfs_create(struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff813e5210)
Location: fs/configfs/inode.c:164
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff813e5210-ffffffff813e5298: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *configfs_create(struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff813ebe20)
Location: fs/configfs/inode.c:163
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff813ebe20-ffffffff813ebea8: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *configfs_create(struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff8143dbc0)
Location: fs/configfs/inode.c:157
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff8143dbc0-ffffffff8143dc48: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *configfs_create(struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff814b9480)
Location: fs/configfs/inode.c:157
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff814b9480-ffffffff814b9523: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *configfs_create(struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81550be0)
Location: fs/configfs/inode.c:157
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff81550be0-ffffffff81550c83: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *configfs_create(struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff815888c0)
Location: fs/configfs/inode.c:157
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff815888c0-ffffffff81588963: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *configfs_create(struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff815c14a0)
Location: fs/configfs/inode.c:156
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_lookup
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff815c14a0-ffffffff815c153b: configfs_create (STB_GLOBAL)
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
struct inode *configfs_create(struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffff800010458a00)
Location: fs/configfs/inode.c:164
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffff800010458a00-ffff800010458ab0: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *configfs_create(struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (c061a7a8)
Location: fs/configfs/inode.c:164
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
c061a7a8-c061a864: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *configfs_create(struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (c000000000573490)
Location: fs/configfs/inode.c:164
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
c000000000573490-c000000000573568: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *configfs_create(struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffe0002e9a44)
Location: fs/configfs/inode.c:164
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffe0002e9a44-ffffffe0002e9ac6: configfs_create (STB_GLOBAL)
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
struct inode *configfs_create(struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81380d70)
Location: fs/configfs/inode.c:164
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff81380d70-ffffffff81380df8: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *configfs_create(struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81371800)
Location: fs/configfs/inode.c:164
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff81371800-ffffffff81371888: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *configfs_create(struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff8137e840)
Location: fs/configfs/inode.c:164
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff8137e840-ffffffff8137e8c8: configfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *configfs_create(struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/inode.c (ffffffff81392350)
Location: fs/configfs/inode.c:164
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_create_link
  - fs/configfs/dir.c:configfs_create_dir
```
**Symbols:**

```
ffffffff81392350-ffffffff813923d8: configfs_create (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void (*init)(struct inode *)</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct inode *</code>
</li>
</ul>
</details>
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
