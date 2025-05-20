# Function: <code>bpf_lsm_inode_getsecid</code>

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
void bpf_lsm_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81238c90)
Location: include/linux/lsm_hook_defs.h:151
Inline: False
```
**Symbols:**

```
ffffffff81238c90-ffffffff81238c9b: bpf_lsm_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_lsm_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123d470)
Location: include/linux/lsm_hook_defs.h:158
Inline: False
```
**Symbols:**

```
ffffffff8123d470-ffffffff8123d47b: bpf_lsm_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_lsm_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81277f30)
Location: include/linux/lsm_hook_defs.h:158
Inline: False
```
**Symbols:**

```
ffffffff81277f30-ffffffff81277f3b: bpf_lsm_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_lsm_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c8140)
Location: include/linux/lsm_hook_defs.h:157
Inline: False
```
**Symbols:**

```
ffffffff812c8140-ffffffff812c814f: bpf_lsm_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_lsm_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132e2d0)
Location: include/linux/lsm_hook_defs.h:163
Inline: False
```
**Symbols:**

```
ffffffff8132e2d0-ffffffff8132e2df: bpf_lsm_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_lsm_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8135ef40)
Location: include/linux/lsm_hook_defs.h:164
Inline: False
```
**Symbols:**

```
ffffffff8135ef40-ffffffff8135ef4f: bpf_lsm_inode_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
