# Function: <code>sk_msg_trim</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818e6ee0)
Location: net/core/skmsg.c:242
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff818e6ee0-ffffffff818e6fe6: sk_msg_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skmsg.c (0)
Location: net/core/skmsg.c:251
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81937058-ffffffff8193706b: sk_msg_trim.cold (STB_LOCAL)
ffffffff81936880-ffffffff81936988: sk_msg_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81969850)
Location: net/core/skmsg.c:250
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81969850-ffffffff819699c4: sk_msg_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3d190)
Location: net/core/skmsg.c:251
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81a3d190-ffffffff81a3d304: sk_msg_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3f430)
Location: net/core/skmsg.c:253
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81a3f430-ffffffff81a3f5a4: sk_msg_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a4dd00)
Location: net/core/skmsg.c:253
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81a4dd00-ffffffff81a4df70: sk_msg_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81b065f0)
Location: net/core/skmsg.c:253
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81b065f0-ffffffff81b069ad: sk_msg_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81c8c300)
Location: net/core/skmsg.c:262
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81c8c300-ffffffff81c8c607: sk_msg_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81e46570)
Location: net/core/skmsg.c:262
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81e46570-ffffffff81e46883: sk_msg_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81ea1fc0)
Location: net/core/skmsg.c:263
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81ea1fc0-ffffffff81ea22d3: sk_msg_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81f645b0)
Location: net/core/skmsg.c:263
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_msg_alloc
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81f645b0-ffffffff81f648c3: sk_msg_trim (STB_GLOBAL)
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
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffff800010c0ee30)
Location: net/core/skmsg.c:250
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffff800010c0ee30-ffff800010c0efd8: sk_msg_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (c0d27870)
Location: net/core/skmsg.c:250
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
c0d27870-c0d27a00: sk_msg_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (c000000000cfbaa0)
Location: net/core/skmsg.c:250
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
c000000000cfbaa0-c000000000cfbd30: sk_msg_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffe00078be6c)
Location: net/core/skmsg.c:250
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffe00078be6c-ffffffe00078bfe6: sk_msg_trim (STB_GLOBAL)
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
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81909820)
Location: net/core/skmsg.c:250
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81909820-ffffffff81909994: sk_msg_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818c3630)
Location: net/core/skmsg.c:250
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff818c3630-ffffffff818c37a4: sk_msg_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff8195a850)
Location: net/core/skmsg.c:250
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff8195a850-ffffffff8195a9c4: sk_msg_trim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sk_msg_trim(struct sock *sk, struct sk_msg *msg, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff8197ca70)
Location: net/core/skmsg.c:250
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff8197ca70-ffffffff8197cbe4: sk_msg_trim (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
