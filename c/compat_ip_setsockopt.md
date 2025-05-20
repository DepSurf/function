# Function: <code>compat_ip_setsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81761850)
Location: net/ipv4/ip_sockglue.c:1221
Inline: True
Direct callers:
  - net/ipv4/raw.c:compat_raw_setsockopt
```
**Symbols:**

```
ffffffff81761850-ffffffff81761904: compat_ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817cdb70)
Location: net/ipv4/ip_sockglue.c:1236
Inline: True
```
**Symbols:**

```
ffffffff817cdb70-ffffffff817cdc36: compat_ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff817fd8d0)
Location: net/ipv4/ip_sockglue.c:1276
Inline: True
```
**Symbols:**

```
ffffffff817fd8d0-ffffffff817fd996: compat_ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8181dd10)
Location: net/ipv4/ip_sockglue.c:1265
Inline: True
```
**Symbols:**

```
ffffffff8181dd10-ffffffff8181ddd6: compat_ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8189cc50)
Location: net/ipv4/ip_sockglue.c:1264
Inline: True
```
**Symbols:**

```
ffffffff8189cc50-ffffffff8189ccee: compat_ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff818f1130)
Location: net/ipv4/ip_sockglue.c:1268
Inline: True
```
**Symbols:**

```
ffffffff818f1130-ffffffff818f11c7: compat_ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff8191ec90)
Location: net/ipv4/ip_sockglue.c:1265
Inline: True
```
**Symbols:**

```
ffffffff8191ec90-ffffffff8191ed27: compat_ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819815a0)
Location: net/ipv4/ip_sockglue.c:1267
Inline: True
```
**Symbols:**

```
ffffffff819815a0-ffffffff8198163f: compat_ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819b7de0)
Location: net/ipv4/ip_sockglue.c:1267
Inline: True
```
**Symbols:**

```
ffffffff819b7de0-ffffffff819b7e7f: compat_ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int compat_ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aa2330)
Location: net/ipv4/ip_sockglue.c:1326
Inline: False
```
**Symbols:**

```
ffffffff81aa2330-ffffffff81aa26d1: compat_ip_setsockopt (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffff800010c691a8)
Location: net/ipv4/ip_sockglue.c:1267
Inline: True
```
**Symbols:**

```
ffff800010c691a8-ffff800010c69288: compat_ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (c000000000d6dc90)
Location: net/ipv4/ip_sockglue.c:1267
Inline: True
```
**Symbols:**

```
c000000000d6dc90-c000000000d6dddc: compat_ip_setsockopt (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81957c50)
Location: net/ipv4/ip_sockglue.c:1267
Inline: True
```
**Symbols:**

```
ffffffff81957c50-ffffffff81957cef: compat_ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81911740)
Location: net/ipv4/ip_sockglue.c:1267
Inline: True
```
**Symbols:**

```
ffffffff81911740-ffffffff819117df: compat_ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819c2420)
Location: net/ipv4/ip_sockglue.c:1267
Inline: True
```
**Symbols:**

```
ffffffff819c2420-ffffffff819c24bf: compat_ip_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int compat_ip_setsockopt(struct sock *sk, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff819cbe20)
Location: net/ipv4/ip_sockglue.c:1267
Inline: True
```
**Symbols:**

```
ffffffff819cbe20-ffffffff819cbebf: compat_ip_setsockopt (STB_GLOBAL)
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
