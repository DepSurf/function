# Function: <code>add_addr6_generate_hmac</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u64 add_addr6_generate_hmac(u64 key1, u64 key2, u8 addr_id, struct in6_addr *addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bb1366)
Location: net/mptcp/options.c:558
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
Direct callers:
  - net/mptcp/options.c:mptcp_established_options_addr
```
**Symbols:**

```
ffffffff81bb0940-ffffffff81bb09b0: add_addr6_generate_hmac (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u64 add_addr6_generate_hmac(u64 key1, u64 key2, u8 addr_id, struct in6_addr *addr, u16 port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bc53f6)
Location: net/mptcp/options.c:574
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
Direct callers:
  - net/mptcp/options.c:mptcp_established_options_add_addr
```
**Symbols:**

```
ffffffff81bc4230-ffffffff81bc42a4: add_addr6_generate_hmac (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<code>u16 port</code>
</li>
</ul>
</details>
</li>
</ul>
