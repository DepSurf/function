# Function: <code>inet_bind2_bucket_match_addr_any</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
bool inet_bind2_bucket_match_addr_any(const struct inet_bind2_bucket *tb, const struct net *net, short unsigned int port, int l3mdev, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea4220)
Location: net/ipv4/inet_hashtables.c:825
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict
```
**Symbols:**

```
ffffffff81ea4220-ffffffff81ea4293: inet_bind2_bucket_match_addr_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool inet_bind2_bucket_match_addr_any(const struct inet_bind2_bucket *tb, const struct net *net, short unsigned int port, int l3mdev, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f02aa0)
Location: net/ipv4/inet_hashtables.c:812
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict
```
**Symbols:**

```
ffffffff81f02aa0-ffffffff81f02b3a: inet_bind2_bucket_match_addr_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool inet_bind2_bucket_match_addr_any(const struct inet_bind2_bucket *tb, const struct net *net, short unsigned int port, int l3mdev, const struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc6e60)
Location: net/ipv4/inet_hashtables.c:826
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict
```
**Symbols:**

```
ffffffff81fc6e60-ffffffff81fc6ed0: inet_bind2_bucket_match_addr_any (STB_GLOBAL)
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
