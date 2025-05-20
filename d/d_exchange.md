# Function: <code>d_exchange</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81226040)
Location: fs/dcache.c:2675
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
ffffffff81226040-ffffffff81226109: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124e6e0)
Location: fs/dcache.c:2846
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
ffffffff8124e6e0-ffffffff8124e7a9: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125fec0)
Location: fs/dcache.c:2855
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
ffffffff8125fec0-ffffffff8125ff89: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126d830)
Location: fs/dcache.c:2885
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
ffffffff8126d830-ffffffff8126d8ba: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81290150)
Location: fs/dcache.c:2897
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
ffffffff81290150-ffffffff812901da: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b5b00)
Location: fs/dcache.c:2882
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
ffffffff812b5b00-ffffffff812b5b7b: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812cae10)
Location: fs/dcache.c:2836
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
ffffffff812cae10-ffffffff812cae8b: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2905
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
ffffffff812e9dba-ffffffff812e9e06: d_exchange.cold (STB_LOCAL)
ffffffff812e7800-ffffffff812e787d: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f9390)
Location: fs/dcache.c:2905
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
ffffffff812f9390-ffffffff812f941b: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81332340)
Location: fs/dcache.c:2926
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
ffffffff81332340-ffffffff813323cb: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133dd60)
Location: fs/dcache.c:2933
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8133dd60-ffffffff8133ddeb: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81346390)
Location: fs/dcache.c:2960
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81346390-ffffffff8134641b: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81391990)
Location: fs/dcache.c:2961
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81391990-ffffffff81391a1b: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81415920)
Location: fs/dcache.c:2986
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81415920-ffffffff814159b2: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814a0cc0)
Location: fs/dcache.c:3042
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff814a0cc0-ffffffff814a0d52: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d5fd0)
Location: fs/dcache.c:3042
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff814d5fd0-ffffffff814d6062: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81508360)
Location: fs/dcache.c:2870
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81508360-ffffffff815083f2: d_exchange (STB_GLOBAL)
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
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a8898)
Location: fs/dcache.c:2905
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
ffff8000103a8898-ffff8000103a89d0: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c05895b0)
Location: fs/dcache.c:2905
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
c05895b0-c05896d8: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a2190)
Location: fs/dcache.c:2905
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
c0000000004a2190-c0000000004a22e4: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026df12)
Location: fs/dcache.c:2905
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
ffffffe00026df12-ffffffe00026dff8: d_exchange (STB_GLOBAL)
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
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f1970)
Location: fs/dcache.c:2905
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
ffffffff812f1970-ffffffff812f19fb: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e25a0)
Location: fs/dcache.c:2905
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
ffffffff812e25a0-ffffffff812e262b: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ef780)
Location: fs/dcache.c:2905
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
ffffffff812ef780-ffffffff812ef80b: d_exchange (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void d_exchange(struct dentry *dentry1, struct dentry *dentry2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81300a90)
Location: fs/dcache.c:2905
Inline: False
Direct callers:
  - fs/namei.c:vfs_rename
```
**Symbols:**

```
ffffffff81300a90-ffffffff81300b19: d_exchange (STB_GLOBAL)
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
