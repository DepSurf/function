# Function: <code>ipv6_raw_deliver</code>

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
In net/ipv6/raw.c (ffffffff817e6ee4)
Location: net/ipv6/raw.c:158
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv6/raw.c (ffffffff8185528d)
Location: net/ipv6/raw.c:158
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv6/raw.c (ffffffff81886ffd)
Location: net/ipv6/raw.c:160
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv6/raw.c (ffffffff818ad5ae)
Location: net/ipv6/raw.c:160
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv6/raw.c (ffffffff819301ad)
Location: net/ipv6/raw.c:162
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv6/raw.c (ffffffff81988e52)
Location: net/ipv6/raw.c:162
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv6/raw.c (ffffffff819bf7b2)
Location: net/ipv6/raw.c:161
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv6/raw.c (ffffffff81a2e451)
Location: net/ipv6/raw.c:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv6/raw.c (ffffffff81a64fc1)
Location: net/ipv6/raw.c:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ipv6_raw_deliver(struct sk_buff *skb, int nexthdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81b5d8a0)
Location: net/ipv6/raw.c:157
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff81b5d8a0-ffffffff81b5db6f: ipv6_raw_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ipv6_raw_deliver(struct sk_buff *skb, int nexthdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81b6c090)
Location: net/ipv6/raw.c:157
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff81b6c090-ffffffff81b6c33f: ipv6_raw_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ipv6_raw_deliver(struct sk_buff *skb, int nexthdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81b5a3b0)
Location: net/ipv6/raw.c:157
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff81b5a3b0-ffffffff81b5a687: ipv6_raw_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ipv6_raw_deliver(struct sk_buff *skb, int nexthdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81c21a30)
Location: net/ipv6/raw.c:157
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff81c21a30-ffffffff81c21d07: ipv6_raw_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ipv6_raw_deliver(struct sk_buff *skb, int nexthdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81dbe8e0)
Location: net/ipv6/raw.c:141
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff81dbe8e0-ffffffff81dbeb59: ipv6_raw_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ipv6_raw_deliver(struct sk_buff *skb, int nexthdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81f8edd0)
Location: net/ipv6/raw.c:141
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff81f8edd0-ffffffff81f8f049: ipv6_raw_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ipv6_raw_deliver(struct sk_buff *skb, int nexthdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff81fef610)
Location: net/ipv6/raw.c:141
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff81fef610-ffffffff81fef84f: ipv6_raw_deliver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ipv6_raw_deliver(struct sk_buff *skb, int nexthdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/raw.c (ffffffff820bd1e0)
Location: net/ipv6/raw.c:141
Inline: False
Direct callers:
  - net/ipv6/raw.c:raw6_local_deliver
```
**Symbols:**

```
ffffffff820bd1e0-ffffffff820bd41f: ipv6_raw_deliver (STB_LOCAL)
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
In net/ipv6/raw.c (ffff800010d2ae48)
Location: net/ipv6/raw.c:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv6/raw.c (c0e2ede8)
Location: net/ipv6/raw.c:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv6/raw.c (c000000000e5c18c)
Location: net/ipv6/raw.c:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv6/raw.c (ffffffe00086b452)
Location: net/ipv6/raw.c:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv6/raw.c (ffffffff81a04651)
Location: net/ipv6/raw.c:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv6/raw.c (ffffffff819c1411)
Location: net/ipv6/raw.c:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv6/raw.c (ffffffff81a6f0d1)
Location: net/ipv6/raw.c:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
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
In net/ipv6/raw.c (ffffffff81a7b701)
Location: net/ipv6/raw.c:157
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_local_deliver
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
