# Function: <code>bpf_lsm_shm_shmat</code>

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
int bpf_lsm_shm_shmat(struct kern_ipc_perm *perm, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81239070)
Location: include/linux/lsm_hook_defs.h:236
Inline: False
```
**Symbols:**

```
ffffffff81239070-ffffffff8123907d: bpf_lsm_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_shm_shmat(struct kern_ipc_perm *perm, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123d860)
Location: include/linux/lsm_hook_defs.h:246
Inline: False
```
**Symbols:**

```
ffffffff8123d860-ffffffff8123d86d: bpf_lsm_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_shm_shmat(struct kern_ipc_perm *perm, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81278320)
Location: include/linux/lsm_hook_defs.h:246
Inline: False
```
**Symbols:**

```
ffffffff81278320-ffffffff8127832d: bpf_lsm_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_shm_shmat(struct kern_ipc_perm *perm, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c8860)
Location: include/linux/lsm_hook_defs.h:245
Inline: False
```
**Symbols:**

```
ffffffff812c8860-ffffffff812c8871: bpf_lsm_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_shm_shmat(struct kern_ipc_perm *perm, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132ee50)
Location: include/linux/lsm_hook_defs.h:253
Inline: False
```
**Symbols:**

```
ffffffff8132ee50-ffffffff8132ee61: bpf_lsm_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_shm_shmat(struct kern_ipc_perm *perm, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8135fac0)
Location: include/linux/lsm_hook_defs.h:254
Inline: False
```
**Symbols:**

```
ffffffff8135fac0-ffffffff8135fad1: bpf_lsm_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_shm_shmat(struct kern_ipc_perm *perm, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff813888e0)
Location: include/linux/lsm_hook_defs.h:259
Inline: False
```
**Symbols:**

```
ffffffff813888e0-ffffffff813888f1: bpf_lsm_shm_shmat (STB_GLOBAL)
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
