# Function: <code>netlink_policy_dump_write</code>

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
int netlink_policy_dump_write(struct sk_buff *skb, long unsigned int _state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81a7d950)
Location: net/netlink/policy.c:160
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81a7d950-ffffffff81a7decb: netlink_policy_dump_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netlink_policy_dump_write(struct sk_buff *skb, struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81a873a0)
Location: net/netlink/policy.c:411
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81a873a0-ffffffff81a87523: netlink_policy_dump_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netlink_policy_dump_write(struct sk_buff *skb, struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81a70470)
Location: net/netlink/policy.c:411
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81a70470-ffffffff81a705f1: netlink_policy_dump_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netlink_policy_dump_write(struct sk_buff *skb, struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81b29bc0)
Location: net/netlink/policy.c:411
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81b29bc0-ffffffff81b29d41: netlink_policy_dump_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netlink_policy_dump_write(struct sk_buff *skb, struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81cb2de0)
Location: net/netlink/policy.c:421
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81cb2de0-ffffffff81cb2f5d: netlink_policy_dump_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netlink_policy_dump_write(struct sk_buff *skb, struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81e70e80)
Location: net/netlink/policy.c:421
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81e70e80-ffffffff81e70ffd: netlink_policy_dump_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netlink_policy_dump_write(struct sk_buff *skb, struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81eccfa0)
Location: net/netlink/policy.c:421
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81eccfa0-ffffffff81ecd11d: netlink_policy_dump_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netlink_policy_dump_write(struct sk_buff *skb, struct netlink_policy_dump_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/policy.c (ffffffff81f907d0)
Location: net/netlink/policy.c:430
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81f907d0-ffffffff81f9094d: netlink_policy_dump_write (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_policy_dump_state *state</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int _state</code>
</li>
</ul>
</details>
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
