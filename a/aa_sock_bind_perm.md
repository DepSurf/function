# Function: <code>aa_sock_bind_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_sock_bind_perm(struct socket *sock, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81390e90)
Location: security/apparmor/net.c:265
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff81390e90-ffffffff81390f9d: aa_sock_bind_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_sock_bind_perm(struct socket *sock, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813cc480)
Location: security/apparmor/net.c:265
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff813cc480-ffffffff813cc58d: aa_sock_bind_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_sock_bind_perm(struct socket *sock, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813e3b00)
Location: security/apparmor/net.c:265
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff813e3b00-ffffffff813e3c0d: aa_sock_bind_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_sock_bind_perm(struct socket *sock, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813f1cc0)
Location: security/apparmor/net.c:264
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff813f1cc0-ffffffff813f1cf1: aa_sock_bind_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_sock_bind_perm(struct socket *sock, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81419d40)
Location: security/apparmor/net.c:264
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_bind
```
**Symbols:**

```
ffffffff81419d40-ffffffff81419d71: aa_sock_bind_perm (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
