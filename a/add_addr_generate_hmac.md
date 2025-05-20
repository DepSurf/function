# Function: <code>add_addr_generate_hmac</code>

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
In net/mptcp/options.c (ffffffff81bb1623)
Location: net/mptcp/options.c:541
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options_addr
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
In net/mptcp/options.c (ffffffff81bc556b)
Location: net/mptcp/options.c:557
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 add_addr_generate_hmac(u64 key1, u64 key2, struct mptcp_addr_info *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bb4960)
Location: net/mptcp/options.c:590
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
**Symbols:**

```
ffffffff81bb4960-ffffffff81bb4a2b: add_addr_generate_hmac (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 add_addr_generate_hmac(u64 key1, u64 key2, struct mptcp_addr_info *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81c83250)
Location: net/mptcp/options.c:617
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
**Symbols:**

```
ffffffff81c83250-ffffffff81c833a2: add_addr_generate_hmac (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 add_addr_generate_hmac(u64 key1, u64 key2, struct mptcp_addr_info *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81e29180)
Location: net/mptcp/options.c:619
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
**Symbols:**

```
ffffffff81e29180-ffffffff81e29307: add_addr_generate_hmac (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 add_addr_generate_hmac(u64 key1, u64 key2, struct mptcp_addr_info *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff82000960)
Location: net/mptcp/options.c:624
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
**Symbols:**

```
ffffffff82000960-ffffffff82000ae7: add_addr_generate_hmac (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 add_addr_generate_hmac(u64 key1, u64 key2, struct mptcp_addr_info *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff8207cb10)
Location: net/mptcp/options.c:621
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
**Symbols:**

```
ffffffff8207cb10-ffffffff8207cc97: add_addr_generate_hmac (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 add_addr_generate_hmac(u64 key1, u64 key2, struct mptcp_addr_info *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff82152010)
Location: net/mptcp/options.c:622
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
**Symbols:**

```
ffffffff82152010-ffffffff82152197: add_addr_generate_hmac (STB_LOCAL)
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
