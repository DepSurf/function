# Function: <code>tcp_proc_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tcp_proc_unregister(struct net *net, struct tcp_seq_afinfo *afinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8177b320)
Location: net/ipv4/tcp_ipv4.c:2126
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
```
**Symbols:**

```
ffffffff8177b320-ffffffff8177b33d: tcp_proc_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tcp_proc_unregister(struct net *net, struct tcp_seq_afinfo *afinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff817e8bb6)
Location: net/ipv4/tcp_ipv4.c:2143
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
```
**Symbols:**

```
ffffffff817e8b90-ffffffff817e8bad: tcp_proc_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tcp_proc_unregister(struct net *net, struct tcp_seq_afinfo *afinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81818da6)
Location: net/ipv4/tcp_ipv4.c:2187
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
```
**Symbols:**

```
ffffffff81818d80-ffffffff81818d9d: tcp_proc_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_proc_unregister(struct net *net, struct tcp_seq_afinfo *afinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81839576)
Location: net/ipv4/tcp_ipv4.c:2243
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
```
**Symbols:**

```
ffffffff81839550-ffffffff8183956d: tcp_proc_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tcp_proc_unregister(struct net *net, struct tcp_seq_afinfo *afinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff818b8d06)
Location: net/ipv4/tcp_ipv4.c:2222
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_proc_exit_net
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp6_proc_exit
```
**Symbols:**

```
ffffffff818b8ce0-ffffffff818b8cfd: tcp_proc_unregister (STB_GLOBAL)
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
