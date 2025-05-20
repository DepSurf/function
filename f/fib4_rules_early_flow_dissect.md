# Function: <code>fib4_rules_early_flow_dissect</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e4bd5)
Location: include/net/ip_fib.h:352
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff8193127e)
Location: include/net/ip_fib.h:352
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
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
In net/ipv4/route.c (ffffffff81911ad4)
Location: include/net/ip_fib.h:363
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81960b70)
Location: include/net/ip_fib.h:363
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
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
In net/ipv4/route.c (ffffffff8197423a)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff819c564b)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
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
In net/ipv4/route.c (ffffffff819aac5a)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff819fc1eb)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
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
In net/ipv4/route.c (ffffffff81a94f9e)
Location: include/net/ip_fib.h:407
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81aea3eb)
Location: include/net/ip_fib.h:407
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
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
In net/ipv4/route.c (ffffffff81a9ef9e)
Location: include/net/ip_fib.h:407
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81af724b)
Location: include/net/ip_fib.h:407
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
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
In net/ipv4/route.c (ffffffff81a89f19)
Location: include/net/ip_fib.h:408
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81ae298b)
Location: include/net/ip_fib.h:408
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/netfilter.c (ffffffff81b03cce)
Location: include/net/ip_fib.h:408
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff81b44da9)
Location: include/net/ip_fib.h:408
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81ba221b)
Location: include/net/ip_fib.h:408
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/netfilter.c (ffffffff81bc5f7e)
Location: include/net/ip_fib.h:408
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff81cd1aca)
Location: include/net/ip_fib.h:411
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81d34958)
Location: include/net/ip_fib.h:411
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/netfilter.c (ffffffff81d5b2ac)
Location: include/net/ip_fib.h:411
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff81e9200a)
Location: include/net/ip_fib.h:411
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81efce56)
Location: include/net/ip_fib.h:411
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/netfilter.c (ffffffff81f2573c)
Location: include/net/ip_fib.h:411
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff81ef0790)
Location: include/net/ip_fib.h:411
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81f5c896)
Location: include/net/ip_fib.h:411
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/netfilter.c (ffffffff81f852cc)
Location: include/net/ip_fib.h:411
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffffffff81fb48e0)
Location: include/net/ip_fib.h:412
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff82022e18)
Location: include/net/ip_fib.h:412
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
```
In net/ipv4/netfilter.c (ffffffff8204b987)
Location: include/net/ip_fib.h:412
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
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
In net/ipv4/route.c (ffff800010c5af84)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffff800010cb45f0)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
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
In net/ipv4/route.c (c0d6a4a0)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (c0dbfaec)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
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
In net/ipv4/route.c (c000000000d5cd18)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (c000000000dcb600)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
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
In net/ipv4/route.c (ffffffe0007c433c)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffe00080c2c4)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
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
In net/ipv4/route.c (ffffffff8194aaca)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff8199bf8b)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
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
In net/ipv4/route.c (ffffffff819045ba)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81955a4b)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
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
In net/ipv4/route.c (ffffffff819b529a)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81a0682b)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
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
In net/ipv4/route.c (ffffffff819be9e4)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_slow
```
```
In net/ipv4/fib_frontend.c (ffffffff81a10eab)
Location: include/net/ip_fib.h:383
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:__fib_validate_source
```
</details>
</li>
</ul>

## Differences
