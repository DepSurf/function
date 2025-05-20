# Function: <code>tcp_fastopen_reset_cipher</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_fastopen_reset_cipher(void *key, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff817826f0)
Location: net/ipv4/tcp_fastopen.c:39
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff817826f0-ffffffff817827f3: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_fastopen_reset_cipher(void *key, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff817efd80)
Location: net/ipv4/tcp_fastopen.c:40
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff817efd80-ffffffff817efe81: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_fastopen_reset_cipher(void *key, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81820790)
Location: net/ipv4/tcp_fastopen.c:40
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81820790-ffffffff81820891: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_fastopen_reset_cipher(void *key, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81840ca0)
Location: net/ipv4/tcp_fastopen.c:40
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81840ca0-ffffffff81840da1: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *key, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff818c04f0)
Location: net/ipv4/tcp_fastopen.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff818c04f0-ffffffff818c0628: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *key, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (0)
Location: net/ipv4/tcp_fastopen.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81916ae6-ffffffff81916b05: tcp_fastopen_reset_cipher.cold.14 (STB_LOCAL)
ffffffff81916040-ffffffff81916162: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *key, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_fastopen.c (0)
Location: net/ipv4/tcp_fastopen.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81945296-ffffffff819452b5: tcp_fastopen_reset_cipher.cold.14 (STB_LOCAL)
ffffffff819447e0-ffffffff81944902: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *primary_key, void *backup_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819a8e70)
Location: net/ipv4/tcp_fastopen.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff819a8e70-ffffffff819a8f4f: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *primary_key, void *backup_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819dfad0)
Location: net/ipv4/tcp_fastopen.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff819dfad0-ffffffff819dfbaf: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *primary_key, void *backup_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81acd3b0)
Location: net/ipv4/tcp_fastopen.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81acd3b0-ffffffff81acd48f: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *primary_key, void *backup_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ad93c0)
Location: net/ipv4/tcp_fastopen.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81ad93c0-ffffffff81ad949f: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *primary_key, void *backup_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ac40b0)
Location: net/ipv4/tcp_fastopen.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81ac40b0-ffffffff81ac418c: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *primary_key, void *backup_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81b82709)
Location: net/ipv4/tcp_fastopen.c:64
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81b827c0-ffffffff81b82869: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *primary_key, void *backup_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81d12c6a)
Location: net/ipv4/tcp_fastopen.c:58
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
Direct callers:
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81d12d60-ffffffff81d12e10: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *primary_key, void *backup_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ed8b7a)
Location: net/ipv4/tcp_fastopen.c:58
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
Direct callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81ed8ca0-ffffffff81ed8d50: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *primary_key, void *backup_key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81f37c8a)
Location: net/ipv4/tcp_fastopen.c:58
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
Direct callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81f37db0-ffffffff81f37e60: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *primary_key, void *backup_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81ffdd90)
Location: net/ipv4/tcp_fastopen.c:58
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81ffdd90-ffffffff81ffde6f: tcp_fastopen_reset_cipher (STB_GLOBAL)
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
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *primary_key, void *backup_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffff800010c93608)
Location: net/ipv4/tcp_fastopen.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffff800010c93608-ffff800010c93734: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *primary_key, void *backup_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (c0da1ee0)
Location: net/ipv4/tcp_fastopen.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
c0da1ee0-c0da1fd8: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *primary_key, void *backup_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (c000000000da39f0)
Location: net/ipv4/tcp_fastopen.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
c000000000da39f0-c000000000da3b68: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *primary_key, void *backup_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffe0007f2bb4)
Location: net/ipv4/tcp_fastopen.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffe0007f2bb4-ffffffe0007f2dd2: tcp_fastopen_reset_cipher (STB_GLOBAL)
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
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *primary_key, void *backup_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff8197f940)
Location: net/ipv4/tcp_fastopen.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff8197f940-ffffffff8197fa1f: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *primary_key, void *backup_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff81939400)
Location: net/ipv4/tcp_fastopen.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff81939400-ffffffff819394df: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *primary_key, void *backup_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819ea110)
Location: net/ipv4/tcp_fastopen.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff819ea110-ffffffff819ea1ef: tcp_fastopen_reset_cipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_fastopen_reset_cipher(struct net *net, struct sock *sk, void *primary_key, void *backup_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_fastopen.c (ffffffff819f3f40)
Location: net/ipv4/tcp_fastopen.c:69
Inline: False
Direct callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_init_key_once
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
```
**Symbols:**

```
ffffffff819f3f40-ffffffff819f401d: tcp_fastopen_reset_cipher (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param added. </b>
<code>struct sock *sk</code>
</li>
<li>
<b>Param reordered. </b>
<code>key, len</code> ➡️ <code>net, sk, key, len</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *primary_key</code>
</li>
<li>
<b>Param added. </b>
<code>void *backup_key</code>
</li>
<li>
<b>Param removed. </b>
<code>void *key</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int len</code>
</li>
</ul>
</details>
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
