# Function: <code>nexthop_set_hw_flags</code>

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
void nexthop_set_hw_flags(struct net *net, u32 id, bool offload, bool trap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81b081e0)
Location: net/ipv4/nexthop.c:2192
Inline: False
```
**Symbols:**

```
ffffffff81b081e0-ffffffff81b08244: nexthop_set_hw_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nexthop_set_hw_flags(struct net *net, u32 id, bool offload, bool trap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af3d50)
Location: net/ipv4/nexthop.c:3609
Inline: False
```
**Symbols:**

```
ffffffff81af3d50-ffffffff81af3db1: nexthop_set_hw_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void nexthop_set_hw_flags(struct net *net, u32 id, bool offload, bool trap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb4190)
Location: net/ipv4/nexthop.c:3647
Inline: False
```
**Symbols:**

```
ffffffff81bb4190-ffffffff81bb41f1: nexthop_set_hw_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void nexthop_set_hw_flags(struct net *net, u32 id, bool offload, bool trap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d47aa0)
Location: net/ipv4/nexthop.c:3647
Inline: False
```
**Symbols:**

```
ffffffff81d47aa0-ffffffff81d47b48: nexthop_set_hw_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void nexthop_set_hw_flags(struct net *net, u32 id, bool offload, bool trap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f10f90)
Location: net/ipv4/nexthop.c:3647
Inline: False
```
**Symbols:**

```
ffffffff81f10f90-ffffffff81f11038: nexthop_set_hw_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void nexthop_set_hw_flags(struct net *net, u32 id, bool offload, bool trap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f70ab0)
Location: net/ipv4/nexthop.c:3633
Inline: False
```
**Symbols:**

```
ffffffff81f70ab0-ffffffff81f70b55: nexthop_set_hw_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void nexthop_set_hw_flags(struct net *net, u32 id, bool offload, bool trap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff82037210)
Location: net/ipv4/nexthop.c:3650
Inline: False
```
**Symbols:**

```
ffffffff82037210-ffffffff820372b5: nexthop_set_hw_flags (STB_GLOBAL)
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
