# Function: <code>security_shm_shmat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_shm_shmat(struct shmid_kernel *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133edd0)
Location: security/security.c:1094
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff8133edd0-ffffffff8133ee2b: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_shm_shmat(struct shmid_kernel *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813743f0)
Location: security/security.c:1118
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff813743f0-ffffffff8137444b: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_shm_shmat(struct shmid_kernel *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138ad20)
Location: security/security.c:1139
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff8138ad20-ffffffff8138ad7b: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_shm_shmat(struct shmid_kernel *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a03f0)
Location: security/security.c:1879
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff813a03f0-ffffffff813a044b: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_shm_shmat(struct shmid_kernel *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c6140)
Location: security/security.c:1850
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff813c6140-ffffffff813c61a1: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5de0)
Location: security/security.c:1243
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff813f5de0-ffffffff813f5e2e: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81411530)
Location: security/security.c:1878
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81411530-ffffffff8141157e: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143eda0)
Location: security/security.c:1897
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff8143eda0-ffffffff8143edf7: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81458770)
Location: security/security.c:1936
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81458770-ffffffff814587bc: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ab680)
Location: security/security.c:2138
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff814ab680-ffffffff814ab6cc: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8c80)
Location: security/security.c:2155
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff814c8c80-ffffffff814c8ccc: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cf2c0)
Location: security/security.c:2218
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff814cf2c0-ffffffff814cf30c: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527f80)
Location: security/security.c:2226
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81527f80-ffffffff81527fcc: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bcff0)
Location: security/security.c:2237
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff815bcff0-ffffffff815bd05b: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81669330)
Location: security/security.c:2313
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81669330-ffffffff8166939b: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a1930)
Location: security/security.c:3891
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff816a1930-ffffffff816a199b: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816de1b0)
Location: security/security.c:3920
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff816de1b0-ffffffff816de21b: security_shm_shmat (STB_GLOBAL)
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
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010544660)
Location: security/security.c:1936
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffff800010544660-ffff8000105446c4: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fa550)
Location: security/security.c:1936
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
c06fa550-c06fa5b4: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000699500)
Location: security/security.c:1936
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
c000000000699500-c0000000006995d0: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a0784)
Location: security/security.c:1936
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffe0003a0784-ffffffe0003a07d0: security_shm_shmat (STB_GLOBAL)
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
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450d50)
Location: security/security.c:1936
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff81450d50-ffffffff81450d9c: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814417a0)
Location: security/security.c:1936
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff814417a0-ffffffff814417ec: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144cdf0)
Location: security/security.c:1936
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff8144cdf0-ffffffff8144ce3c: security_shm_shmat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_shm_shmat(struct kern_ipc_perm *shp, char *shmaddr, int shmflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814641c0)
Location: security/security.c:1936
Inline: False
Direct callers:
  - ipc/shm.c:do_shmat
```
**Symbols:**

```
ffffffff814641c0-ffffffff8146420c: security_shm_shmat (STB_GLOBAL)
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
