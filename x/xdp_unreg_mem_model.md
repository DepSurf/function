# Function: <code>xdp_unreg_mem_model</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xdp_unreg_mem_model(struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81c514c0)
Location: net/core/xdp.c:113
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_rxq_info_reg
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81c514c0-ffffffff81c515d6: xdp_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xdp_unreg_mem_model(struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e05e80)
Location: net/core/xdp.c:113
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_rxq_info_reg
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81e05e80-ffffffff81e05efb: xdp_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xdp_unreg_mem_model(struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e78a70)
Location: net/core/xdp.c:115
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_rxq_info_reg
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81e78a70-ffffffff81e78b5a: xdp_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xdp_unreg_mem_model(struct xdp_mem_info *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81f38940)
Location: net/core/xdp.c:115
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_rxq_info_reg
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81f38940-ffffffff81f38a2a: xdp_unreg_mem_model (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
