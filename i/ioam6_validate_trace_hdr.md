# Function: <code>ioam6_validate_trace_hdr</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ioam6_validate_trace_hdr(struct ioam6_trace_hdr *trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4bac0)
Location: net/ipv6/ioam6_iptunnel.c:73
Inline: False
Direct callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
**Symbols:**

```
ffffffff81c4bac0-ffffffff81c4bb88: ioam6_validate_trace_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ioam6_validate_trace_hdr(struct ioam6_trace_hdr *trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff81deb540)
Location: net/ipv6/ioam6_iptunnel.c:79
Inline: False
Direct callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
**Symbols:**

```
ffffffff81deb540-ffffffff81deb625: ioam6_validate_trace_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ioam6_validate_trace_hdr(struct ioam6_trace_hdr *trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbf180)
Location: net/ipv6/ioam6_iptunnel.c:79
Inline: False
Direct callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
**Symbols:**

```
ffffffff81fbf180-ffffffff81fbf265: ioam6_validate_trace_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ioam6_validate_trace_hdr(struct ioam6_trace_hdr *trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020110)
Location: net/ipv6/ioam6_iptunnel.c:79
Inline: False
Direct callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
**Symbols:**

```
ffffffff82020110-ffffffff820201f5: ioam6_validate_trace_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ioam6_validate_trace_hdr(struct ioam6_trace_hdr *trace);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff820ef240)
Location: net/ipv6/ioam6_iptunnel.c:79
Inline: False
Direct callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_build_state
```
**Symbols:**

```
ffffffff820ef240-ffffffff820ef325: ioam6_validate_trace_hdr (STB_LOCAL)
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
