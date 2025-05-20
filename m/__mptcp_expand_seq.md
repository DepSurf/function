# Function: <code>__mptcp_expand_seq</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u64 __mptcp_expand_seq(u64 old_seq, u64 cur_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bb5b12)
Location: net/mptcp/options.c:896
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff81bb5790-ffffffff81bb57db: __mptcp_expand_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u64 __mptcp_expand_seq(u64 old_seq, u64 cur_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81c8488a)
Location: net/mptcp/options.c:978
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff81c844a0-ffffffff81c844eb: __mptcp_expand_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u64 __mptcp_expand_seq(u64 old_seq, u64 cur_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81e29b80)
Location: net/mptcp/options.c:1004
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff81e2a700-ffffffff81e2a76a: __mptcp_expand_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u64 __mptcp_expand_seq(u64 old_seq, u64 cur_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff82001c80)
Location: net/mptcp/options.c:1013
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff82002870-ffffffff820028da: __mptcp_expand_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u64 __mptcp_expand_seq(u64 old_seq, u64 cur_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff8207e140)
Location: net/mptcp/options.c:1013
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff8207ea50-ffffffff8207eaba: __mptcp_expand_seq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u64 __mptcp_expand_seq(u64 old_seq, u64 cur_seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff82153630)
Location: net/mptcp/options.c:1015
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff82153f40-ffffffff82153faa: __mptcp_expand_seq (STB_GLOBAL)
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
