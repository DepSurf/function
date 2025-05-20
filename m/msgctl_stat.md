# Function: <code>msgctl_stat</code>

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
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813a8230)
Location: ipc/msg.c:476
Inline: False
Direct callers:
  - ipc/msg.c:C_SYSC_msgctl
  - ipc/msg.c:SYSC_msgctl
```
**Symbols:**

```
ffffffff813a8230-ffffffff813a834a: msgctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813d7dd0)
Location: ipc/msg.c:490
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:ksys_msgctl
```
**Symbols:**

```
ffffffff813d7dd0-ffffffff813d7f45: msgctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff813f23e0)
Location: ipc/msg.c:491
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:ksys_msgctl
```
**Symbols:**

```
ffffffff813f23e0-ffffffff813f2568: msgctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8141ecc0)
Location: ipc/msg.c:491
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff8141ecc0-ffffffff8141ee6a: msgctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81438b10)
Location: ipc/msg.c:491
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81438b10-ffffffff81438cba: msgctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814885e0)
Location: ipc/msg.c:510
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff814885e0-ffffffff81488770: msgctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814a5c10)
Location: ipc/msg.c:510
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff814a5c10-ffffffff814a5d9b: msgctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814abbe0)
Location: ipc/msg.c:512
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff814abbe0-ffffffff814abd6b: msgctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/msg.c (0)
Location: ipc/msg.c:512
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff815040a0-ffffffff8150423d: msgctl_stat (STB_LOCAL)
ffffffff81cd2992-ffffffff81cd29a7: msgctl_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/msg.c (0)
Location: ipc/msg.c:512
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81595980-ffffffff81595b31: msgctl_stat (STB_LOCAL)
ffffffff81e85ae8-ffffffff81e85afd: msgctl_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/msg.c (0)
Location: ipc/msg.c:518
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff8163e1e0-ffffffff8163e391: msgctl_stat (STB_LOCAL)
ffffffff82072cf6-ffffffff82072d0b: msgctl_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/msg.c (0)
Location: ipc/msg.c:518
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff816766d0-ffffffff81676881: msgctl_stat (STB_LOCAL)
ffffffff820f294d-ffffffff820f2962: msgctl_stat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/msg.c (0)
Location: ipc/msg.c:518
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff816b2a90-ffffffff816b2c41: msgctl_stat (STB_LOCAL)
ffffffff821cfbfd-ffffffff821cfc12: msgctl_stat.cold (STB_LOCAL)
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
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffff80001051f668)
Location: ipc/msg.c:491
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffff80001051f668-ffff80001051f83c: msgctl_stat (STB_LOCAL)
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
In ipc/msg.c (c06dbe5c)
Location: ipc/msg.c:491
Inline: True
Inline callers:
  - ipc/msg.c:ksys_msgctl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c0000000006690b0)
Location: ipc/msg.c:491
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
  - ipc/msg.c:ksys_msgctl
```
**Symbols:**

```
c0000000006690b0-c000000000669314: msgctl_stat (STB_LOCAL)
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
In ipc/msg.c (ffffffe000386632)
Location: ipc/msg.c:491
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
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814310f0)
Location: ipc/msg.c:491
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff814310f0-ffffffff8143129a: msgctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff81421b70)
Location: ipc/msg.c:491
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff81421b70-ffffffff81421d1a: msgctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff8142d290)
Location: ipc/msg.c:491
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff8142d290-ffffffff8142d43a: msgctl_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int msgctl_stat(struct ipc_namespace *ns, int msqid, int cmd, struct msqid64_ds *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (ffffffff814435e0)
Location: ipc/msg.c:491
Inline: False
Direct callers:
  - ipc/msg.c:compat_ksys_msgctl
```
**Symbols:**

```
ffffffff814435e0-ffffffff8144378d: msgctl_stat (STB_LOCAL)
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
