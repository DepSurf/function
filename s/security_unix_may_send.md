# Function: <code>security_unix_may_send</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133b8a0)
Location: security/security.c:1200
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff8133b8a0-ffffffff8133b8ef: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81370e60)
Location: security/security.c:1230
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff81370e60-ffffffff81370eaf: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81387790)
Location: security/security.c:1251
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff81387790-ffffffff813877df: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8139c430)
Location: security/security.c:2181
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff8139c430-ffffffff8139c47f: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c1b90)
Location: security/security.c:2039
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff813c1b90-ffffffff813c1be5: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f3130)
Location: security/security.c:1355
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff813f3130-ffffffff813f3174: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140e500)
Location: security/security.c:2106
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff8140e500-ffffffff8140e544: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143b0a0)
Location: security/security.c:2125
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff8143b0a0-ffffffff8143b0ed: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81454e50)
Location: security/security.c:2164
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff81454e50-ffffffff81454e94: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a7710)
Location: security/security.c:2468
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff814a7710-ffffffff814a7754: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c4c90)
Location: security/security.c:2485
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff814c4c90-ffffffff814c4cd4: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cb180)
Location: security/security.c:2548
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff814cb180-ffffffff814cb1c4: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81523e80)
Location: security/security.c:2556
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff81523e80-ffffffff81523ec4: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b7cd0)
Location: security/security.c:2586
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff815b7cd0-ffffffff815b7d2d: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81663100)
Location: security/security.c:2566
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff81663100-ffffffff8166315d: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169b600)
Location: security/security.c:4356
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff8169b600-ffffffff8169b65d: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d8210)
Location: security/security.c:4517
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff816d8210-ffffffff816d826d: security_unix_may_send (STB_GLOBAL)
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
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010540118)
Location: security/security.c:2164
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffff800010540118-ffff800010540178: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f61b4)
Location: security/security.c:2164
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
c06f61b4-c06f6210: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006917e0)
Location: security/security.c:2164
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
c0000000006917e0-c00000000069189c: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039d354)
Location: security/security.c:2164
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffe00039d354-ffffffe00039d398: security_unix_may_send (STB_GLOBAL)
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
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144d430)
Location: security/security.c:2164
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff8144d430-ffffffff8144d474: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143de80)
Location: security/security.c:2164
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff8143de80-ffffffff8143dec4: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814494d0)
Location: security/security.c:2164
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff814494d0-ffffffff81449514: security_unix_may_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_unix_may_send(struct socket *sock, struct socket *other);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814608a0)
Location: security/security.c:2164
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_dgram_connect
```
**Symbols:**

```
ffffffff814608a0-ffffffff814608e4: security_unix_may_send (STB_GLOBAL)
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
