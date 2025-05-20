# Function: <code>bpf_lsm_sem_semop</code>

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
int bpf_lsm_sem_semop(struct kern_ipc_perm *perm, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812390c0)
Location: include/linux/lsm_hook_defs.h:242
Inline: False
```
**Symbols:**

```
ffffffff812390c0-ffffffff812390cd: bpf_lsm_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_sem_semop(struct kern_ipc_perm *perm, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123d8b0)
Location: include/linux/lsm_hook_defs.h:252
Inline: False
```
**Symbols:**

```
ffffffff8123d8b0-ffffffff8123d8bd: bpf_lsm_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_sem_semop(struct kern_ipc_perm *perm, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81278370)
Location: include/linux/lsm_hook_defs.h:252
Inline: False
```
**Symbols:**

```
ffffffff81278370-ffffffff8127837d: bpf_lsm_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_sem_semop(struct kern_ipc_perm *perm, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c88f0)
Location: include/linux/lsm_hook_defs.h:251
Inline: False
```
**Symbols:**

```
ffffffff812c88f0-ffffffff812c8901: bpf_lsm_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_sem_semop(struct kern_ipc_perm *perm, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132ef30)
Location: include/linux/lsm_hook_defs.h:259
Inline: False
```
**Symbols:**

```
ffffffff8132ef30-ffffffff8132ef41: bpf_lsm_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_sem_semop(struct kern_ipc_perm *perm, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8135fba0)
Location: include/linux/lsm_hook_defs.h:260
Inline: False
```
**Symbols:**

```
ffffffff8135fba0-ffffffff8135fbb1: bpf_lsm_sem_semop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_sem_semop(struct kern_ipc_perm *perm, struct sembuf *sops, unsigned int nsops, int alter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff813889c0)
Location: include/linux/lsm_hook_defs.h:265
Inline: False
```
**Symbols:**

```
ffffffff813889c0-ffffffff813889d1: bpf_lsm_sem_semop (STB_GLOBAL)
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
