# Function: <code>get_user_ifreq</code>

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
int get_user_ifreq(struct ifreq *ifr, void **ifrdata, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a74a70)
Location: net/socket.c:3158
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81a74a70-ffffffff81a74b17: get_user_ifreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_user_ifreq(struct ifreq *ifr, void **ifrdata, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be5d40)
Location: net/socket.c:3234
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81be5d40-ffffffff81be5ddc: get_user_ifreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_user_ifreq(struct ifreq *ifr, void **ifrdata, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d91f40)
Location: net/socket.c:3222
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81d91f40-ffffffff81d91fdc: get_user_ifreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_user_ifreq(struct ifreq *ifr, void **ifrdata, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e002f0)
Location: net/socket.c:3260
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81e002f0-ffffffff81e0038c: get_user_ifreq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_user_ifreq(struct ifreq *ifr, void **ifrdata, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ebc850)
Location: net/socket.c:3330
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:compat_sock_ioctl_trans
  - net/socket.c:sock_ioctl
  - net/socket.c:sock_do_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81ebc850-ffffffff81ebc8ec: get_user_ifreq (STB_GLOBAL)
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
