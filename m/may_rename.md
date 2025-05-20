# Function: <code>may_rename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81342d85)
Location: security/selinux/hooks.c:1858
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81379fa5)
Location: security/selinux/hooks.c:1931
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813906c5)
Location: security/selinux/hooks.c:1939
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a6b05)
Location: security/selinux/hooks.c:1920
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cc555)
Location: security/selinux/hooks.c:1934
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814006d9)
Location: security/selinux/hooks.c:2042
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8141c76a)
Location: security/selinux/hooks.c:1856
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8144a15a)
Location: security/selinux/hooks.c:1900
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81463e65)
Location: security/selinux/hooks.c:1902
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int may_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b7f20)
Location: security/selinux/hooks.c:1855
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
**Symbols:**

```
ffffffff814b7f20-ffffffff814b80f5: may_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int may_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d5c30)
Location: security/selinux/hooks.c:1864
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
**Symbols:**

```
ffffffff814d5c30-ffffffff814d5e05: may_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int may_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814dca90)
Location: security/selinux/hooks.c:1924
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
**Symbols:**

```
ffffffff814dca90-ffffffff814dcc65: may_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int may_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81535f60)
Location: security/selinux/hooks.c:1916
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
**Symbols:**

```
ffffffff81535f60-ffffffff81536135: may_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int may_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815cc3a0)
Location: security/selinux/hooks.c:1854
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
**Symbols:**

```
ffffffff815cc3a0-ffffffff815cc5a5: may_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int may_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816795c0)
Location: security/selinux/hooks.c:1853
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
**Symbols:**

```
ffffffff816795c0-ffffffff816797c5: may_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int may_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816b1770)
Location: security/selinux/hooks.c:1858
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
**Symbols:**

```
ffffffff816b1770-ffffffff816b194a: may_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int may_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816ee800)
Location: security/selinux/hooks.c:1898
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
**Symbols:**

```
ffffffff816ee800-ffffffff816ee9dd: may_rename (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff800010551f14)
Location: security/selinux/hooks.c:1902
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c07041f8)
Location: security/selinux/hooks.c:1902
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a86f4)
Location: security/selinux/hooks.c:1902
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003aaf54)
Location: security/selinux/hooks.c:1902
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145c445)
Location: security/selinux/hooks.c:1902
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8144ce75)
Location: security/selinux/hooks.c:1902
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814584e5)
Location: security/selinux/hooks.c:1902
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8146d305)
Location: security/selinux/hooks.c:1902
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_rename
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
