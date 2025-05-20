# Function: <code>smk_curacc_shm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int smk_curacc_shm(struct shmid_kernel *shp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8135eab0)
Location: security/smack/smack_lsm.c:2963
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
```
**Symbols:**

```
ffffffff8135eab0-ffffffff8135eb30: smk_curacc_shm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smk_curacc_shm(struct shmid_kernel *shp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81394fb0)
Location: security/smack/smack_lsm.c:2982
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
```
**Symbols:**

```
ffffffff81394fb0-ffffffff81395030: smk_curacc_shm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smk_curacc_shm(struct shmid_kernel *shp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813ab740)
Location: security/smack/smack_lsm.c:2981
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
```
**Symbols:**

```
ffffffff813ab740-ffffffff813ab7c0: smk_curacc_shm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int smk_curacc_shm(struct shmid_kernel *shp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813c3750)
Location: security/smack/smack_lsm.c:2875
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
```
**Symbols:**

```
ffffffff813c3750-ffffffff813c37db: smk_curacc_shm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smk_curacc_shm(struct shmid_kernel *shp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813e9a10)
Location: security/smack/smack_lsm.c:2844
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
```
**Symbols:**

```
ffffffff813e9a10-ffffffff813e9a9b: smk_curacc_shm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int smk_curacc_shm(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8141a940)
Location: security/smack/smack_lsm.c:3027
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
```
**Symbols:**

```
ffffffff8141a940-ffffffff8141a9c0: smk_curacc_shm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int smk_curacc_shm(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81436ff0)
Location: security/smack/smack_lsm.c:2845
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
```
**Symbols:**

```
ffffffff81436ff0-ffffffff8143707b: smk_curacc_shm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int smk_curacc_shm(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81464c80)
Location: security/smack/smack_lsm.c:2937
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
```
**Symbols:**

```
ffffffff81464c80-ffffffff81464d07: smk_curacc_shm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int smk_curacc_shm(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8147e840)
Location: security/smack/smack_lsm.c:2932
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
```
**Symbols:**

```
ffffffff8147e840-ffffffff8147e8c7: smk_curacc_shm (STB_LOCAL)
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
In security/smack/smack_lsm.c (ffffffff814d4966)
Location: security/smack/smack_lsm.c:2913
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
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
In security/smack/smack_lsm.c (ffffffff814f20c6)
Location: security/smack/smack_lsm.c:2928
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
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
In security/smack/smack_lsm.c (ffffffff814f8d25)
Location: security/smack/smack_lsm.c:2927
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
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
In security/smack/smack_lsm.c (ffffffff81553a95)
Location: security/smack/smack_lsm.c:2927
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
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
In security/smack/smack_lsm.c (ffffffff815ed70d)
Location: security/smack/smack_lsm.c:2934
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
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
In security/smack/smack_lsm.c (ffffffff8169d6fd)
Location: security/smack/smack_lsm.c:3009
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
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
In security/smack/smack_lsm.c (ffffffff816d64dd)
Location: security/smack/smack_lsm.c:3072
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
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
In security/smack/smack_lsm.c (ffffffff81712f1d)
Location: security/smack/smack_lsm.c:3131
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
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
int smk_curacc_shm(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffff80001056fec0)
Location: security/smack/smack_lsm.c:2932
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
```
**Symbols:**

```
ffff80001056fec0-ffff80001056ff60: smk_curacc_shm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smk_curacc_shm(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c072317c)
Location: security/smack/smack_lsm.c:2932
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
```
**Symbols:**

```
c072317c-c0723220: smk_curacc_shm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smk_curacc_shm(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0000000006d6050)
Location: security/smack/smack_lsm.c:2932
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
```
**Symbols:**

```
c0000000006d6050-c0000000006d60fc: smk_curacc_shm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smk_curacc_shm(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffe0003c2ce4)
Location: security/smack/smack_lsm.c:2932
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
```
**Symbols:**

```
ffffffe0003c2ce4-ffffffe0003c2d56: smk_curacc_shm (STB_LOCAL)
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
int smk_curacc_shm(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81476e20)
Location: security/smack/smack_lsm.c:2932
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
```
**Symbols:**

```
ffffffff81476e20-ffffffff81476ea7: smk_curacc_shm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int smk_curacc_shm(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81467840)
Location: security/smack/smack_lsm.c:2932
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
```
**Symbols:**

```
ffffffff81467840-ffffffff814678c7: smk_curacc_shm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int smk_curacc_shm(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81472ec0)
Location: security/smack/smack_lsm.c:2932
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
```
**Symbols:**

```
ffffffff81472ec0-ffffffff81472f47: smk_curacc_shm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int smk_curacc_shm(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8148a840)
Location: security/smack/smack_lsm.c:2932
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_shm_shmat
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_shmctl
  - security/smack/smack_lsm.c:smack_shm_associate
```
**Symbols:**

```
ffffffff8148a840-ffffffff8148a8c7: smk_curacc_shm (STB_LOCAL)
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
<code>struct shmid_kernel *shp</code>
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
