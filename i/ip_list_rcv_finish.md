# Function: <code>ip_list_rcv_finish</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81915442)
Location: net/ipv4/ip_input.c:539
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
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
In net/ipv4/ip_input.c (ffffffff81977972)
Location: net/ipv4/ip_input.c:538
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
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
In net/ipv4/ip_input.c (ffffffff819ae302)
Location: net/ipv4/ip_input.c:538
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81a98110)
Location: net/ipv4/ip_input.c:563
Inline: True
Direct callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
**Symbols:**

```
ffffffff81a98110-ffffffff81a9829e: ip_list_rcv_finish.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/ip_input.c (ffffffff81aa2060)
Location: net/ipv4/ip_input.c:563
Inline: True
Direct callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
**Symbols:**

```
ffffffff81aa2060-ffffffff81aa21ee: ip_list_rcv_finish.constprop.0 (STB_LOCAL)
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
In net/ipv4/ip_input.c (ffffffff81a8d485)
Location: net/ipv4/ip_input.c:564
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
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
In net/ipv4/ip_input.c (ffffffff81b48645)
Location: net/ipv4/ip_input.c:564
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
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
In net/ipv4/ip_input.c (ffffffff81cd5a06)
Location: net/ipv4/ip_input.c:588
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
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
In net/ipv4/ip_input.c (ffffffff81e95e96)
Location: net/ipv4/ip_input.c:593
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
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
In net/ipv4/ip_input.c (ffffffff81ef46d6)
Location: net/ipv4/ip_input.c:593
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
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
In net/ipv4/ip_input.c (ffffffff81fb8656)
Location: net/ipv4/ip_input.c:594
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
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
In net/ipv4/ip_input.c (ffff800010c5e7fc)
Location: net/ipv4/ip_input.c:538
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
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
In net/ipv4/ip_input.c (c0d6deb4)
Location: net/ipv4/ip_input.c:538
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
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
In net/ipv4/ip_input.c (c000000000d61118)
Location: net/ipv4/ip_input.c:538
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
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
In net/ipv4/ip_input.c (ffffffe0007c6f02)
Location: net/ipv4/ip_input.c:538
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
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
In net/ipv4/ip_input.c (ffffffff8194e172)
Location: net/ipv4/ip_input.c:538
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
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
In net/ipv4/ip_input.c (ffffffff81907c62)
Location: net/ipv4/ip_input.c:538
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
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
In net/ipv4/ip_input.c (ffffffff819b8942)
Location: net/ipv4/ip_input.c:538
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
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
In net/ipv4/ip_input.c (ffffffff819c21bd)
Location: net/ipv4/ip_input.c:538
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_sublist_rcv
```
</details>
</li>
</ul>

## Differences
