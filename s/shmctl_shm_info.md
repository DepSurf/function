# Function: <code>shmctl_shm_info</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int shmctl_shm_info(struct ipc_namespace *ns, struct shm_info *shm_info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813aebf0)
Location: ipc/shm.c:900
Inline: True
Direct callers:
  - ipc/shm.c:C_SYSC_shmctl
  - ipc/shm.c:SYSC_shmctl
```
**Symbols:**

```
ffffffff813aebf0-ffffffff813aed2c: shmctl_shm_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int shmctl_shm_info(struct ipc_namespace *ns, struct shm_info *shm_info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813ddd10)
Location: ipc/shm.c:940
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
ffffffff813ddd10-ffffffff813dde5a: shmctl_shm_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int shmctl_shm_info(struct ipc_namespace *ns, struct shm_info *shm_info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813f8390)
Location: ipc/shm.c:960
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
ffffffff813f8390-ffffffff813f84da: shmctl_shm_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int shmctl_shm_info(struct ipc_namespace *ns, struct shm_info *shm_info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81424890)
Location: ipc/shm.c:960
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81424890-ffffffff814249ed: shmctl_shm_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int shmctl_shm_info(struct ipc_namespace *ns, struct shm_info *shm_info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8143e5e0)
Location: ipc/shm.c:960
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8143e5e0-ffffffff8143e73d: shmctl_shm_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/shm.c (ffffffff8149020b)
Location: ipc/shm.c:960
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8148f310-ffffffff8148f434: shmctl_shm_info.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/shm.c (ffffffff814ad92b)
Location: ipc/shm.c:959
Inline: True
Inline callers:
  - ipc/shm.c:compat_ksys_shmctl
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814ac9f0-ffffffff814acb14: shmctl_shm_info.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int shmctl_shm_info(struct ipc_namespace *ns, struct shm_info *shm_info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814b2b70)
Location: ipc/shm.c:959
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814b2b70-ffffffff814b2ca0: shmctl_shm_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int shmctl_shm_info(struct ipc_namespace *ns, struct shm_info *shm_info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8150b1b0)
Location: ipc/shm.c:1055
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8150b1b0-ffffffff8150b2e0: shmctl_shm_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int shmctl_shm_info(struct ipc_namespace *ns, struct shm_info *shm_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8159cb80)
Location: ipc/shm.c:1049
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8159cb80-ffffffff8159ccb7: shmctl_shm_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shmctl_shm_info(struct ipc_namespace *ns, struct shm_info *shm_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81646040)
Location: ipc/shm.c:1065
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81646040-ffffffff81646177: shmctl_shm_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shmctl_shm_info(struct ipc_namespace *ns, struct shm_info *shm_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8167e550)
Location: ipc/shm.c:1065
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8167e550-ffffffff8167e687: shmctl_shm_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int shmctl_shm_info(struct ipc_namespace *ns, struct shm_info *shm_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff816ba940)
Location: ipc/shm.c:1061
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff816ba940-ffffffff816baa77: shmctl_shm_info (STB_LOCAL)
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
int shmctl_shm_info(struct ipc_namespace *ns, struct shm_info *shm_info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffff800010527548)
Location: ipc/shm.c:960
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffff800010527548-ffff80001052765c: shmctl_shm_info (STB_LOCAL)
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
In ipc/shm.c (c06e1070)
Location: ipc/shm.c:960
Inline: True
Inline callers:
  - ipc/shm.c:ksys_shmctl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int shmctl_shm_info(struct ipc_namespace *ns, struct shm_info *shm_info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c000000000670df0)
Location: ipc/shm.c:960
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
c000000000670df0-c000000000670f98: shmctl_shm_info (STB_LOCAL)
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
In ipc/shm.c (ffffffe00038b5b8)
Location: ipc/shm.c:960
Inline: True
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
int shmctl_shm_info(struct ipc_namespace *ns, struct shm_info *shm_info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81436bc0)
Location: ipc/shm.c:960
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81436bc0-ffffffff81436d1d: shmctl_shm_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int shmctl_shm_info(struct ipc_namespace *ns, struct shm_info *shm_info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81427630)
Location: ipc/shm.c:960
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81427630-ffffffff8142778d: shmctl_shm_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int shmctl_shm_info(struct ipc_namespace *ns, struct shm_info *shm_info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81432d60)
Location: ipc/shm.c:960
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81432d60-ffffffff81432ebd: shmctl_shm_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int shmctl_shm_info(struct ipc_namespace *ns, struct shm_info *shm_info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81449fd0)
Location: ipc/shm.c:960
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81449fd0-ffffffff8144a12d: shmctl_shm_info (STB_LOCAL)
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
