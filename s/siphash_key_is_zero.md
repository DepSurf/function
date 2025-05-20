# Function: <code>siphash_key_is_zero</code>

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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819709c5)
Location: include/linux/siphash.h:24
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv6/output_core.c (ffffffff81a50ab5)
Location: include/linux/siphash.h:24
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
In net/ipv4/route.c (ffffffff819a73c5)
Location: include/linux/siphash.h:24
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv6/output_core.c (ffffffff81a876d5)
Location: include/linux/siphash.h:24
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
In net/ipv4/route.c (ffffffff81a90705)
Location: include/linux/siphash.h:24
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv6/output_core.c (ffffffff81b82ca6)
Location: include/linux/siphash.h:24
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
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
In net/ipv4/route.c (ffffffff81a9a575)
Location: include/linux/siphash.h:24
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv6/output_core.c (ffffffff81b92326)
Location: include/linux/siphash.h:24
Inline: True
Inline callers:
  - net/ipv6/output_core.c:ipv6_select_ident
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a85865)
Location: include/linux/siphash.h:24
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b40035)
Location: include/linux/siphash.h:24
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81ccc8c5)
Location: include/linux/siphash.h:25
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e8ca85)
Location: include/linux/siphash.h:25
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81eeb1b5)
Location: include/linux/siphash.h:25
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81faf1d5)
Location: include/linux/siphash.h:25
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
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
In net/ipv4/route.c (ffff800010c585c4)
Location: include/linux/siphash.h:24
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv6/output_core.c (ffff800010d53fd8)
Location: include/linux/siphash.h:24
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
In net/ipv4/route.c (c0d67a80)
Location: include/linux/siphash.h:24
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv6/output_core.c (c0e547a4)
Location: include/linux/siphash.h:24
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
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
In net/ipv4/route.c (c000000000d57f44)
Location: include/linux/siphash.h:24
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv6/output_core.c (c000000000e8c9d4)
Location: include/linux/siphash.h:24
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
In net/ipv4/route.c (ffffffe0007c104e)
Location: include/linux/siphash.h:24
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv6/output_core.c (ffffffe00088bad4)
Location: include/linux/siphash.h:24
Inline: True
Inline callers:
  - net/ipv6/output_core.c:__ipv6_select_ident
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
In net/ipv4/route.c (ffffffff81947235)
Location: include/linux/siphash.h:24
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv6/output_core.c (ffffffff81a26d65)
Location: include/linux/siphash.h:24
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
In net/ipv4/route.c (ffffffff81900d25)
Location: include/linux/siphash.h:24
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv6/output_core.c (ffffffff819e3b25)
Location: include/linux/siphash.h:24
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
In net/ipv4/route.c (ffffffff819b1a05)
Location: include/linux/siphash.h:24
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv6/output_core.c (ffffffff81a92915)
Location: include/linux/siphash.h:24
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
In net/ipv4/route.c (ffffffff819bb0a5)
Location: include/linux/siphash.h:24
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_select_ident
```
```
In net/ipv6/output_core.c (ffffffff81a9ea15)
Location: include/linux/siphash.h:24
Inline: True
```
</details>
</li>
</ul>

## Differences
