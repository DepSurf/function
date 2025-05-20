# Function: <code>ip_mc_dec_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ip_mc_dec_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81797b70)
Location: net/ipv4/igmp.c:1564
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_drop_socket
```
**Symbols:**

```
ffffffff81797b70-ffffffff81797c72: ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ip_mc_dec_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81805510)
Location: net/ipv4/igmp.c:1571
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff81805510-ffffffff81805612: ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ip_mc_dec_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff818364e0)
Location: net/ipv4/igmp.c:1602
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff818364e0-ffffffff818365e2: ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ip_mc_dec_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff818579d0)
Location: net/ipv4/igmp.c:1611
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff818579d0-ffffffff81857acf: ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ip_mc_dec_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff818d8020)
Location: net/ipv4/igmp.c:1639
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff818d8020-ffffffff818d811f: ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ip_mc_dec_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8192e1d0)
Location: net/ipv4/igmp.c:1650
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff8192e1d0-ffffffff8192e2e0: ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ip_mc_dec_group(struct in_device *in_dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8195cff0)
Location: net/ipv4/igmp.c:1659
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff8195cff0-ffffffff8195d100: ip_mc_dec_group (STB_GLOBAL)
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
In net/ipv4/igmp.c (ffffffff819c461d)
Location: include/linux/igmp.h:136
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
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
In net/ipv4/igmp.c (ffffffff819fb1bd)
Location: include/linux/igmp.h:136
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
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
In net/ipv4/igmp.c (ffffffff81ae9aed)
Location: include/linux/igmp.h:136
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
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
In net/ipv4/igmp.c (ffffffff81af698d)
Location: include/linux/igmp.h:136
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
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
In net/ipv4/igmp.c (ffffffff81ae20dd)
Location: include/linux/igmp.h:136
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
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
In net/ipv4/igmp.c (ffffffff81ba187d)
Location: include/linux/igmp.h:133
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
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
In net/ipv4/igmp.c (ffffffff81d33e5d)
Location: include/linux/igmp.h:133
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
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
In net/ipv4/igmp.c (ffffffff81efc2dd)
Location: include/linux/igmp.h:133
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
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
In net/ipv4/igmp.c (ffffffff81f5bd0a)
Location: include/linux/igmp.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
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
In net/ipv4/igmp.c (ffffffff8202226a)
Location: include/linux/igmp.h:134
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
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
In net/ipv4/igmp.c (ffff800010cb2d28)
Location: include/linux/igmp.h:136
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
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
In net/ipv4/igmp.c (c0dbe7d8)
Location: include/linux/igmp.h:136
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
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
In net/ipv4/igmp.c (c000000000dc9eac)
Location: include/linux/igmp.h:136
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
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
In net/ipv4/igmp.c (ffffffe00080b0fe)
Location: include/linux/igmp.h:136
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
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
In net/ipv4/igmp.c (ffffffff8199af5d)
Location: include/linux/igmp.h:136
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
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
In net/ipv4/igmp.c (ffffffff81954a1d)
Location: include/linux/igmp.h:136
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
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
In net/ipv4/igmp.c (ffffffff81a057fd)
Location: include/linux/igmp.h:136
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
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
In net/ipv4/igmp.c (ffffffff81a0fdcd)
Location: include/linux/igmp.h:136
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
