# Function: <code>siphash_3u32</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff818f5fd0)
Location: lib/siphash.c:222
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
```
**Symbols:**

```
ffffffff818f5fd0-ffffffff818f61cb: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff8197c9d0)
Location: lib/siphash.c:222
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
```
**Symbols:**

```
ffffffff8197c9d0-ffffffff8197cbcb: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff819d8f50)
Location: lib/siphash.c:222
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
```
**Symbols:**

```
ffffffff819d8f50-ffffffff819d9146: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81a11170)
Location: lib/siphash.c:222
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
```
**Symbols:**

```
ffffffff81a11170-ffffffff81a11366: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81a806d0)
Location: lib/siphash.c:222
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/ipv4/route.c:__ip_select_ident
```
**Symbols:**

```
ffffffff81a806d0-ffffffff81a808c6: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81ab78d0)
Location: lib/siphash.c:222
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/ipv4/route.c:__ip_select_ident
```
**Symbols:**

```
ffffffff81ab78d0-ffffffff81ab7ac6: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff815f2520)
Location: lib/siphash.c:222
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/ipv4/route.c:__ip_select_ident
```
**Symbols:**

```
ffffffff815f2520-ffffffff815f2708: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81616bd0)
Location: lib/siphash.c:222
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/ipv4/route.c:__ip_select_ident
```
**Symbols:**

```
ffffffff81616bd0-ffffffff81616db8: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff815fa260)
Location: lib/siphash.c:222
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/ipv4/route.c:__ip_select_ident
```
**Symbols:**

```
ffffffff815fa260-ffffffff815fa44b: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81667b00)
Location: lib/siphash.c:222
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/ipv4/route.c:__ip_select_ident
```
**Symbols:**

```
ffffffff81667b00-ffffffff81667ceb: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81780fa0)
Location: lib/siphash.c:215
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/ipv4/route.c:__ip_select_ident
```
**Symbols:**

```
ffffffff81780fa0-ffffffff8178119d: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff8203dee0)
Location: lib/siphash.c:215
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/ipv4/route.c:__ip_select_ident
```
**Symbols:**

```
ffffffff8203dee0-ffffffff8203e0dd: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff820bc3e0)
Location: lib/siphash.c:215
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/ipv4/route.c:__ip_select_ident
```
**Symbols:**

```
ffffffff820bc3e0-ffffffff820bc5dd: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff82196ce0)
Location: lib/siphash.c:215
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/ipv4/route.c:__ip_select_ident
```
**Symbols:**

```
ffffffff82196ce0-ffffffff82196edd: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffff800010d91ee8)
Location: lib/siphash.c:222
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/ipv4/route.c:__ip_select_ident
```
**Symbols:**

```
ffff800010d91ee8-ffff800010d920a0: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (c0e8e1f4)
Location: lib/siphash.c:222
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/ipv4/route.c:__ip_select_ident
```
**Symbols:**

```
c0e8e1f4-c0e8e6c8: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (c000000000ed58c0)
Location: lib/siphash.c:222
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/ipv4/route.c:__ip_select_ident
```
**Symbols:**

```
c000000000ed58c0-c000000000ed5b0c: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffe0008bb99c)
Location: lib/siphash.c:222
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/ipv4/route.c:__ip_select_ident
```
**Symbols:**

```
ffffffe0008bb99c-ffffffe0008bbc78: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81a56720)
Location: lib/siphash.c:222
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/ipv4/route.c:__ip_select_ident
```
**Symbols:**

```
ffffffff81a56720-ffffffff81a56916: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81a13800)
Location: lib/siphash.c:222
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/ipv4/route.c:__ip_select_ident
```
**Symbols:**

```
ffffffff81a13800-ffffffff81a139f6: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81ac2b10)
Location: lib/siphash.c:222
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/ipv4/route.c:__ip_select_ident
```
**Symbols:**

```
ffffffff81ac2b10-ffffffff81ac2d06: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 siphash_3u32(const u32 first, const u32 second, const u32 third, const siphash_key_t *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/siphash.c (ffffffff81acefe0)
Location: lib/siphash.c:222
Inline: False
Direct callers:
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_ipv4_port_ephemeral
  - net/core/secure_seq.c:secure_tcp_seq
  - net/ipv4/route.c:__ip_select_ident
```
**Symbols:**

```
ffffffff81acefe0-ffffffff81acf1d6: siphash_3u32 (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
