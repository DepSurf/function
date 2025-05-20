# Function: <code>semctl_down</code>

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
In ipc/sem.c (ffffffff81327f70)
Location: ipc/sem.c:1531
Inline: True
Direct callers:
  - ipc/sem.c:SyS_semctl
```
**Symbols:**

```
ffffffff81327f70-ffffffff81328155: semctl_down.constprop.13 (STB_LOCAL)
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
In ipc/sem.c (ffffffff8135cc00)
Location: ipc/sem.c:1529
Inline: True
Direct callers:
  - ipc/sem.c:SyS_semctl
```
**Symbols:**

```
ffffffff8135cc00-ffffffff8135cdeb: semctl_down.constprop.15 (STB_LOCAL)
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
In ipc/sem.c (ffffffff813732b0)
Location: ipc/sem.c:1520
Inline: True
Direct callers:
  - ipc/sem.c:SyS_semctl
```
**Symbols:**

```
ffffffff813732b0-ffffffff813734c4: semctl_down.constprop.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (ffffffff81386880)
Location: ipc/sem.c:1533
Inline: True
Direct callers:
  - ipc/sem.c:SyS_semctl
```
**Symbols:**

```
ffffffff81386880-ffffffff81386ade: semctl_down.constprop.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813ab190)
Location: ipc/sem.c:1519
Inline: False
Direct callers:
  - ipc/sem.c:C_SYSC_semctl
  - ipc/sem.c:SYSC_semctl
```
**Symbols:**

```
ffffffff813ab190-ffffffff813ab38b: semctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813da8d0)
Location: ipc/sem.c:1580
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:ksys_semctl
```
**Symbols:**

```
ffffffff813da8d0-ffffffff813dab1f: semctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813f4f20)
Location: ipc/sem.c:1587
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:ksys_semctl
```
**Symbols:**

```
ffffffff813f4f20-ffffffff813f516f: semctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81421260)
Location: ipc/sem.c:1583
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81421260-ffffffff814214c1: semctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8143b050)
Location: ipc/sem.c:1583
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff8143b050-ffffffff8143b2b1: semctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8148b5d0)
Location: ipc/sem.c:1599
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff8148b5d0-ffffffff8148b831: semctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814a8bf0)
Location: ipc/sem.c:1598
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff814a8bf0-ffffffff814a8e55: semctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814aeb30)
Location: ipc/sem.c:1600
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff814aeb30-ffffffff814aed95: semctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81506fc0)
Location: ipc/sem.c:1603
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81506fc0-ffffffff81507225: semctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff815992c0)
Location: ipc/sem.c:1601
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff815992c0-ffffffff8159951d: semctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81642530)
Location: ipc/sem.c:1601
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81642530-ffffffff8164278d: semctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8167aac0)
Location: ipc/sem.c:1601
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff8167aac0-ffffffff8167ad12: semctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816b6e60)
Location: ipc/sem.c:1601
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff816b6e60-ffffffff816b70b2: semctl_down (STB_LOCAL)
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
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff800010523058)
Location: ipc/sem.c:1583
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:__arm64_sys_semctl
```
**Symbols:**

```
ffff800010523058-ffff8000105232a8: semctl_down (STB_LOCAL)
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
In ipc/sem.c (c06de738)
Location: ipc/sem.c:1583
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
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066c6f0)
Location: ipc/sem.c:1583
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:ksys_semctl
```
**Symbols:**

```
c00000000066c6f0-c00000000066caac: semctl_down (STB_LOCAL)
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
In ipc/sem.c (ffffffe000389bb4)
Location: ipc/sem.c:1583
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
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81433630)
Location: ipc/sem.c:1583
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81433630-ffffffff81433891: semctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814240b0)
Location: ipc/sem.c:1583
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff814240b0-ffffffff81424311: semctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8142f7d0)
Location: ipc/sem.c:1583
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff8142f7d0-ffffffff8142fa31: semctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int semctl_down(struct ipc_namespace *ns, int semid, int cmd, struct semid64_ds *semid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81446950)
Location: ipc/sem.c:1583
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81446950-ffffffff81446b9f: semctl_down (STB_LOCAL)
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
