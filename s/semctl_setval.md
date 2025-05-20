# Function: <code>semctl_setval</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81329739)
Location: ipc/sem.c:1267
Inline: True
Inline callers:
  - ipc/sem.c:SyS_semctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8135e3c9)
Location: ipc/sem.c:1263
Inline: True
Inline callers:
  - ipc/sem.c:SyS_semctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81374b59)
Location: ipc/sem.c:1258
Inline: True
Inline callers:
  - ipc/sem.c:SyS_semctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813885e9)
Location: ipc/sem.c:1269
Inline: True
Inline callers:
  - ipc/sem.c:SyS_semctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813ac450)
Location: ipc/sem.c:1263
Inline: False
Direct callers:
  - ipc/sem.c:C_SYSC_semctl
  - ipc/sem.c:SYSC_semctl
```
**Symbols:**

```
ffffffff813ac450-ffffffff813ac796: semctl_setval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813db650)
Location: ipc/sem.c:1321
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:ksys_semctl
```
**Symbols:**

```
ffffffff813db650-ffffffff813db9e4: semctl_setval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813f5cc0)
Location: ipc/sem.c:1328
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:ksys_semctl
```
**Symbols:**

```
ffffffff813f5cc0-ffffffff813f6054: semctl_setval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81423040)
Location: ipc/sem.c:1324
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81423040-ffffffff814233ee: semctl_setval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8143cd80)
Location: ipc/sem.c:1324
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff8143cd80-ffffffff8143d12e: semctl_setval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8148d7e0)
Location: ipc/sem.c:1340
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff8148d7e0-ffffffff8148dceb: semctl_setval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814aaf00)
Location: ipc/sem.c:1339
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff814aaf00-ffffffff814ab421: semctl_setval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814af920)
Location: ipc/sem.c:1341
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff814af920-ffffffff814afe40: semctl_setval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1344
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81507de0-ffffffff8150830e: semctl_setval (STB_LOCAL)
ffffffff81cd2b34-ffffffff81cd2b49: semctl_setval.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1343
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff815987c0-ffffffff81598cda: semctl_setval (STB_LOCAL)
ffffffff81e85c55-ffffffff81e85c6a: semctl_setval.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1343
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81641a10-ffffffff81641f2a: semctl_setval (STB_LOCAL)
ffffffff82072dce-ffffffff82072de3: semctl_setval.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1343
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81679f80-ffffffff8167a48a: semctl_setval (STB_LOCAL)
ffffffff820f2a23-ffffffff820f2a37: semctl_setval.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1343
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff816b6320-ffffffff816b6827: semctl_setval (STB_LOCAL)
ffffffff821cfcd3-ffffffff821cfce7: semctl_setval.cold (STB_LOCAL)
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
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff800010524c38)
Location: ipc/sem.c:1324
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:__arm64_sys_semctl
```
**Symbols:**

```
ffff800010524c38-ffff800010524f94: semctl_setval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c06de51c)
Location: ipc/sem.c:1324
Inline: True
Inline callers:
  - ipc/sem.c:ksys_semctl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066da10)
Location: ipc/sem.c:1324
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:ksys_semctl
```
**Symbols:**

```
c00000000066da10-c00000000066dee8: semctl_setval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffe000389cd6)
Location: ipc/sem.c:1324
Inline: True
Inline callers:
  - ipc/sem.c:__se_sys_semctl
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
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81435360)
Location: ipc/sem.c:1324
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81435360-ffffffff8143570e: semctl_setval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81425de0)
Location: ipc/sem.c:1324
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81425de0-ffffffff8142618e: semctl_setval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81431500)
Location: ipc/sem.c:1324
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81431500-ffffffff814318ae: semctl_setval (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int semctl_setval(struct ipc_namespace *ns, int semid, int semnum, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814485b0)
Location: ipc/sem.c:1324
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff814485b0-ffffffff8144897f: semctl_setval (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
