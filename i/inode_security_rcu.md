# Function: <code>inode_security_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137ae6d)
Location: security/selinux/hooks.c:281
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
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
In security/selinux/hooks.c (ffffffff813912bd)
Location: security/selinux/hooks.c:282
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
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
In security/selinux/hooks.c (ffffffff813a7a59)
Location: security/selinux/hooks.c:274
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
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
In security/selinux/hooks.c (ffffffff813cd229)
Location: security/selinux/hooks.c:275
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
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
In security/selinux/hooks.c (ffffffff81400f72)
Location: security/selinux/hooks.c:307
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct inode_security_struct *inode_security_rcu(struct inode *inode, bool rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8141d1e0)
Location: security/selinux/hooks.c:292
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff8141d1e0-ffffffff8141d21a: inode_security_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct inode_security_struct *inode_security_rcu(struct inode *inode, bool rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8144ac10)
Location: security/selinux/hooks.c:293
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff8144ac10-ffffffff8144ac4a: inode_security_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct inode_security_struct *inode_security_rcu(struct inode *inode, bool rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81464860)
Location: security/selinux/hooks.c:295
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff81464860-ffffffff8146489a: inode_security_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b6b77)
Location: security/selinux/hooks.c:280
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_follow_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d4847)
Location: security/selinux/hooks.c:281
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_follow_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814db628)
Location: security/selinux/hooks.c:317
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_follow_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815346d5)
Location: security/selinux/hooks.c:294
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_follow_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815ca86d)
Location: security/selinux/hooks.c:280
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_follow_link
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81677b5d)
Location: security/selinux/hooks.c:282
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_follow_link
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816afe3d)
Location: security/selinux/hooks.c:278
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_follow_link
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816ecdc0)
Location: security/selinux/hooks.c:306
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
  - security/selinux/hooks.c:selinux_inode_follow_link
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct inode_security_struct *inode_security_rcu(struct inode *inode, bool rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff800010552908)
Location: security/selinux/hooks.c:295
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffff800010552908-ffff800010552968: inode_security_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct inode_security_struct *inode_security_rcu(struct inode *inode, bool rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0705bf0)
Location: security/selinux/hooks.c:295
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
c0705bf0-c0705c38: inode_security_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct inode_security_struct *inode_security_rcu(struct inode *inode, bool rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006aa6c0)
Location: security/selinux/hooks.c:295
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
c0000000006aa6c0-c0000000006aa748: inode_security_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct inode_security_struct *inode_security_rcu(struct inode *inode, bool rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003ab782)
Location: security/selinux/hooks.c:295
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffe0003ab782-ffffffe0003ab7c8: inode_security_rcu (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct inode_security_struct *inode_security_rcu(struct inode *inode, bool rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145ce40)
Location: security/selinux/hooks.c:295
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff8145ce40-ffffffff8145ce7a: inode_security_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct inode_security_struct *inode_security_rcu(struct inode *inode, bool rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8144d870)
Location: security/selinux/hooks.c:295
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff8144d870-ffffffff8144d8aa: inode_security_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct inode_security_struct *inode_security_rcu(struct inode *inode, bool rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81458ee0)
Location: security/selinux/hooks.c:295
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff81458ee0-ffffffff81458f1a: inode_security_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct inode_security_struct *inode_security_rcu(struct inode *inode, bool rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8146d8a0)
Location: security/selinux/hooks.c:295
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff8146d8a0-ffffffff8146d8da: inode_security_rcu (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
