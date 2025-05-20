# Function: <code>nexthop_bucket_set_hw_flags</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nexthop_bucket_set_hw_flags(struct net *net, u32 id, u16 bucket_index, bool offload, bool trap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af3dc0)
Location: net/ipv4/nexthop.c:3630
Inline: False
```
**Symbols:**

```
ffffffff81af3dc0-ffffffff81af3e58: nexthop_bucket_set_hw_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void nexthop_bucket_set_hw_flags(struct net *net, u32 id, u16 bucket_index, bool offload, bool trap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3668
Inline: False
```
**Symbols:**

```
ffffffff81d3dc92-ffffffff81d3dce4: nexthop_bucket_set_hw_flags.cold (STB_LOCAL)
ffffffff81bb4450-ffffffff81bb451c: nexthop_bucket_set_hw_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void nexthop_bucket_set_hw_flags(struct net *net, u32 id, u16 bucket_index, bool offload, bool trap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3668
Inline: False
```
**Symbols:**

```
ffffffff81f0a562-ffffffff81f0a58c: nexthop_bucket_set_hw_flags.cold (STB_LOCAL)
ffffffff81d47e90-ffffffff81d47fa4: nexthop_bucket_set_hw_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void nexthop_bucket_set_hw_flags(struct net *net, u32 id, u16 bucket_index, bool offload, bool trap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3668
Inline: False
```
**Symbols:**

```
ffffffff820b1e17-ffffffff820b1e41: nexthop_bucket_set_hw_flags.cold (STB_LOCAL)
ffffffff81f113d0-ffffffff81f114e4: nexthop_bucket_set_hw_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void nexthop_bucket_set_hw_flags(struct net *net, u32 id, u16 bucket_index, bool offload, bool trap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3654
Inline: False
```
**Symbols:**

```
ffffffff82132fea-ffffffff82133014: nexthop_bucket_set_hw_flags.cold (STB_LOCAL)
ffffffff81f70fb0-ffffffff81f710c9: nexthop_bucket_set_hw_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void nexthop_bucket_set_hw_flags(struct net *net, u32 id, u16 bucket_index, bool offload, bool trap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/nexthop.c (0)
Location: net/ipv4/nexthop.c:3671
Inline: False
```
**Symbols:**

```
ffffffff82214999-ffffffff822149c3: nexthop_bucket_set_hw_flags.cold (STB_LOCAL)
ffffffff82037710-ffffffff82037829: nexthop_bucket_set_hw_flags (STB_GLOBAL)
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
