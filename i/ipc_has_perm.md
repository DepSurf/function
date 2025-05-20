# Function: <code>ipc_has_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff81346290)
Location: security/selinux/hooks.c:5196
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
  - security/selinux/hooks.c:selinux_ipc_permission
```
**Symbols:**

```
ffffffff81346290-ffffffff813462fc: ipc_has_perm.isra.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137b9e0)
Location: security/selinux/hooks.c:5340
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
```
**Symbols:**

```
ffffffff8137b9e0-ffffffff8137ba4c: ipc_has_perm.isra.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff81391e50)
Location: security/selinux/hooks.c:5421
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
```
**Symbols:**

```
ffffffff81391e50-ffffffff81391ebc: ipc_has_perm.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a3d20)
Location: security/selinux/hooks.c:5367
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
```
**Symbols:**

```
ffffffff813a3d20-ffffffff813a3d92: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813c9d00)
Location: security/selinux/hooks.c:5382
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
```
**Symbols:**

```
ffffffff813c9d00-ffffffff813c9d72: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fb040)
Location: security/selinux/hooks.c:5953
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
```
**Symbols:**

```
ffffffff813fb040-ffffffff813fb0b2: ipc_has_perm.isra.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81414ee0)
Location: security/selinux/hooks.c:5645
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
```
**Symbols:**

```
ffffffff81414ee0-ffffffff81414f57: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81442820)
Location: security/selinux/hooks.c:5844
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
```
**Symbols:**

```
ffffffff81442820-ffffffff81442897: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145c2f0)
Location: security/selinux/hooks.c:5902
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
```
**Symbols:**

```
ffffffff8145c2f0-ffffffff8145c36f: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b488c)
Location: security/selinux/hooks.c:5900
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_shm_shmctl
```
**Symbols:**

```
ffffffff814af7a0-ffffffff814af81f: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d2013)
Location: security/selinux/hooks.c:5916
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_shm_shmctl
```
**Symbols:**

```
ffffffff814cd240-ffffffff814cd2bf: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d86b3)
Location: security/selinux/hooks.c:6080
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_shm_shmctl
```
**Symbols:**

```
ffffffff814d3840-ffffffff814d38bf: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815314e3)
Location: security/selinux/hooks.c:6065
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_shm_shmctl
```
**Symbols:**

```
ffffffff8152c500-ffffffff8152c57f: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c8773)
Location: security/selinux/hooks.c:5964
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_shm_shmctl
```
**Symbols:**

```
ffffffff815c2650-ffffffff815c2701: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816758c3)
Location: security/selinux/hooks.c:5979
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_shm_shmctl
```
**Symbols:**

```
ffffffff8166ee50-ffffffff8166ef01: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816ada5e)
Location: security/selinux/hooks.c:5932
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_shm_shmctl
  - security/selinux/hooks.c:selinux_shm_shmctl
```
**Symbols:**

```
ffffffff816a7470-ffffffff816a751d: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816eaaee)
Location: security/selinux/hooks.c:6017
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semctl
  - security/selinux/hooks.c:selinux_shm_shmctl
  - security/selinux/hooks.c:selinux_shm_shmctl
```
**Symbols:**

```
ffffffff816e3ec0-ffffffff816e3f70: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff800010548ec0)
Location: security/selinux/hooks.c:5902
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
```
**Symbols:**

```
ffff800010548ec0-ffff800010548f70: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c06febb0)
Location: security/selinux/hooks.c:5902
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
```
**Symbols:**

```
c06febb0-c06fec6c: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a0300)
Location: security/selinux/hooks.c:5902
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
```
**Symbols:**

```
c0000000006a0300-c0000000006a03b4: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a3fe8)
Location: security/selinux/hooks.c:5902
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
```
**Symbols:**

```
ffffffe0003a3fe8-ffffffe0003a4050: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814548d0)
Location: security/selinux/hooks.c:5902
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
```
**Symbols:**

```
ffffffff814548d0-ffffffff8145494f: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81445310)
Location: security/selinux/hooks.c:5902
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
```
**Symbols:**

```
ffffffff81445310-ffffffff8144538f: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81450970)
Location: security/selinux/hooks.c:5902
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
```
**Symbols:**

```
ffffffff81450970-ffffffff814509ef: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ipc_has_perm(struct kern_ipc_perm *ipc_perms, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81467ed0)
Location: security/selinux/hooks.c:5902
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_ipc_permission
  - security/selinux/hooks.c:selinux_sem_semop
  - security/selinux/hooks.c:selinux_shm_shmat
```
**Symbols:**

```
ffffffff81467ed0-ffffffff81467f4f: ipc_has_perm (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
