# Function: <code>ipv6_rpl_addr_compress</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/rpl.c (ffffffff81b72afd)
Location: net/ipv6/rpl.c:21
Inline: True
Inline callers:
  - net/ipv6/rpl.c:ipv6_rpl_srh_compress
  - net/ipv6/rpl.c:ipv6_rpl_srh_compress
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
In net/ipv6/rpl.c (ffffffff81b8186d)
Location: net/ipv6/rpl.c:21
Inline: True
Inline callers:
  - net/ipv6/rpl.c:ipv6_rpl_srh_compress
  - net/ipv6/rpl.c:ipv6_rpl_srh_compress
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
In net/ipv6/rpl.c (ffffffff81b7047d)
Location: net/ipv6/rpl.c:21
Inline: True
Inline callers:
  - net/ipv6/rpl.c:ipv6_rpl_srh_compress
  - net/ipv6/rpl.c:ipv6_rpl_srh_compress
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
In net/ipv6/rpl.c (ffffffff81c3875d)
Location: net/ipv6/rpl.c:21
Inline: True
Inline callers:
  - net/ipv6/rpl.c:ipv6_rpl_srh_compress
  - net/ipv6/rpl.c:ipv6_rpl_srh_compress
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ipv6_rpl_addr_compress(void *dst, const struct in6_addr *addr, unsigned char pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/rpl.c (ffffffff81dd6180)
Location: net/ipv6/rpl.c:21
Inline: False
Direct callers:
  - net/ipv6/rpl.c:ipv6_rpl_srh_compress
  - net/ipv6/rpl.c:ipv6_rpl_srh_compress
```
**Symbols:**

```
ffffffff81dd6180-ffffffff81dd624b: ipv6_rpl_addr_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ipv6_rpl_addr_compress(void *dst, const struct in6_addr *addr, unsigned char pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/rpl.c (ffffffff81fa7a20)
Location: net/ipv6/rpl.c:21
Inline: False
Direct callers:
  - net/ipv6/rpl.c:ipv6_rpl_srh_compress
  - net/ipv6/rpl.c:ipv6_rpl_srh_compress
```
**Symbols:**

```
ffffffff81fa7a20-ffffffff81fa7aeb: ipv6_rpl_addr_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ipv6_rpl_addr_compress(void *dst, const struct in6_addr *addr, unsigned char pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/rpl.c (ffffffff82008250)
Location: net/ipv6/rpl.c:21
Inline: False
Direct callers:
  - net/ipv6/rpl.c:ipv6_rpl_srh_compress
  - net/ipv6/rpl.c:ipv6_rpl_srh_compress
```
**Symbols:**

```
ffffffff82008250-ffffffff820083a5: ipv6_rpl_addr_compress (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ipv6_rpl_addr_compress(void *dst, const struct in6_addr *addr, unsigned char pfx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/rpl.c (ffffffff820d7170)
Location: net/ipv6/rpl.c:21
Inline: False
Direct callers:
  - net/ipv6/rpl.c:ipv6_rpl_srh_compress
  - net/ipv6/rpl.c:ipv6_rpl_srh_compress
```
**Symbols:**

```
ffffffff820d7170-ffffffff820d72c5: ipv6_rpl_addr_compress (STB_LOCAL)
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
