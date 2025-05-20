# Function: <code>security_shm_shmctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_shm_shmctl(struct shmid_kernel *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133ed80)
Location: security/security.c:1089
Inline: False
Direct callers:
  - ipc/shm.c:SyS_shmctl
```
**Symbols:**

```
ffffffff8133ed80-ffffffff8133edcf: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_shm_shmctl(struct shmid_kernel *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813743a0)
Location: security/security.c:1113
Inline: False
Direct callers:
  - ipc/shm.c:SyS_shmctl
```
**Symbols:**

```
ffffffff813743a0-ffffffff813743ef: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_shm_shmctl(struct shmid_kernel *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138acd0)
Location: security/security.c:1134
Inline: False
Direct callers:
  - ipc/shm.c:SyS_shmctl
```
**Symbols:**

```
ffffffff8138acd0-ffffffff8138ad1f: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_shm_shmctl(struct shmid_kernel *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a03a0)
Location: security/security.c:1874
Inline: False
Direct callers:
  - ipc/shm.c:SyS_shmctl
```
**Symbols:**

```
ffffffff813a03a0-ffffffff813a03ef: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_shm_shmctl(struct shmid_kernel *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c60e0)
Location: security/security.c:1845
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff813c60e0-ffffffff813c6135: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5d90)
Location: security/security.c:1238
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff813f5d90-ffffffff813f5dd4: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814114e0)
Location: security/security.c:1873
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff814114e0-ffffffff81411524: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ed50)
Location: security/security.c:1892
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff8143ed50-ffffffff8143ed9d: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81458720)
Location: security/security.c:1931
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff81458720-ffffffff81458764: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ab630)
Location: security/security.c:2133
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff814ab630-ffffffff814ab674: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8c30)
Location: security/security.c:2150
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff814c8c30-ffffffff814c8c74: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cf270)
Location: security/security.c:2213
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff814cf270-ffffffff814cf2b4: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527f30)
Location: security/security.c:2221
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff81527f30-ffffffff81527f74: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bcf90)
Location: security/security.c:2232
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_shm_info
  - ipc/shm.c:shmctl_ipc_info
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff815bcf90-ffffffff815bcfed: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816692c0)
Location: security/security.c:2308
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_shm_info
  - ipc/shm.c:shmctl_ipc_info
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff816692c0-ffffffff8166931d: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a18c0)
Location: security/security.c:3874
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_shm_info
  - ipc/shm.c:shmctl_ipc_info
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff816a18c0-ffffffff816a191d: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816de140)
Location: security/security.c:3903
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_shm_info
  - ipc/shm.c:shmctl_ipc_info
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff816de140-ffffffff816de19d: security_shm_shmctl (STB_GLOBAL)
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
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010544600)
Location: security/security.c:1931
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffff800010544600-ffff800010544660: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fa4f4)
Location: security/security.c:1931
Inline: False
Direct callers:
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
c06fa4f4-c06fa550: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000699440)
Location: security/security.c:1931
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
c000000000699440-c0000000006994fc: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a0740)
Location: security/security.c:1931
Inline: False
```
**Symbols:**

```
ffffffe0003a0740-ffffffe0003a0784: security_shm_shmctl (STB_GLOBAL)
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
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450d00)
Location: security/security.c:1931
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff81450d00-ffffffff81450d44: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81441750)
Location: security/security.c:1931
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff81441750-ffffffff81441794: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144cda0)
Location: security/security.c:1931
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff8144cda0-ffffffff8144cde4: security_shm_shmctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81464170)
Location: security/security.c:1931
Inline: False
Direct callers:
  - ipc/shm.c:shmctl_do_lock
  - ipc/shm.c:shmctl_stat
  - ipc/shm.c:shmctl_down
```
**Symbols:**

```
ffffffff81464170-ffffffff814641b4: security_shm_shmctl (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>struct shmid_kernel *shp</code> ➡️ <code>struct kern_ipc_perm *shp</code>
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
