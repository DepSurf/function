# Function: <code>fuse_unlock_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813512d0)
Location: fs/fuse/inode.c:363
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff813512d0-ffffffff813512fc: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81366c70)
Location: fs/fuse/inode.c:366
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff81366c70-ffffffff81366c9c: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8137b310)
Location: fs/fuse/inode.c:366
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff8137b310-ffffffff8137b33d: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813a01b0)
Location: fs/fuse/inode.c:366
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff813a01b0-ffffffff813a01dd: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813cf580)
Location: fs/fuse/inode.c:372
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_lookup
```
**Symbols:**

```
ffffffff813cf580-ffffffff813cf59d: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff813e8a10)
Location: fs/fuse/inode.c:371
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir
```
**Symbols:**

```
ffffffff813e8a10-ffffffff813e8a2d: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81414ae0)
Location: fs/fuse/inode.c:369
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81414ae0-ffffffff81414afd: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8142e950)
Location: fs/fuse/inode.c:359
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8142e950-ffffffff8142e96d: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8147e6a0)
Location: fs/fuse/inode.c:368
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8147e6a0-ffffffff8147e6bd: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81499ae0)
Location: fs/fuse/inode.c:435
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81499ae0-ffffffff81499afd: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8149ed10)
Location: fs/fuse/inode.c:435
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8149ed10-ffffffff8149ed2d: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814f6f70)
Location: fs/fuse/inode.c:437
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff814f6f70-ffffffff814f6f8d: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81586e20)
Location: fs/fuse/inode.c:475
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81586e20-ffffffff81586e4d: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8162d0d0)
Location: fs/fuse/inode.c:482
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8162d0d0-ffffffff8162d0fd: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81665300)
Location: fs/fuse/inode.c:482
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81665300-ffffffff8166532d: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8169f600)
Location: fs/fuse/inode.c:551
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff8169f600-ffffffff8169f62d: fuse_unlock_inode (STB_GLOBAL)
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
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffff800010513028)
Location: fs/fuse/inode.c:359
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffff800010513028-ffff800010513068: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c06ce0dc)
Location: fs/fuse/inode.c:359
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
c06ce0dc-c06ce104: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (c00000000065aef0)
Location: fs/fuse/inode.c:359
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
c00000000065aef0-c00000000065af30: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffe00037cf88)
Location: fs/fuse/inode.c:359
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffe00037cf88-ffffffe00037cfc8: fuse_unlock_inode (STB_GLOBAL)
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
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81426f30)
Location: fs/fuse/inode.c:359
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81426f30-ffffffff81426f4d: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814179b0)
Location: fs/fuse/inode.c:359
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff814179b0-ffffffff814179cd: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814230d0)
Location: fs/fuse/inode.c:359
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff814230d0-ffffffff814230ed: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fuse_unlock_inode(struct inode *inode, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff81439f00)
Location: fs/fuse/inode.c:359
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_lookup
  - fs/fuse/readdir.c:fuse_readdir_uncached
```
**Symbols:**

```
ffffffff81439f00-ffffffff81439f1d: fuse_unlock_inode (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool locked</code>
</li>
</ul>
</details>
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
