# Function: <code>proc_map_files_get_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proc_map_files_get_link(struct dentry *dentry, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8127c820)
Location: fs/proc/base.c:1901
Inline: False
```
**Symbols:**

```
ffffffff8127c820-ffffffff8127c978: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812a84b0)
Location: fs/proc/base.c:1972
Inline: False
```
**Symbols:**

```
ffffffff812a84b0-ffffffff812a84f7: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812bdd90)
Location: fs/proc/base.c:1992
Inline: False
```
**Symbols:**

```
ffffffff812bdd90-ffffffff812bddd7: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812cb410)
Location: fs/proc/base.c:2024
Inline: True
```
**Symbols:**

```
ffffffff812cb410-ffffffff812cb459: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812efb40)
Location: fs/proc/base.c:2025
Inline: True
```
**Symbols:**

```
ffffffff812efb40-ffffffff812efb89: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8131c8e0)
Location: fs/proc/base.c:2031
Inline: True
```
**Symbols:**

```
ffffffff8131c8e0-ffffffff8131c929: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81334110)
Location: fs/proc/base.c:2045
Inline: True
```
**Symbols:**

```
ffffffff81334110-ffffffff81334159: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135c620)
Location: fs/proc/base.c:2064
Inline: True
```
**Symbols:**

```
ffffffff8135c620-ffffffff8135c669: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81374bc0)
Location: fs/proc/base.c:2064
Inline: True
```
**Symbols:**

```
ffffffff81374bc0-ffffffff81374c09: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813bcda0)
Location: fs/proc/base.c:2197
Inline: True
```
**Symbols:**

```
ffffffff813bcda0-ffffffff813bcde9: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813ce5f0)
Location: fs/proc/base.c:2211
Inline: True
```
**Symbols:**

```
ffffffff813ce5f0-ffffffff813ce657: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d5270)
Location: fs/proc/base.c:2210
Inline: True
```
**Symbols:**

```
ffffffff813d5270-ffffffff813d52d7: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81426bb0)
Location: fs/proc/base.c:2216
Inline: True
```
**Symbols:**

```
ffffffff81426bb0-ffffffff81426c17: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff814a0e10)
Location: fs/proc/base.c:2245
Inline: False
```
**Symbols:**

```
ffffffff814a0e10-ffffffff814a0e88: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81535df0)
Location: fs/proc/base.c:2246
Inline: False
```
**Symbols:**

```
ffffffff81535df0-ffffffff81535e68: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8156dfc0)
Location: fs/proc/base.c:2246
Inline: False
```
**Symbols:**

```
ffffffff8156dfc0-ffffffff8156e038: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a6950)
Location: fs/proc/base.c:2240
Inline: False
```
**Symbols:**

```
ffffffff815a6950-ffffffff815a69c8: proc_map_files_get_link (STB_LOCAL)
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
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff80001043e148)
Location: fs/proc/base.c:2064
Inline: True
```
**Symbols:**

```
ffff80001043e148-ffff80001043e1a4: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c060494c)
Location: fs/proc/base.c:2064
Inline: True
```
**Symbols:**

```
c060494c-c06049a0: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c000000000553610)
Location: fs/proc/base.c:2064
Inline: True
```
**Symbols:**

```
c000000000553610-c0000000005536bc: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe0002d6732)
Location: fs/proc/base.c:2064
Inline: True
```
**Symbols:**

```
ffffffe0002d6732-ffffffe0002d6782: proc_map_files_get_link (STB_LOCAL)
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
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136d1a0)
Location: fs/proc/base.c:2064
Inline: True
```
**Symbols:**

```
ffffffff8136d1a0-ffffffff8136d1e9: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135dc30)
Location: fs/proc/base.c:2064
Inline: True
```
**Symbols:**

```
ffffffff8135dc30-ffffffff8135dc79: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136ac70)
Location: fs/proc/base.c:2064
Inline: True
```
**Symbols:**

```
ffffffff8136ac70-ffffffff8136acb9: proc_map_files_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const char *proc_map_files_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8137e680)
Location: fs/proc/base.c:2064
Inline: True
```
**Symbols:**

```
ffffffff8137e680-ffffffff8137e6c9: proc_map_files_get_link (STB_LOCAL)
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
<b>Param added. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param added. </b>
<code>struct delayed_call *done</code>
</li>
<li>
<b>Param removed. </b>
<code>struct path *path</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>const char *</code>
</li>
</ul>
</details>
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
