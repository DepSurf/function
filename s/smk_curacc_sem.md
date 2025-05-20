# Function: <code>smk_curacc_sem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int smk_curacc_sem(struct sem_array *sma, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8135e980)
Location: security/smack/smack_lsm.c:3090
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
**Symbols:**

```
ffffffff8135e980-ffffffff8135ea00: smk_curacc_sem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smk_curacc_sem(struct sem_array *sma, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81394e80)
Location: security/smack/smack_lsm.c:3109
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
**Symbols:**

```
ffffffff81394e80-ffffffff81394f00: smk_curacc_sem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smk_curacc_sem(struct sem_array *sma, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813ab610)
Location: security/smack/smack_lsm.c:3108
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
**Symbols:**

```
ffffffff813ab610-ffffffff813ab690: smk_curacc_sem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int smk_curacc_sem(struct sem_array *sma, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813c3a50)
Location: security/smack/smack_lsm.c:2978
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
**Symbols:**

```
ffffffff813c3a50-ffffffff813c3adb: smk_curacc_sem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smk_curacc_sem(struct sem_array *sma, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813e9d10)
Location: security/smack/smack_lsm.c:2947
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
**Symbols:**

```
ffffffff813e9d10-ffffffff813e9d9b: smk_curacc_sem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int smk_curacc_sem(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8141aaa0)
Location: security/smack/smack_lsm.c:3116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
**Symbols:**

```
ffffffff8141aaa0-ffffffff8141ab20: smk_curacc_sem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int smk_curacc_sem(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81437160)
Location: security/smack/smack_lsm.c:2934
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
**Symbols:**

```
ffffffff81437160-ffffffff814371eb: smk_curacc_sem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int smk_curacc_sem(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81464df0)
Location: security/smack/smack_lsm.c:3026
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
**Symbols:**

```
ffffffff81464df0-ffffffff81464e77: smk_curacc_sem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int smk_curacc_sem(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8147e9b0)
Location: security/smack/smack_lsm.c:3021
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
**Symbols:**

```
ffffffff8147e9b0-ffffffff8147ea37: smk_curacc_sem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814d4105)
Location: security/smack/smack_lsm.c:3002
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f15d5)
Location: security/smack/smack_lsm.c:3017
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f81f5)
Location: security/smack/smack_lsm.c:3016
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81552de5)
Location: security/smack/smack_lsm.c:3016
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815eca88)
Location: security/smack/smack_lsm.c:3023
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8169c9a8)
Location: security/smack/smack_lsm.c:3098
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff816d56c8)
Location: security/smack/smack_lsm.c:3161
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81711fa8)
Location: security/smack/smack_lsm.c:3220
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
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
int smk_curacc_sem(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffff80001056fa38)
Location: security/smack/smack_lsm.c:3021
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
**Symbols:**

```
ffff80001056fa38-ffff80001056fad4: smk_curacc_sem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smk_curacc_sem(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c07234c4)
Location: security/smack/smack_lsm.c:3021
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
**Symbols:**

```
c07234c4-c0723568: smk_curacc_sem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smk_curacc_sem(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0000000006d6250)
Location: security/smack/smack_lsm.c:3021
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
**Symbols:**

```
c0000000006d6250-c0000000006d62fc: smk_curacc_sem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smk_curacc_sem(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffe0003c2b90)
Location: security/smack/smack_lsm.c:3021
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
**Symbols:**

```
ffffffe0003c2b90-ffffffe0003c2c02: smk_curacc_sem (STB_LOCAL)
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
int smk_curacc_sem(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81476f90)
Location: security/smack/smack_lsm.c:3021
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
**Symbols:**

```
ffffffff81476f90-ffffffff81477017: smk_curacc_sem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int smk_curacc_sem(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814679b0)
Location: security/smack/smack_lsm.c:3021
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
**Symbols:**

```
ffffffff814679b0-ffffffff81467a37: smk_curacc_sem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int smk_curacc_sem(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81473030)
Location: security/smack/smack_lsm.c:3021
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
**Symbols:**

```
ffffffff81473030-ffffffff814730b7: smk_curacc_sem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int smk_curacc_sem(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8148a9b0)
Location: security/smack/smack_lsm.c:3021
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sem_semop
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_semctl
  - security/smack/smack_lsm.c:smack_sem_associate
```
**Symbols:**

```
ffffffff8148a9b0-ffffffff8148aa37: smk_curacc_sem (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kern_ipc_perm *isp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct sem_array *sma</code>
</li>
</ul>
</details>
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
