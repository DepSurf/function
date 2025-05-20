# Function: <code>bpf_skops_init_skb</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac4fa8)
Location: include/net/tcp.h:2232
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81ac693a)
Location: include/net/tcp.h:2232
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab0050)
Location: include/net/tcp.h:2237
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81ab1b40)
Location: include/net/tcp.h:2237
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81b6ce32)
Location: include/net/tcp.h:2229
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81b6e688)
Location: include/net/tcp.h:2229
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cfc296)
Location: include/net/tcp.h:2289
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81cfdc5c)
Location: include/net/tcp.h:2289
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ec0e26)
Location: include/net/tcp.h:2337
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81ec28cc)
Location: include/net/tcp.h:2337
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81f1f396)
Location: include/net/tcp.h:2362
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81f20e2c)
Location: include/net/tcp.h:2362
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81fe3a66)
Location: include/net/tcp.h:2558
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_init_transfer
  - net/ipv4/tcp_input.c:tcp_validate_incoming
```
```
In net/ipv4/tcp_output.c (ffffffff81fe552c)
Location: include/net/tcp.h:2558
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:bpf_skops_hdr_opt_len
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
