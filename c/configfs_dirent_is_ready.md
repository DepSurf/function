# Function: <code>configfs_dirent_is_ready</code>

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
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff812e0860)
Location: fs/configfs/dir.c:339
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff812e0860-ffffffff812e0895: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813051e0)
Location: fs/configfs/dir.c:339
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff813051e0-ffffffff81305215: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8133250d)
Location: fs/configfs/dir.c:339
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff81333840-ffffffff81333875: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8134994d)
Location: fs/configfs/dir.c:339
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff8134abd0-ffffffff8134ac05: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8137176b)
Location: fs/configfs/dir.c:354
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff813734c0-ffffffff813734f8: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81389bab)
Location: fs/configfs/dir.c:343
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff8138b8a0-ffffffff8138b8d8: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813d4dbb)
Location: fs/configfs/dir.c:343
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_lookup
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff813d6b60-ffffffff813d6b9b: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813e6adb)
Location: fs/configfs/dir.c:344
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_lookup
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff813e8830-ffffffff813e886b: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813ed85b)
Location: fs/configfs/dir.c:342
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_lookup
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff813ef3f0-ffffffff813ef42b: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8143fdcb)
Location: fs/configfs/dir.c:350
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_lookup
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff814412e0-ffffffff8144131b: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff814bad1b)
Location: fs/configfs/dir.c:350
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_lookup
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff814bce90-ffffffff814bcecd: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8155261b)
Location: fs/configfs/dir.c:351
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_lookup
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff81554a30-ffffffff81554a6d: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8158a36e)
Location: fs/configfs/dir.c:351
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_lookup
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff8158c7b0-ffffffff8158c7ed: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff815c3041)
Location: fs/configfs/dir.c:351
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_lookup
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff815c54b0-ffffffff815c54ed: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffff80001045a6d4)
Location: fs/configfs/dir.c:343
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffff80001045ca48-ffff80001045cad4: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c061d63c)
Location: fs/configfs/dir.c:343
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
c061d63c-c061d690: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c000000000577dd0)
Location: fs/configfs/dir.c:343
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
c000000000577dd0-c000000000577e9c: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffe0002ec8f4)
Location: fs/configfs/dir.c:343
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffe0002ec8f4-ffffffe0002ec974: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8138218b)
Location: fs/configfs/dir.c:343
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff81383e80-ffffffff81383eb8: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81372c1b)
Location: fs/configfs/dir.c:343
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff81374910-ffffffff81374948: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8137fc5b)
Location: fs/configfs/dir.c:343
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff81381950-ffffffff81381988: configfs_dirent_is_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int configfs_dirent_is_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8139344b)
Location: fs/configfs/dir.c:343
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_mkdir
Direct callers:
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:create_link
```
**Symbols:**

```
ffffffff81395480-ffffffff813954ba: configfs_dirent_is_ready (STB_GLOBAL)
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
