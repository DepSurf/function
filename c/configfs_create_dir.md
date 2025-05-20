# Function: <code>configfs_create_dir</code>

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
int configfs_create_dir(struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff812e02d0)
Location: fs/configfs/dir.c:278
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff812e02d0-ffffffff812e042a: configfs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81304c50)
Location: fs/configfs/dir.c:278
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81304c50-ffffffff81304daa: configfs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81332de0)
Location: fs/configfs/dir.c:278
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81332de0-ffffffff81332f2c: configfs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8134a1d0)
Location: fs/configfs/dir.c:278
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff8134a1d0-ffffffff8134a31c: configfs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (0)
Location: fs/configfs/dir.c:291
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81372960-ffffffff81372ac8: configfs_create_dir (STB_LOCAL)
ffffffff81373670-ffffffff81373683: configfs_create_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8138ada0)
Location: fs/configfs/dir.c:275
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff8138ada0-ffffffff8138aeca: configfs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813d5e70)
Location: fs/configfs/dir.c:275
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:create_default_group
```
**Symbols:**

```
ffffffff813d5e70-ffffffff813d5f9c: configfs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813e7b40)
Location: fs/configfs/dir.c:276
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:create_default_group
```
**Symbols:**

```
ffffffff813e7b40-ffffffff813e7c6c: configfs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813ee760)
Location: fs/configfs/dir.c:274
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff813ee760-ffffffff813ee88c: configfs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81440690)
Location: fs/configfs/dir.c:282
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81440690-ffffffff814407bc: configfs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff814bc1d0)
Location: fs/configfs/dir.c:282
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff814bc1d0-ffffffff814bc307: configfs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81553cb0)
Location: fs/configfs/dir.c:282
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81553cb0-ffffffff81553e35: configfs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8158ba40)
Location: fs/configfs/dir.c:282
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff8158ba40-ffffffff8158bbc5: configfs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff815c4770)
Location: fs/configfs/dir.c:282
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff815c4770-ffffffff815c4901: configfs_create_dir (STB_LOCAL)
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
int configfs_create_dir(struct config_item *item, struct dentry *dentry, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffff80001045bd98)
Location: fs/configfs/dir.c:275
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffff80001045bd98-ffff80001045bedc: configfs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c061d05c)
Location: fs/configfs/dir.c:275
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
c061d05c-c061d188: configfs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c000000000577280)
Location: fs/configfs/dir.c:275
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
c000000000577280-c000000000577600: configfs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffe0002ec23e)
Location: fs/configfs/dir.c:275
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffe0002ec23e-ffffffe0002ec356: configfs_create_dir (STB_LOCAL)
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
int configfs_create_dir(struct config_item *item, struct dentry *dentry, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81383380)
Location: fs/configfs/dir.c:275
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81383380-ffffffff813834aa: configfs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81373e10)
Location: fs/configfs/dir.c:275
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81373e10-ffffffff81373f3a: configfs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81380e50)
Location: fs/configfs/dir.c:275
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81380e50-ffffffff81380f7a: configfs_create_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int configfs_create_dir(struct config_item *item, struct dentry *dentry, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81394910)
Location: fs/configfs/dir.c:275
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81394910-ffffffff81394a3a: configfs_create_dir (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct configfs_fragment *frag</code>
</li>
</ul>
</details>
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
