# Function: <code>xfrm_state_mtu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff817bb290)
Location: net/xfrm/xfrm_state.c:1971
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
```
**Symbols:**

```
ffffffff817bb290-ffffffff817bb2f5: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff818281b0)
Location: net/xfrm/xfrm_state.c:1972
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff818281b0-ffffffff81828214: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81859bd0)
Location: net/xfrm/xfrm_state.c:2001
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff81859bd0-ffffffff81859c34: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff8187da00)
Location: net/xfrm/xfrm_state.c:2164
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff8187da00-ffffffff8187da34: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff818fe7d0)
Location: net/xfrm/xfrm_state.c:2193
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff818fe7d0-ffffffff818fe807: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81955270)
Location: net/xfrm/xfrm_state.c:2200
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
**Symbols:**

```
ffffffff81955270-ffffffff819552a7: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81989e80)
Location: net/xfrm/xfrm_state.c:2232
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
**Symbols:**

```
ffffffff81989e80-ffffffff81989eb7: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff819eebb0)
Location: net/xfrm/xfrm_state.c:2408
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
**Symbols:**

```
ffffffff819eebb0-ffffffff819eec6f: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81a25a90)
Location: net/xfrm/xfrm_state.c:2410
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
**Symbols:**

```
ffffffff81a25a90-ffffffff81a25b4f: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b17560)
Location: net/xfrm/xfrm_state.c:2413
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
**Symbols:**

```
ffffffff81b17560-ffffffff81b17620: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b25620)
Location: net/xfrm/xfrm_state.c:2522
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
**Symbols:**

```
ffffffff81b25620-ffffffff81b256e0: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b19640)
Location: net/xfrm/xfrm_state.c:2554
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
**Symbols:**

```
ffffffff81b19640-ffffffff81b1966f: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81bd7040)
Location: net/xfrm/xfrm_state.c:2581
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
**Symbols:**

```
ffffffff81bd7040-ffffffff81bd70fd: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81d6da00)
Location: net/xfrm/xfrm_state.c:2583
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
**Symbols:**

```
ffffffff81d6da00-ffffffff81d6dae1: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81f39000)
Location: net/xfrm/xfrm_state.c:2747
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
**Symbols:**

```
ffffffff81f39000-ffffffff81f390e1: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81f98890)
Location: net/xfrm/xfrm_state.c:2744
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
**Symbols:**

```
ffffffff81f98890-ffffffff81f98971: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff82065c00)
Location: net/xfrm/xfrm_state.c:2744
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
**Symbols:**

```
ffffffff82065c00-ffffffff82065ce1: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffff800010ce2f28)
Location: net/xfrm/xfrm_state.c:2410
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
**Symbols:**

```
ffff800010ce2f28-ffff800010ce3018: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (c0dec6e8)
Location: net/xfrm/xfrm_state.c:2410
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
**Symbols:**

```
c0dec6e8-c0dec7fc: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (c000000000e063f0)
Location: net/xfrm/xfrm_state.c:2410
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
**Symbols:**

```
c000000000e063f0-c000000000e064dc: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffe000831814)
Location: net/xfrm/xfrm_state.c:2410
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
**Symbols:**

```
ffffffe000831814-ffffffe0008318ca: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff819c5120)
Location: net/xfrm/xfrm_state.c:2410
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
**Symbols:**

```
ffffffff819c5120-ffffffff819c51df: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81981f10)
Location: net/xfrm/xfrm_state.c:2410
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
**Symbols:**

```
ffffffff81981f10-ffffffff81981fcf: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81a2fba0)
Location: net/xfrm/xfrm_state.c:2410
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
**Symbols:**

```
ffffffff81a2fba0-ffffffff81a2fc5f: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u32 xfrm_state_mtu(struct xfrm_state *x, int mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81a3b540)
Location: net/xfrm/xfrm_state.c:2410
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
**Symbols:**

```
ffffffff81a3b540-ffffffff81a3b5ff: xfrm_state_mtu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>u32</code>
</li>
</ul>
</details>
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
