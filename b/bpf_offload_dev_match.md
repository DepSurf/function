# Function: <code>bpf_offload_dev_match</code>

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
bool bpf_offload_dev_match(struct bpf_prog *prog, struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811cc1f0)
Location: kernel/bpf/offload.c:471
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811cc1f0-ffffffff811cc269: bpf_offload_dev_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811df2a0)
Location: kernel/bpf/offload.c:531
Inline: False
```
**Symbols:**

```
ffffffff811df2a0-ffffffff811df2e0: bpf_offload_dev_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f4c60)
Location: kernel/bpf/offload.c:567
Inline: False
```
**Symbols:**

```
ffffffff811f4c60-ffffffff811f4ca1: bpf_offload_dev_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81201c70)
Location: kernel/bpf/offload.c:567
Inline: False
```
**Symbols:**

```
ffffffff81201c70-ffffffff81201cb1: bpf_offload_dev_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812290e0)
Location: kernel/bpf/offload.c:567
Inline: False
```
**Symbols:**

```
ffffffff812290e0-ffffffff81229122: bpf_offload_dev_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81230b80)
Location: kernel/bpf/offload.c:567
Inline: False
```
**Symbols:**

```
ffffffff81230b80-ffffffff81230bc2: bpf_offload_dev_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81234d30)
Location: kernel/bpf/offload.c:567
Inline: False
```
**Symbols:**

```
ffffffff81234d30-ffffffff81234d72: bpf_offload_dev_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff8126ee60)
Location: kernel/bpf/offload.c:567
Inline: False
```
**Symbols:**

```
ffffffff8126ee60-ffffffff8126eea2: bpf_offload_dev_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812bdea0)
Location: kernel/bpf/offload.c:567
Inline: False
```
**Symbols:**

```
ffffffff812bdea0-ffffffff812bdee6: bpf_offload_dev_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81321410)
Location: kernel/bpf/offload.c:564
Inline: False
```
**Symbols:**

```
ffffffff81321410-ffffffff81321456: bpf_offload_dev_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81351070)
Location: kernel/bpf/offload.c:705
Inline: False
Direct callers:
  - net/core/dev.c:dev_xdp_attach
```
**Symbols:**

```
ffffffff81351070-ffffffff813510b6: bpf_offload_dev_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff813784d0)
Location: kernel/bpf/offload.c:715
Inline: False
Direct callers:
  - net/core/dev.c:dev_xdp_attach
```
**Symbols:**

```
ffffffff813784d0-ffffffff81378516: bpf_offload_dev_match (STB_GLOBAL)
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
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffff80001028a7f0)
Location: kernel/bpf/offload.c:567
Inline: False
```
**Symbols:**

```
ffff80001028a7f0-ffff80001028a84c: bpf_offload_dev_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c04b9648)
Location: kernel/bpf/offload.c:567
Inline: False
```
**Symbols:**

```
c04b9648-c04b9694: bpf_offload_dev_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c000000000336360)
Location: kernel/bpf/offload.c:567
Inline: False
```
**Symbols:**

```
c000000000336360-c0000000003363d8: bpf_offload_dev_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffe0001be7e2)
Location: kernel/bpf/offload.c:567
Inline: False
```
**Symbols:**

```
ffffffe0001be7e2-ffffffe0001be838: bpf_offload_dev_match (STB_GLOBAL)
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
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811fa290)
Location: kernel/bpf/offload.c:567
Inline: False
```
**Symbols:**

```
ffffffff811fa290-ffffffff811fa2d1: bpf_offload_dev_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811ecfe0)
Location: kernel/bpf/offload.c:567
Inline: False
```
**Symbols:**

```
ffffffff811ecfe0-ffffffff811ed021: bpf_offload_dev_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f8060)
Location: kernel/bpf/offload.c:567
Inline: False
```
**Symbols:**

```
ffffffff811f8060-ffffffff811f80a1: bpf_offload_dev_match (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81206ca0)
Location: kernel/bpf/offload.c:567
Inline: False
```
**Symbols:**

```
ffffffff81206ca0-ffffffff81206ce1: bpf_offload_dev_match (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net_device *netdev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_map *map</code>
</li>
</ul>
</details>
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
