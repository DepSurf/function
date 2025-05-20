# Function: <code>secure_tcp_sequence_number</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__u32 secure_tcp_sequence_number(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff817114b0)
Location: net/core/secure_seq.c:89
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_sequence
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
```
**Symbols:**

```
ffffffff817114b0-ffffffff81711583: secure_tcp_sequence_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__u32 secure_tcp_sequence_number(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff81778df0)
Location: net/core/secure_seq.c:89
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_sequence
```
**Symbols:**

```
ffffffff81778df0-ffffffff81778ec3: secure_tcp_sequence_number (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 secure_tcp_sequence_number(__be32 saddr, __be32 daddr, __be16 sport, __be16 dport, u32 *tsoff);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/secure_seq.c (ffffffff817a5f30)
Location: net/core/secure_seq.c:91
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_connect
  - net/ipv4/tcp_ipv4.c:tcp_v4_init_sequence
```
**Symbols:**

```
ffffffff817a5f30-ffffffff817a601e: secure_tcp_sequence_number (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 *tsoff</code>
</li>
<li>
<b>Return type changed. </b>
<code>__u32</code> ➡️ <code>u32</code>
</li>
</ul>
</details>
</li>
</ul>
