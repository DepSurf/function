# Function: <code>bpf_lsm_dentry_create_files_as</code>

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
int bpf_lsm_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81238a20)
Location: include/linux/lsm_hook_defs.h:85
Inline: False
```
**Symbols:**

```
ffffffff81238a20-ffffffff81238a2d: bpf_lsm_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123d1f0)
Location: include/linux/lsm_hook_defs.h:87
Inline: False
```
**Symbols:**

```
ffffffff8123d1f0-ffffffff8123d1fd: bpf_lsm_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81277cb0)
Location: include/linux/lsm_hook_defs.h:87
Inline: False
```
**Symbols:**

```
ffffffff81277cb0-ffffffff81277cbd: bpf_lsm_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c7c60)
Location: include/linux/lsm_hook_defs.h:86
Inline: False
```
**Symbols:**

```
ffffffff812c7c60-ffffffff812c7c71: bpf_lsm_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132dae0)
Location: include/linux/lsm_hook_defs.h:86
Inline: False
```
**Symbols:**

```
ffffffff8132dae0-ffffffff8132daf1: bpf_lsm_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8135e750)
Location: include/linux/lsm_hook_defs.h:87
Inline: False
```
**Symbols:**

```
ffffffff8135e750-ffffffff8135e761: bpf_lsm_dentry_create_files_as (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_dentry_create_files_as(struct dentry *dentry, int mode, struct qstr *name, const struct cred *old, struct cred *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81387520)
Location: include/linux/lsm_hook_defs.h:87
Inline: False
```
**Symbols:**

```
ffffffff81387520-ffffffff81387531: bpf_lsm_dentry_create_files_as (STB_GLOBAL)
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
