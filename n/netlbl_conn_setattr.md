# Function: <code>netlbl_conn_setattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff8180be00)
Location: net/netlabel/netlabel_kapi.c:875
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff8180be00-ffffffff8180be77: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff8187dce0)
Location: net/netlabel/netlabel_kapi.c:1109
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff8187dce0-ffffffff8187dd87: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff818b2590)
Location: net/netlabel/netlabel_kapi.c:1109
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff818b2590-ffffffff818b2637: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff818d8f40)
Location: net/netlabel/netlabel_kapi.c:1109
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff818d8f40-ffffffff818d8fe7: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff8195eb30)
Location: net/netlabel/netlabel_kapi.c:1109
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff8195eb30-ffffffff8195ebd7: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff819b8310)
Location: net/netlabel/netlabel_kapi.c:1109
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
ffffffff819b8310-ffffffff819b83b7: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff819ef5e0)
Location: net/netlabel/netlabel_kapi.c:1110
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
ffffffff819ef5e0-ffffffff819ef687: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81a5e830)
Location: net/netlabel/netlabel_kapi.c:1096
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
ffffffff81a5e830-ffffffff81a5e8dd: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81a95460)
Location: net/netlabel/netlabel_kapi.c:1096
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
ffffffff81a95460-ffffffff81a9550d: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81b90a30)
Location: net/netlabel/netlabel_kapi.c:1102
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
ffffffff81b90a30-ffffffff81b90afe: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81ba0680)
Location: net/netlabel/netlabel_kapi.c:1102
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
ffffffff81ba0680-ffffffff81ba0781: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81b8f760)
Location: net/netlabel/netlabel_kapi.c:1102
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
ffffffff81b8f760-ffffffff81b8f85e: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81c5bf00)
Location: net/netlabel/netlabel_kapi.c:1102
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
ffffffff81c5bf00-ffffffff81c5bffe: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81dfdc60)
Location: net/netlabel/netlabel_kapi.c:1104
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
ffffffff81dfdc60-ffffffff81dfdd6d: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81fd27f0)
Location: net/netlabel/netlabel_kapi.c:1104
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
ffffffff81fd27f0-ffffffff81fd28fd: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff8204e430)
Location: net/netlabel/netlabel_kapi.c:1105
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
ffffffff8204e430-ffffffff8204e53d: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff82120ab0)
Location: net/netlabel/netlabel_kapi.c:1105
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
ffffffff82120ab0-ffffffff82120bbd: netlbl_conn_setattr (STB_GLOBAL)
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
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffff800010d64070)
Location: net/netlabel/netlabel_kapi.c:1096
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
ffff800010d64070-ffff800010d64164: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (c0e62d0c)
Location: net/netlabel/netlabel_kapi.c:1096
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
c0e62d0c-c0e62dd0: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (c000000000e9f8a0)
Location: net/netlabel/netlabel_kapi.c:1096
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
c000000000e9f8a0-c000000000e9f9ec: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffe000898164)
Location: net/netlabel/netlabel_kapi.c:1096
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
ffffffe000898164-ffffffe000898236: netlbl_conn_setattr (STB_GLOBAL)
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
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81a347f0)
Location: net/netlabel/netlabel_kapi.c:1096
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
ffffffff81a347f0-ffffffff81a3489d: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff819f1410)
Location: net/netlabel/netlabel_kapi.c:1096
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
ffffffff819f1410-ffffffff819f14bd: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81aa06a0)
Location: net/netlabel/netlabel_kapi.c:1096
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
ffffffff81aa06a0-ffffffff81aa074d: netlbl_conn_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int netlbl_conn_setattr(struct sock *sk, struct sockaddr *addr, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81aac8b0)
Location: net/netlabel/netlabel_kapi.c:1096
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_helper
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
```
**Symbols:**

```
ffffffff81aac8b0-ffffffff81aac99c: netlbl_conn_setattr (STB_GLOBAL)
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
