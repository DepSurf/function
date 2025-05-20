# Function: <code>compat_packet_setsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818773b0)
Location: net/packet/af_packet.c:3907
Inline: False
```
**Symbols:**

```
ffffffff818773b0-ffffffff81877423: compat_packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818ac390)
Location: net/packet/af_packet.c:3880
Inline: False
```
**Symbols:**

```
ffffffff818ac390-ffffffff818ac403: compat_packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int compat_packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818d24b0)
Location: net/packet/af_packet.c:3953
Inline: False
```
**Symbols:**

```
ffffffff818d24b0-ffffffff818d2523: compat_packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int compat_packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819573d0)
Location: net/packet/af_packet.c:3952
Inline: False
```
**Symbols:**

```
ffffffff819573d0-ffffffff81957443: compat_packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int compat_packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819b3ea0)
Location: net/packet/af_packet.c:3957
Inline: False
```
**Symbols:**

```
ffffffff819b3ea0-ffffffff819b3f13: compat_packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int compat_packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819eaed0)
Location: net/packet/af_packet.c:3986
Inline: False
```
**Symbols:**

```
ffffffff819eaed0-ffffffff819eaf43: compat_packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int compat_packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a5a030)
Location: net/packet/af_packet.c:4025
Inline: False
```
**Symbols:**

```
ffffffff81a5a030-ffffffff81a5a0a5: compat_packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int compat_packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a90140)
Location: net/packet/af_packet.c:4044
Inline: False
```
**Symbols:**

```
ffffffff81a90140-ffffffff81a901b5: compat_packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int compat_packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b8ae20)
Location: net/packet/af_packet.c:4055
Inline: False
```
**Symbols:**

```
ffffffff81b8ae20-ffffffff81b8ae93: compat_packet_setsockopt (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int compat_packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffff800010d5d1c8)
Location: net/packet/af_packet.c:4044
Inline: False
```
**Symbols:**

```
ffff800010d5d1c8-ffff800010d5d274: compat_packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int compat_packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c000000000e99090)
Location: net/packet/af_packet.c:4044
Inline: False
```
**Symbols:**

```
c000000000e99090-c000000000e99150: compat_packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int compat_packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a2f7d0)
Location: net/packet/af_packet.c:4044
Inline: False
```
**Symbols:**

```
ffffffff81a2f7d0-ffffffff81a2f845: compat_packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int compat_packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819ec9c0)
Location: net/packet/af_packet.c:4044
Inline: False
```
**Symbols:**

```
ffffffff819ec9c0-ffffffff819eca35: compat_packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int compat_packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a9b380)
Location: net/packet/af_packet.c:4044
Inline: False
```
**Symbols:**

```
ffffffff81a9b380-ffffffff81a9b3f5: compat_packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int compat_packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81aa80f0)
Location: net/packet/af_packet.c:4044
Inline: False
```
**Symbols:**

```
ffffffff81aa80f0-ffffffff81aa8165: compat_packet_setsockopt (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
