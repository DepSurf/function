# Function: <code>init_symlink</code>

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
void init_symlink(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff812decc0)
Location: fs/configfs/dir.c:264
Inline: False
```
**Symbols:**

```
ffffffff812decc0-ffffffff812decd3: init_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void init_symlink(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81303630)
Location: fs/configfs/dir.c:264
Inline: False
```
**Symbols:**

```
ffffffff81303630-ffffffff81303643: init_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void init_symlink(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813315a0)
Location: fs/configfs/dir.c:264
Inline: False
```
**Symbols:**

```
ffffffff813315a0-ffffffff813315b3: init_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void init_symlink(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81348990)
Location: fs/configfs/dir.c:264
Inline: False
```
**Symbols:**

```
ffffffff81348990-ffffffff813489a3: init_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void init_symlink(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81370ef0)
Location: fs/configfs/dir.c:277
Inline: False
```
**Symbols:**

```
ffffffff81370ef0-ffffffff81370f03: init_symlink (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int init_symlink(const char *oldname, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff82fedf4c)
Location: fs/init.c:199
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
```
**Symbols:**

```
ffffffff82fedf4c-ffffffff82fedfea: init_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int init_symlink(const char *oldname, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff831f8779)
Location: fs/init.c:201
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
```
**Symbols:**

```
ffffffff831f8779-ffffffff831f881f: init_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int init_symlink(const char *oldname, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff832df6f1)
Location: fs/init.c:201
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
```
**Symbols:**

```
ffffffff832df6f1-ffffffff832df797: init_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int init_symlink(const char *oldname, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff834953ae)
Location: fs/init.c:201
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
```
**Symbols:**

```
ffffffff834953ae-ffffffff83495467: init_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int init_symlink(const char *oldname, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff83ec9e10)
Location: fs/init.c:201
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
```
**Symbols:**

```
ffffffff83ec9e10-ffffffff83ec9ed9: init_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_symlink(const char *oldname, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff836eee50)
Location: fs/init.c:201
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
```
**Symbols:**

```
ffffffff836eee50-ffffffff836eef12: init_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_symlink(const char *oldname, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff83921ea0)
Location: fs/init.c:200
Inline: False
Direct callers:
  - init/initramfs.c:do_symlink
```
**Symbols:**

```
ffffffff83921ea0-ffffffff83921f62: init_symlink (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
