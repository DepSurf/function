# Function: <code>bpf_get_stackid_tp</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81174160)
Location: kernel/trace/bpf_trace.c:473
Inline: False
```
**Symbols:**

```
ffffffff81174160-ffffffff8117416e: bpf_get_stackid_tp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8117fcd0)
Location: kernel/trace/bpf_trace.c:499
Inline: False
```
**Symbols:**

```
ffffffff8117fcd0-ffffffff8117fce3: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81182cd0)
Location: kernel/trace/bpf_trace.c:567
Inline: False
```
**Symbols:**

```
ffffffff81182cd0-ffffffff81182ce3: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81190760)
Location: kernel/trace/bpf_trace.c:616
Inline: False
```
**Symbols:**

```
ffffffff81190760-ffffffff81190773: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a5610)
Location: kernel/trace/bpf_trace.c:650
Inline: False
```
**Symbols:**

```
ffffffff811a5610-ffffffff811a5623: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b3730)
Location: kernel/trace/bpf_trace.c:686
Inline: False
```
**Symbols:**

```
ffffffff811b3730-ffffffff811b3743: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c2470)
Location: kernel/trace/bpf_trace.c:791
Inline: False
```
**Symbols:**

```
ffffffff811c2470-ffffffff811c2483: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811cdbe0)
Location: kernel/trace/bpf_trace.c:815
Inline: False
```
**Symbols:**

```
ffffffff811cdbe0-ffffffff811cdbf3: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e9860)
Location: kernel/trace/bpf_trace.c:1214
Inline: False
```
**Symbols:**

```
ffffffff811e9860-ffffffff811e9873: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e6d00)
Location: kernel/trace/bpf_trace.c:1443
Inline: False
```
**Symbols:**

```
ffffffff811e6d00-ffffffff811e6d13: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e7fa0)
Location: kernel/trace/bpf_trace.c:1137
Inline: False
```
**Symbols:**

```
ffffffff811e7fa0-ffffffff811e7fb3: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81218c20)
Location: kernel/trace/bpf_trace.c:1214
Inline: False
```
**Symbols:**

```
ffffffff81218c20-ffffffff81218c33: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81257130)
Location: kernel/trace/bpf_trace.c:1392
Inline: False
```
**Symbols:**

```
ffffffff81257130-ffffffff81257152: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a6420)
Location: kernel/trace/bpf_trace.c:1606
Inline: False
```
**Symbols:**

```
ffffffff812a6420-ffffffff812a6442: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c8620)
Location: kernel/trace/bpf_trace.c:1615
Inline: False
```
**Symbols:**

```
ffffffff812c8620-ffffffff812c8642: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e50b0)
Location: kernel/trace/bpf_trace.c:1720
Inline: False
```
**Symbols:**

```
ffffffff812e50b0-ffffffff812e50d2: bpf_get_stackid_tp (STB_GLOBAL)
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
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024cc68)
Location: kernel/trace/bpf_trace.c:815
Inline: False
```
**Symbols:**

```
ffff80001024cc68-ffff80001024cc88: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c048072c)
Location: kernel/trace/bpf_trace.c:815
Inline: False
```
**Symbols:**

```
c048072c-c048076c: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e9610)
Location: kernel/trace/bpf_trace.c:815
Inline: False
```
**Symbols:**

```
c0000000002e9610-c0000000002e9648: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c6200)
Location: kernel/trace/bpf_trace.c:815
Inline: False
```
**Symbols:**

```
ffffffff811c6200-ffffffff811c6213: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b8fe0)
Location: kernel/trace/bpf_trace.c:815
Inline: False
```
**Symbols:**

```
ffffffff811b8fe0-ffffffff811b8ff3: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c3fd0)
Location: kernel/trace/bpf_trace.c:815
Inline: False
```
**Symbols:**

```
ffffffff811c3fd0-ffffffff811c3fe3: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_get_stackid_tp(u64 tp_buff, u64 map, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d18b0)
Location: kernel/trace/bpf_trace.c:815
Inline: False
```
**Symbols:**

```
ffffffff811d18b0-ffffffff811d18c3: bpf_get_stackid_tp (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 tp_buff</code>
</li>
<li>
<b>Param added. </b>
<code>u64 map</code>
</li>
<li>
<b>Param added. </b>
<code>u64 flags</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r3</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r4</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r5</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
