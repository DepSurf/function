# Function: <code>copy_compat_msqid_to_user</code>

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
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813a8720)
Location: ipc/msg.c:609
Inline: False
Direct callers:
  - ipc/msg.c:C_SYSC_msgctl
```
**Symbols:**

```
ffffffff813a8720-ffffffff813a8846: copy_compat_msqid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813d7670)
Location: ipc/msg.c:647
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff813d7670-ffffffff813d7794: copy_compat_msqid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813f1c80)
Location: ipc/msg.c:657
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff813f1c80-ffffffff813f1da4: copy_compat_msqid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8141df70)
Location: ipc/msg.c:669
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff8141df70-ffffffff8141e094: copy_compat_msqid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81437dc0)
Location: ipc/msg.c:670
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81437dc0-ffffffff81437ee4: copy_compat_msqid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81487d90)
Location: ipc/msg.c:689
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81487d90-ffffffff81487e9c: copy_compat_msqid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814a53b0)
Location: ipc/msg.c:689
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff814a53b0-ffffffff814a54bc: copy_compat_msqid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814ab350)
Location: ipc/msg.c:691
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff814ab350-ffffffff814ab474: copy_compat_msqid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81503810)
Location: ipc/msg.c:691
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81503810-ffffffff81503934: copy_compat_msqid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81595110)
Location: ipc/msg.c:691
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81595110-ffffffff8159525e: copy_compat_msqid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8163de40)
Location: ipc/msg.c:697
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff8163de40-ffffffff8163df8e: copy_compat_msqid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81676330)
Location: ipc/msg.c:697
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81676330-ffffffff8167647e: copy_compat_msqid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff816b26f0)
Location: ipc/msg.c:697
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff816b26f0-ffffffff816b283e: copy_compat_msqid_to_user (STB_LOCAL)
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
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffff800010520308)
Location: ipc/msg.c:670
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffff800010520308-ffff80001052063c: copy_compat_msqid_to_user (STB_LOCAL)
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
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c000000000667e40)
Location: ipc/msg.c:670
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
c000000000667e40-c000000000667fc8: copy_compat_msqid_to_user (STB_LOCAL)
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
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814303a0)
Location: ipc/msg.c:670
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff814303a0-ffffffff814304c4: copy_compat_msqid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81420e20)
Location: ipc/msg.c:670
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81420e20-ffffffff81420f44: copy_compat_msqid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8142c540)
Location: ipc/msg.c:670
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff8142c540-ffffffff8142c664: copy_compat_msqid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_compat_msqid_to_user(void *buf, struct msqid64_ds *in, int version);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81443890)
Location: ipc/msg.c:670
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81443890-ffffffff814439b4: copy_compat_msqid_to_user (STB_LOCAL)
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
