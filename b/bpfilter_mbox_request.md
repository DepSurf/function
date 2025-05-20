# Function: <code>bpfilter_mbox_request</code>

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
int bpfilter_mbox_request(struct sock *sk, int optname, char *optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff8193cad0)
Location: net/ipv4/bpfilter/sockopt.c:13
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
ffffffff8193cad0-ffffffff8193cb48: bpfilter_mbox_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpfilter_mbox_request(struct sock *sk, int optname, char *optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff8196c860)
Location: net/ipv4/bpfilter/sockopt.c:25
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
ffffffff8196c860-ffffffff8196c93b: bpfilter_mbox_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpfilter_mbox_request(struct sock *sk, int optname, char *optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff819d6000)
Location: net/ipv4/bpfilter/sockopt.c:25
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
ffffffff819d6000-ffffffff819d60d1: bpfilter_mbox_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpfilter_mbox_request(struct sock *sk, int optname, char *optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81a0caf0)
Location: net/ipv4/bpfilter/sockopt.c:25
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
ffffffff81a0caf0-ffffffff81a0cbc1: bpfilter_mbox_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpfilter_mbox_request(struct sock *sk, int optname, char *optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81afd8a0)
Location: net/ipv4/bpfilter/sockopt.c:25
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
ffffffff81afd8a0-ffffffff81afd971: bpfilter_mbox_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpfilter_mbox_request(struct sock *sk, int optname, sockptr_t optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81b0b8f0)
Location: net/ipv4/bpfilter/sockopt.c:24
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
ffffffff81b0b8f0-ffffffff81b0ba21: bpfilter_mbox_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpfilter_mbox_request(struct sock *sk, int optname, sockptr_t optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81af9550)
Location: net/ipv4/bpfilter/sockopt.c:24
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
ffffffff81af9550-ffffffff81af9681: bpfilter_mbox_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpfilter_mbox_request(struct sock *sk, int optname, sockptr_t optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81bba0a0)
Location: net/ipv4/bpfilter/sockopt.c:24
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
ffffffff81bba0a0-ffffffff81bba1d1: bpfilter_mbox_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpfilter_mbox_request(struct sock *sk, int optname, sockptr_t optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81d4e090)
Location: net/ipv4/bpfilter/sockopt.c:24
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
ffffffff81d4e090-ffffffff81d4e1d1: bpfilter_mbox_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpfilter_mbox_request(struct sock *sk, int optname, sockptr_t optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81f179f0)
Location: net/ipv4/bpfilter/sockopt.c:24
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
ffffffff81f179f0-ffffffff81f17b31: bpfilter_mbox_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpfilter_mbox_request(struct sock *sk, int optname, sockptr_t optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81f77680)
Location: net/ipv4/bpfilter/sockopt.c:15
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
ffffffff81f77680-ffffffff81f77794: bpfilter_mbox_request (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int bpfilter_mbox_request(struct sock *sk, int optname, char *optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffff800010cc61a0)
Location: net/ipv4/bpfilter/sockopt.c:25
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
ffff800010cc61a0-ffff800010cc6280: bpfilter_mbox_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpfilter_mbox_request(struct sock *sk, int optname, char *optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (c0dd1980)
Location: net/ipv4/bpfilter/sockopt.c:25
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
c0dd1980-c0dd1a54: bpfilter_mbox_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpfilter_mbox_request(struct sock *sk, int optname, char *optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (c000000000de2c60)
Location: net/ipv4/bpfilter/sockopt.c:25
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
c000000000de2c60-c000000000de2db4: bpfilter_mbox_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpfilter_mbox_request(struct sock *sk, int optname, char *optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffe00081abee)
Location: net/ipv4/bpfilter/sockopt.c:25
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
ffffffe00081abee-ffffffe00081acc0: bpfilter_mbox_request (STB_LOCAL)
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
int bpfilter_mbox_request(struct sock *sk, int optname, char *optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff819ac890)
Location: net/ipv4/bpfilter/sockopt.c:25
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
ffffffff819ac890-ffffffff819ac961: bpfilter_mbox_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpfilter_mbox_request(struct sock *sk, int optname, char *optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81966350)
Location: net/ipv4/bpfilter/sockopt.c:25
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
ffffffff81966350-ffffffff81966421: bpfilter_mbox_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpfilter_mbox_request(struct sock *sk, int optname, char *optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81a17130)
Location: net/ipv4/bpfilter/sockopt.c:25
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
ffffffff81a17130-ffffffff81a17201: bpfilter_mbox_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpfilter_mbox_request(struct sock *sk, int optname, char *optval, unsigned int optlen, bool is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/bpfilter/sockopt.c (ffffffff81a21b60)
Location: net/ipv4/bpfilter/sockopt.c:25
Inline: False
Direct callers:
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_get_sockopt
  - net/ipv4/bpfilter/sockopt.c:bpfilter_ip_set_sockopt
```
**Symbols:**

```
ffffffff81a21b60-ffffffff81a21c31: bpfilter_mbox_request (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *optval</code> ➡️ <code>sockptr_t optval</code>
</li>
</ul>
</details>
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
