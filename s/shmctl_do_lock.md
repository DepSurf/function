# Function: <code>shmctl_do_lock</code>

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
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813ae330)
Location: ipc/shm.c:969
Inline: False
Direct callers:
  - ipc/shm.c:C_SYSC_shmctl
  - ipc/shm.c:SYSC_shmctl
```
**Symbols:**

```
ffffffff813ae330-ffffffff813ae543: shmctl_do_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813de890)
Location: ipc/shm.c:1035
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
ffffffff813de890-ffffffff813deab6: shmctl_do_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813f8f90)
Location: ipc/shm.c:1064
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
ffffffff813f8f90-ffffffff813f91b6: shmctl_do_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81425510)
Location: ipc/shm.c:1064
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81425510-ffffffff81425738: shmctl_do_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8143f260)
Location: ipc/shm.c:1064
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8143f260-ffffffff8143f488: shmctl_do_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8148fdd0)
Location: ipc/shm.c:1064
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8148fdd0-ffffffff8148fff8: shmctl_do_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814ad4e0)
Location: ipc/shm.c:1063
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814ad4e0-ffffffff814ad712: shmctl_do_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814b3360)
Location: ipc/shm.c:1063
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814b3360-ffffffff814b3592: shmctl_do_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:1159
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8150b9d0-ffffffff8150bc10: shmctl_do_lock (STB_LOCAL)
ffffffff81cd2c84-ffffffff81cd2c99: shmctl_do_lock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:1153
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8159d000-ffffffff8159d240: shmctl_do_lock (STB_LOCAL)
ffffffff81e85dd3-ffffffff81e85de8: shmctl_do_lock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:1169
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff816464f0-ffffffff81646730: shmctl_do_lock (STB_LOCAL)
ffffffff82072f4b-ffffffff82072f60: shmctl_do_lock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:1169
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8167ea00-ffffffff8167ec49: shmctl_do_lock (STB_LOCAL)
ffffffff820f2b93-ffffffff820f2ba8: shmctl_do_lock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:1165
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff816badf0-ffffffff816bb039: shmctl_do_lock (STB_LOCAL)
ffffffff821cfe2b-ffffffff821cfe40: shmctl_do_lock.cold (STB_LOCAL)
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
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffff800010527660)
Location: ipc/shm.c:1064
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffff800010527660-ffff8000105278b4: shmctl_do_lock (STB_LOCAL)
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
In ipc/shm.c (c06e0e98)
Location: ipc/shm.c:1064
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
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c000000000672030)
Location: ipc/shm.c:1064
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
  - ipc/shm.c:ksys_shmctl
```
**Symbols:**

```
c000000000672030-c0000000006722dc: shmctl_do_lock (STB_LOCAL)
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
In ipc/shm.c (ffffffe00038b43e)
Location: ipc/shm.c:1064
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
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81437840)
Location: ipc/shm.c:1064
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81437840-ffffffff81437a68: shmctl_do_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814282b0)
Location: ipc/shm.c:1064
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814282b0-ffffffff814284d8: shmctl_do_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814339e0)
Location: ipc/shm.c:1064
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814339e0-ffffffff81433c08: shmctl_do_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shmctl_do_lock(struct ipc_namespace *ns, int shmid, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8144a130)
Location: ipc/shm.c:1064
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8144a130-ffffffff8144a369: shmctl_do_lock (STB_LOCAL)
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
