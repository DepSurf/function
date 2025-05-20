# Function: <code>fib4_has_custom_rules</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:137
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:137
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:137
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:134
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:135
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
In net/ipv4/ip_input.c (ffffffff81a981c8)
Location: include/net/ip_fib.h:397
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81aeb785)
Location: include/net/ip_fib.h:397
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
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
In net/ipv4/ip_input.c (ffffffff81aa2118)
Location: include/net/ip_fib.h:397
Inline: True
```
```
In net/ipv4/fib_frontend.c (ffffffff81af8695)
Location: include/net/ip_fib.h:397
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
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
In net/ipv4/ip_input.c (ffffffff81a8d511)
Location: include/net/ip_fib.h:398
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae3db6)
Location: include/net/ip_fib.h:398
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
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
In net/ipv4/ip_input.c (ffffffff81b486e2)
Location: include/net/ip_fib.h:398
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba36fb)
Location: include/net/ip_fib.h:398
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
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
In net/ipv4/ip_input.c (ffffffff81cd5a95)
Location: include/net/ip_fib.h:401
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81d35f80)
Location: include/net/ip_fib.h:401
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
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
In net/ipv4/ip_input.c (ffffffff81e95f25)
Location: include/net/ip_fib.h:401
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81efe580)
Location: include/net/ip_fib.h:401
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
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
In net/ipv4/ip_input.c (ffffffff81ef4764)
Location: include/net/ip_fib.h:401
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5e010)
Location: include/net/ip_fib.h:401
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
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
In net/ipv4/ip_input.c (ffffffff81fb86e4)
Location: include/net/ip_fib.h:402
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
```
In net/ipv4/fib_frontend.c (ffffffff820245d0)
Location: include/net/ip_fib.h:402
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:135
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c0dc07fc)
Location: net/ipv4/fib_frontend.c:135
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c000000000dcc164)
Location: net/ipv4/fib_frontend.c:135
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffe00080c9a4)
Location: net/ipv4/fib_frontend.c:135
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_validate_source
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:135
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:135
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:135
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (0)
Location: net/ipv4/fib_frontend.c:135
Inline: True
```
</details>
</li>
</ul>

## Differences
