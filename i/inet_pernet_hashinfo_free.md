# Function: <code>inet_pernet_hashinfo_free</code>

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
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet_pernet_hashinfo_free(struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea22a4)
Location: net/ipv4/inet_hashtables.c:1260
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit_batch
```
**Symbols:**

```
ffffffff820ae50d-ffffffff820ae522: inet_pernet_hashinfo_free.cold (STB_LOCAL)
ffffffff81ea2280-ffffffff81ea22d2: inet_pernet_hashinfo_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet_pernet_hashinfo_free(struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f00ac4)
Location: net/ipv4/inet_hashtables.c:1250
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit_batch
```
**Symbols:**

```
ffffffff8212fa1e-ffffffff8212fa33: inet_pernet_hashinfo_free.cold (STB_LOCAL)
ffffffff81f00aa0-ffffffff81f00af2: inet_pernet_hashinfo_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void inet_pernet_hashinfo_free(struct inet_hashinfo *hashinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81fc4f44)
Location: net/ipv4/inet_hashtables.c:1290
Inline: True
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_sk_exit_batch
```
**Symbols:**

```
ffffffff822117e1-ffffffff822117f6: inet_pernet_hashinfo_free.cold (STB_LOCAL)
ffffffff81fc4f20-ffffffff81fc4f72: inet_pernet_hashinfo_free (STB_GLOBAL)
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
