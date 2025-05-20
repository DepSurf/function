# Function: <code>ecryptfs_read_metadata</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81306a80)
Location: fs/ecryptfs/crypto.c:1423
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff81306a80-ffffffff81306bec: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8133aca0)
Location: fs/ecryptfs/crypto.c:1420
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff8133aca0-ffffffff8133ae0c: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81350a30)
Location: fs/ecryptfs/crypto.c:1420
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff81350a30-ffffffff81350b9c: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81365540)
Location: fs/ecryptfs/crypto.c:1420
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff81365540-ffffffff813656b7: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8138a210)
Location: fs/ecryptfs/crypto.c:1404
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff8138a210-ffffffff8138a374: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1404
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff813b9bca-ffffffff813b9c1e: ecryptfs_read_metadata.cold.36 (STB_LOCAL)
ffffffff813b8ff0-ffffffff813b9110: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1404
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff813d3179-ffffffff813d31cd: ecryptfs_read_metadata.cold.34 (STB_LOCAL)
ffffffff813d2560-ffffffff813d2680: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1398
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff813fdc6b-ffffffff813fdcbc: ecryptfs_read_metadata.cold (STB_LOCAL)
ffffffff813fd000-ffffffff813fd117: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1400
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff81417b57-ffffffff81417ba8: ecryptfs_read_metadata.cold (STB_LOCAL)
ffffffff81416ee0-ffffffff81416ff7: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1385
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:read_or_initialize_metadata
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff81466122-ffffffff814661a2: ecryptfs_read_metadata.cold (STB_LOCAL)
ffffffff81465490-ffffffff81465723: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1385
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:read_or_initialize_metadata
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff81bee8d9-ffffffff81bee959: ecryptfs_read_metadata.cold (STB_LOCAL)
ffffffff81480d30-ffffffff81480fc3: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1380
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff81be0924-ffffffff81be09a4: ecryptfs_read_metadata.cold (STB_LOCAL)
ffffffff81486620-ffffffff814868b3: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1380
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff81cd10c1-ffffffff81cd1141: ecryptfs_read_metadata.cold (STB_LOCAL)
ffffffff814dddb0-ffffffff814de043: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1380
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff81e842ea-ffffffff81e8433d: ecryptfs_read_metadata.cold (STB_LOCAL)
ffffffff8156bec0-ffffffff8156c033: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8160fff0)
Location: fs/ecryptfs/crypto.c:1380
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff8160fff0-ffffffff816101a3: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81647e80)
Location: fs/ecryptfs/crypto.c:1356
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff81647e80-ffffffff81648036: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81681330)
Location: fs/ecryptfs/crypto.c:1356
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff81681330-ffffffff816814e6: ecryptfs_read_metadata (STB_GLOBAL)
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
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffff8000104f88e8)
Location: fs/ecryptfs/crypto.c:1400
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffff8000104f88e8-ffff8000104f8a4c: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c06b61a4)
Location: fs/ecryptfs/crypto.c:1400
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
c06b61a4-c06b630c: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c00000000063a5e0)
Location: fs/ecryptfs/crypto.c:1400
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
c00000000063a5e0-c00000000063a79c: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffe0003671ea)
Location: fs/ecryptfs/crypto.c:1400
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffe0003671ea-ffffffe000367334: ecryptfs_read_metadata (STB_GLOBAL)
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
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1400
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff81410137-ffffffff81410188: ecryptfs_read_metadata.cold (STB_LOCAL)
ffffffff8140f4c0-ffffffff8140f5d7: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1400
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff81400bb7-ffffffff81400c08: ecryptfs_read_metadata.cold (STB_LOCAL)
ffffffff813fff40-ffffffff81400057: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1400
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff8140d4b7-ffffffff8140d508: ecryptfs_read_metadata.cold (STB_LOCAL)
ffffffff8140c840-ffffffff8140c957: ecryptfs_read_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_read_metadata(struct dentry *ecryptfs_dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1400
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff81423130-ffffffff81423181: ecryptfs_read_metadata.cold (STB_LOCAL)
ffffffff814224c0-ffffffff814225d7: ecryptfs_read_metadata (STB_GLOBAL)
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
