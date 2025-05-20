# Function: <code>security_msg_queue_msgrcv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct msg_queue *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133ec20)
Location: security/security.c:1068
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
  - ipc/msg.c:do_msgrcv
```
**Symbols:**

```
ffffffff8133ec20-ffffffff8133ec9b: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct msg_queue *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81374240)
Location: security/security.c:1092
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff81374240-ffffffff813742bb: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct msg_queue *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138ab70)
Location: security/security.c:1113
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff8138ab70-ffffffff8138abeb: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct msg_queue *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a0210)
Location: security/security.c:1845
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff813a0210-ffffffff813a028b: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct msg_queue *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c5f00)
Location: security/security.c:1813
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff813c5f00-ffffffff813c5f81: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5c50)
Location: security/security.c:1217
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff813f5c50-ffffffff813f5cb8: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81411340)
Location: security/security.c:1843
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff81411340-ffffffff814113a8: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143eba0)
Location: security/security.c:1862
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff8143eba0-ffffffff8143ec19: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81458580)
Location: security/security.c:1901
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff81458580-ffffffff814585e8: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ab470)
Location: security/security.c:2103
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff814ab470-ffffffff814ab4d8: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8a70)
Location: security/security.c:2120
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff814c8a70-ffffffff814c8ad8: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cf0b0)
Location: security/security.c:2183
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff814cf0b0-ffffffff814cf118: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527d70)
Location: security/security.c:2191
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff81527d70-ffffffff81527dd8: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bcd70)
Location: security/security.c:2202
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff815bcd70-ffffffff815bce07: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81669060)
Location: security/security.c:2278
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff81669060-ffffffff816690f7: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a1660)
Location: security/security.c:3807
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff816a1660-ffffffff816a16f7: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816ddee0)
Location: security/security.c:3836
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff816ddee0-ffffffff816ddf77: security_msg_queue_msgrcv (STB_GLOBAL)
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
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010544430)
Location: security/security.c:1901
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffff800010544430-ffff8000105444b0: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fa330)
Location: security/security.c:1901
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
c06fa330-c06fa3ac: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006990f0)
Location: security/security.c:1901
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
c0000000006990f0-c0000000006991e8: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a05da)
Location: security/security.c:1901
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffe0003a05da-ffffffe0003a0636: security_msg_queue_msgrcv (STB_GLOBAL)
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
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450b60)
Location: security/security.c:1901
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff81450b60-ffffffff81450bc8: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814415b0)
Location: security/security.c:1901
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff814415b0-ffffffff81441618: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144cc00)
Location: security/security.c:1901
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff8144cc00-ffffffff8144cc68: security_msg_queue_msgrcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_msg_queue_msgrcv(struct kern_ipc_perm *msq, struct msg_msg *msg, struct task_struct *target, long int type, int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463fd0)
Location: security/security.c:1901
Inline: False
Direct callers:
  - ipc/msg.c:do_msgrcv
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff81463fd0-ffffffff81464038: security_msg_queue_msgrcv (STB_GLOBAL)
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
<code>struct msg_queue *msq</code> ➡️ <code>struct kern_ipc_perm *msq</code>
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
