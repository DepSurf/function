# Function: <code>create_profile_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81375b80)
Location: security/apparmor/apparmorfs.c:591
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
```
**Symbols:**

```
ffffffff81375b80-ffffffff81375c3e: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813ac110)
Location: security/apparmor/apparmorfs.c:913
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
```
**Symbols:**

```
ffffffff813ac110-ffffffff813ac1f8: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813c2f20)
Location: security/apparmor/apparmorfs.c:1009
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_profile_mkdir
```
**Symbols:**

```
ffffffff813c2f20-ffffffff813c3008: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813d8c40)
Location: security/apparmor/apparmorfs.c:1461
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff813d8c40-ffffffff813d8cbc: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814013e0)
Location: security/apparmor/apparmorfs.c:1460
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff814013e0-ffffffff81401464: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81430900)
Location: security/apparmor/apparmorfs.c:1457
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff81430900-ffffffff81430984: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8144db40)
Location: security/apparmor/apparmorfs.c:1455
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff8144db40-ffffffff8144dbc4: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147cb80)
Location: security/apparmor/apparmorfs.c:1460
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff8147cb80-ffffffff8147cc0b: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81496850)
Location: security/apparmor/apparmorfs.c:1428
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff81496850-ffffffff814968db: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814edb40)
Location: security/apparmor/apparmorfs.c:1547
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff814edb40-ffffffff814edc3a: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8150b1c0)
Location: security/apparmor/apparmorfs.c:1547
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff8150b1c0-ffffffff8150b2ba: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81511920)
Location: security/apparmor/apparmorfs.c:1547
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff81511920-ffffffff81511a1a: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8156f520)
Location: security/apparmor/apparmorfs.c:1547
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff8156f520-ffffffff8156f61a: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8160b360)
Location: security/apparmor/apparmorfs.c:1563
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff8160b360-ffffffff8160b489: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816bd4e0)
Location: security/apparmor/apparmorfs.c:1744
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff816bd4e0-ffffffff816bd609: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816f5fa0)
Location: security/apparmor/apparmorfs.c:1792
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff816f5fa0-ffffffff816f60c9: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81732d00)
Location: security/apparmor/apparmorfs.c:1795
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff81732d00-ffffffff81732e29: create_profile_file (STB_LOCAL)
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
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffff80001058a250)
Location: security/apparmor/apparmorfs.c:1428
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffff80001058a250-ffff80001058a320: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c073b404)
Location: security/apparmor/apparmorfs.c:1428
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
c073b404-c073b4b8: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c0000000006fb760)
Location: security/apparmor/apparmorfs.c:1428
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
c0000000006fb760-c0000000006fb844: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffe0003d96a8)
Location: security/apparmor/apparmorfs.c:1428
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffe0003d96a8-ffffffe0003d9740: create_profile_file (STB_LOCAL)
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
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8148ee30)
Location: security/apparmor/apparmorfs.c:1428
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff8148ee30-ffffffff8148eebb: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147f850)
Location: security/apparmor/apparmorfs.c:1428
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff8147f850-ffffffff8147f8db: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8148aed0)
Location: security/apparmor/apparmorfs.c:1428
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff8148aed0-ffffffff8148af5b: create_profile_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *create_profile_file(struct dentry *dir, const char *name, struct aa_profile *profile, const struct file_operations *fops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814a2c10)
Location: security/apparmor/apparmorfs.c:1428
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
  - security/apparmor/apparmorfs.c:__aafs_profile_mkdir
```
**Symbols:**

```
ffffffff814a2c10-ffffffff814a2c9b: create_profile_file (STB_LOCAL)
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
