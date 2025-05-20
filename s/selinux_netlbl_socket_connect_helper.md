# Function: <code>selinux_netlbl_socket_connect_helper</code>

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
int selinux_netlbl_socket_connect_helper(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81417870)
Location: security/selinux/netlabel.c:559
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff81417870-ffffffff814178d9: selinux_netlbl_socket_connect_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int selinux_netlbl_socket_connect_helper(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81433da0)
Location: security/selinux/netlabel.c:560
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff81433da0-ffffffff81433e0f: selinux_netlbl_socket_connect_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int selinux_netlbl_socket_connect_helper(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81461850)
Location: security/selinux/netlabel.c:542
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff81461850-ffffffff814618bc: selinux_netlbl_socket_connect_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int selinux_netlbl_socket_connect_helper(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff8147b600)
Location: security/selinux/netlabel.c:542
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff8147b600-ffffffff8147b66c: selinux_netlbl_socket_connect_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814d1762)
Location: security/selinux/netlabel.c:542
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814eec72)
Location: security/selinux/netlabel.c:542
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814f59ca)
Location: security/selinux/netlabel.c:542
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff815503ca)
Location: security/selinux/netlabel.c:542
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff815e9856)
Location: security/selinux/netlabel.c:545
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff816991a6)
Location: security/selinux/netlabel.c:545
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff816d1656)
Location: security/selinux/netlabel.c:544
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff8170dc86)
Location: security/selinux/netlabel.c:545
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect_locked
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
int selinux_netlbl_socket_connect_helper(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffff80001056c028)
Location: security/selinux/netlabel.c:542
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffff80001056c028-ffff80001056c0c0: selinux_netlbl_socket_connect_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int selinux_netlbl_socket_connect_helper(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (c071f89c)
Location: security/selinux/netlabel.c:542
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
c071f89c-c071f918: selinux_netlbl_socket_connect_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int selinux_netlbl_socket_connect_helper(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (c0000000006d0060)
Location: security/selinux/netlabel.c:542
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
c0000000006d0060-c0000000006d016c: selinux_netlbl_socket_connect_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int selinux_netlbl_socket_connect_helper(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffe0003c0bb4)
Location: security/selinux/netlabel.c:542
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffe0003c0bb4-ffffffe0003c0c36: selinux_netlbl_socket_connect_helper (STB_LOCAL)
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
int selinux_netlbl_socket_connect_helper(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81473be0)
Location: security/selinux/netlabel.c:542
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff81473be0-ffffffff81473c4c: selinux_netlbl_socket_connect_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int selinux_netlbl_socket_connect_helper(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81464600)
Location: security/selinux/netlabel.c:542
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff81464600-ffffffff8146466c: selinux_netlbl_socket_connect_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int selinux_netlbl_socket_connect_helper(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff8146fc80)
Location: security/selinux/netlabel.c:542
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff8146fc80-ffffffff8146fcec: selinux_netlbl_socket_connect_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int selinux_netlbl_socket_connect_helper(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814874f0)
Location: security/selinux/netlabel.c:542
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff814874f0-ffffffff8148755c: selinux_netlbl_socket_connect_helper (STB_LOCAL)
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
