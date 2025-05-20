# Function: <code>mld_send_cr</code>

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
In net/ipv6/mcast.c (ffffffff817eb686)
Location: net/ipv6/mcast.c:1858
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
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
In net/ipv6/mcast.c (ffffffff81859ee6)
Location: net/ipv6/mcast.c:1857
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
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
In net/ipv6/mcast.c (ffffffff8188be36)
Location: net/ipv6/mcast.c:1881
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
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
In net/ipv6/mcast.c (ffffffff818b24e6)
Location: net/ipv6/mcast.c:1881
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
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
In net/ipv6/mcast.c (ffffffff81935051)
Location: net/ipv6/mcast.c:1886
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
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
In net/ipv6/mcast.c (ffffffff8198deb1)
Location: net/ipv6/mcast.c:1909
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
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
In net/ipv6/mcast.c (ffffffff819c44b1)
Location: net/ipv6/mcast.c:1909
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
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
In net/ipv6/mcast.c (ffffffff81a33525)
Location: net/ipv6/mcast.c:1908
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
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
In net/ipv6/mcast.c (ffffffff81a6a075)
Location: net/ipv6/mcast.c:1908
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mld_send_cr(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b620d0)
Location: net/ipv6/mcast.c:1905
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
```
**Symbols:**

```
ffffffff81b620d0-ffffffff81b623c0: mld_send_cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mld_send_cr(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b70910)
Location: net/ipv6/mcast.c:1905
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
```
**Symbols:**

```
ffffffff81b70910-ffffffff81b70c00: mld_send_cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mld_send_cr(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b5e8f0)
Location: net/ipv6/mcast.c:2055
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_work
```
**Symbols:**

```
ffffffff81b5e8f0-ffffffff81b5ebc5: mld_send_cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mld_send_cr(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81c26090)
Location: net/ipv6/mcast.c:2053
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_work
```
**Symbols:**

```
ffffffff81c26090-ffffffff81c26365: mld_send_cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mld_send_cr(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81dc3dd0)
Location: net/ipv6/mcast.c:2055
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_work
```
**Symbols:**

```
ffffffff81dc3dd0-ffffffff81dc40b7: mld_send_cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mld_send_cr(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81f93f20)
Location: net/ipv6/mcast.c:2055
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_work
```
**Symbols:**

```
ffffffff81f93f20-ffffffff81f94207: mld_send_cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mld_send_cr(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81ff48b0)
Location: net/ipv6/mcast.c:2055
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_work
```
**Symbols:**

```
ffffffff81ff48b0-ffffffff81ff4b8b: mld_send_cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mld_send_cr(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff820c2480)
Location: net/ipv6/mcast.c:2053
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_work
```
**Symbols:**

```
ffffffff820c2480-ffffffff820c275b: mld_send_cr (STB_LOCAL)
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
In net/ipv6/mcast.c (ffff800010d2fa08)
Location: net/ipv6/mcast.c:1908
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
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
In net/ipv6/mcast.c (c0e342a0)
Location: net/ipv6/mcast.c:1908
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
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
In net/ipv6/mcast.c (c000000000e633a0)
Location: net/ipv6/mcast.c:1908
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
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
In net/ipv6/mcast.c (ffffffe0008702b6)
Location: net/ipv6/mcast.c:1908
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
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
In net/ipv6/mcast.c (ffffffff81a09705)
Location: net/ipv6/mcast.c:1908
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
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
In net/ipv6/mcast.c (ffffffff819c64c5)
Location: net/ipv6/mcast.c:1908
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
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
In net/ipv6/mcast.c (ffffffff81a74185)
Location: net/ipv6/mcast.c:1908
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
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
In net/ipv6/mcast.c (ffffffff81a80805)
Location: net/ipv6/mcast.c:1908
Inline: True
Inline callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
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
