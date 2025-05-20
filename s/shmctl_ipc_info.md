# Function: <code>shmctl_ipc_info</code>

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
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813ae790)
Location: ipc/shm.c:881
Inline: True
Direct callers:
  - ipc/shm.c:C_SYSC_shmctl
  - ipc/shm.c:SYSC_shmctl
```
**Symbols:**

```
ffffffff813ae790-ffffffff813ae864: shmctl_ipc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813dda20)
Location: ipc/shm.c:921
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
ffffffff813dda20-ffffffff813ddaeb: shmctl_ipc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813f80a0)
Location: ipc/shm.c:941
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
ffffffff813f80a0-ffffffff813f816b: shmctl_ipc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81424590)
Location: ipc/shm.c:941
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81424590-ffffffff8142466f: shmctl_ipc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8143e2e0)
Location: ipc/shm.c:941
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8143e2e0-ffffffff8143e3bf: shmctl_ipc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8148eee0)
Location: ipc/shm.c:941
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8148eee0-ffffffff8148efa0: shmctl_ipc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814ac5b0)
Location: ipc/shm.c:940
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814ac5b0-ffffffff814ac670: shmctl_ipc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814b2450)
Location: ipc/shm.c:940
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814b2450-ffffffff814b2509: shmctl_ipc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8150a9f0)
Location: ipc/shm.c:1036
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8150a9f0-ffffffff8150aaa9: shmctl_ipc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8159c840)
Location: ipc/shm.c:1030
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8159c840-ffffffff8159c8fc: shmctl_ipc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81645cd0)
Location: ipc/shm.c:1046
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81645cd0-ffffffff81645d8c: shmctl_ipc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8167e1e0)
Location: ipc/shm.c:1046
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8167e1e0-ffffffff8167e29c: shmctl_ipc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff816ba5d0)
Location: ipc/shm.c:1042
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff816ba5d0-ffffffff816ba68c: shmctl_ipc_info (STB_LOCAL)
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
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffff8000105267d8)
Location: ipc/shm.c:941
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffff8000105267d8-ffff800010526898: shmctl_ipc_info (STB_LOCAL)
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
In ipc/shm.c (c06e0f24)
Location: ipc/shm.c:941
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
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c000000000670cd0)
Location: ipc/shm.c:941
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
c000000000670cd0-c000000000670de8: shmctl_ipc_info (STB_LOCAL)
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
In ipc/shm.c (ffffffe00038b4c4)
Location: ipc/shm.c:941
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
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814368c0)
Location: ipc/shm.c:941
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814368c0-ffffffff8143699f: shmctl_ipc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81427340)
Location: ipc/shm.c:941
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81427340-ffffffff8142741f: shmctl_ipc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81432a60)
Location: ipc/shm.c:941
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81432a60-ffffffff81432b3f: shmctl_ipc_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int shmctl_ipc_info(struct ipc_namespace *ns, struct shminfo64 *shminfo);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81449ce0)
Location: ipc/shm.c:941
Inline: True
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81449ce0-ffffffff81449dbf: shmctl_ipc_info (STB_LOCAL)
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
