# Function: <code>icmp_ndo_send</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void icmp_ndo_send(struct sk_buff *skb_in, int type, int code, __be32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81adc9a0)
Location: net/ipv4/icmp.c:753
Inline: False
```
**Symbols:**

```
ffffffff81adc9a0-ffffffff81adcaf7: icmp_ndo_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void icmp_ndo_send(struct sk_buff *skb_in, int type, int code, __be32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81ae96c0)
Location: net/ipv4/icmp.c:775
Inline: False
```
**Symbols:**

```
ffffffff81ae96c0-ffffffff81ae983b: icmp_ndo_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void icmp_ndo_send(struct sk_buff *skb_in, int type, int code, __be32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81ad4d80)
Location: net/ipv4/icmp.c:782
Inline: False
```
**Symbols:**

```
ffffffff81ad4d80-ffffffff81ad4efb: icmp_ndo_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void icmp_ndo_send(struct sk_buff *skb_in, int type, int code, __be32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81b93c30)
Location: net/ipv4/icmp.c:782
Inline: False
```
**Symbols:**

```
ffffffff81b93c30-ffffffff81b93dab: icmp_ndo_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void icmp_ndo_send(struct sk_buff *skb_in, int type, int code, __be32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81d24b20)
Location: net/ipv4/icmp.c:775
Inline: False
```
**Symbols:**

```
ffffffff81d24b20-ffffffff81d24c9f: icmp_ndo_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void icmp_ndo_send(struct sk_buff *skb_in, int type, int code, __be32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81eec310)
Location: net/ipv4/icmp.c:775
Inline: False
```
**Symbols:**

```
ffffffff81eec310-ffffffff81eec48f: icmp_ndo_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void icmp_ndo_send(struct sk_buff *skb_in, int type, int code, __be32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff81f4c100)
Location: net/ipv4/icmp.c:783
Inline: False
```
**Symbols:**

```
ffffffff81f4c100-ffffffff81f4c27f: icmp_ndo_send (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void icmp_ndo_send(struct sk_buff *skb_in, int type, int code, __be32 info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/icmp.c (ffffffff82012210)
Location: net/ipv4/icmp.c:783
Inline: False
```
**Symbols:**

```
ffffffff82012210-ffffffff8201238f: icmp_ndo_send (STB_GLOBAL)
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
