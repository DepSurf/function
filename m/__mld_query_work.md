# Function: <code>__mld_query_work</code>

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
void __mld_query_work(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b60480)
Location: net/ipv6/mcast.c:1392
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_query_work
```
**Symbols:**

```
ffffffff81b60480-ffffffff81b60adc: __mld_query_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __mld_query_work(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:1393
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_query_work
```
**Symbols:**

```
ffffffff81c27d80-ffffffff81c2849b: __mld_query_work (STB_LOCAL)
ffffffff81d40a5b-ffffffff81d40a74: __mld_query_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __mld_query_work(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/mcast.c (0)
Location: net/ipv6/mcast.c:1393
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_query_work
```
**Symbols:**

```
ffffffff81dc5160-ffffffff81dc5874: __mld_query_work (STB_LOCAL)
ffffffff81f0d445-ffffffff81f0d45e: __mld_query_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __mld_query_work(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81f95cf0)
Location: net/ipv6/mcast.c:1393
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_query_work
```
**Symbols:**

```
ffffffff81f95cf0-ffffffff81f96412: __mld_query_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __mld_query_work(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81ff66c0)
Location: net/ipv6/mcast.c:1393
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_query_work
```
**Symbols:**

```
ffffffff81ff66c0-ffffffff81ff6de2: __mld_query_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __mld_query_work(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff820c4300)
Location: net/ipv6/mcast.c:1393
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_query_work
```
**Symbols:**

```
ffffffff820c4300-ffffffff820c4a22: __mld_query_work (STB_LOCAL)
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
