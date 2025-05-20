# Function: <code>__xdp_release_frame</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __xdp_release_frame(void *data, struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff8192ffe0)
Location: net/core/xdp.c:455
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff8192ffe0-ffffffff8193014d: __xdp_release_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __xdp_release_frame(void *data, struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81962240)
Location: net/core/xdp.c:422
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff81962240-ffffffff819623ad: __xdp_release_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __xdp_release_frame(void *data, struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a36390)
Location: net/core/xdp.c:389
Inline: False
```
**Symbols:**

```
ffffffff81a36390-ffffffff81a364ba: __xdp_release_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __xdp_release_frame(void *data, struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a38270)
Location: net/core/xdp.c:447
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_build_skb
```
**Symbols:**

```
ffffffff81a38270-ffffffff81a382e8: __xdp_release_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __xdp_release_frame(void *data, struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a1f870)
Location: net/core/xdp.c:448
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
**Symbols:**

```
ffffffff81a1f870-ffffffff81a1f8e9: __xdp_release_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __xdp_release_frame(void *data, struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81ad3830)
Location: net/core/xdp.c:449
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
**Symbols:**

```
ffffffff81ad3830-ffffffff81ad38a9: __xdp_release_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __xdp_release_frame(void *data, struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81c510c0)
Location: net/core/xdp.c:535
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
**Symbols:**

```
ffffffff81c510c0-ffffffff81c5123d: __xdp_release_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __xdp_release_frame(void *data, struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e06910)
Location: net/core/xdp.c:533
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
**Symbols:**

```
ffffffff81e06910-ffffffff81e069c7: __xdp_release_frame (STB_GLOBAL)
```
</details>
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
void __xdp_release_frame(void *data, struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffff800010c06500)
Location: net/core/xdp.c:422
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffff800010c06500-ffff800010c0666c: __xdp_release_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __xdp_release_frame(void *data, struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c0d1f5b4)
Location: net/core/xdp.c:422
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
c0d1f5b4-c0d1f744: __xdp_release_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __xdp_release_frame(void *data, struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c000000000cf09b0)
Location: net/core/xdp.c:422
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
c000000000cf09b0-c000000000cf0b90: __xdp_release_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __xdp_release_frame(void *data, struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffe000784ab0)
Location: net/core/xdp.c:422
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffe000784ab0-ffffffe000784bea: __xdp_release_frame (STB_GLOBAL)
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
void __xdp_release_frame(void *data, struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81902210)
Location: net/core/xdp.c:422
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff81902210-ffffffff8190237d: __xdp_release_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __xdp_release_frame(void *data, struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818bc040)
Location: net/core/xdp.c:422
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff818bc040-ffffffff818bc1ad: __xdp_release_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __xdp_release_frame(void *data, struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81953240)
Location: net/core/xdp.c:422
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff81953240-ffffffff819533ad: __xdp_release_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __xdp_release_frame(void *data, struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81974d40)
Location: net/core/xdp.c:422
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff81974d40-ffffffff81974eba: __xdp_release_frame (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
