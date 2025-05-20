# Function: <code>tcp_sendmsg_locked</code>

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
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a4580)
Location: net/ipv4/tcp.c:1182
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff818a4580-ffffffff818a53e8: tcp_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818fa2f0)
Location: net/ipv4/tcp.c:1175
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff818fa2f0-ffffffff818fb044: tcp_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81928220)
Location: net/ipv4/tcp.c:1174
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff81928220-ffffffff81928f80: tcp_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:1177
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff8198d3a2-ffffffff8198d3c2: tcp_sendmsg_locked.cold (STB_LOCAL)
ffffffff8198b180-ffffffff8198be8a: tcp_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c1a00)
Location: net/ipv4/tcp.c:1178
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff819c1a00-ffffffff819c27d6: tcp_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aad230)
Location: net/ipv4/tcp.c:1185
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff81aad230-ffffffff81aadd90: tcp_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab4600)
Location: net/ipv4/tcp.c:1204
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff81ab4600-ffffffff81ab517e: tcp_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81a9f760)
Location: net/ipv4/tcp.c:1203
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff81a9f760-ffffffff81aa036d: tcp_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:1200
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff81d3a49f-ffffffff81d3a4b8: tcp_sendmsg_locked.cold (STB_LOCAL)
ffffffff81b5b510-ffffffff81b5c182: tcp_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:1213
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff81f06cf1-ffffffff81f06d0b: tcp_sendmsg_locked.cold (STB_LOCAL)
ffffffff81cea690-ffffffff81ceb2f3: tcp_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:1214
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff820ae865-ffffffff820ae8a0: tcp_sendmsg_locked.cold (STB_LOCAL)
ffffffff81eae590-ffffffff81eaf040: tcp_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:1032
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
**Symbols:**

```
ffffffff8212fcf5-ffffffff8212fd38: tcp_sendmsg_locked.cold (STB_LOCAL)
ffffffff81f0c620-ffffffff81f0d36d: tcp_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:1038
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
  - net/xfrm/espintcp.c:espintcp_sendskmsg_locked
```
**Symbols:**

```
ffffffff822119e1-ffffffff82211a24: tcp_sendmsg_locked.cold (STB_LOCAL)
ffffffff81fd0700-ffffffff81fd146a: tcp_sendmsg_locked (STB_GLOBAL)
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
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c74870)
Location: net/ipv4/tcp.c:1178
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffff800010c74870-ffff800010c754c8: tcp_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d82ed0)
Location: net/ipv4/tcp.c:1178
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
c0d82ed0-c0d83c1c: tcp_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d7bb30)
Location: net/ipv4/tcp.c:1178
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
c000000000d7bb30-c000000000d7cb2c: tcp_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d7c94)
Location: net/ipv4/tcp.c:1178
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffe0007d7c94-ffffffe0007d879a: tcp_sendmsg_locked (STB_GLOBAL)
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
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81961870)
Location: net/ipv4/tcp.c:1178
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff81961870-ffffffff81962646: tcp_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8191b360)
Location: net/ipv4/tcp.c:1178
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff8191b360-ffffffff8191c136: tcp_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819cc040)
Location: net/ipv4/tcp.c:1178
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff819cc040-ffffffff819cce16: tcp_sendmsg_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_sendmsg_locked(struct sock *sk, struct msghdr *msg, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d5bd0)
Location: net/ipv4/tcp.c:1178
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_sendmsg
```
**Symbols:**

```
ffffffff819d5bd0-ffffffff819d69a6: tcp_sendmsg_locked (STB_GLOBAL)
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
