# Function: <code>addrconf_ifid_6lowpan</code>

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
In net/ipv6/addrconf.c (ffffffff8188d654)
Location: net/ipv6/addrconf.c:2095
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
In net/ipv6/addrconf.c (ffffffff8190e6c4)
Location: net/ipv6/addrconf.c:2119
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
In net/ipv6/addrconf.c (ffffffff81965816)
Location: net/ipv6/addrconf.c:2141
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
In net/ipv6/addrconf.c (ffffffff8199ac96)
Location: net/ipv6/addrconf.c:2157
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
In net/ipv6/addrconf.c (ffffffff81a06b87)
Location: net/ipv6/addrconf.c:2190
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
In net/ipv6/addrconf.c (ffffffff81a3d6f7)
Location: net/ipv6/addrconf.c:2192
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
In net/ipv6/addrconf.c (ffffffff81b32492)
Location: net/ipv6/addrconf.c:2183
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
In net/ipv6/addrconf.c (ffffffff81b410c2)
Location: net/ipv6/addrconf.c:2209
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
In net/ipv6/addrconf.c (ffffffff81b2efe5)
Location: net/ipv6/addrconf.c:2211
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
In net/ipv6/addrconf.c (ffffffff81bf5315)
Location: net/ipv6/addrconf.c:2218
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int addrconf_ifid_6lowpan(u8 *eui, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d8e150)
Location: net/ipv6/addrconf.c:2221
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
```
**Symbols:**

```
ffffffff81d8e150-ffffffff81d8e1d8: addrconf_ifid_6lowpan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int addrconf_ifid_6lowpan(u8 *eui, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f5c5c0)
Location: net/ipv6/addrconf.c:2221
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
```
**Symbols:**

```
ffffffff81f5c5c0-ffffffff81f5c648: addrconf_ifid_6lowpan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int addrconf_ifid_6lowpan(u8 *eui, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fbc400)
Location: net/ipv6/addrconf.c:2220
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
```
**Symbols:**

```
ffffffff81fbc400-ffffffff81fbc480: addrconf_ifid_6lowpan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int addrconf_ifid_6lowpan(u8 *eui, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff82089830)
Location: net/ipv6/addrconf.c:2248
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_generate_eui64
```
**Symbols:**

```
ffffffff82089830-ffffffff820898b0: addrconf_ifid_6lowpan (STB_LOCAL)
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
In net/ipv6/addrconf.c (ffff800010cfea38)
Location: net/ipv6/addrconf.c:2192
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
In net/ipv6/addrconf.c (c0e05f08)
Location: net/ipv6/addrconf.c:2192
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
In net/ipv6/addrconf.c (c000000000e268a0)
Location: net/ipv6/addrconf.c:2192
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
In net/ipv6/addrconf.c (ffffffe000848866)
Location: net/ipv6/addrconf.c:2192
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
In net/ipv6/addrconf.c (ffffffff819dcd87)
Location: net/ipv6/addrconf.c:2192
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
In net/ipv6/addrconf.c (ffffffff81999b47)
Location: net/ipv6/addrconf.c:2192
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
In net/ipv6/addrconf.c (ffffffff81a47807)
Location: net/ipv6/addrconf.c:2192
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
In net/ipv6/addrconf.c (ffffffff81a53707)
Location: net/ipv6/addrconf.c:2192
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
