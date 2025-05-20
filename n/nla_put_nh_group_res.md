# Function: <code>nla_put_nh_group_res</code>

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
int nla_put_nh_group_res(struct sk_buff *skb, struct nh_group *nhg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81af6c00)
Location: net/ipv4/nexthop.c:628
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
**Symbols:**

```
ffffffff81af6c00-ffffffff81af6d79: nla_put_nh_group_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nla_put_nh_group_res(struct sk_buff *skb, struct nh_group *nhg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81bb6530)
Location: net/ipv4/nexthop.c:628
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
**Symbols:**

```
ffffffff81bb6530-ffffffff81bb66a9: nla_put_nh_group_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nla_put_nh_group_res(struct sk_buff *skb, struct nh_group *nhg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81d4a150)
Location: net/ipv4/nexthop.c:629
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
**Symbols:**

```
ffffffff81d4a150-ffffffff81d4a2da: nla_put_nh_group_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nla_put_nh_group_res(struct sk_buff *skb, struct nh_group *nhg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f137e0)
Location: net/ipv4/nexthop.c:629
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
**Symbols:**

```
ffffffff81f137e0-ffffffff81f1396a: nla_put_nh_group_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nla_put_nh_group_res(struct sk_buff *skb, struct nh_group *nhg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff81f734b0)
Location: net/ipv4/nexthop.c:629
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
**Symbols:**

```
ffffffff81f734b0-ffffffff81f7363a: nla_put_nh_group_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nla_put_nh_group_res(struct sk_buff *skb, struct nh_group *nhg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/nexthop.c (ffffffff82039ca0)
Location: net/ipv4/nexthop.c:629
Inline: False
Direct callers:
  - net/ipv4/nexthop.c:nh_fill_node
```
**Symbols:**

```
ffffffff82039ca0-ffffffff82039e2a: nla_put_nh_group_res (STB_LOCAL)
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
