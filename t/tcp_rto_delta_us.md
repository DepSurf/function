# Function: <code>tcp_rto_delta_us</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8182b5b4)
Location: include/net/tcp.h:1918
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff818333ac)
Location: include/net/tcp.h:1918
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_schedule_loss_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff818a9b64)
Location: include/net/tcp.h:1882
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff818b2735)
Location: include/net/tcp.h:1882
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819025fd)
Location: include/net/tcp.h:1897
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81907bc1)
Location: include/net/tcp.h:1897
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819306cd)
Location: include/net/tcp.h:1973
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81935e51)
Location: include/net/tcp.h:1973
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81993cd7)
Location: include/net/tcp.h:2002
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8199a282)
Location: include/net/tcp.h:2002
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819ca822)
Location: include/net/tcp.h:2025
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819d0ca0)
Location: include/net/tcp.h:2025
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ab77d1)
Location: include/net/tcp.h:2068
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81abc87e)
Location: include/net/tcp.h:2068
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81ac2a81)
Location: include/net/tcp.h:2076
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ac7fee)
Location: include/net/tcp.h:2076
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
In net/ipv4/tcp_input.c (ffffffff81aadc11)
Location: include/net/tcp.h:2080
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ab30bf)
Location: include/net/tcp.h:2080
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
In net/ipv4/tcp_input.c (ffffffff81b6a701)
Location: include/net/tcp.h:2072
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81b6feff)
Location: include/net/tcp.h:2072
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
In net/ipv4/tcp_input.c (ffffffff81cf98c1)
Location: include/net/tcp.h:2128
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81d00ac9)
Location: include/net/tcp.h:2128
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
In net/ipv4/tcp_input.c (ffffffff81ebe3c1)
Location: include/net/tcp.h:2176
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81ec5c09)
Location: include/net/tcp.h:2176
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81f1c861)
Location: include/net/tcp.h:2193
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81f241b9)
Location: include/net/tcp.h:2193
Inline: True
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
In net/ipv4/tcp_input.c (ffffffff81fe1041)
Location: include/net/tcp.h:2390
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81fe89cd)
Location: include/net/tcp.h:2390
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffff800010c7d51c)
Location: include/net/tcp.h:2025
Inline: True
```
```
In net/ipv4/tcp_output.c (ffff800010c8393c)
Location: include/net/tcp.h:2025
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c0d88e80)
Location: include/net/tcp.h:2025
Inline: True
```
```
In net/ipv4/tcp_output.c (c0d92b68)
Location: include/net/tcp.h:2025
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (c000000000d83010)
Location: include/net/tcp.h:2025
Inline: True
```
```
In net/ipv4/tcp_output.c (c000000000d8f220)
Location: include/net/tcp.h:2025
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffe0007dcd2a)
Location: include/net/tcp.h:2025
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffe0007e5498)
Location: include/net/tcp.h:2025
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff8196a692)
Location: include/net/tcp.h:2025
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81970b10)
Location: include/net/tcp.h:2025
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff81924182)
Location: include/net/tcp.h:2025
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8192a5e0)
Location: include/net/tcp.h:2025
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819d4e62)
Location: include/net/tcp.h:2025
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819db2e0)
Location: include/net/tcp.h:2025
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_input.c (ffffffff819dea42)
Location: include/net/tcp.h:2025
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819e4f60)
Location: include/net/tcp.h:2025
Inline: True
```
</details>
</li>
</ul>

## Differences
