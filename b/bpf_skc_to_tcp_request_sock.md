# Function: <code>bpf_skc_to_tcp_request_sock</code>

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
u64 bpf_skc_to_tcp_request_sock(u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a27d30)
Location: net/core/filter.c:10375
Inline: False
```
**Symbols:**

```
ffffffff81a27d30-ffffffff81a27d7e: bpf_skc_to_tcp_request_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_skc_to_tcp_request_sock(u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a0f0b0)
Location: net/core/filter.c:10517
Inline: False
```
**Symbols:**

```
ffffffff81a0f0b0-ffffffff81a0f0fe: bpf_skc_to_tcp_request_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_skc_to_tcp_request_sock(u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac1650)
Location: net/core/filter.c:10716
Inline: False
```
**Symbols:**

```
ffffffff81ac1650-ffffffff81ac169e: bpf_skc_to_tcp_request_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_skc_to_tcp_request_sock(u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3b980)
Location: net/core/filter.c:11244
Inline: False
```
**Symbols:**

```
ffffffff81c3b980-ffffffff81c3b9e2: bpf_skc_to_tcp_request_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_skc_to_tcp_request_sock(u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df02f0)
Location: net/core/filter.c:11450
Inline: False
```
**Symbols:**

```
ffffffff81df02f0-ffffffff81df0352: bpf_skc_to_tcp_request_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_skc_to_tcp_request_sock(u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e62040)
Location: net/core/filter.c:11599
Inline: False
```
**Symbols:**

```
ffffffff81e62040-ffffffff81e620a2: bpf_skc_to_tcp_request_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_skc_to_tcp_request_sock(u64 sk, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f21430)
Location: net/core/filter.c:11690
Inline: False
```
**Symbols:**

```
ffffffff81f21430-ffffffff81f21492: bpf_skc_to_tcp_request_sock (STB_GLOBAL)
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
