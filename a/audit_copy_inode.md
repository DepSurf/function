# Function: <code>audit_copy_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811224d0)
Location: kernel/audit.c:1724
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff811224d0-ffffffff8112257f: audit_copy_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8112a400)
Location: kernel/audit.c:1735
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff8112a400-ffffffff8112a4af: audit_copy_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81134120)
Location: kernel/audit.c:1874
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff81134120-ffffffff811341cf: audit_copy_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81135630)
Location: kernel/audit.c:2041
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff81135630-ffffffff811356df: audit_copy_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81142370)
Location: kernel/audit.c:2049
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_link_denied
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff81142370-ffffffff8114241f: audit_copy_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81150d40)
Location: kernel/audit.c:2102
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff81150d40-ffffffff81150def: audit_copy_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115da00)
Location: kernel/audit.c:2101
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff8115da00-ffffffff8115daaf: audit_copy_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8116e320)
Location: kernel/auditsc.c:1920
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff8116e320-ffffffff8116e3eb: audit_copy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117a1a0)
Location: kernel/auditsc.c:1920
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff8117a1a0-ffffffff8117a26b: audit_copy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118f2be)
Location: kernel/auditsc.c:1951
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff8118ed00-ffffffff8118edc8: audit_copy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118c52d)
Location: kernel/auditsc.c:1968
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff8118bed0-ffffffff8118bf98: audit_copy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118d17c)
Location: kernel/auditsc.c:1965
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff8118cd80-ffffffff8118ce4f: audit_copy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b5e2c)
Location: kernel/auditsc.c:1978
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff811b5a10-ffffffff811b5adf: audit_copy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811e96e7)
Location: kernel/auditsc.c:2269
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff811e84f0-ffffffff811e85e8: audit_copy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8122f667)
Location: kernel/auditsc.c:2247
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff8122e6a0-ffffffff8122e798: audit_copy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff812451c1)
Location: kernel/auditsc.c:2244
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff812434d0-ffffffff812435c8: audit_copy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8125f11a)
Location: kernel/auditsc.c:2239
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode_child
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff8125d490-ffffffff8125d591: audit_copy_inode (STB_LOCAL)
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
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101ef2a8)
Location: kernel/auditsc.c:1920
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffff8000101ef2a8-ffff8000101ef398: audit_copy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c042f6b8)
Location: kernel/auditsc.c:1920
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
c042f6b8-c042f7c0: audit_copy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c000000000262260)
Location: kernel/auditsc.c:1920
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
c000000000262260-c000000000262388: audit_copy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe00016313c)
Location: kernel/auditsc.c:1920
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffe00016313c-ffffffe0001631fe: audit_copy_inode (STB_LOCAL)
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
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811727c0)
Location: kernel/auditsc.c:1920
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff811727c0-ffffffff8117288b: audit_copy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81165960)
Location: kernel/auditsc.c:1920
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff81165960-ffffffff81165a2b: audit_copy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81170590)
Location: kernel/auditsc.c:1920
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff81170590-ffffffff8117065b: audit_copy_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_copy_inode(struct audit_names *name, const struct dentry *dentry, struct inode *inode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117dd90)
Location: kernel/auditsc.c:1920
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff8117dd90-ffffffff8117de5b: audit_copy_inode (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct inode *inode</code> ➡️ <code>struct inode *inode</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
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
