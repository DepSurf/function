# Function: <code>sel_make_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct inode *sel_make_inode(struct super_block *sb, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8134a000)
Location: security/selinux/selinuxfs.c:1029
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff8134a000-ffffffff8134a053: sel_make_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *sel_make_inode(struct super_block *sb, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8137fd50)
Location: security/selinux/selinuxfs.c:1086
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff8137fd50-ffffffff8137fda3: sel_make_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *sel_make_inode(struct super_block *sb, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff813967e0)
Location: security/selinux/selinuxfs.c:1088
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff813967e0-ffffffff8139682b: sel_make_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *sel_make_inode(struct super_block *sb, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff813acba0)
Location: security/selinux/selinuxfs.c:1087
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff813acba0-ffffffff813acbef: sel_make_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *sel_make_inode(struct super_block *sb, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff813d2c60)
Location: security/selinux/selinuxfs.c:1087
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
  - security/selinux/selinuxfs.c:sel_write_load
```
**Symbols:**

```
ffffffff813d2c60-ffffffff813d2caf: sel_make_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *sel_make_inode(struct super_block *sb, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff81402ea0)
Location: security/selinux/selinuxfs.c:1158
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81402ea0-ffffffff81402eeb: sel_make_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *sel_make_inode(struct super_block *sb, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8141e9b0)
Location: security/selinux/selinuxfs.c:1158
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8141e9b0-ffffffff8141e9fb: sel_make_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *sel_make_inode(struct super_block *sb, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8144c620)
Location: security/selinux/selinuxfs.c:1157
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8144c620-ffffffff8144c66f: sel_make_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *sel_make_inode(struct super_block *sb, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff81466410)
Location: security/selinux/selinuxfs.c:1157
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81466410-ffffffff8146645f: sel_make_inode (STB_LOCAL)
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
In security/selinux/selinuxfs.c (ffffffff814bc4cf)
Location: security/selinux/selinuxfs.c:1167
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_perm_files
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/selinuxfs.c (ffffffff814d9fc1)
Location: security/selinux/selinuxfs.c:1250
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_perm_files
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/selinuxfs.c (ffffffff814e1731)
Location: security/selinux/selinuxfs.c:1253
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/selinuxfs.c (ffffffff8153a6b1)
Location: security/selinux/selinuxfs.c:1253
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/selinuxfs.c (ffffffff815d1de5)
Location: security/selinux/selinuxfs.c:1257
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/selinuxfs.c (ffffffff8167fc75)
Location: security/selinux/selinuxfs.c:1257
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/selinuxfs.c (ffffffff816b7d4d)
Location: security/selinux/selinuxfs.c:1194
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_bools
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/selinuxfs.c (ffffffff816f384b)
Location: security/selinux/selinuxfs.c:1184
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_classes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
struct inode *sel_make_inode(struct super_block *sb, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffff800010554688)
Location: security/selinux/selinuxfs.c:1157
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffff800010554688-ffff8000105546d8: sel_make_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *sel_make_inode(struct super_block *sb, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (c07097cc)
Location: security/selinux/selinuxfs.c:1157
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
c07097cc-c0709860: sel_make_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *sel_make_inode(struct super_block *sb, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (c0000000006b15c0)
Location: security/selinux/selinuxfs.c:1157
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
c0000000006b15c0-c0000000006b1638: sel_make_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *sel_make_inode(struct super_block *sb, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffe0003acc3c)
Location: security/selinux/selinuxfs.c:1157
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffe0003acc3c-ffffffe0003acc8a: sel_make_inode (STB_LOCAL)
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
struct inode *sel_make_inode(struct super_block *sb, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8145e9f0)
Location: security/selinux/selinuxfs.c:1157
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8145e9f0-ffffffff8145ea3f: sel_make_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *sel_make_inode(struct super_block *sb, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8144f420)
Location: security/selinux/selinuxfs.c:1157
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8144f420-ffffffff8144f46f: sel_make_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *sel_make_inode(struct super_block *sb, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8145aa90)
Location: security/selinux/selinuxfs.c:1157
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8145aa90-ffffffff8145aadf: sel_make_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *sel_make_inode(struct super_block *sb, int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff81472230)
Location: security/selinux/selinuxfs.c:1157
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_make_dir
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81472230-ffffffff8147227f: sel_make_inode (STB_LOCAL)
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
