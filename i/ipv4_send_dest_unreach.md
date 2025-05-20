# Function: <code>ipv4_send_dest_unreach</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81971c18)
Location: net/ipv4/route.c:1195
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
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
In net/ipv4/route.c (ffffffff819a86e8)
Location: net/ipv4/route.c:1197
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ipv4_send_dest_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a91d70)
Location: net/ipv4/route.c:1201
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
```
**Symbols:**

```
ffffffff81a91d70-ffffffff81a91edf: ipv4_send_dest_unreach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ipv4_send_dest_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9bc00)
Location: net/ipv4/route.c:1207
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
```
**Symbols:**

```
ffffffff81a9bc00-ffffffff81a9bd7c: ipv4_send_dest_unreach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ipv4_send_dest_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a86c70)
Location: net/ipv4/route.c:1193
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
```
**Symbols:**

```
ffffffff81a86c70-ffffffff81a86ded: ipv4_send_dest_unreach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ipv4_send_dest_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b41430)
Location: net/ipv4/route.c:1208
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
```
**Symbols:**

```
ffffffff81b41430-ffffffff81b415ad: ipv4_send_dest_unreach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ipv4_send_dest_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81ccde20)
Location: net/ipv4/route.c:1214
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
```
**Symbols:**

```
ffffffff81ccde20-ffffffff81ccdfbb: ipv4_send_dest_unreach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ipv4_send_dest_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e8ddc0)
Location: net/ipv4/route.c:1214
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
```
**Symbols:**

```
ffffffff81e8ddc0-ffffffff81e8df5b: ipv4_send_dest_unreach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ipv4_send_dest_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81eec500)
Location: net/ipv4/route.c:1214
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
```
**Symbols:**

```
ffffffff81eec500-ffffffff81eec69b: ipv4_send_dest_unreach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ipv4_send_dest_unreach(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb0550)
Location: net/ipv4/route.c:1214
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_link_failure
```
**Symbols:**

```
ffffffff81fb0550-ffffffff81fb0700: ipv4_send_dest_unreach (STB_LOCAL)
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
In net/ipv4/route.c (ffff800010c57ffc)
Location: net/ipv4/route.c:1197
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
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
In net/ipv4/route.c (c0d67c00)
Location: net/ipv4/route.c:1197
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
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
In net/ipv4/route.c (c000000000d59918)
Location: net/ipv4/route.c:1197
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
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
In net/ipv4/route.c (ffffffe0007c227e)
Location: net/ipv4/route.c:1197
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
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
In net/ipv4/route.c (ffffffff81948558)
Location: net/ipv4/route.c:1197
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
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
In net/ipv4/route.c (ffffffff81902048)
Location: net/ipv4/route.c:1197
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
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
In net/ipv4/route.c (ffffffff819b2d28)
Location: net/ipv4/route.c:1197
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
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
In net/ipv4/route.c (ffffffff819bc3ea)
Location: net/ipv4/route.c:1197
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_link_failure
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
