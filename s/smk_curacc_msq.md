# Function: <code>smk_curacc_msq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int smk_curacc_msq(struct msg_queue *msq, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8135ec00)
Location: security/smack/smack_lsm.c:3223
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
```
**Symbols:**

```
ffffffff8135ec00-ffffffff8135ec80: smk_curacc_msq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smk_curacc_msq(struct msg_queue *msq, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81395100)
Location: security/smack/smack_lsm.c:3242
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
```
**Symbols:**

```
ffffffff81395100-ffffffff81395180: smk_curacc_msq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smk_curacc_msq(struct msg_queue *msq, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813ab890)
Location: security/smack/smack_lsm.c:3241
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
```
**Symbols:**

```
ffffffff813ab890-ffffffff813ab910: smk_curacc_msq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int smk_curacc_msq(struct msg_queue *msq, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813c38c0)
Location: security/smack/smack_lsm.c:3087
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
```
**Symbols:**

```
ffffffff813c38c0-ffffffff813c394b: smk_curacc_msq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smk_curacc_msq(struct msg_queue *msq, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813e9b80)
Location: security/smack/smack_lsm.c:3056
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
```
**Symbols:**

```
ffffffff813e9b80-ffffffff813e9c0b: smk_curacc_msq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int smk_curacc_msq(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8141abe0)
Location: security/smack/smack_lsm.c:3211
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
```
**Symbols:**

```
ffffffff8141abe0-ffffffff8141ac60: smk_curacc_msq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int smk_curacc_msq(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814372b0)
Location: security/smack/smack_lsm.c:3029
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
```
**Symbols:**

```
ffffffff814372b0-ffffffff8143733b: smk_curacc_msq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int smk_curacc_msq(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81464a70)
Location: security/smack/smack_lsm.c:3121
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
```
**Symbols:**

```
ffffffff81464a70-ffffffff81464af7: smk_curacc_msq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int smk_curacc_msq(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8147eb90)
Location: security/smack/smack_lsm.c:3116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
```
**Symbols:**

```
ffffffff8147eb90-ffffffff8147ec17: smk_curacc_msq (STB_LOCAL)
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
In security/smack/smack_lsm.c (ffffffff814d4195)
Location: security/smack/smack_lsm.c:3097
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
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
In security/smack/smack_lsm.c (ffffffff814f1665)
Location: security/smack/smack_lsm.c:3112
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
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
In security/smack/smack_lsm.c (ffffffff814f8285)
Location: security/smack/smack_lsm.c:3111
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
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
In security/smack/smack_lsm.c (ffffffff81552e75)
Location: security/smack/smack_lsm.c:3111
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
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
In security/smack/smack_lsm.c (ffffffff815ecb18)
Location: security/smack/smack_lsm.c:3118
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
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
In security/smack/smack_lsm.c (ffffffff8169c908)
Location: security/smack/smack_lsm.c:3193
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
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
In security/smack/smack_lsm.c (ffffffff816d5628)
Location: security/smack/smack_lsm.c:3256
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
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
In security/smack/smack_lsm.c (ffffffff81712048)
Location: security/smack/smack_lsm.c:3315
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
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
int smk_curacc_msq(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffff80001056fc00)
Location: security/smack/smack_lsm.c:3116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
```
**Symbols:**

```
ffff80001056fc00-ffff80001056fc9c: smk_curacc_msq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smk_curacc_msq(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0723314)
Location: security/smack/smack_lsm.c:3116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
```
**Symbols:**

```
c0723314-c07233b8: smk_curacc_msq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smk_curacc_msq(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0000000006d6440)
Location: security/smack/smack_lsm.c:3116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
```
**Symbols:**

```
c0000000006d6440-c0000000006d64ec: smk_curacc_msq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smk_curacc_msq(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffe0003c2e58)
Location: security/smack/smack_lsm.c:3116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
```
**Symbols:**

```
ffffffe0003c2e58-ffffffe0003c2eca: smk_curacc_msq (STB_LOCAL)
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
int smk_curacc_msq(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81477170)
Location: security/smack/smack_lsm.c:3116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
```
**Symbols:**

```
ffffffff81477170-ffffffff814771f7: smk_curacc_msq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int smk_curacc_msq(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81467b90)
Location: security/smack/smack_lsm.c:3116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
```
**Symbols:**

```
ffffffff81467b90-ffffffff81467c17: smk_curacc_msq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int smk_curacc_msq(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81473210)
Location: security/smack/smack_lsm.c:3116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
```
**Symbols:**

```
ffffffff81473210-ffffffff81473297: smk_curacc_msq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int smk_curacc_msq(struct kern_ipc_perm *isp, int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8148ab00)
Location: security/smack/smack_lsm.c:3116
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_msg_queue_msgrcv
  - security/smack/smack_lsm.c:smack_msg_queue_msgsnd
  - security/smack/smack_lsm.c:smack_msg_queue_msgctl
  - security/smack/smack_lsm.c:smack_msg_queue_associate
```
**Symbols:**

```
ffffffff8148ab00-ffffffff8148ab87: smk_curacc_msq (STB_LOCAL)
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
<code>struct msg_queue *msq</code>
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
