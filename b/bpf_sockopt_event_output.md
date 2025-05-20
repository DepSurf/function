# Function: <code>bpf_sockopt_event_output</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_sockopt_event_output(u64 bpf_sock, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d6550)
Location: net/core/filter.c:4073
Inline: False
```
**Symbols:**

```
ffffffff818d6550-ffffffff818d6592: bpf_sockopt_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_sockopt_event_output(u64 bpf_sock, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81923de0)
Location: net/core/filter.c:4210
Inline: False
```
**Symbols:**

```
ffffffff81923de0-ffffffff81923e1c: bpf_sockopt_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_sockopt_event_output(u64 bpf_sock, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819560f0)
Location: net/core/filter.c:4217
Inline: False
```
**Symbols:**

```
ffffffff819560f0-ffffffff8195612c: bpf_sockopt_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
u64 bpf_sockopt_event_output(u64 bpf_sock, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf7db0)
Location: net/core/filter.c:4217
Inline: False
```
**Symbols:**

```
ffff800010bf7db0-ffff800010bf7e24: bpf_sockopt_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_sockopt_event_output(u64 bpf_sock, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d1170c)
Location: net/core/filter.c:4217
Inline: False
```
**Symbols:**

```
c0d1170c-c0d1177c: bpf_sockopt_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_sockopt_event_output(u64 bpf_sock, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cde040)
Location: net/core/filter.c:4217
Inline: False
```
**Symbols:**

```
c000000000cde040-c000000000cde0a8: bpf_sockopt_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_sockopt_event_output(u64 bpf_sock, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe000779864)
Location: net/core/filter.c:4217
Inline: False
```
**Symbols:**

```
ffffffe000779864-ffffffe0007798c2: bpf_sockopt_event_output (STB_GLOBAL)
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
u64 bpf_sockopt_event_output(u64 bpf_sock, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f60c0)
Location: net/core/filter.c:4217
Inline: False
```
**Symbols:**

```
ffffffff818f60c0-ffffffff818f60fc: bpf_sockopt_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_sockopt_event_output(u64 bpf_sock, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818afef0)
Location: net/core/filter.c:4217
Inline: False
```
**Symbols:**

```
ffffffff818afef0-ffffffff818aff2c: bpf_sockopt_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_sockopt_event_output(u64 bpf_sock, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819470f0)
Location: net/core/filter.c:4217
Inline: False
```
**Symbols:**

```
ffffffff819470f0-ffffffff8194712c: bpf_sockopt_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_sockopt_event_output(u64 bpf_sock, u64 map, u64 flags, u64 data, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81968a00)
Location: net/core/filter.c:4217
Inline: False
```
**Symbols:**

```
ffffffff81968a00-ffffffff81968a3c: bpf_sockopt_event_output (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
