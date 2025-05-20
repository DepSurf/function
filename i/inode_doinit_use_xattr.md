# Function: <code>inode_doinit_use_xattr</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int inode_doinit_use_xattr(struct inode *inode, struct dentry *dentry, u32 def_sid, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1367
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff81445bd0-ffffffff81445d4e: inode_doinit_use_xattr (STB_LOCAL)
ffffffff8144c2ab-ffffffff8144c31e: inode_doinit_use_xattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int inode_doinit_use_xattr(struct inode *inode, struct dentry *dentry, u32 def_sid, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1369
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff8145f760-ffffffff8145f8de: inode_doinit_use_xattr (STB_LOCAL)
ffffffff8146609b-ffffffff8146610e: inode_doinit_use_xattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int inode_doinit_use_xattr(struct inode *inode, struct dentry *dentry, u32 def_sid, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1320
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff814b07a0-ffffffff814b091e: inode_doinit_use_xattr (STB_LOCAL)
ffffffff814b9cab-ffffffff814b9d1e: inode_doinit_use_xattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int inode_doinit_use_xattr(struct inode *inode, struct dentry *dentry, u32 def_sid, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1321
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff814cdb70-ffffffff814cdcee: inode_doinit_use_xattr (STB_LOCAL)
ffffffff81bf0155-ffffffff81bf01c8: inode_doinit_use_xattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int inode_doinit_use_xattr(struct inode *inode, struct dentry *dentry, u32 def_sid, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1380
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff814d4260-ffffffff814d43de: inode_doinit_use_xattr (STB_LOCAL)
ffffffff81be21d4-ffffffff81be2247: inode_doinit_use_xattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int inode_doinit_use_xattr(struct inode *inode, struct dentry *dentry, u32 def_sid, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1372
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff8152cf20-ffffffff8152d09e: inode_doinit_use_xattr (STB_LOCAL)
ffffffff81cd3594-ffffffff81cd3607: inode_doinit_use_xattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int inode_doinit_use_xattr(struct inode *inode, struct dentry *dentry, u32 def_sid, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1310
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff815c37a0-ffffffff815c3936: inode_doinit_use_xattr (STB_LOCAL)
ffffffff81e866a7-ffffffff81e8671c: inode_doinit_use_xattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inode_doinit_use_xattr(struct inode *inode, struct dentry *dentry, u32 def_sid, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81670200)
Location: security/selinux/hooks.c:1309
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff81670200-ffffffff8167040b: inode_doinit_use_xattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inode_doinit_use_xattr(struct inode *inode, struct dentry *dentry, u32 def_sid, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816a8820)
Location: security/selinux/hooks.c:1320
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff816a8820-ffffffff816a8a1e: inode_doinit_use_xattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inode_doinit_use_xattr(struct inode *inode, struct dentry *dentry, u32 def_sid, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e51c0)
Location: security/selinux/hooks.c:1362
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff816e51c0-ffffffff816e53ea: inode_doinit_use_xattr (STB_LOCAL)
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
int inode_doinit_use_xattr(struct inode *inode, struct dentry *dentry, u32 def_sid, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054ca40)
Location: security/selinux/hooks.c:1369
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffff80001054ca40-ffff80001054cc54: inode_doinit_use_xattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inode_doinit_use_xattr(struct inode *inode, struct dentry *dentry, u32 def_sid, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0702c20)
Location: security/selinux/hooks.c:1369
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
c0702c20-c0702e08: inode_doinit_use_xattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inode_doinit_use_xattr(struct inode *inode, struct dentry *dentry, u32 def_sid, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a5600)
Location: security/selinux/hooks.c:1369
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
c0000000006a5600-c0000000006a58ec: inode_doinit_use_xattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inode_doinit_use_xattr(struct inode *inode, struct dentry *dentry, u32 def_sid, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a6f10)
Location: security/selinux/hooks.c:1369
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffe0003a6f10-ffffffe0003a70f0: inode_doinit_use_xattr (STB_LOCAL)
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
int inode_doinit_use_xattr(struct inode *inode, struct dentry *dentry, u32 def_sid, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1369
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff81457d40-ffffffff81457ebe: inode_doinit_use_xattr (STB_LOCAL)
ffffffff8145e67b-ffffffff8145e6ee: inode_doinit_use_xattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int inode_doinit_use_xattr(struct inode *inode, struct dentry *dentry, u32 def_sid, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1369
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff81448770-ffffffff814488ee: inode_doinit_use_xattr (STB_LOCAL)
ffffffff8144f0ab-ffffffff8144f11e: inode_doinit_use_xattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int inode_doinit_use_xattr(struct inode *inode, struct dentry *dentry, u32 def_sid, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1369
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff81453de0-ffffffff81453f5e: inode_doinit_use_xattr (STB_LOCAL)
ffffffff8145a71b-ffffffff8145a78e: inode_doinit_use_xattr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int inode_doinit_use_xattr(struct inode *inode, struct dentry *dentry, u32 def_sid, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:1369
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff8146b8e0-ffffffff8146ba5e: inode_doinit_use_xattr (STB_LOCAL)
ffffffff81471ebb-ffffffff81471f2e: inode_doinit_use_xattr.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
