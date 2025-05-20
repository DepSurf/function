# Function: <code>msgctl_down</code>

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
In ipc/msg.c (ffffffff81325bd0)
Location: ipc/msg.c:339
Inline: True
Direct callers:
  - ipc/msg.c:SyS_msgctl
```
**Symbols:**

```
ffffffff81325bd0-ffffffff81325dc6: msgctl_down.constprop.4 (STB_LOCAL)
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
In ipc/msg.c (ffffffff8135a7f0)
Location: ipc/msg.c:339
Inline: True
Direct callers:
  - ipc/msg.c:SyS_msgctl
```
**Symbols:**

```
ffffffff8135a7f0-ffffffff8135a9eb: msgctl_down.constprop.6 (STB_LOCAL)
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
In ipc/msg.c (ffffffff81370dd0)
Location: ipc/msg.c:363
Inline: True
Direct callers:
  - ipc/msg.c:SyS_msgctl
```
**Symbols:**

```
ffffffff81370dd0-ffffffff81370fe2: msgctl_down.constprop.8 (STB_LOCAL)
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
In ipc/msg.c (ffffffff81384160)
Location: ipc/msg.c:363
Inline: True
Direct callers:
  - ipc/msg.c:SyS_msgctl
```
**Symbols:**

```
ffffffff81384160-ffffffff81384376: msgctl_down.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *msqid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813a8560)
Location: ipc/msg.c:364
Inline: False
Direct callers:
  - ipc/msg.c:C_SYSC_msgctl
  - ipc/msg.c:SYSC_msgctl
```
**Symbols:**

```
ffffffff813a8560-ffffffff813a8713: msgctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *msqid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813d84f0)
Location: ipc/msg.c:378
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:ksys_msgctl
```
**Symbols:**

```
ffffffff813d84f0-ffffffff813d86e1: msgctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *msqid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813f3160)
Location: ipc/msg.c:379
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:ksys_msgctl
```
**Symbols:**

```
ffffffff813f3160-ffffffff813f3351: msgctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *msqid64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8141ee70)
Location: ipc/msg.c:379
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff8141ee70-ffffffff8141f038: msgctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct ipc64_perm *perm, int msg_qbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81438cc0)
Location: ipc/msg.c:379
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81438cc0-ffffffff81438e80: msgctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct ipc64_perm *perm, int msg_qbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81488db0)
Location: ipc/msg.c:398
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81488db0-ffffffff81488f3e: msgctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct ipc64_perm *perm, int msg_qbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814a63e0)
Location: ipc/msg.c:398
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff814a63e0-ffffffff814a655e: msgctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct ipc64_perm *perm, int msg_qbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814ac370)
Location: ipc/msg.c:400
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff814ac370-ffffffff814ac4ee: msgctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct ipc64_perm *perm, int msg_qbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81504850)
Location: ipc/msg.c:400
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81504850-ffffffff815049ce: msgctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct ipc64_perm *perm, int msg_qbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff815957e0)
Location: ipc/msg.c:400
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff815957e0-ffffffff81595979: msgctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct ipc64_perm *perm, int msg_qbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8163e7b0)
Location: ipc/msg.c:401
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff8163e7b0-ffffffff8163e949: msgctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct ipc64_perm *perm, int msg_qbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81676ca0)
Location: ipc/msg.c:401
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81676ca0-ffffffff81676e39: msgctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct ipc64_perm *perm, int msg_qbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff816b3060)
Location: ipc/msg.c:401
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff816b3060-ffffffff816b31f9: msgctl_down (STB_LOCAL)
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
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct ipc64_perm *perm, int msg_qbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffff8000105200d8)
Location: ipc/msg.c:379
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffff8000105200d8-ffff800010520304: msgctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct ipc64_perm *perm, int msg_qbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c06daf18)
Location: ipc/msg.c:379
Inline: False
Direct callers:
  - ipc/msg.c:ksys_msgctl
  - ipc/msg.c:ksys_msgctl
```
**Symbols:**

```
c06daf18-c06db0d0: msgctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct ipc64_perm *perm, int msg_qbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c000000000669320)
Location: ipc/msg.c:379
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:ksys_msgctl
  - ipc/msg.c:ksys_msgctl
```
**Symbols:**

```
c000000000669320-c0000000006695b8: msgctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct ipc64_perm *perm, int msg_qbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffe00038640c)
Location: ipc/msg.c:379
Inline: False
```
**Symbols:**

```
ffffffe00038640c-ffffffe0003865ce: msgctl_down (STB_LOCAL)
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
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct ipc64_perm *perm, int msg_qbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814312a0)
Location: ipc/msg.c:379
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff814312a0-ffffffff81431460: msgctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct ipc64_perm *perm, int msg_qbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81421d20)
Location: ipc/msg.c:379
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81421d20-ffffffff81421ee0: msgctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct ipc64_perm *perm, int msg_qbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8142d440)
Location: ipc/msg.c:379
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff8142d440-ffffffff8142d600: msgctl_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int msgctl_down(struct ipc_namespace *ns, int msqid, int cmd, struct ipc64_perm *perm, int msg_qbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81443e70)
Location: ipc/msg.c:379
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81443e70-ffffffff81444030: msgctl_down (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ipc64_perm *perm</code>
</li>
<li>
<b>Param added. </b>
<code>int msg_qbytes</code>
</li>
<li>
<b>Param removed. </b>
<code>struct msqid64_ds *msqid64</code>
</li>
</ul>
</details>
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
