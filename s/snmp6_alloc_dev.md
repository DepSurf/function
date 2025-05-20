# Function: <code>snmp6_alloc_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817cbcae)
Location: net/ipv6/addrconf.c:299
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8183a2fb)
Location: net/ipv6/addrconf.c:301
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186bd27)
Location: net/ipv6/addrconf.c:333
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81890856)
Location: net/ipv6/addrconf.c:340
Inline: True
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
In net/ipv6/addrconf.c (ffffffff81911f9c)
Location: net/ipv6/addrconf.c:341
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
In net/ipv6/addrconf.c (ffffffff819693dc)
Location: net/ipv6/addrconf.c:332
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
In net/ipv6/addrconf.c (ffffffff8199ecb1)
Location: net/ipv6/addrconf.c:332
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
In net/ipv6/addrconf.c (ffffffff81a0ad93)
Location: net/ipv6/addrconf.c:329
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
In net/ipv6/addrconf.c (ffffffff81a41a43)
Location: net/ipv6/addrconf.c:329
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int snmp6_alloc_dev(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b33cd0)
Location: net/ipv6/addrconf.c:330
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
**Symbols:**

```
ffffffff81b33cd0-ffffffff81b33d89: snmp6_alloc_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int snmp6_alloc_dev(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b42840)
Location: net/ipv6/addrconf.c:330
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
**Symbols:**

```
ffffffff81b42840-ffffffff81b428f9: snmp6_alloc_dev (STB_LOCAL)
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
In net/ipv6/addrconf.c (ffffffff81b33fae)
Location: net/ipv6/addrconf.c:332
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
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
In net/ipv6/addrconf.c (ffffffff81bfa636)
Location: net/ipv6/addrconf.c:339
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
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
In net/ipv6/addrconf.c (ffffffff81d93a95)
Location: net/ipv6/addrconf.c:334
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int snmp6_alloc_dev(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f5e7b0)
Location: net/ipv6/addrconf.c:334
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
**Symbols:**

```
ffffffff81f5e7b0-ffffffff81f5e8b0: snmp6_alloc_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int snmp6_alloc_dev(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fbe250)
Location: net/ipv6/addrconf.c:333
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
**Symbols:**

```
ffffffff81fbe250-ffffffff81fbe350: snmp6_alloc_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int snmp6_alloc_dev(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8208b7d0)
Location: net/ipv6/addrconf.c:337
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_add_dev
```
**Symbols:**

```
ffffffff8208b7d0-ffffffff8208b903: snmp6_alloc_dev (STB_LOCAL)
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
In net/ipv6/addrconf.c (ffff800010d034cc)
Location: net/ipv6/addrconf.c:329
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
In net/ipv6/addrconf.c (c0e0a95c)
Location: net/ipv6/addrconf.c:329
Inline: True
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
In net/ipv6/addrconf.c (c000000000e2cf00)
Location: net/ipv6/addrconf.c:329
Inline: True
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
In net/ipv6/addrconf.c (ffffffe00084c79a)
Location: net/ipv6/addrconf.c:329
Inline: True
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
In net/ipv6/addrconf.c (ffffffff819e10d3)
Location: net/ipv6/addrconf.c:329
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
In net/ipv6/addrconf.c (ffffffff8199de93)
Location: net/ipv6/addrconf.c:329
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
In net/ipv6/addrconf.c (ffffffff81a4bb53)
Location: net/ipv6/addrconf.c:329
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
In net/ipv6/addrconf.c (ffffffff81a57ac3)
Location: net/ipv6/addrconf.c:329
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
