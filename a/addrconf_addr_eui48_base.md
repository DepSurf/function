# Function: <code>addrconf_addr_eui48_base</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8188d6cc)
Location: include/net/addrconf.h:112
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8190e73c)
Location: include/net/addrconf.h:111
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
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
In net/ipv6/addrconf.c (ffffffff81965899)
Location: include/net/addrconf.h:124
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
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
In net/ipv6/addrconf.c (ffffffff8199ad19)
Location: include/net/addrconf.h:125
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
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
In net/ipv6/addrconf.c (ffffffff81a06c54)
Location: include/net/addrconf.h:126
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
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
In net/ipv6/addrconf.c (ffffffff81a3d7c4)
Location: include/net/addrconf.h:126
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
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
In net/ipv6/addrconf.c (ffffffff81b32568)
Location: include/net/addrconf.h:127
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b41198)
Location: include/net/addrconf.h:130
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
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
In net/ipv6/addrconf.c (ffffffff81b2f0b5)
Location: include/net/addrconf.h:130
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
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
In net/ipv6/addrconf.c (ffffffff81bf53e5)
Location: include/net/addrconf.h:130
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
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
In net/ipv6/addrconf.c (ffffffff81d8e2b2)
Location: include/net/addrconf.h:132
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void addrconf_addr_eui48_base(u8 *eui, const const char * addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f5c570)
Location: include/net/addrconf.h:132
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
```
**Symbols:**

```
ffffffff81f5c570-ffffffff81f5c5a2: addrconf_addr_eui48_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void addrconf_addr_eui48_base(u8 *eui, const const char * addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fbc3c0)
Location: include/net/addrconf.h:132
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
```
**Symbols:**

```
ffffffff81fbc3c0-ffffffff81fbc3f0: addrconf_addr_eui48_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void addrconf_addr_eui48_base(u8 *eui, const const char * addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff820897f0)
Location: include/net/addrconf.h:140
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
```
**Symbols:**

```
ffffffff820897f0-ffffffff82089820: addrconf_addr_eui48_base (STB_LOCAL)
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
In net/ipv6/addrconf.c (ffff800010cfeb14)
Location: include/net/addrconf.h:126
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
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
In net/ipv6/addrconf.c (c0e06038)
Location: include/net/addrconf.h:126
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
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
In net/ipv6/addrconf.c (c000000000e268f0)
Location: include/net/addrconf.h:126
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
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
In net/ipv6/addrconf.c (ffffffe0008488cc)
Location: include/net/addrconf.h:126
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
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
In net/ipv6/addrconf.c (ffffffff819dce54)
Location: include/net/addrconf.h:126
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
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
In net/ipv6/addrconf.c (ffffffff81999c14)
Location: include/net/addrconf.h:126
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
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
In net/ipv6/addrconf.c (ffffffff81a478d4)
Location: include/net/addrconf.h:126
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
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
In net/ipv6/addrconf.c (ffffffff81a537d4)
Location: include/net/addrconf.h:126
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
