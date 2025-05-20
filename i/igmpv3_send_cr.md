# Function: <code>igmpv3_send_cr</code>

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
In net/ipv4/igmp.c (ffffffff81798106)
Location: net/ipv4/igmp.c:600
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
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
In net/ipv4/igmp.c (ffffffff81805146)
Location: net/ipv4/igmp.c:595
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
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
In net/ipv4/igmp.c (ffffffff81836116)
Location: net/ipv4/igmp.c:610
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
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
In net/ipv4/igmp.c (ffffffff81857616)
Location: net/ipv4/igmp.c:610
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
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
In net/ipv4/igmp.c (ffffffff818d7821)
Location: net/ipv4/igmp.c:638
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
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
In net/ipv4/igmp.c (ffffffff8192e9c1)
Location: net/ipv4/igmp.c:638
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
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
In net/ipv4/igmp.c (ffffffff8195de24)
Location: net/ipv4/igmp.c:635
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
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
In net/ipv4/igmp.c (ffffffff819c31d4)
Location: net/ipv4/igmp.c:651
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
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
In net/ipv4/igmp.c (ffffffff819f9d74)
Location: net/ipv4/igmp.c:651
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void igmpv3_send_cr(struct in_device *in_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae6270)
Location: net/ipv4/igmp.c:649
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
**Symbols:**

```
ffffffff81ae6270-ffffffff81ae6583: igmpv3_send_cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void igmpv3_send_cr(struct in_device *in_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81af3140)
Location: net/ipv4/igmp.c:649
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
**Symbols:**

```
ffffffff81af3140-ffffffff81af345d: igmpv3_send_cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void igmpv3_send_cr(struct in_device *in_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ade900)
Location: net/ipv4/igmp.c:649
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
**Symbols:**

```
ffffffff81ade900-ffffffff81adec1c: igmpv3_send_cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void igmpv3_send_cr(struct in_device *in_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81b9dde0)
Location: net/ipv4/igmp.c:649
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
**Symbols:**

```
ffffffff81b9dde0-ffffffff81b9e0fc: igmpv3_send_cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void igmpv3_send_cr(struct in_device *in_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81d30080)
Location: net/ipv4/igmp.c:650
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
**Symbols:**

```
ffffffff81d30080-ffffffff81d303ac: igmpv3_send_cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void igmpv3_send_cr(struct in_device *in_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ef81a0)
Location: net/ipv4/igmp.c:650
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
**Symbols:**

```
ffffffff81ef81a0-ffffffff81ef84cc: igmpv3_send_cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void igmpv3_send_cr(struct in_device *in_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81f57c10)
Location: net/ipv4/igmp.c:651
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
**Symbols:**

```
ffffffff81f57c10-ffffffff81f57f3c: igmpv3_send_cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void igmpv3_send_cr(struct in_device *in_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8201e0c0)
Location: net/ipv4/igmp.c:653
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
**Symbols:**

```
ffffffff8201e0c0-ffffffff8201e3ec: igmpv3_send_cr (STB_LOCAL)
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
In net/ipv4/igmp.c (ffff800010caea44)
Location: net/ipv4/igmp.c:651
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
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
In net/ipv4/igmp.c (c0dbc544)
Location: net/ipv4/igmp.c:651
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
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
In net/ipv4/igmp.c (c000000000dc64bc)
Location: net/ipv4/igmp.c:651
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
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
In net/ipv4/igmp.c (ffffffe000808c70)
Location: net/ipv4/igmp.c:651
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
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
In net/ipv4/igmp.c (ffffffff81999b14)
Location: net/ipv4/igmp.c:651
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
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
In net/ipv4/igmp.c (ffffffff819535d4)
Location: net/ipv4/igmp.c:651
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
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
In net/ipv4/igmp.c (ffffffff81a043b4)
Location: net/ipv4/igmp.c:651
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
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
In net/ipv4/igmp.c (ffffffff81a0e928)
Location: net/ipv4/igmp.c:651
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
