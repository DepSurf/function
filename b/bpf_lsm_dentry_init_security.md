# Function: <code>bpf_lsm_dentry_init_security</code>

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
int bpf_lsm_dentry_init_security(struct dentry *dentry, int mode, const struct qstr *name, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81238a10)
Location: include/linux/lsm_hook_defs.h:83
Inline: False
```
**Symbols:**

```
ffffffff81238a10-ffffffff81238a1d: bpf_lsm_dentry_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_dentry_init_security(struct dentry *dentry, int mode, const struct qstr *name, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123d1e0)
Location: include/linux/lsm_hook_defs.h:85
Inline: False
```
**Symbols:**

```
ffffffff8123d1e0-ffffffff8123d1ed: bpf_lsm_dentry_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_dentry_init_security(struct dentry *dentry, int mode, const struct qstr *name, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81277ca0)
Location: include/linux/lsm_hook_defs.h:85
Inline: False
```
**Symbols:**

```
ffffffff81277ca0-ffffffff81277cad: bpf_lsm_dentry_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_dentry_init_security(struct dentry *dentry, int mode, const struct qstr *name, const char **xattr_name, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c7c40)
Location: include/linux/lsm_hook_defs.h:83
Inline: False
```
**Symbols:**

```
ffffffff812c7c40-ffffffff812c7c54: bpf_lsm_dentry_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_dentry_init_security(struct dentry *dentry, int mode, const struct qstr *name, const char **xattr_name, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132dab0)
Location: include/linux/lsm_hook_defs.h:83
Inline: False
```
**Symbols:**

```
ffffffff8132dab0-ffffffff8132dac4: bpf_lsm_dentry_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_dentry_init_security(struct dentry *dentry, int mode, const struct qstr *name, const char **xattr_name, void **ctx, u32 *ctxlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8135e720)
Location: include/linux/lsm_hook_defs.h:84
Inline: False
```
**Symbols:**

```
ffffffff8135e720-ffffffff8135e734: bpf_lsm_dentry_init_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_dentry_init_security(struct dentry *dentry, int mode, const struct qstr *name, const char **xattr_name, struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff813874f0)
Location: include/linux/lsm_hook_defs.h:84
Inline: False
```
**Symbols:**

```
ffffffff813874f0-ffffffff81387504: bpf_lsm_dentry_init_security (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char **xattr_name</code>
</li>
<li>
<b>Param reordered. </b>
<code>dentry, mode, name, ctx, ctxlen</code> ➡️ <code>dentry, mode, name, xattr_name, ctx, ctxlen</code>
</li>
</ul>
</details>
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
