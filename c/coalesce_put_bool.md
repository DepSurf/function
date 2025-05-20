# Function: <code>coalesce_put_bool</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/coalesce.c (ffffffff81a8b6ef)
Location: net/ethtool/coalesce.c:137
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/coalesce.c (ffffffff81a94dbf)
Location: net/ethtool/coalesce.c:114
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/coalesce.c (ffffffff81a7e81d)
Location: net/ethtool/coalesce.c:114
Inline: True
Inline callers:
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool coalesce_put_bool(struct sk_buff *skb, u16 attr_type, u32 val, u32 supported_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/coalesce.c (ffffffff81b387c0)
Location: net/ethtool/coalesce.c:119
Inline: False
Direct callers:
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
```
**Symbols:**

```
ffffffff81b387c0-ffffffff81b38828: coalesce_put_bool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool coalesce_put_bool(struct sk_buff *skb, u16 attr_type, u32 val, u32 supported_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/coalesce.c (ffffffff81cc4430)
Location: net/ethtool/coalesce.c:119
Inline: False
Direct callers:
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
```
**Symbols:**

```
ffffffff81cc4430-ffffffff81cc44ac: coalesce_put_bool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool coalesce_put_bool(struct sk_buff *skb, u16 attr_type, u32 val, u32 supported_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/coalesce.c (ffffffff81e838b0)
Location: net/ethtool/coalesce.c:119
Inline: False
Direct callers:
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
```
**Symbols:**

```
ffffffff81e838b0-ffffffff81e8392c: coalesce_put_bool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool coalesce_put_bool(struct sk_buff *skb, u16 attr_type, u32 val, u32 supported_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/coalesce.c (ffffffff81edffe0)
Location: net/ethtool/coalesce.c:122
Inline: False
Direct callers:
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
```
**Symbols:**

```
ffffffff81edffe0-ffffffff81ee005c: coalesce_put_bool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool coalesce_put_bool(struct sk_buff *skb, u16 attr_type, u32 val, u32 supported_params);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/coalesce.c (ffffffff81fa3e80)
Location: net/ethtool/coalesce.c:122
Inline: False
Direct callers:
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
  - net/ethtool/coalesce.c:coalesce_fill_reply
```
**Symbols:**

```
ffffffff81fa3e80-ffffffff81fa3efc: coalesce_put_bool (STB_LOCAL)
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
