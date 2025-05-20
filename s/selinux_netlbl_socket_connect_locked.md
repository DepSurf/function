# Function: <code>selinux_netlbl_socket_connect_locked</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff8141830e)
Location: security/selinux/netlabel.c:599
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff814182c0-ffffffff814182e4: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff8143489e)
Location: security/selinux/netlabel.c:600
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff81434850-ffffffff8143487c: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff8146234f)
Location: security/selinux/netlabel.c:582
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff81462300-ffffffff8146232c: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff8147c0ff)
Location: security/selinux/netlabel.c:582
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff8147c0b0-ffffffff8147c0dc: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814d1720)
Location: security/selinux/netlabel.c:582
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff814d1720-ffffffff814d17bd: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814eec30)
Location: security/selinux/netlabel.c:582
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff814eec30-ffffffff814eeccd: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814f5990)
Location: security/selinux/netlabel.c:582
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff814f5990-ffffffff814f5a1d: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81550390)
Location: security/selinux/netlabel.c:582
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff81550390-ffffffff8155041d: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff815e9810)
Location: security/selinux/netlabel.c:585
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_bind_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff815e9810-ffffffff815e9899: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81699160)
Location: security/selinux/netlabel.c:585
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_bind_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff81699160-ffffffff816991e9: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff816d1610)
Location: security/selinux/netlabel.c:584
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_bind_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff816d1610-ffffffff816d16aa: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff8170dc40)
Location: security/selinux/netlabel.c:585
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sctp_bind_connect
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff8170dc40-ffffffff8170dcda: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
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
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffff80001056ccb8)
Location: security/selinux/netlabel.c:582
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffff80001056cc30-ffff80001056cc90: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (c0720514)
Location: security/selinux/netlabel.c:582
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
c07204ac-c07204f0: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (c0000000006d1278)
Location: security/selinux/netlabel.c:582
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
c0000000006d11f0-c0000000006d1234: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffe0003c1672)
Location: security/selinux/netlabel.c:582
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffe0003c1600-ffffffe0003c164c: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
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
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814746df)
Location: security/selinux/netlabel.c:582
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff81474690-ffffffff814746bc: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814650ff)
Location: security/selinux/netlabel.c:582
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff814650b0-ffffffff814650dc: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff8147077f)
Location: security/selinux/netlabel.c:582
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff81470730-ffffffff8147075c: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_socket_connect_locked(struct sock *sk, struct sockaddr *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81487fef)
Location: security/selinux/netlabel.c:582
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_socket_connect
```
**Symbols:**

```
ffffffff81487fa0-ffffffff81487fcc: selinux_netlbl_socket_connect_locked (STB_GLOBAL)
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
