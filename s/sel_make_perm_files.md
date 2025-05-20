# Function: <code>sel_make_perm_files</code>

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
In security/selinux/selinuxfs.c (ffffffff8134bac5)
Location: security/selinux/selinuxfs.c:1576
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
In security/selinux/selinuxfs.c (ffffffff813815b1)
Location: security/selinux/selinuxfs.c:1622
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
In security/selinux/selinuxfs.c (ffffffff81398031)
Location: security/selinux/selinuxfs.c:1624
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
In security/selinux/selinuxfs.c (ffffffff813ae1bf)
Location: security/selinux/selinuxfs.c:1632
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
In security/selinux/selinuxfs.c (ffffffff813d427f)
Location: security/selinux/selinuxfs.c:1632
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
In security/selinux/selinuxfs.c (ffffffff8140469b)
Location: security/selinux/selinuxfs.c:1723
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
In security/selinux/selinuxfs.c (ffffffff814203a2)
Location: security/selinux/selinuxfs.c:1723
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
In security/selinux/selinuxfs.c (ffffffff8144dff9)
Location: security/selinux/selinuxfs.c:1722
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
In security/selinux/selinuxfs.c (ffffffff81467e19)
Location: security/selinux/selinuxfs.c:1722
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
int sel_make_perm_files(char *objclass, int classvalue, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff814bb6c0)
Location: security/selinux/selinuxfs.c:1794
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_classes
```
**Symbols:**

```
ffffffff814bb6c0-ffffffff814bb845: sel_make_perm_files (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sel_make_perm_files(struct selinux_policy *newpolicy, char *objclass, int classvalue, struct dentry *dir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff814d90a0)
Location: security/selinux/selinuxfs.c:1865
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_make_classes
```
**Symbols:**

```
ffffffff814d90a0-ffffffff814d9212: sel_make_perm_files (STB_LOCAL)
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
In security/selinux/selinuxfs.c (ffffffff814e09a3)
Location: security/selinux/selinuxfs.c:1868
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_classes
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
In security/selinux/selinuxfs.c (ffffffff81539923)
Location: security/selinux/selinuxfs.c:1868
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_classes
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
In security/selinux/selinuxfs.c (ffffffff815d0aca)
Location: security/selinux/selinuxfs.c:1872
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_classes
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
In security/selinux/selinuxfs.c (ffffffff8167edaa)
Location: security/selinux/selinuxfs.c:1872
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_classes
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
In security/selinux/selinuxfs.c (ffffffff816b6ed7)
Location: security/selinux/selinuxfs.c:1796
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_classes
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
In security/selinux/selinuxfs.c (ffffffff816f2e19)
Location: security/selinux/selinuxfs.c:1765
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_make_classes
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
In security/selinux/selinuxfs.c (ffff8000105561dc)
Location: security/selinux/selinuxfs.c:1722
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
In security/selinux/selinuxfs.c (c070a820)
Location: security/selinux/selinuxfs.c:1722
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
In security/selinux/selinuxfs.c (c0000000006b2e78)
Location: security/selinux/selinuxfs.c:1722
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
In security/selinux/selinuxfs.c (ffffffe0003ad95a)
Location: security/selinux/selinuxfs.c:1722
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
In security/selinux/selinuxfs.c (ffffffff814603f9)
Location: security/selinux/selinuxfs.c:1722
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
In security/selinux/selinuxfs.c (ffffffff81450e29)
Location: security/selinux/selinuxfs.c:1722
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
In security/selinux/selinuxfs.c (ffffffff8145c499)
Location: security/selinux/selinuxfs.c:1722
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
In security/selinux/selinuxfs.c (ffffffff81473c39)
Location: security/selinux/selinuxfs.c:1722
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
<b>Param reordered. </b>
<code>objclass, classvalue, dir</code> ➡️ <code>newpolicy, objclass, classvalue, dir</code>
</li>
</ul>
</details>
</li>
</ul>
