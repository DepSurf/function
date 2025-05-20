# Function: <code>bpf_lsm_inode_getsecctx</code>

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
int bpf_lsm_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81239180)
Location: include/linux/lsm_hook_defs.h:258
Inline: False
```
**Symbols:**

```
ffffffff81239180-ffffffff8123918d: bpf_lsm_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123d970)
Location: include/linux/lsm_hook_defs.h:268
Inline: False
```
**Symbols:**

```
ffffffff8123d970-ffffffff8123d97d: bpf_lsm_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81278430)
Location: include/linux/lsm_hook_defs.h:268
Inline: False
```
**Symbols:**

```
ffffffff81278430-ffffffff8127843d: bpf_lsm_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c8a40)
Location: include/linux/lsm_hook_defs.h:267
Inline: False
```
**Symbols:**

```
ffffffff812c8a40-ffffffff812c8a51: bpf_lsm_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132f140)
Location: include/linux/lsm_hook_defs.h:275
Inline: False
```
**Symbols:**

```
ffffffff8132f140-ffffffff8132f151: bpf_lsm_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_inode_getsecctx(struct inode *inode, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8135fdb0)
Location: include/linux/lsm_hook_defs.h:276
Inline: False
```
**Symbols:**

```
ffffffff8135fdb0-ffffffff8135fdc1: bpf_lsm_inode_getsecctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_inode_getsecctx(struct inode *inode, struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81388c60)
Location: include/linux/lsm_hook_defs.h:286
Inline: False
```
**Symbols:**

```
ffffffff81388c60-ffffffff81388c74: bpf_lsm_inode_getsecctx (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsmcontext *cp</code>
</li>
<li>
<b>Param removed. </b>
<code>void **ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 *ctxlen</code>
</li>
</ul>
</details>
</li>
</ul>
