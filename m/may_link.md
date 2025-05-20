# Function: <code>may_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff813465a0)
Location: security/selinux/hooks.c:1815
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff813465a0-ffffffff81346698: may_link.isra.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137a170)
Location: security/selinux/hooks.c:1888
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff8137a170-ffffffff8137a2a3: may_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81390890)
Location: security/selinux/hooks.c:1896
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff81390890-ffffffff813909c3: may_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a6d00)
Location: security/selinux/hooks.c:1877
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff813a6d00-ffffffff813a6e16: may_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cc750)
Location: security/selinux/hooks.c:1891
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff813cc750-ffffffff813cc866: may_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814008b0)
Location: security/selinux/hooks.c:1997
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff814008b0-ffffffff8140099f: may_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8141c980)
Location: security/selinux/hooks.c:1811
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff8141c980-ffffffff8141ca8c: may_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1855
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff8144a370-ffffffff8144a4b3: may_link (STB_LOCAL)
ffffffff8144c43f-ffffffff8144c45a: may_link.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1857
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff81464090-ffffffff814641db: may_link (STB_LOCAL)
ffffffff8146622f-ffffffff8146624a: may_link.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b8110)
Location: security/selinux/hooks.c:1810
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff814b8110-ffffffff814b81ed: may_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d5e20)
Location: security/selinux/hooks.c:1819
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff814d5e20-ffffffff814d5efd: may_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814dcc80)
Location: security/selinux/hooks.c:1879
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff814dcc80-ffffffff814dcd61: may_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81536150)
Location: security/selinux/hooks.c:1871
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff81536150-ffffffff81536231: may_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815cc5d0)
Location: security/selinux/hooks.c:1809
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff815cc5d0-ffffffff815cc6e2: may_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81679810)
Location: security/selinux/hooks.c:1808
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff81679810-ffffffff81679922: may_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816b1990)
Location: security/selinux/hooks.c:1815
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff816b1990-ffffffff816b1a8d: may_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816eea20)
Location: security/selinux/hooks.c:1855
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff816eea20-ffffffff816eeb20: may_link (STB_LOCAL)
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
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff8000105520e8)
Location: security/selinux/hooks.c:1857
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffff8000105520e8-ffff800010552224: may_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c07043f4)
Location: security/selinux/hooks.c:1857
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
c07043f4-c070452c: may_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a8960)
Location: security/selinux/hooks.c:1857
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
c0000000006a8960-c0000000006a8b38: may_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003ab128)
Location: security/selinux/hooks.c:1857
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffe0003ab128-ffffffe0003ab218: may_link (STB_LOCAL)
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
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1857
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff8145c670-ffffffff8145c7bb: may_link (STB_LOCAL)
ffffffff8145e80f-ffffffff8145e82a: may_link.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1857
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff8144d0a0-ffffffff8144d1eb: may_link (STB_LOCAL)
ffffffff8144f23f-ffffffff8144f25a: may_link.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1857
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff81458710-ffffffff8145885b: may_link (STB_LOCAL)
ffffffff8145a8af-ffffffff8145a8ca: may_link.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int may_link(struct inode *dir, struct dentry *dentry, int kind);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1857
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rmdir
  - security/selinux/hooks.c:selinux_inode_unlink
  - security/selinux/hooks.c:selinux_inode_link
```
**Symbols:**

```
ffffffff8146d530-ffffffff8146d67b: may_link (STB_LOCAL)
ffffffff81472006-ffffffff81472021: may_link.cold (STB_LOCAL)
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
