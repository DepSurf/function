# Function: <code>mptcp_parse_option</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void mptcp_parse_option(const struct sk_buff *skb, const unsigned char *ptr, int opsize, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:20
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_get_options
```
**Symbols:**

```
ffffffff81bb0370-ffffffff81bb093a: mptcp_parse_option (STB_LOCAL)
ffffffff81bb19d7-ffffffff81bb19ec: mptcp_parse_option.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void mptcp_parse_option(const struct sk_buff *skb, const unsigned char *ptr, int opsize, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (0)
Location: net/mptcp/options.c:21
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_get_options
```
**Symbols:**

```
ffffffff81bc3c20-ffffffff81bc4230: mptcp_parse_option (STB_LOCAL)
ffffffff81c33f2f-ffffffff81c33f44: mptcp_parse_option.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_parse_option(const struct sk_buff *skb, const unsigned char *ptr, int opsize, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bb4280)
Location: net/mptcp/options.c:23
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_get_options
```
**Symbols:**

```
ffffffff81bb4280-ffffffff81bb4951: mptcp_parse_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_parse_option(const struct sk_buff *skb, const unsigned char *ptr, int opsize, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81c82a50)
Location: net/mptcp/options.c:23
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_get_options
```
**Symbols:**

```
ffffffff81c82a50-ffffffff81c8324e: mptcp_parse_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_parse_option(const struct sk_buff *skb, const unsigned char *ptr, int opsize, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81e28910)
Location: net/mptcp/options.c:23
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_get_options
```
**Symbols:**

```
ffffffff81e28910-ffffffff81e29171: mptcp_parse_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_parse_option(const struct sk_buff *skb, const unsigned char *ptr, int opsize, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff82000b00)
Location: net/mptcp/options.c:23
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_get_options
```
**Symbols:**

```
ffffffff82000b00-ffffffff8200134a: mptcp_parse_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_parse_option(const struct sk_buff *skb, const unsigned char *ptr, int opsize, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff8207ccb0)
Location: net/mptcp/options.c:23
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_get_options
```
**Symbols:**

```
ffffffff8207ccb0-ffffffff8207d4d1: mptcp_parse_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_parse_option(const struct sk_buff *skb, const unsigned char *ptr, int opsize, struct mptcp_options_received *mp_opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff821521b0)
Location: net/mptcp/options.c:23
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_get_options
```
**Symbols:**

```
ffffffff821521b0-ffffffff821529cb: mptcp_parse_option (STB_LOCAL)
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
