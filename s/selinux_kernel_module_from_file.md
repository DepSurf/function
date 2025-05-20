# Function: <code>selinux_kernel_module_from_file</code>

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
In security/selinux/hooks.c (ffffffff813799d8)
Location: security/selinux/hooks.c:3764
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
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
In security/selinux/hooks.c (ffffffff81390446)
Location: security/selinux/hooks.c:3836
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
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
In security/selinux/hooks.c (ffffffff813a6866)
Location: security/selinux/hooks.c:3794
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
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
In security/selinux/hooks.c (ffffffff813cc2b6)
Location: security/selinux/hooks.c:3809
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
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
In security/selinux/hooks.c (ffffffff813ffe17)
Location: security/selinux/hooks.c:4027
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8141bd70)
Location: security/selinux/hooks.c:3733
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
```
**Symbols:**

```
ffffffff8141bd70-ffffffff8141be7f: selinux_kernel_module_from_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81449710)
Location: security/selinux/hooks.c:3921
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
```
**Symbols:**

```
ffffffff81449710-ffffffff8144981f: selinux_kernel_module_from_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814632a0)
Location: security/selinux/hooks.c:3979
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
```
**Symbols:**

```
ffffffff814632a0-ffffffff814633b7: selinux_kernel_module_from_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b39cd)
Location: security/selinux/hooks.c:3972
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
```
**Symbols:**

```
ffffffff814b6df0-ffffffff814b6eea: selinux_kernel_module_from_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d086d)
Location: security/selinux/hooks.c:3986
Inline: True
```
**Symbols:**

```
ffffffff814d4ac0-ffffffff814d4bba: selinux_kernel_module_from_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d6e3d)
Location: security/selinux/hooks.c:4145
Inline: True
```
**Symbols:**

```
ffffffff814db8a0-ffffffff814db99a: selinux_kernel_module_from_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8152fa7d)
Location: security/selinux/hooks.c:4130
Inline: True
```
**Symbols:**

```
ffffffff81534d20-ffffffff81534e1a: selinux_kernel_module_from_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c6acf)
Location: security/selinux/hooks.c:4026
Inline: True
```
**Symbols:**

```
ffffffff815caf80-ffffffff815cb0a6: selinux_kernel_module_from_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8167381f)
Location: security/selinux/hooks.c:4044
Inline: True
```
**Symbols:**

```
ffffffff81678060-ffffffff81678186: selinux_kernel_module_from_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816abc4c)
Location: security/selinux/hooks.c:4020
Inline: True
```
**Symbols:**

```
ffffffff816b0310-ffffffff816b041e: selinux_kernel_module_from_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e88bc)
Location: security/selinux/hooks.c:4107
Inline: True
```
**Symbols:**

```
ffffffff816ed290-ffffffff816ed3a1: selinux_kernel_module_from_file (STB_LOCAL)
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
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff800010551120)
Location: security/selinux/hooks.c:3979
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
```
**Symbols:**

```
ffff800010551120-ffff800010551250: selinux_kernel_module_from_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0703cb4)
Location: security/selinux/hooks.c:3979
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
```
**Symbols:**

```
c0703cb4-c0703de8: selinux_kernel_module_from_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a7ee0)
Location: security/selinux/hooks.c:3979
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
```
**Symbols:**

```
c0000000006a7ee0-c0000000006a8050: selinux_kernel_module_from_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003aa514)
Location: security/selinux/hooks.c:3979
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
```
**Symbols:**

```
ffffffe0003aa514-ffffffe0003aa5e4: selinux_kernel_module_from_file (STB_LOCAL)
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
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145b880)
Location: security/selinux/hooks.c:3979
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
```
**Symbols:**

```
ffffffff8145b880-ffffffff8145b997: selinux_kernel_module_from_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8144c2b0)
Location: security/selinux/hooks.c:3979
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
```
**Symbols:**

```
ffffffff8144c2b0-ffffffff8144c3c7: selinux_kernel_module_from_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81457920)
Location: security/selinux/hooks.c:3979
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
```
**Symbols:**

```
ffffffff81457920-ffffffff81457a37: selinux_kernel_module_from_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int selinux_kernel_module_from_file(struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8146c880)
Location: security/selinux/hooks.c:3979
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernel_read_file
```
**Symbols:**

```
ffffffff8146c880-ffffffff8146c997: selinux_kernel_module_from_file (STB_LOCAL)
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
