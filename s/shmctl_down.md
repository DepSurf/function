# Function: <code>shmctl_down</code>

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
In ipc/shm.c (ffffffff8132a860)
Location: ipc/shm.c:811
Inline: True
Direct callers:
  - ipc/shm.c:SyS_shmctl
```
**Symbols:**

```
ffffffff8132a860-ffffffff8132a9a5: shmctl_down.constprop.17 (STB_LOCAL)
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
In ipc/shm.c (ffffffff8135f510)
Location: ipc/shm.c:813
Inline: True
Direct callers:
  - ipc/shm.c:SyS_shmctl
```
**Symbols:**

```
ffffffff8135f510-ffffffff8135f65a: shmctl_down.constprop.19 (STB_LOCAL)
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
In ipc/shm.c (ffffffff81375d10)
Location: ipc/shm.c:817
Inline: True
Direct callers:
  - ipc/shm.c:SyS_shmctl
```
**Symbols:**

```
ffffffff81375d10-ffffffff81375e5a: shmctl_down.constprop.21 (STB_LOCAL)
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
In ipc/shm.c (ffffffff81389890)
Location: ipc/shm.c:815
Inline: True
Direct callers:
  - ipc/shm.c:SyS_shmctl
```
**Symbols:**

```
ffffffff81389890-ffffffff813899dd: shmctl_down.constprop.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813ae8b0)
Location: ipc/shm.c:831
Inline: False
Direct callers:
  - ipc/shm.c:C_SYSC_shmctl
  - ipc/shm.c:SYSC_shmctl
```
**Symbols:**

```
ffffffff813ae8b0-ffffffff813ae994: shmctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813de280)
Location: ipc/shm.c:871
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
ffffffff813de280-ffffffff813de367: shmctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813f8930)
Location: ipc/shm.c:891
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
ffffffff813f8930-ffffffff813f8a17: shmctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81424e90)
Location: ipc/shm.c:891
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81424e90-ffffffff81424f7e: shmctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8143ebe0)
Location: ipc/shm.c:891
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8143ebe0-ffffffff8143ecce: shmctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8148fcc0)
Location: ipc/shm.c:891
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8148fcc0-ffffffff8148fdcd: shmctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814ad3d0)
Location: ipc/shm.c:890
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814ad3d0-ffffffff814ad4d8: shmctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814b3250)
Location: ipc/shm.c:890
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814b3250-ffffffff814b3358: shmctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8150b460)
Location: ipc/shm.c:986
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8150b460-ffffffff8150b542: shmctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8159dbf0)
Location: ipc/shm.c:980
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8159dbf0-ffffffff8159dd2e: shmctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff816471d0)
Location: ipc/shm.c:996
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff816471d0-ffffffff8164730e: shmctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8167f710)
Location: ipc/shm.c:996
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8167f710-ffffffff8167f84e: shmctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff816bbb00)
Location: ipc/shm.c:992
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff816bbb00-ffffffff816bbc3e: shmctl_down (STB_LOCAL)
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
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffff800010527968)
Location: ipc/shm.c:891
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffff800010527968-ffff800010527ae8: shmctl_down (STB_LOCAL)
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
In ipc/shm.c (c06e116c)
Location: ipc/shm.c:891
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
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c000000000671730)
Location: ipc/shm.c:891
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
c000000000671730-c0000000006718d0: shmctl_down (STB_LOCAL)
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
In ipc/shm.c (ffffffe00038b50e)
Location: ipc/shm.c:891
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
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814371c0)
Location: ipc/shm.c:891
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814371c0-ffffffff814372ae: shmctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81427c30)
Location: ipc/shm.c:891
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81427c30-ffffffff81427d1e: shmctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81433360)
Location: ipc/shm.c:891
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81433360-ffffffff8143344e: shmctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shmctl_down(struct ipc_namespace *ns, int shmid, int cmd, struct shmid64_ds *shmid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8144a4e0)
Location: ipc/shm.c:891
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8144a4e0-ffffffff8144a5c5: shmctl_down (STB_LOCAL)
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
