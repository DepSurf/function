# Function: <code>ip_icmp_error_rfc4884_validate</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ip_icmp_error_rfc4884_validate(const struct sk_buff *skb, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81ae8b50)
Location: net/ipv4/icmp.c:1142
Inline: False
Direct callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
```
**Symbols:**

```
ffffffff81ae8b50-ffffffff81ae8c89: ip_icmp_error_rfc4884_validate (STB_LOCAL)
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
In net/ipv4/icmp.c (ffffffff81ad41ba)
Location: net/ipv4/icmp.c:1261
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
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
In net/ipv4/icmp.c (ffffffff81b92eaa)
Location: net/ipv4/icmp.c:1278
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
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
In net/ipv4/icmp.c (ffffffff81d250c8)
Location: net/ipv4/icmp.c:1284
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
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
In net/ipv4/icmp.c (ffffffff81eec6a8)
Location: net/ipv4/icmp.c:1284
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
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
In net/ipv4/icmp.c (ffffffff81f4c498)
Location: net/ipv4/icmp.c:1292
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
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
In net/ipv4/icmp.c (ffffffff820125a8)
Location: net/ipv4/icmp.c:1292
Inline: True
Inline callers:
  - net/ipv4/icmp.c:ip_icmp_error_rfc4884
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
