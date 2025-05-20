# Function: <code>sel_make_classes</code>

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
In security/selinux/selinuxfs.c (ffffffff8134b98e)
Location: security/selinux/selinuxfs.c:1641
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
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
In security/selinux/selinuxfs.c (ffffffff81381483)
Location: security/selinux/selinuxfs.c:1687
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
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
In security/selinux/selinuxfs.c (ffffffff81397f03)
Location: security/selinux/selinuxfs.c:1689
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
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
In security/selinux/selinuxfs.c (ffffffff813ae099)
Location: security/selinux/selinuxfs.c:1697
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
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
In security/selinux/selinuxfs.c (ffffffff813d4159)
Location: security/selinux/selinuxfs.c:1697
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_write_load
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
In security/selinux/selinuxfs.c (ffffffff81404578)
Location: security/selinux/selinuxfs.c:1795
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/selinuxfs.c (ffffffff81420281)
Location: security/selinux/selinuxfs.c:1795
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/selinuxfs.c (ffffffff8144dece)
Location: security/selinux/selinuxfs.c:1794
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/selinuxfs.c (ffffffff81467cee)
Location: security/selinux/selinuxfs.c:1794
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sel_make_classes(struct selinux_fs_info *fsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff814bbf00)
Location: security/selinux/selinuxfs.c:1866
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff814bbf00-ffffffff814bc11d: sel_make_classes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sel_make_classes(struct selinux_policy *newpolicy, struct dentry *class_dir, long unsigned int *last_class_ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff814d9860)
Location: security/selinux/selinuxfs.c:1938
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff814d9860-ffffffff814d9a62: sel_make_classes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sel_make_classes(struct selinux_policy *newpolicy, struct dentry *class_dir, long unsigned int *last_class_ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff814e0830)
Location: security/selinux/selinuxfs.c:1941
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff814e0830-ffffffff814e0bb3: sel_make_classes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sel_make_classes(struct selinux_policy *newpolicy, struct dentry *class_dir, long unsigned int *last_class_ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff815397b0)
Location: security/selinux/selinuxfs.c:1941
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff815397b0-ffffffff81539b33: sel_make_classes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sel_make_classes(struct selinux_policy *newpolicy, struct dentry *class_dir, long unsigned int *last_class_ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff815d0940)
Location: security/selinux/selinuxfs.c:1945
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff815d0940-ffffffff815d0cd4: sel_make_classes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sel_make_classes(struct selinux_policy *newpolicy, struct dentry *class_dir, long unsigned int *last_class_ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8167ec20)
Location: security/selinux/selinuxfs.c:1942
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8167ec20-ffffffff8167efb4: sel_make_classes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sel_make_classes(struct selinux_policy *newpolicy, struct dentry *class_dir, long unsigned int *last_class_ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff816b6d50)
Location: security/selinux/selinuxfs.c:1866
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff816b6d50-ffffffff816b70e6: sel_make_classes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sel_make_classes(struct selinux_policy *newpolicy, struct dentry *class_dir, long unsigned int *last_class_ino);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff816f2cc0)
Location: security/selinux/selinuxfs.c:1836
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff816f2cc0-ffffffff816f2fe2: sel_make_classes (STB_LOCAL)
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
In security/selinux/selinuxfs.c (ffff8000105560cc)
Location: security/selinux/selinuxfs.c:1794
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/selinuxfs.c (c070a720)
Location: security/selinux/selinuxfs.c:1794
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/selinuxfs.c (c0000000006b2d34)
Location: security/selinux/selinuxfs.c:1794
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/selinuxfs.c (ffffffe0003ad846)
Location: security/selinux/selinuxfs.c:1794
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/selinuxfs.c (ffffffff814602ce)
Location: security/selinux/selinuxfs.c:1794
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/selinuxfs.c (ffffffff81450cfe)
Location: security/selinux/selinuxfs.c:1794
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/selinuxfs.c (ffffffff8145c36e)
Location: security/selinux/selinuxfs.c:1794
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
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
In security/selinux/selinuxfs.c (ffffffff81473b0e)
Location: security/selinux/selinuxfs.c:1794
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_policy *newpolicy</code>
</li>
<li>
<b>Param added. </b>
<code>struct dentry *class_dir</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int *last_class_ino</code>
</li>
<li>
<b>Param removed. </b>
<code>struct selinux_fs_info *fsi</code>
</li>
</ul>
</details>
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
