# Function: <code>inet_pernet_hashinfo_alloc</code>

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
struct inet_hashinfo *inet_pernet_hashinfo_alloc(struct inet_hashinfo *hashinfo, unsigned int ehash_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea26d0)
Location: net/ipv4/inet_hashtables.c:1224
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
```
**Symbols:**

```
ffffffff81ea26d0-ffffffff81ea277d: inet_pernet_hashinfo_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inet_hashinfo *inet_pernet_hashinfo_alloc(struct inet_hashinfo *hashinfo, unsigned int ehash_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f00ef0)
Location: net/ipv4/inet_hashtables.c:1214
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
```
**Symbols:**

```
ffffffff81f00ef0-ffffffff81f00f9d: inet_pernet_hashinfo_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inet_hashinfo *inet_pernet_hashinfo_alloc(struct inet_hashinfo *hashinfo, unsigned int ehash_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc5250)
Location: net/ipv4/inet_hashtables.c:1254
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_init
```
**Symbols:**

```
ffffffff81fc5250-ffffffff81fc52fd: inet_pernet_hashinfo_alloc (STB_GLOBAL)
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
