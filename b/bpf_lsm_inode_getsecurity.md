# Function: <code>bpf_lsm_inode_getsecurity</code>

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
int bpf_lsm_inode_getsecurity(struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81238c60)
Location: include/linux/lsm_hook_defs.h:145
Inline: False
```
**Symbols:**

```
ffffffff81238c60-ffffffff81238c70: bpf_lsm_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_inode_getsecurity(struct user_namespace *mnt_userns, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123d440)
Location: include/linux/lsm_hook_defs.h:152
Inline: False
```
**Symbols:**

```
ffffffff8123d440-ffffffff8123d450: bpf_lsm_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_inode_getsecurity(struct user_namespace *mnt_userns, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81277f00)
Location: include/linux/lsm_hook_defs.h:152
Inline: False
```
**Symbols:**

```
ffffffff81277f00-ffffffff81277f10: bpf_lsm_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_inode_getsecurity(struct user_namespace *mnt_userns, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c80e0)
Location: include/linux/lsm_hook_defs.h:151
Inline: False
```
**Symbols:**

```
ffffffff812c80e0-ffffffff812c80f4: bpf_lsm_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_inode_getsecurity(struct user_namespace *mnt_userns, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132e240)
Location: include/linux/lsm_hook_defs.h:157
Inline: False
```
**Symbols:**

```
ffffffff8132e240-ffffffff8132e254: bpf_lsm_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_inode_getsecurity(struct mnt_idmap *idmap, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8135eeb0)
Location: include/linux/lsm_hook_defs.h:158
Inline: False
```
**Symbols:**

```
ffffffff8135eeb0-ffffffff8135eec4: bpf_lsm_inode_getsecurity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_inode_getsecurity(struct mnt_idmap *idmap, struct inode *inode, const char *name, void **buffer, bool alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81387c80)
Location: include/linux/lsm_hook_defs.h:158
Inline: False
```
**Symbols:**

```
ffffffff81387c80-ffffffff81387c94: bpf_lsm_inode_getsecurity (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, name, buffer, alloc</code> ➡️ <code>mnt_userns, inode, name, buffer, alloc</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
