# Function: <code>ip_neigh_for_gw</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff8197bcfa)
Location: include/net/route.h:368
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/ip_output.c (ffffffff819b269a)
Location: include/net/route.h:369
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_output.c (ffffffff81a9bd93)
Location: include/net/route.h:379
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81a30c07)
Location: include/net/route.h:379
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81aa5bf3)
Location: include/net/route.h:379
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81a17c6b)
Location: include/net/route.h:379
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81a90bc3)
Location: include/net/route.h:379
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81acb30a)
Location: include/net/route.h:379
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81b4c01a)
Location: include/net/route.h:379
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81c46f96)
Location: include/net/route.h:392
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81cd9759)
Location: include/net/route.h:392
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81dfb4e6)
Location: include/net/route.h:387
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81e99ed9)
Location: include/net/route.h:387
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81e6c400)
Location: include/net/route.h:379
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81ef8849)
Location: include/net/route.h:379
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/core/filter.c (ffffffff81f2bced)
Location: include/net/route.h:373
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81fbc77e)
Location: include/net/route.h:373
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/ip_output.c (ffff800010c635ac)
Location: include/net/route.h:369
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/ip_output.c (c0d7292c)
Location: include/net/route.h:369
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/ip_output.c (c000000000d668c0)
Location: include/net/route.h:369
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/ip_output.c (ffffffe0007cabe6)
Location: include/net/route.h:369
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/ip_output.c (ffffffff8195250a)
Location: include/net/route.h:369
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/ip_output.c (ffffffff8190bffa)
Location: include/net/route.h:369
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/ip_output.c (ffffffff819bccda)
Location: include/net/route.h:369
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
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
In net/ipv4/ip_output.c (ffffffff819c65ea)
Location: include/net/route.h:369
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_finish_output2
```
</details>
</li>
</ul>

## Differences
