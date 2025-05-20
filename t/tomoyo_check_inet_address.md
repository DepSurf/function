# Function: <code>tomoyo_check_inet_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff81371d80)
Location: security/tomoyo/network.c:500
Inline: True
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
```
**Symbols:**

```
ffffffff81371d80-ffffffff81371eb4: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff813a81b0)
Location: security/tomoyo/network.c:500
Inline: True
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff813a81b0-ffffffff813a82e9: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff813bed40)
Location: security/tomoyo/network.c:500
Inline: True
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff813bed40-ffffffff813bee79: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff813d5630)
Location: security/tomoyo/network.c:500
Inline: True
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff813d5630-ffffffff813d5766: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff813fbb40)
Location: security/tomoyo/network.c:501
Inline: True
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff813fbb40-ffffffff813fbc76: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff8142ca80)
Location: security/tomoyo/network.c:501
Inline: True
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff8142ca80-ffffffff8142cbb3: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff814493d0)
Location: security/tomoyo/network.c:501
Inline: True
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff814493d0-ffffffff81449503: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff81477030)
Location: security/tomoyo/network.c:501
Inline: True
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff81477030-ffffffff81477170: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff81490dd0)
Location: security/tomoyo/network.c:501
Inline: True
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff81490dd0-ffffffff81490f10: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff814e8260)
Location: security/tomoyo/network.c:501
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff814e8260-ffffffff814e82d2: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff815055e0)
Location: security/tomoyo/network.c:501
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff815055e0-ffffffff81505652: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff8150c060)
Location: security/tomoyo/network.c:501
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff8150c060-ffffffff8150c19c: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (0)
Location: security/tomoyo/network.c:501
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff81569830-ffffffff815699c5: tomoyo_check_inet_address (STB_LOCAL)
ffffffff81cd6124-ffffffff81cd6139: tomoyo_check_inet_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (0)
Location: security/tomoyo/network.c:501
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff81605660-ffffffff8160580a: tomoyo_check_inet_address (STB_LOCAL)
ffffffff81e88f09-ffffffff81e88f1e: tomoyo_check_inet_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (0)
Location: security/tomoyo/network.c:501
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff816b6a40-ffffffff816b6bea: tomoyo_check_inet_address (STB_LOCAL)
ffffffff820749be-ffffffff820749d3: tomoyo_check_inet_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (0)
Location: security/tomoyo/network.c:501
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff816ef410-ffffffff816ef5cf: tomoyo_check_inet_address (STB_LOCAL)
ffffffff820f4515-ffffffff820f452a: tomoyo_check_inet_address.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (0)
Location: security/tomoyo/network.c:501
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff8172c1e0-ffffffff8172c39f: tomoyo_check_inet_address (STB_LOCAL)
ffffffff821d195a-ffffffff821d196f: tomoyo_check_inet_address.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffff800010585218)
Location: security/tomoyo/network.c:501
Inline: True
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffff800010585218-ffff8000105853c0: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (c0736bec)
Location: security/tomoyo/network.c:501
Inline: True
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
c0736bec-c0736dac: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (c0000000006f4830)
Location: security/tomoyo/network.c:501
Inline: True
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
c0000000006f4830-c0000000006f4a54: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffe0003d4f34)
Location: security/tomoyo/network.c:501
Inline: True
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffe0003d4f34-ffffffe0003d5086: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff814893b0)
Location: security/tomoyo/network.c:501
Inline: True
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff814893b0-ffffffff814894f0: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff81479dd0)
Location: security/tomoyo/network.c:501
Inline: True
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff81479dd0-ffffffff81479f10: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff81485450)
Location: security/tomoyo/network.c:501
Inline: True
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff81485450-ffffffff81485590: tomoyo_check_inet_address (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int tomoyo_check_inet_address(const struct sockaddr *addr, const unsigned int addr_len, const u16 port, struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff8149cf90)
Location: security/tomoyo/network.c:501
Inline: True
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff8149cf90-ffffffff8149d0d0: tomoyo_check_inet_address (STB_LOCAL)
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
