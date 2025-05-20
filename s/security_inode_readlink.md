# Function: <code>security_inode_readlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133c3f0)
Location: security/security.c:586
Inline: False
Direct callers:
  - fs/stat.c:SyS_readlink
```
**Symbols:**

```
ffffffff8133c3f0-ffffffff8133c440: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813719c0)
Location: security/security.c:587
Inline: False
Direct callers:
  - fs/stat.c:SyS_readlink
```
**Symbols:**

```
ffffffff813719c0-ffffffff81371a10: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813882f0)
Location: security/security.c:596
Inline: False
Direct callers:
  - fs/stat.c:SyS_readlink
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff813882f0-ffffffff81388340: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139d2f0)
Location: security/security.c:1201
Inline: False
Direct callers:
  - fs/stat.c:SyS_readlink
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff8139d2f0-ffffffff8139d340: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c2b90)
Location: security/security.c:1150
Inline: False
Direct callers:
  - fs/stat.c:SyS_readlink
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff813c2b90-ffffffff813c2be6: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f2be0)
Location: security/security.c:692
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff813f2be0-ffffffff813f2c27: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140e080)
Location: security/security.c:1213
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff8140e080-ffffffff8140e0c7: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143d450)
Location: security/security.c:1227
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff8143d450-ffffffff8143d49e: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81456ee0)
Location: security/security.c:1267
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff81456ee0-ffffffff81456f27: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a9cf0)
Location: security/security.c:1415
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff814a9cf0-ffffffff814a9d37: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c7300)
Location: security/security.c:1417
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff814c7300-ffffffff814c7347: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cd740)
Location: security/security.c:1464
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff814cd740-ffffffff814cd787: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81526690)
Location: security/security.c:1470
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff81526690-ffffffff815266d7: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815baf60)
Location: security/security.c:1477
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff815baf60-ffffffff815bafc0: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81666a20)
Location: security/security.c:1475
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff81666a20-ffffffff81666a80: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169f010)
Location: security/security.c:2181
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff8169f010-ffffffff8169f070: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816db960)
Location: security/security.c:2254
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff816db960-ffffffff816db9c0: security_inode_readlink (STB_GLOBAL)
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
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010542970)
Location: security/security.c:1267
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffff800010542970-ffff8000105429c8: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f8924)
Location: security/security.c:1267
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
c06f8924-c06f8988: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000696060)
Location: security/security.c:1267
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
c000000000696060-c000000000696108: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039f190)
Location: security/security.c:1267
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffe00039f190-ffffffe00039f1d8: security_inode_readlink (STB_GLOBAL)
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
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144f4c0)
Location: security/security.c:1267
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff8144f4c0-ffffffff8144f507: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ff10)
Location: security/security.c:1267
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff8143ff10-ffffffff8143ff57: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144b560)
Location: security/security.c:1267
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff8144b560-ffffffff8144b5a7: security_inode_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_inode_readlink(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81462930)
Location: security/security.c:1267
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
  - fs/namei.c:vfs_get_link
```
**Symbols:**

```
ffffffff81462930-ffffffff81462977: security_inode_readlink (STB_GLOBAL)
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
