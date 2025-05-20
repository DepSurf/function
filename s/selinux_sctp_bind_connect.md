# Function: <code>selinux_sctp_bind_connect</code>

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
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fbda0)
Location: security/selinux/hooks.c:5287
Inline: True
```
**Symbols:**

```
ffffffff813fbda0-ffffffff813fbebf: selinux_sctp_bind_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814182a0)
Location: security/selinux/hooks.c:5002
Inline: True
```
**Symbols:**

```
ffffffff814182a0-ffffffff814183d8: selinux_sctp_bind_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81446070)
Location: security/selinux/hooks.c:5201
Inline: True
```
**Symbols:**

```
ffffffff81446070-ffffffff814461b6: selinux_sctp_bind_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145fc00)
Location: security/selinux/hooks.c:5259
Inline: True
```
**Symbols:**

```
ffffffff8145fc00-ffffffff8145fd46: selinux_sctp_bind_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b27e0)
Location: security/selinux/hooks.c:5252
Inline: True
```
**Symbols:**

```
ffffffff814b27e0-ffffffff814b2926: selinux_sctp_bind_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814cfb60)
Location: security/selinux/hooks.c:5268
Inline: True
```
**Symbols:**

```
ffffffff814cfb60-ffffffff814cfca8: selinux_sctp_bind_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d6270)
Location: security/selinux/hooks.c:5432
Inline: True
```
**Symbols:**

```
ffffffff814d6270-ffffffff814d63b8: selinux_sctp_bind_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff8152f5ad)
Location: security/selinux/hooks.c:5417
Inline: True
```
**Symbols:**

```
ffffffff8152f570-ffffffff8152f6c4: selinux_sctp_bind_connect (STB_LOCAL)
ffffffff81cd36ee-ffffffff81cd3703: selinux_sctp_bind_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5362
Inline: False
```
**Symbols:**

```
ffffffff815c6920-ffffffff815c6aa7: selinux_sctp_bind_connect (STB_LOCAL)
ffffffff81e8683f-ffffffff81e8685c: selinux_sctp_bind_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5377
Inline: False
```
**Symbols:**

```
ffffffff81673660-ffffffff816737e7: selinux_sctp_bind_connect (STB_LOCAL)
ffffffff82073376-ffffffff82073393: selinux_sctp_bind_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5325
Inline: False
```
**Symbols:**

```
ffffffff816aba90-ffffffff816abc1a: selinux_sctp_bind_connect (STB_LOCAL)
ffffffff820f2f7f-ffffffff820f2f9c: selinux_sctp_bind_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:5419
Inline: False
```
**Symbols:**

```
ffffffff816e8700-ffffffff816e888a: selinux_sctp_bind_connect (STB_LOCAL)
ffffffff821d0213-ffffffff821d0230: selinux_sctp_bind_connect.cold (STB_LOCAL)
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
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054d210)
Location: security/selinux/hooks.c:5259
Inline: True
```
**Symbols:**

```
ffff80001054d210-ffff80001054d38c: selinux_sctp_bind_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0705354)
Location: security/selinux/hooks.c:5259
Inline: True
```
**Symbols:**

```
c0705354-c0705498: selinux_sctp_bind_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a9a80)
Location: security/selinux/hooks.c:5259
Inline: True
```
**Symbols:**

```
c0000000006a9a80-c0000000006a9d64: selinux_sctp_bind_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a7424)
Location: security/selinux/hooks.c:5259
Inline: True
```
**Symbols:**

```
ffffffe0003a7424-ffffffe0003a752e: selinux_sctp_bind_connect (STB_LOCAL)
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
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814581e0)
Location: security/selinux/hooks.c:5259
Inline: True
```
**Symbols:**

```
ffffffff814581e0-ffffffff81458326: selinux_sctp_bind_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81448c10)
Location: security/selinux/hooks.c:5259
Inline: True
```
**Symbols:**

```
ffffffff81448c10-ffffffff81448d56: selinux_sctp_bind_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81454280)
Location: security/selinux/hooks.c:5259
Inline: True
```
**Symbols:**

```
ffffffff81454280-ffffffff814543c6: selinux_sctp_bind_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int selinux_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8146e6a0)
Location: security/selinux/hooks.c:5259
Inline: True
```
**Symbols:**

```
ffffffff8146e6a0-ffffffff8146e7e6: selinux_sctp_bind_connect (STB_LOCAL)
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
