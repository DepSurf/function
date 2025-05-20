# Function: <code>ipcctl_obtain_check</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813f1550)
Location: ipc/util.c:659
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff813f1550-ffffffff813f1641: ipcctl_obtain_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8141d810)
Location: ipc/util.c:688
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff8141d810-ffffffff8141d903: ipcctl_obtain_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81437660)
Location: ipc/util.c:688
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff81437660-ffffffff81437753: ipcctl_obtain_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81487660)
Location: ipc/util.c:688
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff81487660-ffffffff8148778d: ipcctl_obtain_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814a4c80)
Location: ipc/util.c:688
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff814a4c80-ffffffff814a4dad: ipcctl_obtain_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814aac40)
Location: ipc/util.c:688
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff814aac40-ffffffff814aad6d: ipcctl_obtain_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81503130)
Location: ipc/util.c:722
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff81503130-ffffffff81503223: ipcctl_obtain_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81594780)
Location: ipc/util.c:722
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff81594780-ffffffff8159489d: ipcctl_obtain_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8163d400)
Location: ipc/util.c:722
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff8163d400-ffffffff8163d51d: ipcctl_obtain_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81675920)
Location: ipc/util.c:722
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff81675920-ffffffff81675a16: ipcctl_obtain_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff816b1ce0)
Location: ipc/util.c:722
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff816b1ce0-ffffffff816b1dd6: ipcctl_obtain_check (STB_GLOBAL)
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
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffff80001051de80)
Location: ipc/util.c:688
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffff80001051de80-ffff80001051df84: ipcctl_obtain_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (c06da2fc)
Location: ipc/util.c:688
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:ksys_semctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
c06da2fc-c06da418: ipcctl_obtain_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (c000000000667300)
Location: ipc/util.c:688
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
c000000000667300-c00000000066746c: ipcctl_obtain_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffe00038564a)
Location: ipc/util.c:688
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:__se_sys_semctl
```
**Symbols:**

```
ffffffe00038564a-ffffffe000385704: ipcctl_obtain_check (STB_GLOBAL)
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
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142fc40)
Location: ipc/util.c:688
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff8142fc40-ffffffff8142fd33: ipcctl_obtain_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814206c0)
Location: ipc/util.c:688
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff814206c0-ffffffff814207b3: ipcctl_obtain_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142bde0)
Location: ipc/util.c:688
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff8142bde0-ffffffff8142bed3: ipcctl_obtain_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kern_ipc_perm *ipcctl_obtain_check(struct ipc_namespace *ns, struct ipc_ids *ids, int id, int cmd, struct ipc64_perm *perm, int extra_perm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81442e00)
Location: ipc/util.c:688
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
  - ipc/sem.c:semctl_down
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff81442e00-ffffffff81442ef3: ipcctl_obtain_check (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
