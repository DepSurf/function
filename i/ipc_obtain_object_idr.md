# Function: <code>ipc_obtain_object_idr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81324e90)
Location: ipc/util.c:558
Inline: True
Inline callers:
  - ipc/util.c:ipc_lock
  - ipc/util.c:ipc_obtain_object_check
Direct callers:
  - ipc/sem.c:SYSC_semtimedop
```
**Symbols:**

```
ffffffff81324e90-ffffffff81324ef4: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81359b85)
Location: ipc/util.c:553
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_lock
Direct callers:
  - ipc/sem.c:SYSC_semtimedop
```
**Symbols:**

```
ffffffff81359a80-ffffffff81359ae3: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81370065)
Location: ipc/util.c:553
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_lock
```
**Symbols:**

```
ffffffff8136ff60-ffffffff8136ffc3: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81383485)
Location: ipc/util.c:497
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_lock
```
**Symbols:**

```
ffffffff813833d0-ffffffff81383407: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813a7835)
Location: ipc/util.c:560
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_lock
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff813a7770-ffffffff813a77b5: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813d6bd5)
Location: ipc/util.c:564
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
  - ipc/util.c:ipc_lock
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:shmctl_stat
```
**Symbols:**

```
ffffffff813d6b10-ffffffff813d6b55: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813f11e5)
Location: ipc/util.c:564
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff813f11a0-ffffffff813f11d7: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8141d485)
Location: ipc/util.c:593
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff8141d440-ffffffff8141d47b: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814372d5)
Location: ipc/util.c:593
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff81437290-ffffffff814372cb: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81487665)
Location: ipc/util.c:593
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff814873d0-ffffffff8148740b: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814a4c89)
Location: ipc/util.c:593
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff814a49f0-ffffffff814a4a2b: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814aac49)
Location: ipc/util.c:593
Inline: True
Inline callers:
  - ipc/util.c:ipcctl_obtain_check
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff814aa9b0-ffffffff814aa9eb: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/util.c (ffffffff81502ee1)
Location: ipc/util.c:627
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff81cd292f-ffffffff81cd294e: ipc_obtain_object_idr.cold (STB_LOCAL)
ffffffff81502e70-ffffffff81502ec5: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/util.c (ffffffff81594501)
Location: ipc/util.c:627
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff81e85a85-ffffffff81e85aa4: ipc_obtain_object_idr.cold (STB_LOCAL)
ffffffff81594480-ffffffff815944e1: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/util.c (ffffffff8163d151)
Location: ipc/util.c:627
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_open
```
**Symbols:**

```
ffffffff82072c93-ffffffff82072cb2: ipc_obtain_object_idr.cold (STB_LOCAL)
ffffffff8163d0c0-ffffffff8163d121: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/util.c (ffffffff81675661)
Location: ipc/util.c:627
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_open
```
**Symbols:**

```
ffffffff820f28ea-ffffffff820f2909: ipc_obtain_object_idr.cold (STB_LOCAL)
ffffffff816755d0-ffffffff81675631: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/util.c (ffffffff816b1a21)
Location: ipc/util.c:627
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:__shm_close
  - ipc/shm.c:__shm_open
```
**Symbols:**

```
ffffffff821cfb9a-ffffffff821cfbb9: ipc_obtain_object_idr.cold (STB_LOCAL)
ffffffff816b1990-ffffffff816b19f1: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffff80001051daac)
Location: ipc/util.c:593
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffff80001051da30-ffff80001051da88: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (c06d9f1c)
Location: ipc/util.c:593
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
Direct callers:
  - ipc/msg.c:ksys_msgctl
  - ipc/sem.c:ksys_semctl
  - ipc/shm.c:do_shmat
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:shm_close
  - ipc/shm.c:__shm_open
```
**Symbols:**

```
c06d9ecc-c06d9f08: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (c000000000666e14)
Location: ipc/util.c:593
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shm_close
```
**Symbols:**

```
c000000000666d70-c000000000666de4: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffe000385302)
Location: ipc/util.c:593
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
Direct callers:
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:__se_sys_semctl
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffe000385298-ffffffe0003852ee: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142f8b5)
Location: ipc/util.c:593
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff8142f870-ffffffff8142f8ab: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81420335)
Location: ipc/util.c:593
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff814202f0-ffffffff8142032b: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142ba55)
Location: ipc/util.c:593
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff8142ba10-ffffffff8142ba4b: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *ipc_obtain_object_idr(struct ipc_ids *ids, int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81442a65)
Location: ipc/util.c:593
Inline: True
Inline callers:
  - ipc/util.c:ipc_obtain_object_check
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/sem.c:semctl_stat
  - ipc/shm.c:do_shmat
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff81442a20-ffffffff81442a5b: ipc_obtain_object_idr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
