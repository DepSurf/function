# Function: <code>tcp_saved_syn_len</code>

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
In net/core/filter.c (ffffffff81a2a8c1)
Location: include/linux/tcp.h:492
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff81ab76d2)
Location: include/linux/tcp.h:492
Inline: True
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
In net/core/filter.c (ffffffff81a11aa2)
Location: include/linux/tcp.h:492
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff81aa28cc)
Location: include/linux/tcp.h:492
Inline: True
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
In net/core/filter.c (ffffffff81acd7b6)
Location: include/linux/tcp.h:492
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff81b5ea6e)
Location: include/linux/tcp.h:492
Inline: True
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
In net/core/filter.c (ffffffff81c4b93f)
Location: include/linux/tcp.h:493
Inline: True
Inline callers:
  - net/core/filter.c:_bpf_getsockopt
```
```
In net/ipv4/tcp.c (ffffffff81ced4ab)
Location: include/linux/tcp.h:493
Inline: True
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
In net/core/filter.c (ffffffff81df547b)
Location: include/linux/tcp.h:530
Inline: True
Inline callers:
  - net/core/filter.c:sol_tcp_sockopt
```
```
In net/ipv4/tcp.c (ffffffff81eb3bfc)
Location: include/linux/tcp.h:530
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
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
In net/core/filter.c (ffffffff81e66d6e)
Location: include/linux/tcp.h:532
Inline: True
Inline callers:
  - net/core/filter.c:sol_tcp_sockopt
```
```
In net/ipv4/tcp.c (ffffffff81f1275f)
Location: include/linux/tcp.h:532
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
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
In net/core/filter.c (ffffffff81f25f1e)
Location: include/linux/tcp.h:588
Inline: True
Inline callers:
  - net/core/filter.c:sol_tcp_sockopt
```
```
In net/ipv4/tcp.c (ffffffff81fd6d34)
Location: include/linux/tcp.h:588
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
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
