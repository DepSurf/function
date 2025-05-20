# Function: <code>tomoyo_unix_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff81371a10)
Location: security/tomoyo/network.c:541
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
```
**Symbols:**

```
ffffffff81371a10-ffffffff81371b9b: tomoyo_unix_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff813a7e30)
Location: security/tomoyo/network.c:541
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff813a7e30-ffffffff813a7fc4: tomoyo_unix_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff813be9c0)
Location: security/tomoyo/network.c:541
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff813be9c0-ffffffff813beb54: tomoyo_unix_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff813d53a0)
Location: security/tomoyo/network.c:541
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff813d53a0-ffffffff813d554c: tomoyo_unix_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff813fb7a0)
Location: security/tomoyo/network.c:542
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff813fb7a0-ffffffff813fb94c: tomoyo_unix_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff8142c710)
Location: security/tomoyo/network.c:542
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff8142c710-ffffffff8142c8b8: tomoyo_unix_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff81449060)
Location: security/tomoyo/network.c:542
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff81449060-ffffffff81449208: tomoyo_unix_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (0)
Location: security/tomoyo/network.c:544
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff81476e70-ffffffff81477022: tomoyo_unix_entry (STB_LOCAL)
ffffffff8147797f-ffffffff8147798b: tomoyo_unix_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (0)
Location: security/tomoyo/network.c:544
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff81490c10-ffffffff81490dc2: tomoyo_unix_entry (STB_LOCAL)
ffffffff8149171f-ffffffff8149172b: tomoyo_unix_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (0)
Location: security/tomoyo/network.c:544
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff814e7fa0-ffffffff814e8152: tomoyo_unix_entry (STB_LOCAL)
ffffffff814e8aef-ffffffff814e8afb: tomoyo_unix_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (0)
Location: security/tomoyo/network.c:544
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff81505320-ffffffff815054d2: tomoyo_unix_entry (STB_LOCAL)
ffffffff81bf1499-ffffffff81bf14a5: tomoyo_unix_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (0)
Location: security/tomoyo/network.c:544
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff8150bea0-ffffffff8150c052: tomoyo_unix_entry (STB_LOCAL)
ffffffff81be3626-ffffffff81be3632: tomoyo_unix_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (0)
Location: security/tomoyo/network.c:544
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff815699d0-ffffffff81569c21: tomoyo_unix_entry (STB_LOCAL)
ffffffff81cd6139-ffffffff81cd6145: tomoyo_unix_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (0)
Location: security/tomoyo/network.c:544
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff81605810-ffffffff81605a7a: tomoyo_unix_entry (STB_LOCAL)
ffffffff81e88f1e-ffffffff81e88f2a: tomoyo_unix_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff816b6c00)
Location: security/tomoyo/network.c:544
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff816b6c00-ffffffff816b6e54: tomoyo_unix_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff816ef5e0)
Location: security/tomoyo/network.c:544
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff816ef5e0-ffffffff816ef835: tomoyo_unix_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffff8172c3b0)
Location: security/tomoyo/network.c:544
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff8172c3b0-ffffffff8172c605: tomoyo_unix_entry (STB_LOCAL)
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
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffff800010585028)
Location: security/tomoyo/network.c:544
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffff800010585028-ffff800010585214: tomoyo_unix_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (c07369e0)
Location: security/tomoyo/network.c:544
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
c07369e0-c0736bec: tomoyo_unix_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (c0000000006f4570)
Location: security/tomoyo/network.c:544
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
c0000000006f4570-c0000000006f482c: tomoyo_unix_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/network.c (ffffffe0003d4dbc)
Location: security/tomoyo/network.c:544
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffe0003d4dbc-ffffffe0003d4f34: tomoyo_unix_entry (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (0)
Location: security/tomoyo/network.c:544
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff814891f0-ffffffff814893a2: tomoyo_unix_entry (STB_LOCAL)
ffffffff81489cff-ffffffff81489d0b: tomoyo_unix_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (0)
Location: security/tomoyo/network.c:544
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff81479c10-ffffffff81479dc2: tomoyo_unix_entry (STB_LOCAL)
ffffffff8147a71f-ffffffff8147a72b: tomoyo_unix_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (0)
Location: security/tomoyo/network.c:544
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff81485290-ffffffff81485442: tomoyo_unix_entry (STB_LOCAL)
ffffffff81485d9f-ffffffff81485dab: tomoyo_unix_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tomoyo_unix_entry(const struct tomoyo_addr_info *address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/network.c (0)
Location: security/tomoyo/network.c:544
Inline: False
Direct callers:
  - security/tomoyo/network.c:tomoyo_socket_sendmsg_permission
  - security/tomoyo/network.c:tomoyo_socket_bind_permission
  - security/tomoyo/network.c:tomoyo_socket_connect_permission
  - security/tomoyo/network.c:tomoyo_socket_listen_permission
```
**Symbols:**

```
ffffffff8149cdd0-ffffffff8149cf82: tomoyo_unix_entry (STB_LOCAL)
ffffffff8149d8df-ffffffff8149d8eb: tomoyo_unix_entry.cold (STB_LOCAL)
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
