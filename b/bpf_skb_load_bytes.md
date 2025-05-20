# Function: <code>bpf_skb_load_bytes</code>

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
u64 bpf_skb_load_bytes(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179d510)
Location: net/core/filter.c:1416
Inline: False
```
**Symbols:**

```
ffffffff8179d510-ffffffff8179d589: bpf_skb_load_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cad20)
Location: net/core/filter.c:1424
Inline: False
```
**Symbols:**

```
ffffffff817cad20-ffffffff817cad99: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e9e00)
Location: net/core/filter.c:1449
Inline: False
```
**Symbols:**

```
ffffffff817e9e00-ffffffff817e9e7b: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81865490)
Location: net/core/filter.c:1470
Inline: False
```
**Symbols:**

```
ffffffff81865490-ffffffff8186550b: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b2db0)
Location: net/core/filter.c:1682
Inline: False
```
**Symbols:**

```
ffffffff818b2db0-ffffffff818b2e2b: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d9820)
Location: net/core/filter.c:1701
Inline: False
```
**Symbols:**

```
ffffffff818d9820-ffffffff818d9895: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81927550)
Location: net/core/filter.c:1701
Inline: False
```
**Symbols:**

```
ffffffff81927550-ffffffff819275c5: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81959c10)
Location: net/core/filter.c:1701
Inline: False
```
**Symbols:**

```
ffffffff81959c10-ffffffff81959c85: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2ce00)
Location: net/core/filter.c:1690
Inline: False
```
**Symbols:**

```
ffffffff81a2ce00-ffffffff81a2ce75: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2e3b0)
Location: net/core/filter.c:1720
Inline: False
```
**Symbols:**

```
ffffffff81a2e3b0-ffffffff81a2e425: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a15930)
Location: net/core/filter.c:1720
Inline: False
```
**Symbols:**

```
ffffffff81a15930-ffffffff81a159a9: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac6ba0)
Location: net/core/filter.c:1721
Inline: False
```
**Symbols:**

```
ffffffff81ac6ba0-ffffffff81ac6c19: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c425e0)
Location: net/core/filter.c:1722
Inline: False
```
**Symbols:**

```
ffffffff81c425e0-ffffffff81c42673: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df7c20)
Location: net/core/filter.c:1724
Inline: False
```
**Symbols:**

```
ffffffff81df7c20-ffffffff81df7cb3: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6a260)
Location: net/core/filter.c:1730
Inline: False
```
**Symbols:**

```
ffffffff81e6a260-ffffffff81e6a2f3: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f29180)
Location: net/core/filter.c:1737
Inline: False
```
**Symbols:**

```
ffffffff81f29180-ffffffff81f29213: bpf_skb_load_bytes (STB_GLOBAL)
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
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfb820)
Location: net/core/filter.c:1701
Inline: False
```
**Symbols:**

```
ffff800010bfb820-ffff800010bfb8e4: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d156e8)
Location: net/core/filter.c:1701
Inline: False
```
**Symbols:**

```
c0d156e8-c0d15794: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce3c80)
Location: net/core/filter.c:1701
Inline: False
```
**Symbols:**

```
c000000000ce3c80-c000000000ce3d78: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077d766)
Location: net/core/filter.c:1701
Inline: False
```
**Symbols:**

```
ffffffe00077d766-ffffffe00077d812: bpf_skb_load_bytes (STB_GLOBAL)
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
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f9be0)
Location: net/core/filter.c:1701
Inline: False
```
**Symbols:**

```
ffffffff818f9be0-ffffffff818f9c55: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b3a10)
Location: net/core/filter.c:1701
Inline: False
```
**Symbols:**

```
ffffffff818b3a10-ffffffff818b3a85: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194ac10)
Location: net/core/filter.c:1701
Inline: False
```
**Symbols:**

```
ffffffff8194ac10-ffffffff8194ac85: bpf_skb_load_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_skb_load_bytes(u64 skb, u64 offset, u64 to, u64 len, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196c520)
Location: net/core/filter.c:1701
Inline: False
```
**Symbols:**

```
ffffffff8196c520-ffffffff8196c595: bpf_skb_load_bytes (STB_GLOBAL)
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
<code>u64 skb</code>
</li>
<li>
<b>Param added. </b>
<code>u64 offset</code>
</li>
<li>
<b>Param added. </b>
<code>u64 to</code>
</li>
<li>
<b>Param added. </b>
<code>u64 len</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
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
