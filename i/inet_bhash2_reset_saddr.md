# Function: <code>inet_bhash2_reset_saddr</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void inet_bhash2_reset_saddr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea4fc0)
Location: net/ipv4/inet_hashtables.c:972
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
**Symbols:**

```
ffffffff81ea4fc0-ffffffff81ea4fff: inet_bhash2_reset_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void inet_bhash2_reset_saddr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f03790)
Location: net/ipv4/inet_hashtables.c:962
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
**Symbols:**

```
ffffffff81f03790-ffffffff81f037cf: inet_bhash2_reset_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void inet_bhash2_reset_saddr(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc7a20)
Location: net/ipv4/inet_hashtables.c:974
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_disconnect
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv6/tcp_ipv6.c:tcp_v6_connect
```
**Symbols:**

```
ffffffff81fc7a20-ffffffff81fc7a5f: inet_bhash2_reset_saddr (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
