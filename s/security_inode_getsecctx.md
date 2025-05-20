# Function: <code>security_inode_getsecctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133b7e0)
Location: security/security.c:1186
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setxattr
```
**Symbols:**

```
ffffffff8133b7e0-ffffffff8133b835: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81370da0)
Location: security/security.c:1216
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setxattr
```
**Symbols:**

```
ffffffff81370da0-ffffffff81370df5: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813876d0)
Location: security/security.c:1237
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_security_xattr_set
```
**Symbols:**

```
ffffffff813876d0-ffffffff81387725: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139c370)
Location: security/security.c:2167
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_security_xattr_set
```
**Symbols:**

```
ffffffff8139c370-ffffffff8139c3c5: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c1ac0)
Location: security/security.c:2025
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_security_xattr_set
```
**Symbols:**

```
ffffffff813c1ac0-ffffffff813c1b1b: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f3080)
Location: security/security.c:1341
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_security_xattr_set
```
**Symbols:**

```
ffffffff813f3080-ffffffff813f30d1: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140e450)
Location: security/security.c:2092
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_security_xattr_set
```
**Symbols:**

```
ffffffff8140e450-ffffffff8140e4a1: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143afe0)
Location: security/security.c:2111
Inline: False
```
**Symbols:**

```
ffffffff8143afe0-ffffffff8143b035: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81454da0)
Location: security/security.c:2150
Inline: False
```
**Symbols:**

```
ffffffff81454da0-ffffffff81454df1: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a8920)
Location: security/security.c:2429
Inline: False
```
**Symbols:**

```
ffffffff814a8920-ffffffff814a8963: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c5e90)
Location: security/security.c:2446
Inline: False
```
**Symbols:**

```
ffffffff814c5e90-ffffffff814c5ed3: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cc150)
Location: security/security.c:2509
Inline: False
```
**Symbols:**

```
ffffffff814cc150-ffffffff814cc193: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81525120)
Location: security/security.c:2517
Inline: False
```
**Symbols:**

```
ffffffff81525120-ffffffff81525163: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b9540)
Location: security/security.c:2547
Inline: False
```
**Symbols:**

```
ffffffff815b9540-ffffffff815b9597: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81664d20)
Location: security/security.c:2527
Inline: False
```
**Symbols:**

```
ffffffff81664d20-ffffffff81664d77: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169d200)
Location: security/security.c:4257
Inline: False
```
**Symbols:**

```
ffffffff8169d200-ffffffff8169d257: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d9990)
Location: security/security.c:4414
Inline: False
```
**Symbols:**

```
ffffffff816d9990-ffffffff816d9a00: security_inode_getsecctx (STB_GLOBAL)
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
int security_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010540048)
Location: security/security.c:2150
Inline: False
```
**Symbols:**

```
ffff800010540048-ffff8000105400b0: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f60e8)
Location: security/security.c:2150
Inline: False
```
**Symbols:**

```
c06f60e8-c06f6150: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000691660)
Location: security/security.c:2150
Inline: False
```
**Symbols:**

```
c000000000691660-c000000000691710: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039d2ba)
Location: security/security.c:2150
Inline: False
```
**Symbols:**

```
ffffffe00039d2ba-ffffffe00039d308: security_inode_getsecctx (STB_GLOBAL)
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
int security_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144d380)
Location: security/security.c:2150
Inline: False
```
**Symbols:**

```
ffffffff8144d380-ffffffff8144d3d1: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ddd0)
Location: security/security.c:2150
Inline: False
```
**Symbols:**

```
ffffffff8143ddd0-ffffffff8143de21: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81449420)
Location: security/security.c:2150
Inline: False
```
**Symbols:**

```
ffffffff81449420-ffffffff81449471: security_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814607f0)
Location: security/security.c:2150
Inline: False
```
**Symbols:**

```
ffffffff814607f0-ffffffff81460841: security_inode_getsecctx (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsmcontext *cp</code>
</li>
<li>
<b>Param removed. </b>
<code>void **ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 *ctxlen</code>
</li>
</ul>
</details>
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
