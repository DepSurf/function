# Function: <code>bpf_skb_change_tail</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cb480)
Location: net/core/filter.c:2146
Inline: False
```
**Symbols:**

```
ffffffff817cb480-ffffffff817cb709: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817eac90)
Location: net/core/filter.c:2303
Inline: False
```
**Symbols:**

```
ffffffff817eac90-ffffffff817eaef9: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81867740)
Location: net/core/filter.c:2368
Inline: False
```
**Symbols:**

```
ffffffff81867740-ffffffff818679db: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b6bd0)
Location: net/core/filter.c:2950
Inline: False
```
**Symbols:**

```
ffffffff818b6bd0-ffffffff818b6e0a: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818dc9a0)
Location: net/core/filter.c:3138
Inline: False
```
**Symbols:**

```
ffffffff818dc9a0-ffffffff818dcc5a: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:3273
Inline: False
```
**Symbols:**

```
ffffffff8192da22-ffffffff8192da56: bpf_skb_change_tail.cold (STB_LOCAL)
ffffffff81929b00-ffffffff81929dcc: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81958030)
Location: net/core/filter.c:3275
Inline: False
```
**Symbols:**

```
ffffffff81958030-ffffffff8195824b: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2ef50)
Location: net/core/filter.c:3317
Inline: False
```
**Symbols:**

```
ffffffff81a2ef50-ffffffff81a2f166: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a31290)
Location: net/core/filter.c:3724
Inline: False
```
**Symbols:**

```
ffffffff81a31290-ffffffff81a3147d: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a192b0)
Location: net/core/filter.c:3725
Inline: False
```
**Symbols:**

```
ffffffff81a192b0-ffffffff81a192fa: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac79f0)
Location: net/core/filter.c:3694
Inline: False
```
**Symbols:**

```
ffffffff81ac79f0-ffffffff81ac7a3a: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c45080)
Location: net/core/filter.c:3695
Inline: False
```
**Symbols:**

```
ffffffff81c45080-ffffffff81c450d6: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df91e0)
Location: net/core/filter.c:3705
Inline: False
```
**Symbols:**

```
ffffffff81df91e0-ffffffff81df9236: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6ab70)
Location: net/core/filter.c:3750
Inline: False
```
**Symbols:**

```
ffffffff81e6ab70-ffffffff81e6abc6: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f29b00)
Location: net/core/filter.c:3784
Inline: False
```
**Symbols:**

```
ffffffff81f29b00-ffffffff81f29b56: bpf_skb_change_tail (STB_GLOBAL)
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
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfd1b0)
Location: net/core/filter.c:3275
Inline: False
```
**Symbols:**

```
ffff800010bfd1b0-ffff800010bfd420: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d16250)
Location: net/core/filter.c:3275
Inline: False
```
**Symbols:**

```
c0d16250-c0d164ec: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce56e0)
Location: net/core/filter.c:3275
Inline: False
```
**Symbols:**

```
c000000000ce56e0-c000000000ce5ac0: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077fbb6)
Location: net/core/filter.c:3275
Inline: False
```
**Symbols:**

```
ffffffe00077fbb6-ffffffe00077fd9c: bpf_skb_change_tail (STB_GLOBAL)
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
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f8000)
Location: net/core/filter.c:3275
Inline: False
```
**Symbols:**

```
ffffffff818f8000-ffffffff818f821b: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b1e30)
Location: net/core/filter.c:3275
Inline: False
```
**Symbols:**

```
ffffffff818b1e30-ffffffff818b204b: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81949030)
Location: net/core/filter.c:3275
Inline: False
```
**Symbols:**

```
ffffffff81949030-ffffffff8194924b: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_skb_change_tail(u64 skb, u64 new_len, u64 flags, u64 __ur_1, u64 __ur_2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196a940)
Location: net/core/filter.c:3275
Inline: False
```
**Symbols:**

```
ffffffff8196a940-ffffffff8196ab5b: bpf_skb_change_tail (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
