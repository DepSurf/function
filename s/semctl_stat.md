# Function: <code>semctl_stat</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813aa160)
Location: ipc/sem.c:1183
Inline: False
Direct callers:
  - ipc/sem.c:C_SYSC_semctl
  - ipc/sem.c:SYSC_semctl
```
**Symbols:**

```
ffffffff813aa160-ffffffff813aa278: semctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813dab20)
Location: ipc/sem.c:1220
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:ksys_semctl
```
**Symbols:**

```
ffffffff813dab20-ffffffff813dac80: semctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813f5170)
Location: ipc/sem.c:1219
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:ksys_semctl
```
**Symbols:**

```
ffffffff813f5170-ffffffff813f52e2: semctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814214d0)
Location: ipc/sem.c:1215
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff814214d0-ffffffff8142165c: semctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8143b2c0)
Location: ipc/sem.c:1215
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff8143b2c0-ffffffff8143b44c: semctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8148b840)
Location: ipc/sem.c:1231
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff8148b840-ffffffff8148b9ba: semctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814a8e60)
Location: ipc/sem.c:1230
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff814a8e60-ffffffff814a8fd7: semctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814b0250)
Location: ipc/sem.c:1232
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff814b0250-ffffffff814b03c7: semctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1235
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81508310-ffffffff81508499: semctl_stat (STB_LOCAL)
ffffffff81cd2b49-ffffffff81cd2b5e: semctl_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1234
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81597850-ffffffff815979eb: semctl_stat (STB_LOCAL)
ffffffff81e85c24-ffffffff81e85c39: semctl_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1234
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81640a00-ffffffff81640b9c: semctl_stat (STB_LOCAL)
ffffffff82072d9d-ffffffff82072db2: semctl_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1234
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81678f60-ffffffff81679127: semctl_stat (STB_LOCAL)
ffffffff820f29f2-ffffffff820f2a07: semctl_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1234
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff816b5350-ffffffff816b5517: semctl_stat (STB_LOCAL)
ffffffff821cfca2-ffffffff821cfcb7: semctl_stat.cold (STB_LOCAL)
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
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff800010522e88)
Location: ipc/sem.c:1215
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:__arm64_sys_semctl
```
**Symbols:**

```
ffff800010522e88-ffff800010523058: semctl_stat (STB_LOCAL)
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
In ipc/sem.c (c06de494)
Location: ipc/sem.c:1215
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
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066cab0)
Location: ipc/sem.c:1215
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:ksys_semctl
```
**Symbols:**

```
c00000000066cab0-c00000000066cd14: semctl_stat (STB_LOCAL)
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
In ipc/sem.c (ffffffe000389a60)
Location: ipc/sem.c:1215
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
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814338a0)
Location: ipc/sem.c:1215
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff814338a0-ffffffff81433a2c: semctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81424320)
Location: ipc/sem.c:1215
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81424320-ffffffff814244ac: semctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8142fa40)
Location: ipc/sem.c:1215
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff8142fa40-ffffffff8142fbcc: semctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int semctl_stat(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81445370)
Location: ipc/sem.c:1215
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81445370-ffffffff81445507: semctl_stat (STB_LOCAL)
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
