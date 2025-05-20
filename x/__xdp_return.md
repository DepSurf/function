# Function: <code>__xdp_return</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818ba830)
Location: net/core/xdp.c:310
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
ffffffff818ba830-ffffffff818bab92: __xdp_return (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818e1760)
Location: net/core/xdp.c:324
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
ffffffff818e1760-ffffffff818e1b09: __xdp_return (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81930150)
Location: net/core/xdp.c:393
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
ffffffff81930150-ffffffff8193058f: __xdp_return (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff819623b0)
Location: net/core/xdp.c:367
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
ffffffff819623b0-ffffffff819626e8: __xdp_return (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a35d60)
Location: net/core/xdp.c:342
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
ffffffff81a35d60-ffffffff81a35ed3: __xdp_return (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, struct xdp_buff *xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a37c50)
Location: net/core/xdp.c:341
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
ffffffff81a37c50-ffffffff81a37dc0: __xdp_return (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, struct xdp_buff *xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a1ede0)
Location: net/core/xdp.c:341
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
ffffffff81a1ede0-ffffffff81a1ef54: __xdp_return (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, struct xdp_buff *xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81ad2e80)
Location: net/core/xdp.c:342
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
ffffffff81ad2e80-ffffffff81ad2ff4: __xdp_return (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81c517a0)
Location: net/core/xdp.c:375
Inline: False
Direct callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
ffffffff81c517a0-ffffffff81c51b05: __xdp_return (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e06c70)
Location: net/core/xdp.c:375
Inline: False
Direct callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
ffffffff81e06c70-ffffffff81e06eb4: __xdp_return (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e795b0)
Location: net/core/xdp.c:377
Inline: False
Direct callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
ffffffff81e795b0-ffffffff81e797f7: __xdp_return (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81f39640)
Location: net/core/xdp.c:377
Inline: False
Direct callers:
  - net/core/filter.c:bpf_xdp_frags_shrink_tail
  - net/core/filter.c:bpf_xdp_frags_shrink_tail
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:xdp_return_buff
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
ffffffff81f39640-ffffffff81f3991c: __xdp_return (STB_GLOBAL)
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
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffff800010c06cd8)
Location: net/core/xdp.c:367
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
ffff800010c06cd8-ffff800010c06fc4: __xdp_return (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c0d20008)
Location: net/core/xdp.c:367
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
c0d20008-c0d201e0: __xdp_return (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c000000000cf1410)
Location: net/core/xdp.c:367
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
c000000000cf1410-c000000000cf1864: __xdp_return (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffe000785134)
Location: net/core/xdp.c:367
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
ffffffe000785134-ffffffe0007853c2: __xdp_return (STB_LOCAL)
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
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81902380)
Location: net/core/xdp.c:367
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
ffffffff81902380-ffffffff819026b8: __xdp_return (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818bc1b0)
Location: net/core/xdp.c:367
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
ffffffff818bc1b0-ffffffff818bc4e8: __xdp_return (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff819533b0)
Location: net/core/xdp.c:367
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
ffffffff819533b0-ffffffff819536e8: __xdp_return (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __xdp_return(void *data, struct xdp_mem_info *mem, bool napi_direct, long unsigned int handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81974ec0)
Location: net/core/xdp.c:367
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_convert_zc_to_xdp_frame
  - net/core/xdp.c:xdp_return_frame_rx_napi
  - net/core/xdp.c:xdp_return_frame
```
**Symbols:**

```
ffffffff81974ec0-ffffffff8197520f: __xdp_return (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int handle</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xdp_buff *xdp</code>
</li>
</ul>
</details>
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
