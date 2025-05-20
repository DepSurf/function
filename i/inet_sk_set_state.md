# Function: <code>inet_sk_set_state</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8192a740)
Location: net/ipv4/af_inet.c:1278
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
ffffffff8192a740-ffffffff8192a7bc: inet_sk_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81959ed0)
Location: net/ipv4/af_inet.c:1278
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
ffffffff81959ed0-ffffffff81959f4c: inet_sk_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819bee20)
Location: net/ipv4/af_inet.c:1284
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
ffffffff819bee20-ffffffff819bee9d: inet_sk_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819f5a60)
Location: net/ipv4/af_inet.c:1284
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
ffffffff819f5a60-ffffffff819f5add: inet_sk_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ae3e50)
Location: net/ipv4/af_inet.c:1316
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
ffffffff81ae3e50-ffffffff81ae3ecc: inet_sk_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81af0d80)
Location: net/ipv4/af_inet.c:1314
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
ffffffff81af0d80-ffffffff81af0dda: inet_sk_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81adc540)
Location: net/ipv4/af_inet.c:1318
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
ffffffff81adc540-ffffffff81adc59a: inet_sk_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81b9b780)
Location: net/ipv4/af_inet.c:1320
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
ffffffff81b9b780-ffffffff81b9b7d7: inet_sk_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81d2d5e0)
Location: net/ipv4/af_inet.c:1315
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
ffffffff81d2d5e0-ffffffff81d2d653: inet_sk_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ef54a0)
Location: net/ipv4/af_inet.c:1335
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
ffffffff81ef54a0-ffffffff81ef5513: inet_sk_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81f55080)
Location: net/ipv4/af_inet.c:1334
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
ffffffff81f55080-ffffffff81f550f3: inet_sk_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8201b2f0)
Location: net/ipv4/af_inet.c:1354
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
ffffffff8201b2f0-ffffffff8201b363: inet_sk_set_state (STB_GLOBAL)
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
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffff800010cac220)
Location: net/ipv4/af_inet.c:1284
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
ffff800010cac220-ffff800010cac2e4: inet_sk_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c0db837c)
Location: net/ipv4/af_inet.c:1284
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
c0db837c-c0db8430: inet_sk_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c000000000dc1f90)
Location: net/ipv4/af_inet.c:1284
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
c000000000dc1f90-c000000000dc2084: inet_sk_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffe0008061f4)
Location: net/ipv4/af_inet.c:1284
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
ffffffe0008061f4-ffffffe000806290: inet_sk_set_state (STB_GLOBAL)
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
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81995800)
Location: net/ipv4/af_inet.c:1284
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
ffffffff81995800-ffffffff8199587d: inet_sk_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8194f2c0)
Location: net/ipv4/af_inet.c:1284
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
ffffffff8194f2c0-ffffffff8194f33d: inet_sk_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81a000a0)
Location: net/ipv4/af_inet.c:1284
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
ffffffff81a000a0-ffffffff81a0011d: inet_sk_set_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inet_sk_set_state(struct sock *sk, int state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81a0a0e0)
Location: net/ipv4/af_inet.c:1284
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_csk_listen_start
  - net/ipv4/inet_connection_sock.c:inet_csk_clone_lock
```
**Symbols:**

```
ffffffff81a0a0e0-ffffffff81a0a167: inet_sk_set_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
