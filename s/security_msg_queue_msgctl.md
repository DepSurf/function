# Function: <code>security_msg_queue_msgctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct msg_queue *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133eb70)
Location: security/security.c:1057
Inline: False
```
**Symbols:**

```
ffffffff8133eb70-ffffffff8133ebbf: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct msg_queue *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81374190)
Location: security/security.c:1081
Inline: False
```
**Symbols:**

```
ffffffff81374190-ffffffff813741df: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct msg_queue *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138aac0)
Location: security/security.c:1102
Inline: False
```
**Symbols:**

```
ffffffff8138aac0-ffffffff8138ab0f: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct msg_queue *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a0160)
Location: security/security.c:1834
Inline: False
```
**Symbols:**

```
ffffffff813a0160-ffffffff813a01af: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct msg_queue *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c5e30)
Location: security/security.c:1802
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffff813c5e30-ffffffff813c5e85: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5bb0)
Location: security/security.c:1206
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffff813f5bb0-ffffffff813f5bf4: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814112a0)
Location: security/security.c:1832
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffff814112a0-ffffffff814112e4: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143eaf0)
Location: security/security.c:1851
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffff8143eaf0-ffffffff8143eb3d: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814584e0)
Location: security/security.c:1890
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffff814584e0-ffffffff81458524: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ab3d0)
Location: security/security.c:2092
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffff814ab3d0-ffffffff814ab414: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c89d0)
Location: security/security.c:2109
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffff814c89d0-ffffffff814c8a14: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cf010)
Location: security/security.c:2172
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffff814cf010-ffffffff814cf054: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527cd0)
Location: security/security.c:2180
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffff81527cd0-ffffffff81527d14: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bcca0)
Location: security/security.c:2191
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffff815bcca0-ffffffff815bccfd: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81668f70)
Location: security/security.c:2267
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffff81668f70-ffffffff81668fcd: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a1570)
Location: security/security.c:3770
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffff816a1570-ffffffff816a15cd: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dddf0)
Location: security/security.c:3799
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffff816dddf0-ffffffff816dde4d: security_msg_queue_msgctl (STB_GLOBAL)
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
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010544368)
Location: security/security.c:1890
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffff800010544368-ffff8000105443c8: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fa270)
Location: security/security.c:1890
Inline: False
Direct callers:
  - ipc/msg.c:ksys_msgctl
  - ipc/msg.c:ksys_msgctl
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
c06fa270-c06fa2cc: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000698f60)
Location: security/security.c:1890
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
c000000000698f60-c00000000069901c: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a054a)
Location: security/security.c:1890
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffe0003a054a-ffffffe0003a058e: security_msg_queue_msgctl (STB_GLOBAL)
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
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450ac0)
Location: security/security.c:1890
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffff81450ac0-ffffffff81450b04: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81441510)
Location: security/security.c:1890
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffff81441510-ffffffff81441554: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144cb60)
Location: security/security.c:1890
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffff8144cb60-ffffffff8144cba4: security_msg_queue_msgctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_msg_queue_msgctl(struct kern_ipc_perm *msq, int cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463f30)
Location: security/security.c:1890
Inline: False
Direct callers:
  - ipc/msg.c:msgctl_stat
  - ipc/msg.c:msgctl_down
```
**Symbols:**

```
ffffffff81463f30-ffffffff81463f74: security_msg_queue_msgctl (STB_GLOBAL)
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
