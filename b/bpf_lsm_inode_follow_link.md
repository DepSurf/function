# Function: <code>bpf_lsm_inode_follow_link</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_lsm_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81238bb0)
Location: include/linux/lsm_hook_defs.h:131
Inline: False
```
**Symbols:**

```
ffffffff81238bb0-ffffffff81238bbd: bpf_lsm_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123d390)
Location: include/linux/lsm_hook_defs.h:135
Inline: False
```
**Symbols:**

```
ffffffff8123d390-ffffffff8123d39d: bpf_lsm_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81277e50)
Location: include/linux/lsm_hook_defs.h:135
Inline: False
```
**Symbols:**

```
ffffffff81277e50-ffffffff81277e5d: bpf_lsm_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c7f90)
Location: include/linux/lsm_hook_defs.h:134
Inline: False
```
**Symbols:**

```
ffffffff812c7f90-ffffffff812c7fa1: bpf_lsm_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132dfb0)
Location: include/linux/lsm_hook_defs.h:134
Inline: False
```
**Symbols:**

```
ffffffff8132dfb0-ffffffff8132dfc1: bpf_lsm_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8135ec20)
Location: include/linux/lsm_hook_defs.h:135
Inline: False
```
**Symbols:**

```
ffffffff8135ec20-ffffffff8135ec31: bpf_lsm_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_inode_follow_link(struct dentry *dentry, struct inode *inode, bool rcu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff813879f0)
Location: include/linux/lsm_hook_defs.h:135
Inline: False
```
**Symbols:**

```
ffffffff813879f0-ffffffff81387a01: bpf_lsm_inode_follow_link (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
