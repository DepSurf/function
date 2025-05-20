# Function: <code>security_inode_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133c310)
Location: security/security.c:514
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff8133c310-ffffffff8133c375: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813718e0)
Location: security/security.c:515
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff813718e0-ffffffff81371945: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81388210)
Location: security/security.c:524
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81388210-ffffffff81388275: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139d210)
Location: security/security.c:1129
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff8139d210-ffffffff8139d275: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c2ab0)
Location: security/security.c:1078
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff813c2ab0-ffffffff813c2b1b: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f2b20)
Location: security/security.c:620
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
ffffffff813f2b20-ffffffff813f2b78: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140dfc0)
Location: security/security.c:1141
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
ffffffff8140dfc0-ffffffff8140e018: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143bec0)
Location: security/security.c:1155
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
ffffffff8143bec0-ffffffff8143bf21: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81455bb0)
Location: security/security.c:1195
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
ffffffff81455bb0-ffffffff81455c06: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a83e0)
Location: security/security.c:1343
Inline: False
Direct callers:
  - fs/namei.c:may_o_create
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
ffffffff814a83e0-ffffffff814a8436: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c5970)
Location: security/security.c:1345
Inline: False
Direct callers:
  - fs/namei.c:may_o_create
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
ffffffff814c5970-ffffffff814c59c6: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cbc30)
Location: security/security.c:1392
Inline: False
Direct callers:
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
ffffffff814cbc30-ffffffff814cbc86: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81524b60)
Location: security/security.c:1398
Inline: False
Direct callers:
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
ffffffff81524b60-ffffffff81524bb6: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b8ae0)
Location: security/security.c:1405
Inline: False
Direct callers:
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
ffffffff815b8ae0-ffffffff815b8b5f: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81664160)
Location: security/security.c:1403
Inline: False
Direct callers:
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
ffffffff81664160-ffffffff816641df: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169c5a0)
Location: security/security.c:2023
Inline: False
Direct callers:
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
ffffffff8169c5a0-ffffffff8169c61f: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d9240)
Location: security/security.c:2096
Inline: False
Direct callers:
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
ffffffff816d9240-ffffffff816d92bf: security_inode_create (STB_GLOBAL)
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
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105411c8)
Location: security/security.c:1195
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
ffff8000105411c8-ffff800010541234: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f720c)
Location: security/security.c:1195
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
c06f720c-c06f727c: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006936c0)
Location: security/security.c:1195
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
c0000000006936c0-c000000000693788: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039df8e)
Location: security/security.c:1195
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
ffffffe00039df8e-ffffffe00039dfe4: security_inode_create (STB_GLOBAL)
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
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144e190)
Location: security/security.c:1195
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
ffffffff8144e190-ffffffff8144e1e6: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ebe0)
Location: security/security.c:1195
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
ffffffff8143ebe0-ffffffff8143ec36: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144a230)
Location: security/security.c:1195
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
ffffffff8144a230-ffffffff8144a286: security_inode_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_inode_create(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81461600)
Location: security/security.c:1195
Inline: False
Direct callers:
  - fs/namei.c:lookup_open
  - fs/namei.c:vfs_mkobj
```
**Symbols:**

```
ffffffff81461600-ffffffff81461656: security_inode_create (STB_GLOBAL)
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
