# Function: <code>security_msg_queue_associate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_msg_queue_associate(struct msg_queue *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133eb20)
Location: security/security.c:1052
Inline: False
Direct callers:
  - ipc/msg.c:msg_security
```
**Symbols:**

```
ffffffff8133eb20-ffffffff8133eb6f: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_msg_queue_associate(struct msg_queue *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81374140)
Location: security/security.c:1076
Inline: False
Direct callers:
  - ipc/msg.c:msg_security
```
**Symbols:**

```
ffffffff81374140-ffffffff8137418f: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_msg_queue_associate(struct msg_queue *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138aa70)
Location: security/security.c:1097
Inline: False
Direct callers:
  - ipc/msg.c:msg_security
```
**Symbols:**

```
ffffffff8138aa70-ffffffff8138aabf: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_msg_queue_associate(struct msg_queue *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a0110)
Location: security/security.c:1829
Inline: False
Direct callers:
  - ipc/msg.c:msg_security
```
**Symbols:**

```
ffffffff813a0110-ffffffff813a015f: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_msg_queue_associate(struct msg_queue *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c5dd0)
Location: security/security.c:1797
Inline: False
Direct callers:
  - ipc/msg.c:msg_security
```
**Symbols:**

```
ffffffff813c5dd0-ffffffff813c5e25: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5b60)
Location: security/security.c:1201
Inline: False
```
**Symbols:**

```
ffffffff813f5b60-ffffffff813f5ba4: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81411250)
Location: security/security.c:1827
Inline: False
```
**Symbols:**

```
ffffffff81411250-ffffffff81411294: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143eaa0)
Location: security/security.c:1846
Inline: False
```
**Symbols:**

```
ffffffff8143eaa0-ffffffff8143eaed: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81458490)
Location: security/security.c:1885
Inline: False
```
**Symbols:**

```
ffffffff81458490-ffffffff814584d4: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ab380)
Location: security/security.c:2087
Inline: False
```
**Symbols:**

```
ffffffff814ab380-ffffffff814ab3c4: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8980)
Location: security/security.c:2104
Inline: False
```
**Symbols:**

```
ffffffff814c8980-ffffffff814c89c4: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cefc0)
Location: security/security.c:2167
Inline: False
```
**Symbols:**

```
ffffffff814cefc0-ffffffff814cf004: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527c80)
Location: security/security.c:2175
Inline: False
```
**Symbols:**

```
ffffffff81527c80-ffffffff81527cc4: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bcc40)
Location: security/security.c:2186
Inline: False
```
**Symbols:**

```
ffffffff815bcc40-ffffffff815bcc9d: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81668f00)
Location: security/security.c:2262
Inline: False
```
**Symbols:**

```
ffffffff81668f00-ffffffff81668f5d: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a1500)
Location: security/security.c:3755
Inline: False
```
**Symbols:**

```
ffffffff816a1500-ffffffff816a155d: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816ddd80)
Location: security/security.c:3784
Inline: False
```
**Symbols:**

```
ffffffff816ddd80-ffffffff816ddddd: security_msg_queue_associate (STB_GLOBAL)
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
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010544308)
Location: security/security.c:1885
Inline: False
```
**Symbols:**

```
ffff800010544308-ffff800010544368: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fa214)
Location: security/security.c:1885
Inline: False
```
**Symbols:**

```
c06fa214-c06fa270: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000698ea0)
Location: security/security.c:1885
Inline: False
```
**Symbols:**

```
c000000000698ea0-c000000000698f5c: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a0506)
Location: security/security.c:1885
Inline: False
```
**Symbols:**

```
ffffffe0003a0506-ffffffe0003a054a: security_msg_queue_associate (STB_GLOBAL)
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
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450a70)
Location: security/security.c:1885
Inline: False
```
**Symbols:**

```
ffffffff81450a70-ffffffff81450ab4: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814414c0)
Location: security/security.c:1885
Inline: False
```
**Symbols:**

```
ffffffff814414c0-ffffffff81441504: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144cb10)
Location: security/security.c:1885
Inline: False
```
**Symbols:**

```
ffffffff8144cb10-ffffffff8144cb54: security_msg_queue_associate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_msg_queue_associate(struct kern_ipc_perm *msq, int msqflg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463ee0)
Location: security/security.c:1885
Inline: False
```
**Symbols:**

```
ffffffff81463ee0-ffffffff81463f24: security_msg_queue_associate (STB_GLOBAL)
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
