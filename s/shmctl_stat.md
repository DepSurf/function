# Function: <code>shmctl_stat</code>

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
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813ae220)
Location: ipc/shm.c:920
Inline: False
Direct callers:
  - ipc/shm.c:C_SYSC_shmctl
  - ipc/shm.c:SYSC_shmctl
```
**Symbols:**

```
ffffffff813ae220-ffffffff813ae32e: shmctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813de110)
Location: ipc/shm.c:960
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
ffffffff813de110-ffffffff813de27b: shmctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813f86a0)
Location: ipc/shm.c:980
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
ffffffff813f86a0-ffffffff813f881e: shmctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81424cf0)
Location: ipc/shm.c:980
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81424cf0-ffffffff81424e90: shmctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8143ea40)
Location: ipc/shm.c:980
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8143ea40-ffffffff8143ebe0: shmctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8148f5c0)
Location: ipc/shm.c:980
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8148f5c0-ffffffff8148f746: shmctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814acca0)
Location: ipc/shm.c:979
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814acca0-ffffffff814ace21: shmctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814b27f0)
Location: ipc/shm.c:979
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814b27f0-ffffffff814b2971: shmctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:1075
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8150ade0-ffffffff8150af73: shmctl_stat (STB_LOCAL)
ffffffff81cd2bc8-ffffffff81cd2bdd: shmctl_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:1069
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8159ce50-ffffffff8159cff7: shmctl_stat (STB_LOCAL)
ffffffff81e85dbe-ffffffff81e85dd3: shmctl_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:1085
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81646330-ffffffff816464d7: shmctl_stat (STB_LOCAL)
ffffffff82072f36-ffffffff82072f4b: shmctl_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:1085
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8167e840-ffffffff8167e9e7: shmctl_stat (STB_LOCAL)
ffffffff820f2b7e-ffffffff820f2b93: shmctl_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:1081
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff816bac30-ffffffff816badd7: shmctl_stat (STB_LOCAL)
ffffffff821cfe16-ffffffff821cfe2b: shmctl_stat.cold (STB_LOCAL)
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
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffff8000105270e0)
Location: ipc/shm.c:980
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffff8000105270e0-ffff8000105272a8: shmctl_stat (STB_LOCAL)
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
In ipc/shm.c (c06e0e28)
Location: ipc/shm.c:980
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmctl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c0000000006714c0)
Location: ipc/shm.c:980
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
c0000000006714c0-c000000000671724: shmctl_stat (STB_LOCAL)
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
In ipc/shm.c (ffffffe00038b2f8)
Location: ipc/shm.c:980
Inline: True
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
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81437020)
Location: ipc/shm.c:980
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81437020-ffffffff814371c0: shmctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81427a90)
Location: ipc/shm.c:980
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81427a90-ffffffff81427c30: shmctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814331c0)
Location: ipc/shm.c:980
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814331c0-ffffffff81433360: shmctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shmctl_stat(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *tbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81449a10)
Location: ipc/shm.c:980
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81449a10-ffffffff81449bb3: shmctl_stat (STB_LOCAL)
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
