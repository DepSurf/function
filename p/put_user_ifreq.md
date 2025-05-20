# Function: <code>put_user_ifreq</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int put_user_ifreq(struct ifreq *ifr, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a749f0)
Location: net/socket.c:3183
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81a749f0-ffffffff81a74a67: put_user_ifreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int put_user_ifreq(struct ifreq *ifr, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be6050)
Location: net/socket.c:3259
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81be6050-ffffffff81be60b4: put_user_ifreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int put_user_ifreq(struct ifreq *ifr, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d922a0)
Location: net/socket.c:3247
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81d922a0-ffffffff81d92304: put_user_ifreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int put_user_ifreq(struct ifreq *ifr, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e00660)
Location: net/socket.c:3285
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81e00660-ffffffff81e006c4: put_user_ifreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int put_user_ifreq(struct ifreq *ifr, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebcbc0)
Location: net/socket.c:3355
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81ebcbc0-ffffffff81ebcc24: put_user_ifreq (STB_GLOBAL)
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
