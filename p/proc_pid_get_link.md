# Function: <code>proc_pid_get_link</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812a8420)
Location: fs/proc/base.c:1582
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_get_link
```
**Symbols:**

```
ffffffff812a8420-ffffffff812a84a6: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812bdd00)
Location: fs/proc/base.c:1600
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_get_link
```
**Symbols:**

```
ffffffff812bdd00-ffffffff812bdd86: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff812cb370)
Location: fs/proc/base.c:1617
Inline: True
```
**Symbols:**

```
ffffffff812cb370-ffffffff812cb3e6: proc_pid_get_link.part.10 (STB_LOCAL)
ffffffff812cb3f0-ffffffff812cb40d: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff812efaa0)
Location: fs/proc/base.c:1618
Inline: True
```
**Symbols:**

```
ffffffff812efaa0-ffffffff812efb1c: proc_pid_get_link.part.9 (STB_LOCAL)
ffffffff812efb20-ffffffff812efb3d: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff8131c840)
Location: fs/proc/base.c:1584
Inline: True
```
**Symbols:**

```
ffffffff8131c840-ffffffff8131c8bc: proc_pid_get_link.part.12 (STB_LOCAL)
ffffffff8131c8c0-ffffffff8131c8dd: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff81334070)
Location: fs/proc/base.c:1598
Inline: True
```
**Symbols:**

```
ffffffff81334070-ffffffff813340ec: proc_pid_get_link.part.12 (STB_LOCAL)
ffffffff813340f0-ffffffff8133410d: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff8135c580)
Location: fs/proc/base.c:1611
Inline: True
```
**Symbols:**

```
ffffffff8135c580-ffffffff8135c5fc: proc_pid_get_link.part.0 (STB_LOCAL)
ffffffff8135c600-ffffffff8135c61d: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff81374b20)
Location: fs/proc/base.c:1611
Inline: True
```
**Symbols:**

```
ffffffff81374b20-ffffffff81374b9c: proc_pid_get_link.part.0 (STB_LOCAL)
ffffffff81374ba0-ffffffff81374bbd: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff813bccb0)
Location: fs/proc/base.c:1723
Inline: True
```
**Symbols:**

```
ffffffff813bccb0-ffffffff813bcd7a: proc_pid_get_link.part.0 (STB_LOCAL)
ffffffff813bcd80-ffffffff813bcd9d: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff813ce500)
Location: fs/proc/base.c:1737
Inline: True
```
**Symbols:**

```
ffffffff813ce500-ffffffff813ce5ca: proc_pid_get_link.part.0 (STB_LOCAL)
ffffffff813ce5d0-ffffffff813ce5ed: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff813d5180)
Location: fs/proc/base.c:1736
Inline: True
```
**Symbols:**

```
ffffffff813d5180-ffffffff813d524a: proc_pid_get_link.part.0 (STB_LOCAL)
ffffffff813d5250-ffffffff813d526d: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff81426ac0)
Location: fs/proc/base.c:1742
Inline: True
```
**Symbols:**

```
ffffffff81426ac0-ffffffff81426b8a: proc_pid_get_link.part.0 (STB_LOCAL)
ffffffff81426b90-ffffffff81426bad: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff814a0d20)
Location: fs/proc/base.c:1741
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_get_link
```
**Symbols:**

```
ffffffff814a0d20-ffffffff814a0e0d: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81535cf0)
Location: fs/proc/base.c:1742
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_get_link
```
**Symbols:**

```
ffffffff81535cf0-ffffffff81535ddd: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8156dec0)
Location: fs/proc/base.c:1742
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_get_link
```
**Symbols:**

```
ffffffff8156dec0-ffffffff8156dfad: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a6850)
Location: fs/proc/base.c:1738
Inline: False
Direct callers:
  - fs/proc/base.c:proc_map_files_get_link
```
**Symbols:**

```
ffffffff815a6850-ffffffff815a693d: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffff80001043e070)
Location: fs/proc/base.c:1611
Inline: True
```
**Symbols:**

```
ffff80001043e070-ffff80001043e104: proc_pid_get_link.part.0 (STB_LOCAL)
ffff80001043e108-ffff80001043e144: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (c060488c)
Location: fs/proc/base.c:1611
Inline: True
```
**Symbols:**

```
c060488c-c0604920: proc_pid_get_link.part.0 (STB_LOCAL)
c0604920-c060494c: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (c000000000553520)
Location: fs/proc/base.c:1611
Inline: True
```
**Symbols:**

```
c000000000553520-c0000000005535dc: proc_pid_get_link.part.0 (STB_LOCAL)
c0000000005535e0-c000000000553608: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffe0002d64cc)
Location: fs/proc/base.c:1611
Inline: True
```
**Symbols:**

```
ffffffe0002d64cc-ffffffe0002d6534: proc_pid_get_link.part.0 (STB_LOCAL)
ffffffe0002d6534-ffffffe0002d656a: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff8136d100)
Location: fs/proc/base.c:1611
Inline: True
```
**Symbols:**

```
ffffffff8136d100-ffffffff8136d17c: proc_pid_get_link.part.0 (STB_LOCAL)
ffffffff8136d180-ffffffff8136d19d: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff8135db90)
Location: fs/proc/base.c:1611
Inline: True
```
**Symbols:**

```
ffffffff8135db90-ffffffff8135dc0c: proc_pid_get_link.part.0 (STB_LOCAL)
ffffffff8135dc10-ffffffff8135dc2d: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff8136abd0)
Location: fs/proc/base.c:1611
Inline: True
```
**Symbols:**

```
ffffffff8136abd0-ffffffff8136ac4c: proc_pid_get_link.part.0 (STB_LOCAL)
ffffffff8136ac50-ffffffff8136ac6d: proc_pid_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *proc_pid_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/base.c (ffffffff8137e5e0)
Location: fs/proc/base.c:1611
Inline: True
```
**Symbols:**

```
ffffffff8137e5e0-ffffffff8137e65c: proc_pid_get_link.part.0 (STB_LOCAL)
ffffffff8137e660-ffffffff8137e67d: proc_pid_get_link (STB_LOCAL)
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
