# Function: <code>security_msg_queue_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_msg_queue_free(struct msg_queue *msq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133eae0)
Location: security/security.c:1047
Inline: False
Direct callers:
  - ipc/msg.c:msg_rcu_free
```
**Symbols:**

```
ffffffff8133eae0-ffffffff8133eb16: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_msg_queue_free(struct msg_queue *msq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81374100)
Location: security/security.c:1071
Inline: False
Direct callers:
  - ipc/msg.c:msg_rcu_free
```
**Symbols:**

```
ffffffff81374100-ffffffff81374136: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_msg_queue_free(struct msg_queue *msq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138aa30)
Location: security/security.c:1092
Inline: False
Direct callers:
  - ipc/msg.c:msg_rcu_free
```
**Symbols:**

```
ffffffff8138aa30-ffffffff8138aa66: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_msg_queue_free(struct msg_queue *msq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a00c0)
Location: security/security.c:1820
Inline: False
Direct callers:
  - ipc/msg.c:msg_rcu_free
```
**Symbols:**

```
ffffffff813a00c0-ffffffff813a0109: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_msg_queue_free(struct msg_queue *msq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c5ce0)
Location: security/security.c:1788
Inline: False
Direct callers:
  - ipc/msg.c:msg_rcu_free
  - security/security.c:security_msg_queue_alloc
```
**Symbols:**

```
ffffffff813c5ce0-ffffffff813c5d2f: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5b20)
Location: security/security.c:1196
Inline: False
Direct callers:
  - ipc/msg.c:msg_rcu_free
```
**Symbols:**

```
ffffffff813f5b20-ffffffff813f5b54: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81411170)
Location: security/security.c:1820
Inline: False
Direct callers:
  - ipc/msg.c:msg_rcu_free
  - security/security.c:security_msg_queue_alloc
```
**Symbols:**

```
ffffffff81411170-ffffffff814111b7: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e9c0)
Location: security/security.c:1839
Inline: False
Direct callers:
  - ipc/msg.c:msg_rcu_free
  - security/security.c:security_msg_queue_alloc
```
**Symbols:**

```
ffffffff8143e9c0-ffffffff8143ea09: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814583b0)
Location: security/security.c:1878
Inline: False
Direct callers:
  - ipc/msg.c:msg_rcu_free
  - security/security.c:security_msg_queue_alloc
```
**Symbols:**

```
ffffffff814583b0-ffffffff814583f7: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ab2ef)
Location: security/security.c:2080
Inline: True
Inline callers:
  - security/security.c:security_msg_queue_alloc
Direct callers:
  - ipc/msg.c:msg_rcu_free
```
**Symbols:**

```
ffffffff814ab330-ffffffff814ab377: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c88ef)
Location: security/security.c:2097
Inline: True
Inline callers:
  - security/security.c:security_msg_queue_alloc
Direct callers:
  - ipc/msg.c:msg_rcu_free
```
**Symbols:**

```
ffffffff814c8930-ffffffff814c8977: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cef2f)
Location: security/security.c:2160
Inline: True
Inline callers:
  - security/security.c:security_msg_queue_alloc
Direct callers:
  - ipc/msg.c:msg_rcu_free
```
**Symbols:**

```
ffffffff814cef70-ffffffff814cefb7: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527bef)
Location: security/security.c:2168
Inline: True
Inline callers:
  - security/security.c:security_msg_queue_alloc
Direct callers:
  - ipc/msg.c:msg_rcu_free
```
**Symbols:**

```
ffffffff81527c30-ffffffff81527c77: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bcb73)
Location: security/security.c:2179
Inline: True
Inline callers:
  - security/security.c:security_msg_queue_alloc
Direct callers:
  - ipc/msg.c:msg_rcu_free
```
**Symbols:**

```
ffffffff815bcbf0-ffffffff815bcc3f: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81668e13)
Location: security/security.c:2255
Inline: True
Inline callers:
  - security/security.c:security_msg_queue_alloc
Direct callers:
  - ipc/msg.c:msg_rcu_free
```
**Symbols:**

```
ffffffff81668ea0-ffffffff81668eef: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a1413)
Location: security/security.c:3737
Inline: True
Inline callers:
  - security/security.c:security_msg_queue_alloc
Direct callers:
  - ipc/msg.c:msg_rcu_free
```
**Symbols:**

```
ffffffff816a14a0-ffffffff816a14ef: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816ddc93)
Location: security/security.c:3766
Inline: True
Inline callers:
  - security/security.c:security_msg_queue_alloc
Direct callers:
  - ipc/msg.c:msg_rcu_free
```
**Symbols:**

```
ffffffff816ddd20-ffffffff816ddd6f: security_msg_queue_free (STB_GLOBAL)
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
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010544218)
Location: security/security.c:1878
Inline: False
Direct callers:
  - ipc/msg.c:msg_rcu_free
  - security/security.c:security_msg_queue_alloc
```
**Symbols:**

```
ffff800010544218-ffff80001054426c: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fa128)
Location: security/security.c:1878
Inline: False
Direct callers:
  - ipc/msg.c:msg_rcu_free
  - security/security.c:security_msg_queue_alloc
```
**Symbols:**

```
c06fa128-c06fa180: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000698d10)
Location: security/security.c:1878
Inline: False
Direct callers:
  - ipc/msg.c:msg_rcu_free
  - security/security.c:security_msg_queue_alloc
```
**Symbols:**

```
c000000000698d10-c000000000698d9c: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a0440)
Location: security/security.c:1878
Inline: False
Direct callers:
  - ipc/msg.c:msg_rcu_free
  - security/security.c:security_msg_queue_alloc
```
**Symbols:**

```
ffffffe0003a0440-ffffffe0003a0488: security_msg_queue_free (STB_GLOBAL)
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
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450990)
Location: security/security.c:1878
Inline: False
Direct callers:
  - ipc/msg.c:msg_rcu_free
  - security/security.c:security_msg_queue_alloc
```
**Symbols:**

```
ffffffff81450990-ffffffff814509d7: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814413e0)
Location: security/security.c:1878
Inline: False
Direct callers:
  - ipc/msg.c:msg_rcu_free
  - security/security.c:security_msg_queue_alloc
```
**Symbols:**

```
ffffffff814413e0-ffffffff81441427: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144ca30)
Location: security/security.c:1878
Inline: False
Direct callers:
  - ipc/msg.c:msg_rcu_free
  - security/security.c:security_msg_queue_alloc
```
**Symbols:**

```
ffffffff8144ca30-ffffffff8144ca77: security_msg_queue_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_msg_queue_free(struct kern_ipc_perm *msq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463e00)
Location: security/security.c:1878
Inline: False
Direct callers:
  - ipc/msg.c:msg_rcu_free
  - security/security.c:security_msg_queue_alloc
```
**Symbols:**

```
ffffffff81463e00-ffffffff81463e47: security_msg_queue_free (STB_GLOBAL)
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
