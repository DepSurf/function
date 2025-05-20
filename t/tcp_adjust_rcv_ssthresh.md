# Function: <code>tcp_adjust_rcv_ssthresh</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81cf3c41)
Location: include/net/tcp.h:1442
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81d00d52)
Location: include/net/tcp.h:1442
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff81eb864a)
Location: include/net/tcp.h:1458
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81ec5ea2)
Location: include/net/tcp.h:1458
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff81f16aba)
Location: include/net/tcp.h:1456
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81f244ab)
Location: include/net/tcp.h:1456
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In net/ipv4/tcp_input.c (ffffffff81fdb92a)
Location: include/net/tcp.h:1532
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81fe8cc1)
Location: include/net/tcp.h:1532
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
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
