# Function: <code>proc_lookup_de</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct proc_dir_entry *de, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8127f560)
Location: fs/proc/generic.c:232
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_lookup
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff8127f560-ffffffff8127f610: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct proc_dir_entry *de, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812ac640)
Location: fs/proc/generic.c:236
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_lookup
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff812ac640-ffffffff812ac6e8: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct proc_dir_entry *de, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812c1f30)
Location: fs/proc/generic.c:236
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_lookup
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff812c1f30-ffffffff812c1fd8: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct proc_dir_entry *de, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812cf1f0)
Location: fs/proc/generic.c:219
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_lookup
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff812cf1f0-ffffffff812cf293: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct proc_dir_entry *de, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff812f3960)
Location: fs/proc/generic.c:221
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_lookup
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff812f3960-ffffffff812f3a03: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81320540)
Location: fs/proc/generic.c:246
Inline: True
Direct callers:
  - fs/proc/generic.c:proc_lookup
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff81320540-ffffffff813205e5: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81337630)
Location: fs/proc/generic.c:246
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_lookup
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff81337630-ffffffff813376d8: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8135f770)
Location: fs/proc/generic.c:247
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_lookup
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff8135f770-ffffffff8135f81e: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813779d0)
Location: fs/proc/generic.c:247
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_lookup
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff813779d0-ffffffff81377a7e: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813c0840)
Location: fs/proc/generic.c:249
Inline: False
Direct callers:
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff813c0840-ffffffff813c0915: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d2690)
Location: fs/proc/generic.c:249
Inline: False
Direct callers:
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff813d2690-ffffffff813d2765: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813d9490)
Location: fs/proc/generic.c:244
Inline: False
Direct callers:
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff813d9490-ffffffff813d9565: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8142abc0)
Location: fs/proc/generic.c:244
Inline: False
Direct callers:
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff8142abc0-ffffffff8142ac95: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff814a41e0)
Location: fs/proc/generic.c:244
Inline: False
Direct callers:
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff814a41e0-ffffffff814a42c8: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81539620)
Location: fs/proc/generic.c:244
Inline: False
Direct callers:
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff81539620-ffffffff81539708: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81571860)
Location: fs/proc/generic.c:243
Inline: False
Direct callers:
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff81571860-ffffffff8157198e: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff815aa210)
Location: fs/proc/generic.c:243
Inline: False
Direct callers:
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff815aa210-ffffffff815aa33e: proc_lookup_de (STB_GLOBAL)
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
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffff8000104436d8)
Location: fs/proc/generic.c:247
Inline: True
Direct callers:
  - fs/proc/generic.c:proc_lookup
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffff8000104436d8-ffff800010443824: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c06089d4)
Location: fs/proc/generic.c:247
Inline: True
Direct callers:
  - fs/proc/generic.c:proc_lookup
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
c06089d4-c0608abc: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (c000000000558dc0)
Location: fs/proc/generic.c:247
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_lookup
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
c000000000558dc0-c000000000558eec: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffe0002da0a0)
Location: fs/proc/generic.c:247
Inline: True
Direct callers:
  - fs/proc/generic.c:proc_lookup
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffe0002da0a0-ffffffe0002da15e: proc_lookup_de (STB_GLOBAL)
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
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136ffb0)
Location: fs/proc/generic.c:247
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_lookup
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff8136ffb0-ffffffff8137005e: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff81360a40)
Location: fs/proc/generic.c:247
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_lookup
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff81360a40-ffffffff81360aee: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff8136da80)
Location: fs/proc/generic.c:247
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_lookup
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff8136da80-ffffffff8136db2e: proc_lookup_de (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *proc_lookup_de(struct inode *dir, struct dentry *dentry, struct proc_dir_entry *de);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/generic.c (ffffffff813813b0)
Location: fs/proc/generic.c:247
Inline: False
Direct callers:
  - fs/proc/generic.c:proc_lookup
  - fs/proc/proc_net.c:proc_tgid_net_lookup
```
**Symbols:**

```
ffffffff813813b0-ffffffff8138145c: proc_lookup_de (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param reordered. </b>
<code>de, dir, dentry</code> ➡️ <code>dir, dentry, de</code>
</li>
</ul>
</details>
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
