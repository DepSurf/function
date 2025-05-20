# Function: <code>bpf_lsm_key_permission</code>

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
int bpf_lsm_key_permission(key_ref_t key_ref, const struct cred *cred, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81239540)
Location: include/linux/lsm_hook_defs.h:364
Inline: False
```
**Symbols:**

```
ffffffff81239540-ffffffff8123954d: bpf_lsm_key_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_key_permission(key_ref_t key_ref, const struct cred *cred, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123dd30)
Location: include/linux/lsm_hook_defs.h:374
Inline: False
```
**Symbols:**

```
ffffffff8123dd30-ffffffff8123dd3d: bpf_lsm_key_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_key_permission(key_ref_t key_ref, const struct cred *cred, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812787f0)
Location: include/linux/lsm_hook_defs.h:373
Inline: False
```
**Symbols:**

```
ffffffff812787f0-ffffffff812787fd: bpf_lsm_key_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_key_permission(key_ref_t key_ref, const struct cred *cred, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c90f0)
Location: include/linux/lsm_hook_defs.h:374
Inline: False
```
**Symbols:**

```
ffffffff812c90f0-ffffffff812c9101: bpf_lsm_key_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_key_permission(key_ref_t key_ref, const struct cred *cred, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132fbc0)
Location: include/linux/lsm_hook_defs.h:382
Inline: False
```
**Symbols:**

```
ffffffff8132fbc0-ffffffff8132fbd1: bpf_lsm_key_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_key_permission(key_ref_t key_ref, const struct cred *cred, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81360860)
Location: include/linux/lsm_hook_defs.h:384
Inline: False
```
**Symbols:**

```
ffffffff81360860-ffffffff81360871: bpf_lsm_key_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_key_permission(key_ref_t key_ref, const struct cred *cred, enum key_need_perm need_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81389710)
Location: include/linux/lsm_hook_defs.h:394
Inline: False
```
**Symbols:**

```
ffffffff81389710-ffffffff81389721: bpf_lsm_key_permission (STB_GLOBAL)
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
