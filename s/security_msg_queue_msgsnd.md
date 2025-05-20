# Function: <code>security_msg_queue_msgsnd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct msg_queue *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133ebc0)
Location: security/security.c:1062
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff8133ebc0-ffffffff8133ec1b: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct msg_queue *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813741e0)
Location: security/security.c:1086
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff813741e0-ffffffff8137423b: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct msg_queue *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138ab10)
Location: security/security.c:1107
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff8138ab10-ffffffff8138ab6b: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct msg_queue *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a01b0)
Location: security/security.c:1839
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff813a01b0-ffffffff813a020b: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct msg_queue *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c5e90)
Location: security/security.c:1807
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff813c5e90-ffffffff813c5ef1: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5c00)
Location: security/security.c:1211
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff813f5c00-ffffffff813f5c4e: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814112f0)
Location: security/security.c:1837
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff814112f0-ffffffff8141133e: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143eb40)
Location: security/security.c:1856
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff8143eb40-ffffffff8143eb97: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81458530)
Location: security/security.c:1895
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff81458530-ffffffff8145857c: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ab420)
Location: security/security.c:2097
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff814ab420-ffffffff814ab46c: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8a20)
Location: security/security.c:2114
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff814c8a20-ffffffff814c8a6c: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cf060)
Location: security/security.c:2177
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff814cf060-ffffffff814cf0ac: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527d20)
Location: security/security.c:2185
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff81527d20-ffffffff81527d6c: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bcd00)
Location: security/security.c:2196
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff815bcd00-ffffffff815bcd6b: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81668fe0)
Location: security/security.c:2272
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff81668fe0-ffffffff8166904b: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a15e0)
Location: security/security.c:3786
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff816a15e0-ffffffff816a164b: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dde60)
Location: security/security.c:3815
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff816dde60-ffffffff816ddecb: security_msg_queue_msgsnd (STB_GLOBAL)
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
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105443c8)
Location: security/security.c:1895
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffff8000105443c8-ffff80001054442c: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fa2cc)
Location: security/security.c:1895
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
c06fa2cc-c06fa330: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000699020)
Location: security/security.c:1895
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
c000000000699020-c0000000006990f0: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a058e)
Location: security/security.c:1895
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffe0003a058e-ffffffe0003a05da: security_msg_queue_msgsnd (STB_GLOBAL)
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
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450b10)
Location: security/security.c:1895
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff81450b10-ffffffff81450b5c: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81441560)
Location: security/security.c:1895
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff81441560-ffffffff814415ac: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144cbb0)
Location: security/security.c:1895
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff8144cbb0-ffffffff8144cbfc: security_msg_queue_msgsnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_msg_queue_msgsnd(struct kern_ipc_perm *msq, struct msg_msg *msg, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463f80)
Location: security/security.c:1895
Inline: False
Direct callers:
  - ipc/msg.c:do_msgsnd
```
**Symbols:**

```
ffffffff81463f80-ffffffff81463fcc: security_msg_queue_msgsnd (STB_GLOBAL)
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
