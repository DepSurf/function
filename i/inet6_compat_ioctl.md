# Function: <code>inet6_compat_ioctl</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inet6_compat_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81b29f20)
Location: net/ipv6/af_inet6.c:613
Inline: False
```
**Symbols:**

```
ffffffff81b29f20-ffffffff81b29f47: inet6_compat_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inet6_compat_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81b38860)
Location: net/ipv6/af_inet6.c:613
Inline: False
```
**Symbols:**

```
ffffffff81b38860-ffffffff81b38887: inet6_compat_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inet6_compat_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81b26450)
Location: net/ipv6/af_inet6.c:617
Inline: False
```
**Symbols:**

```
ffffffff81b26450-ffffffff81b26569: inet6_compat_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inet6_compat_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81bebeb0)
Location: net/ipv6/af_inet6.c:619
Inline: False
```
**Symbols:**

```
ffffffff81bebeb0-ffffffff81bebfc9: inet6_compat_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inet6_compat_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81d843a0)
Location: net/ipv6/af_inet6.c:625
Inline: False
```
**Symbols:**

```
ffffffff81d843a0-ffffffff81d844dd: inet6_compat_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet6_compat_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81f51c90)
Location: net/ipv6/af_inet6.c:633
Inline: False
```
**Symbols:**

```
ffffffff81f51c90-ffffffff81f51dcd: inet6_compat_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet6_compat_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81fb16b0)
Location: net/ipv6/af_inet6.c:623
Inline: False
```
**Symbols:**

```
ffffffff81fb16b0-ffffffff81fb17ed: inet6_compat_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet6_compat_ioctl(struct socket *sock, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff8207edd0)
Location: net/ipv6/af_inet6.c:632
Inline: False
```
**Symbols:**

```
ffffffff8207edd0-ffffffff8207ef0d: inet6_compat_ioctl (STB_GLOBAL)
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
