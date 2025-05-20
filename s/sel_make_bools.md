# Function: <code>sel_make_bools</code>

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
In security/selinux/selinuxfs.c (ffffffff8134b6df)
Location: security/selinux/selinuxfs.c:1196
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
In security/selinux/selinuxfs.c (ffffffff813811de)
Location: security/selinux/selinuxfs.c:1249
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
In security/selinux/selinuxfs.c (ffffffff81397c5e)
Location: security/selinux/selinuxfs.c:1251
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
In security/selinux/selinuxfs.c (ffffffff813adf7b)
Location: security/selinux/selinuxfs.c:1254
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
In security/selinux/selinuxfs.c (ffffffff813d403b)
Location: security/selinux/selinuxfs.c:1254
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
In security/selinux/selinuxfs.c (ffffffff8140430f)
Location: security/selinux/selinuxfs.c:1327
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
In security/selinux/selinuxfs.c (ffffffff8141ffff)
Location: security/selinux/selinuxfs.c:1327
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
In security/selinux/selinuxfs.c (ffffffff8144dc52)
Location: security/selinux/selinuxfs.c:1326
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
In security/selinux/selinuxfs.c (ffffffff81467a72)
Location: security/selinux/selinuxfs.c:1326
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sel_make_bools(struct selinux_fs_info *fsi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:1336
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff814bbae0-ffffffff814bbe12: sel_make_bools (STB_LOCAL)
ffffffff814bd6e0-ffffffff814bd6fe: sel_make_bools.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sel_make_bools(struct selinux_policy *newpolicy, struct dentry *bool_dir, unsigned int *bool_num, char ***bool_pending_names, unsigned int **bool_pending_values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:1417
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff814d94b0-ffffffff814d9773: sel_make_bools (STB_LOCAL)
ffffffff81bf0503-ffffffff81bf0517: sel_make_bools.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sel_make_bools(struct selinux_policy *newpolicy, struct dentry *bool_dir, unsigned int *bool_num, char ***bool_pending_names, unsigned int **bool_pending_values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:1420
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff814dfba0-ffffffff814dfe63: sel_make_bools (STB_LOCAL)
ffffffff81be2666-ffffffff81be267a: sel_make_bools.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sel_make_bools(struct selinux_policy *newpolicy, struct dentry *bool_dir, unsigned int *bool_num, char ***bool_pending_names, unsigned int **bool_pending_values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:1420
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81538b20-ffffffff81538de3: sel_make_bools (STB_LOCAL)
ffffffff81cd40cf-ffffffff81cd40e3: sel_make_bools.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sel_make_bools(struct selinux_policy *newpolicy, struct dentry *bool_dir, unsigned int *bool_num, char ***bool_pending_names, unsigned int **bool_pending_values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (0)
Location: security/selinux/selinuxfs.c:1424
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff815d00d0-ffffffff815d03ad: sel_make_bools (STB_LOCAL)
ffffffff81e8708f-ffffffff81e870a5: sel_make_bools.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sel_make_bools(struct selinux_policy *newpolicy, struct dentry *bool_dir, unsigned int *bool_num, char ***bool_pending_names, int **bool_pending_values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8167dff0)
Location: security/selinux/selinuxfs.c:1424
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8167dff0-ffffffff8167e307: sel_make_bools (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sel_make_bools(struct selinux_policy *newpolicy, struct dentry *bool_dir, unsigned int *bool_num, char ***bool_pending_names, int **bool_pending_values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff816b61b0)
Location: security/selinux/selinuxfs.c:1359
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff816b61b0-ffffffff816b64c2: sel_make_bools (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff816f29a0)
Location: security/selinux/selinuxfs.c:1343
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff816f29a0-ffffffff816f2bdd: sel_make_bools.constprop.0 (STB_LOCAL)
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
In security/selinux/selinuxfs.c (ffff800010555e60)
Location: security/selinux/selinuxfs.c:1326
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
In security/selinux/selinuxfs.c (c070a4a4)
Location: security/selinux/selinuxfs.c:1326
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
In security/selinux/selinuxfs.c (c0000000006b29e4)
Location: security/selinux/selinuxfs.c:1326
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
In security/selinux/selinuxfs.c (ffffffe0003ad606)
Location: security/selinux/selinuxfs.c:1326
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
In security/selinux/selinuxfs.c (ffffffff81460052)
Location: security/selinux/selinuxfs.c:1326
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
In security/selinux/selinuxfs.c (ffffffff81450a82)
Location: security/selinux/selinuxfs.c:1326
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
In security/selinux/selinuxfs.c (ffffffff8145c0f2)
Location: security/selinux/selinuxfs.c:1326
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
In security/selinux/selinuxfs.c (ffffffff81473892)
Location: security/selinux/selinuxfs.c:1326
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
<code>struct dentry *bool_dir</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int *bool_num</code>
</li>
<li>
<b>Param added. </b>
<code>char ***bool_pending_names</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int **bool_pending_values</code>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int **bool_pending_values</code> ➡️ <code>int **bool_pending_values</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
