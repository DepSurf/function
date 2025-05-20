# Function: <code>udp_proc_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void udp_proc_unregister(struct net *net, struct udp_seq_afinfo *afinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81787290)
Location: net/ipv4/udp.c:2420
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_proc_exit_net
Direct callers:
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
```
**Symbols:**

```
ffffffff81787290-ffffffff817872ad: udp_proc_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void udp_proc_unregister(struct net *net, struct udp_seq_afinfo *afinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff817f4446)
Location: net/ipv4/udp.c:2350
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_proc_exit_net
Direct callers:
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
```
**Symbols:**

```
ffffffff817f4420-ffffffff817f443d: udp_proc_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void udp_proc_unregister(struct net *net, struct udp_seq_afinfo *afinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81825516)
Location: net/ipv4/udp.c:2520
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_proc_exit_net
Direct callers:
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
```
**Symbols:**

```
ffffffff818254f0-ffffffff8182550d: udp_proc_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void udp_proc_unregister(struct net *net, struct udp_seq_afinfo *afinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81846446)
Location: net/ipv4/udp.c:2684
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_proc_exit_net
Direct callers:
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
```
**Symbols:**

```
ffffffff81846420-ffffffff8184643d: udp_proc_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void udp_proc_unregister(struct net *net, struct udp_seq_afinfo *afinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c5e76)
Location: net/ipv4/udp.c:2699
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_proc_exit_net
Direct callers:
  - net/ipv4/udplite.c:udplite4_proc_exit_net
  - net/ipv6/udp.c:udp6_proc_exit
  - net/ipv6/udplite.c:udplite6_proc_exit_net
```
**Symbols:**

```
ffffffff818c5e50-ffffffff818c5e6d: udp_proc_unregister (STB_GLOBAL)
```
</details>
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
</ul>
