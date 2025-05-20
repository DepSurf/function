# Function: <code>ecryptfs_write_metadata</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813064a0)
Location: fs/ecryptfs/crypto.c:1184
Inline: False
```
**Symbols:**

```
ffffffff813064a0-ffffffff81306706: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8133a860)
Location: fs/ecryptfs/crypto.c:1178
Inline: False
```
**Symbols:**

```
ffffffff8133a860-ffffffff8133aaf1: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81350600)
Location: fs/ecryptfs/crypto.c:1178
Inline: False
```
**Symbols:**

```
ffffffff81350600-ffffffff8135088e: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81365110)
Location: fs/ecryptfs/crypto.c:1178
Inline: False
```
**Symbols:**

```
ffffffff81365110-ffffffff81365393: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81389de0)
Location: fs/ecryptfs/crypto.c:1162
Inline: False
```
**Symbols:**

```
ffffffff81389de0-ffffffff8138a063: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1162
Inline: False
```
**Symbols:**

```
ffffffff813b9b47-ffffffff813b9baf: ecryptfs_write_metadata.cold.34 (STB_LOCAL)
ffffffff813b8c40-ffffffff813b8e5c: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1162
Inline: False
```
**Symbols:**

```
ffffffff813d30f6-ffffffff813d315e: ecryptfs_write_metadata.cold.32 (STB_LOCAL)
ffffffff813d21b0-ffffffff813d23cc: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1159
Inline: False
```
**Symbols:**

```
ffffffff813fdbae-ffffffff813fdc4b: ecryptfs_write_metadata.cold (STB_LOCAL)
ffffffff813fcc10-ffffffff813fce67: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1161
Inline: False
```
**Symbols:**

```
ffffffff81417a9a-ffffffff81417b37: ecryptfs_write_metadata.cold (STB_LOCAL)
ffffffff81416af0-ffffffff81416d47: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1146
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
```
**Symbols:**

```
ffffffff8146607b-ffffffff81466102: ecryptfs_write_metadata.cold (STB_LOCAL)
ffffffff814650e0-ffffffff814652a6: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1146
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
```
**Symbols:**

```
ffffffff81bee832-ffffffff81bee8b9: ecryptfs_write_metadata.cold (STB_LOCAL)
ffffffff81480980-ffffffff81480b4c: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1141
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
```
**Symbols:**

```
ffffffff81be0867-ffffffff81be0904: ecryptfs_write_metadata.cold (STB_LOCAL)
ffffffff814861d0-ffffffff81486436: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1141
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
```
**Symbols:**

```
ffffffff81cd1004-ffffffff81cd10a1: ecryptfs_write_metadata.cold (STB_LOCAL)
ffffffff814dd960-ffffffff814ddbc6: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1141
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
```
**Symbols:**

```
ffffffff81e84237-ffffffff81e842cf: ecryptfs_write_metadata.cold (STB_LOCAL)
ffffffff8156ba20-ffffffff8156bc96: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8160fa50)
Location: fs/ecryptfs/crypto.c:1141
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
```
**Symbols:**

```
ffffffff8160fa50-ffffffff8160fd64: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff816478e0)
Location: fs/ecryptfs/crypto.c:1117
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
```
**Symbols:**

```
ffffffff816478e0-ffffffff81647bf4: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81680d90)
Location: fs/ecryptfs/crypto.c:1117
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
```
**Symbols:**

```
ffffffff81680d90-ffffffff816810a7: ecryptfs_write_metadata (STB_GLOBAL)
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
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffff8000104f81f8)
Location: fs/ecryptfs/crypto.c:1161
Inline: False
```
**Symbols:**

```
ffff8000104f81f8-ffff8000104f84c0: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c06b5a0c)
Location: fs/ecryptfs/crypto.c:1161
Inline: False
```
**Symbols:**

```
c06b5a0c-c06b5d48: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c000000000639fd0)
Location: fs/ecryptfs/crypto.c:1161
Inline: False
```
**Symbols:**

```
c000000000639fd0-c00000000063a39c: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffe000366b04)
Location: fs/ecryptfs/crypto.c:1161
Inline: False
```
**Symbols:**

```
ffffffe000366b04-ffffffe000366e1e: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1161
Inline: False
```
**Symbols:**

```
ffffffff8141007a-ffffffff81410117: ecryptfs_write_metadata.cold (STB_LOCAL)
ffffffff8140f0d0-ffffffff8140f327: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1161
Inline: False
```
**Symbols:**

```
ffffffff81400afa-ffffffff81400b97: ecryptfs_write_metadata.cold (STB_LOCAL)
ffffffff813ffb50-ffffffff813ffda7: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1161
Inline: False
```
**Symbols:**

```
ffffffff8140d3fa-ffffffff8140d497: ecryptfs_write_metadata.cold (STB_LOCAL)
ffffffff8140c450-ffffffff8140c6a7: ecryptfs_write_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_write_metadata(struct dentry *ecryptfs_dentry, struct inode *ecryptfs_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1161
Inline: False
```
**Symbols:**

```
ffffffff81423073-ffffffff81423110: ecryptfs_write_metadata.cold (STB_LOCAL)
ffffffff814220d0-ffffffff81422327: ecryptfs_write_metadata (STB_GLOBAL)
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
