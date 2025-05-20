# Function: <code>inet_bhash2_addr_any_hashbucket</code>

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
struct inet_bind_hashbucket *inet_bhash2_addr_any_hashbucket(const struct sock *sk, const struct net *net, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea5010)
Location: net/ipv4/inet_hashtables.c:859
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict
```
**Symbols:**

```
ffffffff81ea5010-ffffffff81ea5103: inet_bhash2_addr_any_hashbucket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inet_bind_hashbucket *inet_bhash2_addr_any_hashbucket(const struct sock *sk, const struct net *net, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f037e0)
Location: net/ipv4/inet_hashtables.c:850
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict
```
**Symbols:**

```
ffffffff81f037e0-ffffffff81f0389b: inet_bhash2_addr_any_hashbucket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inet_bind_hashbucket *inet_bhash2_addr_any_hashbucket(const struct sock *sk, const struct net *net, int port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc7a70)
Location: net/ipv4/inet_hashtables.c:862
Inline: False
Direct callers:
  - net/ipv4/inet_connection_sock.c:inet_bhash2_addr_any_conflict
```
**Symbols:**

```
ffffffff81fc7a70-ffffffff81fc7b2b: inet_bhash2_addr_any_hashbucket (STB_GLOBAL)
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
