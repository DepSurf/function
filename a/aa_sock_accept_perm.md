# Function: <code>aa_sock_accept_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int aa_sock_accept_perm(struct socket *sock, struct socket *newsock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81391180)
Location: security/apparmor/net.c:306
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_accept
```
**Symbols:**

```
ffffffff81391180-ffffffff81391281: aa_sock_accept_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int aa_sock_accept_perm(struct socket *sock, struct socket *newsock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813cc770)
Location: security/apparmor/net.c:306
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_accept
```
**Symbols:**

```
ffffffff813cc770-ffffffff813cc871: aa_sock_accept_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int aa_sock_accept_perm(struct socket *sock, struct socket *newsock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813e3df0)
Location: security/apparmor/net.c:306
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_accept
```
**Symbols:**

```
ffffffff813e3df0-ffffffff813e3ef1: aa_sock_accept_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int aa_sock_accept_perm(struct socket *sock, struct socket *newsock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813f1d70)
Location: security/apparmor/net.c:305
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_accept
```
**Symbols:**

```
ffffffff813f1d70-ffffffff813f1d9e: aa_sock_accept_perm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int aa_sock_accept_perm(struct socket *sock, struct socket *newsock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81419df0)
Location: security/apparmor/net.c:305
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_socket_accept
```
**Symbols:**

```
ffffffff81419df0-ffffffff81419e1e: aa_sock_accept_perm (STB_GLOBAL)
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
