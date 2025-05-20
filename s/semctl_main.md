# Function: <code>semctl_main</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81328f40)
Location: ipc/sem.c:1338
Inline: False
Direct callers:
  - ipc/sem.c:SyS_semctl
```
**Symbols:**

```
ffffffff81328f40-ffffffff813295e0: semctl_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8135db90)
Location: ipc/sem.c:1334
Inline: False
Direct callers:
  - ipc/sem.c:SyS_semctl
```
**Symbols:**

```
ffffffff8135db90-ffffffff8135e26f: semctl_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813742d0)
Location: ipc/sem.c:1327
Inline: False
Direct callers:
  - ipc/sem.c:SyS_semctl
```
**Symbols:**

```
ffffffff813742d0-ffffffff813749f7: semctl_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81387c10)
Location: ipc/sem.c:1338
Inline: False
Direct callers:
  - ipc/sem.c:SyS_semctl
```
**Symbols:**

```
ffffffff81387c10-ffffffff81388493: semctl_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813ac7a0)
Location: ipc/sem.c:1324
Inline: False
Direct callers:
  - ipc/sem.c:C_SYSC_semctl
  - ipc/sem.c:SYSC_semctl
```
**Symbols:**

```
ffffffff813ac7a0-ffffffff813ad011: semctl_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813dac80)
Location: ipc/sem.c:1383
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:ksys_semctl
```
**Symbols:**

```
ffffffff813dac80-ffffffff813db64c: semctl_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813f52f0)
Location: ipc/sem.c:1390
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:ksys_semctl
```
**Symbols:**

```
ffffffff813f52f0-ffffffff813f5cbc: semctl_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81421660)
Location: ipc/sem.c:1386
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81421660-ffffffff81422035: semctl_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8143b450)
Location: ipc/sem.c:1386
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff8143b450-ffffffff8143bdf9: semctl_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8148b9c0)
Location: ipc/sem.c:1402
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff8148b9c0-ffffffff8148c522: semctl_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814a8fe0)
Location: ipc/sem.c:1401
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff814a8fe0-ffffffff814a9b57: semctl_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814aeda0)
Location: ipc/sem.c:1403
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff814aeda0-ffffffff814af913: semctl_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1406
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81507230-ffffffff81507dd5: semctl_main (STB_LOCAL)
ffffffff81cd2ae3-ffffffff81cd2b34: semctl_main.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1405
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81599940-ffffffff8159a4f0: semctl_main (STB_LOCAL)
ffffffff81e85c85-ffffffff81e85cf0: semctl_main.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1405
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81642bd0-ffffffff81643789: semctl_main (STB_LOCAL)
ffffffff82072dfe-ffffffff82072e69: semctl_main.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1405
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff8167b160-ffffffff8167bccf: semctl_main (STB_LOCAL)
ffffffff820f2a52-ffffffff820f2abd: semctl_main.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1405
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff816b7510-ffffffff816b809a: semctl_main (STB_LOCAL)
ffffffff821cfd02-ffffffff821cfd55: semctl_main.cold (STB_LOCAL)
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
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff8000105232a8)
Location: ipc/sem.c:1386
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:__arm64_sys_semctl
```
**Symbols:**

```
ffff8000105232a8-ffff800010523c64: semctl_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c06dda10)
Location: ipc/sem.c:1386
Inline: False
Direct callers:
  - ipc/sem.c:ksys_semctl
```
**Symbols:**

```
c06dda10-c06de394: semctl_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066cd20)
Location: ipc/sem.c:1386
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
  - ipc/sem.c:ksys_semctl
```
**Symbols:**

```
c00000000066cd20-c00000000066da10: semctl_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffe000388320)
Location: ipc/sem.c:1386
Inline: False
Direct callers:
  - ipc/sem.c:__se_sys_semctl
```
**Symbols:**

```
ffffffe000388320-ffffffe000388b10: semctl_main (STB_LOCAL)
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
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81433a30)
Location: ipc/sem.c:1386
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81433a30-ffffffff814343d9: semctl_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814244b0)
Location: ipc/sem.c:1386
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff814244b0-ffffffff81424e59: semctl_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8142fbd0)
Location: ipc/sem.c:1386
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff8142fbd0-ffffffff81430579: semctl_main (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int semctl_main(struct ipc_namespace *ns, int semid, int semnum, int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81447be0)
Location: ipc/sem.c:1386
Inline: False
Direct callers:
  - ipc/sem.c:compat_ksys_semctl
```
**Symbols:**

```
ffffffff81447be0-ffffffff814485a6: semctl_main (STB_LOCAL)
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
