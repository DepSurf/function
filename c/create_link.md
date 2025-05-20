# Function: <code>create_link</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff812e14df)
Location: fs/configfs/symlink.c:72
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81305e19)
Location: fs/configfs/symlink.c:72
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81333e25)
Location: fs/configfs/symlink.c:72
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff8134b191)
Location: fs/configfs/symlink.c:72
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81373b1e)
Location: fs/configfs/symlink.c:58
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int create_link(struct config_item *parent_item, struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff8138b9c0)
Location: fs/configfs/symlink.c:79
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff8138b9c0-ffffffff8138bcb2: create_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int create_link(struct config_item *parent_item, struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff813d6e40)
Location: fs/configfs/symlink.c:79
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff813d6e40-ffffffff813d6fef: create_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int create_link(struct config_item *parent_item, struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff813e8ae0)
Location: fs/configfs/symlink.c:79
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff813e8ae0-ffffffff813e8c8f: create_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int create_link(struct config_item *parent_item, struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff813ef650)
Location: fs/configfs/symlink.c:77
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff813ef650-ffffffff813ef7ff: create_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int create_link(struct config_item *parent_item, struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81441540)
Location: fs/configfs/symlink.c:77
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff81441540-ffffffff814416ef: create_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int create_link(struct config_item *parent_item, struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff814bd130)
Location: fs/configfs/symlink.c:77
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff814bd130-ffffffff814bd2eb: create_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int create_link(struct config_item *parent_item, struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81554d90)
Location: fs/configfs/symlink.c:77
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff81554d90-ffffffff81554f4b: create_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int create_link(struct config_item *parent_item, struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff8158cb30)
Location: fs/configfs/symlink.c:77
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff8158cb30-ffffffff8158cceb: create_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int create_link(struct config_item *parent_item, struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff815c5840)
Location: fs/configfs/symlink.c:77
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff815c5840-ffffffff815c5a2d: create_link (STB_LOCAL)
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
int create_link(struct config_item *parent_item, struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffff80001045d008)
Location: fs/configfs/symlink.c:79
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffff80001045d008-ffff80001045d3f8: create_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int create_link(struct config_item *parent_item, struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (c061de0c)
Location: fs/configfs/symlink.c:79
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
c061de0c-c061e200: create_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int create_link(struct config_item *parent_item, struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (c000000000578ad0)
Location: fs/configfs/symlink.c:79
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
c000000000578ad0-c000000000578ff0: create_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffe0002ed2d8)
Location: fs/configfs/symlink.c:79
Inline: True
Inline callers:
  - fs/configfs/symlink.c:configfs_symlink
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
int create_link(struct config_item *parent_item, struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81383fa0)
Location: fs/configfs/symlink.c:79
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff81383fa0-ffffffff81384292: create_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int create_link(struct config_item *parent_item, struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81374a30)
Location: fs/configfs/symlink.c:79
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff81374a30-ffffffff81374d22: create_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int create_link(struct config_item *parent_item, struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff81381a70)
Location: fs/configfs/symlink.c:79
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff81381a70-ffffffff81381d62: create_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int create_link(struct config_item *parent_item, struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/symlink.c (ffffffff813955a0)
Location: fs/configfs/symlink.c:79
Inline: False
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff813955a0-ffffffff81395898: create_link (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
