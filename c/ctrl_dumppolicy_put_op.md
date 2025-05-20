# Function: <code>ctrl_dumppolicy_put_op</code>

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
int ctrl_dumppolicy_put_op(struct sk_buff *skb, struct netlink_callback *cb, struct genl_ops *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a857c0)
Location: net/netlink/genetlink.c:1212
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81a857c0-ffffffff81a859ab: ctrl_dumppolicy_put_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ctrl_dumppolicy_put_op(struct sk_buff *skb, struct netlink_callback *cb, struct genl_ops *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81a6f160)
Location: net/netlink/genetlink.c:1212
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81a6f160-ffffffff81a6f34a: ctrl_dumppolicy_put_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ctrl_dumppolicy_put_op(struct sk_buff *skb, struct netlink_callback *cb, struct genl_ops *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81b27f00)
Location: net/netlink/genetlink.c:1204
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81b27f00-ffffffff81b280ea: ctrl_dumppolicy_put_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ctrl_dumppolicy_put_op(struct sk_buff *skb, struct netlink_callback *cb, struct genl_ops *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81cb0ec0)
Location: net/netlink/genetlink.c:1208
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81cb0ec0-ffffffff81cb10b2: ctrl_dumppolicy_put_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ctrl_dumppolicy_put_op(struct sk_buff *skb, struct netlink_callback *cb, struct genl_split_ops *doit, struct genl_split_ops *dumpit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81e6ee50)
Location: net/netlink/genetlink.c:1508
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81e6ee50-ffffffff81e6f031: ctrl_dumppolicy_put_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ctrl_dumppolicy_put_op(struct sk_buff *skb, struct netlink_callback *cb, struct genl_split_ops *doit, struct genl_split_ops *dumpit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81ecaf60)
Location: net/netlink/genetlink.c:1510
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81ecaf60-ffffffff81ecb141: ctrl_dumppolicy_put_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ctrl_dumppolicy_put_op(struct sk_buff *skb, struct netlink_callback *cb, struct genl_split_ops *doit, struct genl_split_ops *dumpit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81f8e450)
Location: net/netlink/genetlink.c:1649
Inline: False
Direct callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy
  - net/netlink/genetlink.c:ctrl_dumppolicy
```
**Symbols:**

```
ffffffff81f8e450-ffffffff81f8e631: ctrl_dumppolicy_put_op (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct genl_split_ops *doit</code>
</li>
<li>
<b>Param added. </b>
<code>struct genl_split_ops *dumpit</code>
</li>
<li>
<b>Param removed. </b>
<code>struct genl_ops *op</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
