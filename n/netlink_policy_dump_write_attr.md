# Function: <code>netlink_policy_dump_write_attr</code>

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
int netlink_policy_dump_write_attr(struct sk_buff *skb, const struct nla_policy *pt, int nestattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81a87380)
Location: net/netlink/policy.c:397
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_ack
```
**Symbols:**

```
ffffffff81a87380-ffffffff81a8739a: netlink_policy_dump_write_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netlink_policy_dump_write_attr(struct sk_buff *skb, const struct nla_policy *pt, int nestattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81a70450)
Location: net/netlink/policy.c:397
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_ack
```
**Symbols:**

```
ffffffff81a70450-ffffffff81a7046a: netlink_policy_dump_write_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netlink_policy_dump_write_attr(struct sk_buff *skb, const struct nla_policy *pt, int nestattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81b29ba0)
Location: net/netlink/policy.c:397
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_ack
```
**Symbols:**

```
ffffffff81b29ba0-ffffffff81b29bba: netlink_policy_dump_write_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netlink_policy_dump_write_attr(struct sk_buff *skb, const struct nla_policy *pt, int nestattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81cb2db0)
Location: net/netlink/policy.c:407
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_ack
```
**Symbols:**

```
ffffffff81cb2db0-ffffffff81cb2dd6: netlink_policy_dump_write_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netlink_policy_dump_write_attr(struct sk_buff *skb, const struct nla_policy *pt, int nestattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81e70e40)
Location: net/netlink/policy.c:407
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_ack_tlv_fill
```
**Symbols:**

```
ffffffff81e70e40-ffffffff81e70e66: netlink_policy_dump_write_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netlink_policy_dump_write_attr(struct sk_buff *skb, const struct nla_policy *pt, int nestattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81eccf60)
Location: net/netlink/policy.c:407
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_ack_tlv_fill
```
**Symbols:**

```
ffffffff81eccf60-ffffffff81eccf86: netlink_policy_dump_write_attr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netlink_policy_dump_write_attr(struct sk_buff *skb, const struct nla_policy *pt, int nestattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81f90790)
Location: net/netlink/policy.c:416
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_ack_tlv_fill
```
**Symbols:**

```
ffffffff81f90790-ffffffff81f907b6: netlink_policy_dump_write_attr (STB_GLOBAL)
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
