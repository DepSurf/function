# Function: <code>ip_sock_set_mtu_discover</code>

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
int ip_sock_set_mtu_discover(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81a9f790)
Location: net/ipv4/ip_sockglue.c:600
Inline: False
```
**Symbols:**

```
ffffffff81a9f790-ffffffff81a9f7ca: ip_sock_set_mtu_discover (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ip_sock_set_mtu_discover(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aa96e0)
Location: net/ipv4/ip_sockglue.c:616
Inline: False
```
**Symbols:**

```
ffffffff81aa96e0-ffffffff81aa971a: ip_sock_set_mtu_discover (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ip_sock_set_mtu_discover(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81a948b0)
Location: net/ipv4/ip_sockglue.c:616
Inline: False
```
**Symbols:**

```
ffffffff81a948b0-ffffffff81a948ea: ip_sock_set_mtu_discover (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ip_sock_set_mtu_discover(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81b4fd30)
Location: net/ipv4/ip_sockglue.c:616
Inline: False
```
**Symbols:**

```
ffffffff81b4fd30-ffffffff81b4fd6a: ip_sock_set_mtu_discover (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ip_sock_set_mtu_discover(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81cdd840)
Location: net/ipv4/ip_sockglue.c:618
Inline: False
```
**Symbols:**

```
ffffffff81cdd840-ffffffff81cdd88a: ip_sock_set_mtu_discover (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ip_sock_set_mtu_discover(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81e9e490)
Location: net/ipv4/ip_sockglue.c:619
Inline: False
```
**Symbols:**

```
ffffffff81e9e490-ffffffff81e9e4da: ip_sock_set_mtu_discover (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ip_sock_set_mtu_discover(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81efcc90)
Location: net/ipv4/ip_sockglue.c:626
Inline: False
```
**Symbols:**

```
ffffffff81efcc90-ffffffff81efccda: ip_sock_set_mtu_discover (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ip_sock_set_mtu_discover(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81fc32fe)
Location: net/ipv4/ip_sockglue.c:621
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
```
**Symbols:**

```
ffffffff81fc0a30-ffffffff81fc0a60: ip_sock_set_mtu_discover (STB_GLOBAL)
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
