# Function: <code>inet_frag_maybe_warn_overflow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inet_frag_maybe_warn_overflow(struct inet_frag_queue *q, const char *prefix);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff817a1790)
Location: net/ipv4/inet_fragment.c:437
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff817a1790-ffffffff817a179b: inet_frag_maybe_warn_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void inet_frag_maybe_warn_overflow(struct inet_frag_queue *q, const char *prefix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff8180fe60)
Location: net/ipv4/inet_fragment.c:429
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff8180fe60-ffffffff8180feab: inet_frag_maybe_warn_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void inet_frag_maybe_warn_overflow(struct inet_frag_queue *q, const char *prefix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff818413b0)
Location: net/ipv4/inet_fragment.c:429
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff818413b0-ffffffff818413fb: inet_frag_maybe_warn_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void inet_frag_maybe_warn_overflow(struct inet_frag_queue *q, const char *prefix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81862c20)
Location: net/ipv4/inet_fragment.c:427
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff81862c20-ffffffff81862c67: inet_frag_maybe_warn_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void inet_frag_maybe_warn_overflow(struct inet_frag_queue *q, const char *prefix);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff818e2d50)
Location: net/ipv4/inet_fragment.c:430
Inline: True
Direct callers:
  - net/ipv4/ip_fragment.c:ip_defrag
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
**Symbols:**

```
ffffffff818e2d50-ffffffff818e2d97: inet_frag_maybe_warn_overflow (STB_GLOBAL)
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
