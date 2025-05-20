# Function: <code>copy_compat_shmid_to_user</code>

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
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813ae550)
Location: ipc/shm.c:1174
Inline: False
Direct callers:
  - ipc/shm.c:C_SYSC_shmctl
```
**Symbols:**

```
ffffffff813ae550-ffffffff813ae66d: copy_compat_shmid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813dd900)
Location: ipc/shm.c:1246
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff813dd900-ffffffff813dda19: copy_compat_shmid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813f7f80)
Location: ipc/shm.c:1275
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff813f7f80-ffffffff813f8099: copy_compat_shmid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81424470)
Location: ipc/shm.c:1288
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81424470-ffffffff81424589: copy_compat_shmid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8143e1c0)
Location: ipc/shm.c:1288
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8143e1c0-ffffffff8143e2d9: copy_compat_shmid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8148edd0)
Location: ipc/shm.c:1288
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8148edd0-ffffffff8148eed7: copy_compat_shmid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814ac4a0)
Location: ipc/shm.c:1287
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814ac4a0-ffffffff814ac5a7: copy_compat_shmid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814b2330)
Location: ipc/shm.c:1287
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814b2330-ffffffff814b2449: copy_compat_shmid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8150a8d0)
Location: ipc/shm.c:1383
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8150a8d0-ffffffff8150a9e9: copy_compat_shmid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8159c900)
Location: ipc/shm.c:1377
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8159c900-ffffffff8159ca3a: copy_compat_shmid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81645da0)
Location: ipc/shm.c:1393
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81645da0-ffffffff81645eda: copy_compat_shmid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8167e2b0)
Location: ipc/shm.c:1393
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff8167e2b0-ffffffff8167e3ea: copy_compat_shmid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff816ba6a0)
Location: ipc/shm.c:1389
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff816ba6a0-ffffffff816ba7da: copy_compat_shmid_to_user (STB_LOCAL)
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
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffff800010526a00)
Location: ipc/shm.c:1288
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffff800010526a00-ffff800010526bcc: copy_compat_shmid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c000000000670b40)
Location: ipc/shm.c:1288
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
c000000000670b40-c000000000670cd0: copy_compat_shmid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814367a0)
Location: ipc/shm.c:1288
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff814367a0-ffffffff814368b9: copy_compat_shmid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81427220)
Location: ipc/shm.c:1288
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81427220-ffffffff81427339: copy_compat_shmid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81432940)
Location: ipc/shm.c:1288
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81432940-ffffffff81432a59: copy_compat_shmid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_compat_shmid_to_user(void *buf, struct shmid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81449bc0)
Location: ipc/shm.c:1288
Inline: False
Direct callers:
  - ipc/shm.c:compat_ksys_shmctl
```
**Symbols:**

```
ffffffff81449bc0-ffffffff81449cd9: copy_compat_shmid_to_user (STB_LOCAL)
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
