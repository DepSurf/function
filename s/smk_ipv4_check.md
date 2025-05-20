# Function: <code>smk_ipv4_check</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int smk_ipv4_check(struct sock *sk, struct sockaddr_in *sap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f3880)
Location: security/smack/smack_lsm.c:2447
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_socket_connect
```
**Symbols:**

```
ffffffff814f3880-ffffffff814f3a0b: smk_ipv4_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int smk_ipv4_check(struct sock *sk, struct sockaddr_in *sap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814fa840)
Location: security/smack/smack_lsm.c:2446
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_socket_connect
```
**Symbols:**

```
ffffffff814fa840-ffffffff814fa9cb: smk_ipv4_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int smk_ipv4_check(struct sock *sk, struct sockaddr_in *sap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815554b0)
Location: security/smack/smack_lsm.c:2446
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_socket_connect
```
**Symbols:**

```
ffffffff815554b0-ffffffff8155563b: smk_ipv4_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int smk_ipv4_check(struct sock *sk, struct sockaddr_in *sap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815ef100)
Location: security/smack/smack_lsm.c:2452
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_socket_connect
```
**Symbols:**

```
ffffffff815ef100-ffffffff815ef2bc: smk_ipv4_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int smk_ipv4_check(struct sock *sk, struct sockaddr_in *sap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8169f3f0)
Location: security/smack/smack_lsm.c:2527
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_socket_connect
```
**Symbols:**

```
ffffffff8169f3f0-ffffffff8169f5ac: smk_ipv4_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int smk_ipv4_check(struct sock *sk, struct sockaddr_in *sap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff816d7ad0)
Location: security/smack/smack_lsm.c:2590
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_socket_connect
```
**Symbols:**

```
ffffffff816d7ad0-ffffffff816d7c8c: smk_ipv4_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int smk_ipv4_check(struct sock *sk, struct sockaddr_in *sap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:2649
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_socket_sendmsg
  - security/smack/smack_lsm.c:smack_socket_connect
```
**Symbols:**

```
ffffffff81714630-ffffffff81714807: smk_ipv4_check (STB_LOCAL)
ffffffff821d0e14-ffffffff821d0e6e: smk_ipv4_check.cold (STB_LOCAL)
```
</details>
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
