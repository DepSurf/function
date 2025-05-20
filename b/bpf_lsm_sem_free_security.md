# Function: <code>bpf_lsm_sem_free_security</code>

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
void bpf_lsm_sem_free_security(struct kern_ipc_perm *perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81239090)
Location: include/linux/lsm_hook_defs.h:239
Inline: False
```
**Symbols:**

```
ffffffff81239090-ffffffff8123909b: bpf_lsm_sem_free_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_lsm_sem_free_security(struct kern_ipc_perm *perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123d880)
Location: include/linux/lsm_hook_defs.h:249
Inline: False
```
**Symbols:**

```
ffffffff8123d880-ffffffff8123d88b: bpf_lsm_sem_free_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_lsm_sem_free_security(struct kern_ipc_perm *perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81278340)
Location: include/linux/lsm_hook_defs.h:249
Inline: False
```
**Symbols:**

```
ffffffff81278340-ffffffff8127834b: bpf_lsm_sem_free_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_lsm_sem_free_security(struct kern_ipc_perm *perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c88a0)
Location: include/linux/lsm_hook_defs.h:248
Inline: False
```
**Symbols:**

```
ffffffff812c88a0-ffffffff812c88af: bpf_lsm_sem_free_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_lsm_sem_free_security(struct kern_ipc_perm *perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132eeb0)
Location: include/linux/lsm_hook_defs.h:256
Inline: False
```
**Symbols:**

```
ffffffff8132eeb0-ffffffff8132eebf: bpf_lsm_sem_free_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_lsm_sem_free_security(struct kern_ipc_perm *perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8135fb20)
Location: include/linux/lsm_hook_defs.h:257
Inline: False
```
**Symbols:**

```
ffffffff8135fb20-ffffffff8135fb2f: bpf_lsm_sem_free_security (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_lsm_sem_free_security(struct kern_ipc_perm *perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81388940)
Location: include/linux/lsm_hook_defs.h:262
Inline: False
```
**Symbols:**

```
ffffffff81388940-ffffffff8138894f: bpf_lsm_sem_free_security (STB_GLOBAL)
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
