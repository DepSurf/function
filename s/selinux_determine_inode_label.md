# Function: <code>selinux_determine_inode_label</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int selinux_determine_inode_label(const struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81341e10)
Location: security/selinux/hooks.c:1738
Inline: False
Direct callers:
  - security/selinux/hooks.c:may_create
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff81341e10-ffffffff81341e81: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int selinux_determine_inode_label(struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81379b00)
Location: security/selinux/hooks.c:1811
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff81379b00-ffffffff81379ba5: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813922e0)
Location: security/selinux/hooks.c:1820
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff813922e0-ffffffff8139236d: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a87c0)
Location: security/selinux/hooks.c:1809
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff813a87c0-ffffffff813a885f: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813ce6f0)
Location: security/selinux/hooks.c:1823
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff813ce6f0-ffffffff813ce78f: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fff40)
Location: security/selinux/hooks.c:1926
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff813fff40-ffffffff813fffd4: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8141bf50)
Location: security/selinux/hooks.c:1740
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff8141bf50-ffffffff8141bff4: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814498f0)
Location: security/selinux/hooks.c:1784
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff814498f0-ffffffff814499a5: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81463490)
Location: security/selinux/hooks.c:1786
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff81463490-ffffffff81463545: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b6f90)
Location: security/selinux/hooks.c:1739
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff814b6f90-ffffffff814b7020: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d4c70)
Location: security/selinux/hooks.c:1748
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff814d4c70-ffffffff814d4d00: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814dba40)
Location: security/selinux/hooks.c:1807
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff814dba40-ffffffff814dbad6: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81534ec0)
Location: security/selinux/hooks.c:1799
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff81534ec0-ffffffff81534f56: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815cb180)
Location: security/selinux/hooks.c:1737
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff815cb180-ffffffff815cb233: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81678290)
Location: security/selinux/hooks.c:1736
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff81678290-ffffffff81678343: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816b0510)
Location: security/selinux/hooks.c:1746
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff816b0510-ffffffff816b05b1: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816ed4a0)
Location: security/selinux/hooks.c:1786
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff816ed4a0-ffffffff816ed541: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffff800010551388)
Location: security/selinux/hooks.c:1786
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffff800010551388-ffff80001055147c: selinux_determine_inode_label.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c07054c0)
Location: security/selinux/hooks.c:1786
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
c07054c0-c070559c: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (c0000000006a9d90)
Location: security/selinux/hooks.c:1786
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
c0000000006a9d90-c0000000006a9ec4: selinux_determine_inode_label.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003aa6e0)
Location: security/selinux/hooks.c:1786
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffe0003aa6e0-ffffffe0003aa78a: selinux_determine_inode_label.isra.0 (STB_LOCAL)
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
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145ba70)
Location: security/selinux/hooks.c:1786
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff8145ba70-ffffffff8145bb25: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8144c4a0)
Location: security/selinux/hooks.c:1786
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff8144c4a0-ffffffff8144c555: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81457b10)
Location: security/selinux/hooks.c:1786
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff81457b10-ffffffff81457bc5: selinux_determine_inode_label (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int selinux_determine_inode_label(const struct task_security_struct *tsec, struct inode *dir, const struct qstr *name, u16 tclass, u32 *_new_isid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8146ca70)
Location: security/selinux/hooks.c:1786
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_dentry_create_files_as
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:may_create
```
**Symbols:**

```
ffffffff8146ca70-ffffffff8146cb25: selinux_determine_inode_label (STB_LOCAL)
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
<code>const struct inode *dir</code> ➡️ <code>struct inode *dir</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct task_security_struct *tsec</code>
</li>
<li>
<b>Param reordered. </b>
<code>dir, name, tclass, _new_isid</code> ➡️ <code>tsec, dir, name, tclass, _new_isid</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
