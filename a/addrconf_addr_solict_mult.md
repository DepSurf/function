# Function: <code>addrconf_addr_solict_mult</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817cac11)
Location: include/net/addrconf.h:335
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (ffffffff817d366b)
Location: include/net/addrconf.h:335
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff817de2a6)
Location: include/net/addrconf.h:335
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
  - net/ipv6/ndisc.c:ndisc_solicit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8183d46b)
Location: include/net/addrconf.h:348
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (ffffffff8184119b)
Location: include/net/addrconf.h:348
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff8184daf1)
Location: include/net/addrconf.h:348
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186f079)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (ffffffff81872e9e)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff8187f9c1)
Location: include/net/addrconf.h:350
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81893e7a)
Location: include/net/addrconf.h:382
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (ffffffff81897acd)
Location: include/net/addrconf.h:382
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff818a5abf)
Location: include/net/addrconf.h:382
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffffffff81915306)
Location: include/net/addrconf.h:381
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (ffffffff81918d7d)
Location: include/net/addrconf.h:381
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff819284cf)
Location: include/net/addrconf.h:381
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffffffff8196c8d2)
Location: include/net/addrconf.h:431
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (ffffffff81970b2e)
Location: include/net/addrconf.h:431
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff81980864)
Location: include/net/addrconf.h:431
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffffffff819a2372)
Location: include/net/addrconf.h:439
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (ffffffff819a675e)
Location: include/net/addrconf.h:439
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff819b6e74)
Location: include/net/addrconf.h:439
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffffffff81a0e910)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (ffffffff81a12e1f)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff81a258f9)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffffffff81a45650)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (ffffffff81a49a0f)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff81a5c379)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffffffff81b3c3bc)
Location: include/net/addrconf.h:430
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_begin
```
```
In net/ipv6/route.c (0)
Location: include/net/addrconf.h:430
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff81b56940)
Location: include/net/addrconf.h:430
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffffffff81b4b0cc)
Location: include/net/addrconf.h:433
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_begin
```
```
In net/ipv6/route.c (0)
Location: include/net/addrconf.h:433
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff81b64fb0)
Location: include/net/addrconf.h:433
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffffffff81b31fad)
Location: include/net/addrconf.h:432
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_begin
```
```
In net/ipv6/route.c (0)
Location: include/net/addrconf.h:432
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff81b53299)
Location: include/net/addrconf.h:432
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffffffff81bf807d)
Location: include/net/addrconf.h:432
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_begin
```
```
In net/ipv6/route.c (0)
Location: include/net/addrconf.h:432
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff81c1a7a9)
Location: include/net/addrconf.h:432
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffffffff81d9142d)
Location: include/net/addrconf.h:437
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (0)
Location: include/net/addrconf.h:437
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff81db6cee)
Location: include/net/addrconf.h:437
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffffffff81f5fb8d)
Location: include/net/addrconf.h:437
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (0)
Location: include/net/addrconf.h:437
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff81f8698e)
Location: include/net/addrconf.h:437
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffffffff81fbf8bd)
Location: include/net/addrconf.h:437
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (0)
Location: include/net/addrconf.h:437
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff81fe6cce)
Location: include/net/addrconf.h:437
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffffffff8208cd5d)
Location: include/net/addrconf.h:445
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (0)
Location: include/net/addrconf.h:445
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff820b4b2e)
Location: include/net/addrconf.h:445
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffff800010d07e88)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (ffff800010d0ee44)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffff800010d21708)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (c0e0e5f8)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (c0e1327c)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (c0e26178)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (c000000000e32230)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (c000000000e3b74c)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (c000000000e50d54)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffffffe00084fed4)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (ffffffe000854174)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffe00086357a)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffffffff819e4ce0)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (ffffffff819e909f)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff819fba09)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffffffff819a1aa0)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (ffffffff819a5e5f)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff819b87c9)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffffffff81a4f760)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (ffffffff81a53b1f)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff81a66489)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
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
In net/ipv6/addrconf.c (ffffffff81a5b70d)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_work
```
```
In net/ipv6/route.c (ffffffff81a5fb0f)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_probe_deferred
```
```
In net/ipv6/ndisc.c (ffffffff81a72a69)
Location: include/net/addrconf.h:428
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_solicit
  - net/ipv6/ndisc.c:pndisc_destructor
  - net/ipv6/ndisc.c:pndisc_constructor
```
</details>
</li>
</ul>

## Differences
