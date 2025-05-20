# Function: <code>__bpf_offload_dev_match</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811df230)
Location: kernel/bpf/offload.c:510
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
ffffffff811df230-ffffffff811df296: __bpf_offload_dev_match.isra.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f4bf0)
Location: kernel/bpf/offload.c:546
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
ffffffff811f4bf0-ffffffff811f4c53: __bpf_offload_dev_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81201c00)
Location: kernel/bpf/offload.c:546
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
ffffffff81201c00-ffffffff81201c63: __bpf_offload_dev_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81229070)
Location: kernel/bpf/offload.c:546
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
ffffffff81229070-ffffffff812290d7: __bpf_offload_dev_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81230b10)
Location: kernel/bpf/offload.c:546
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
ffffffff81230b10-ffffffff81230b7a: __bpf_offload_dev_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81234cc0)
Location: kernel/bpf/offload.c:546
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
ffffffff81234cc0-ffffffff81234d2a: __bpf_offload_dev_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff8126edfe)
Location: kernel/bpf/offload.c:546
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
ffffffff8126edd0-ffffffff8126ee59: __bpf_offload_dev_match (STB_LOCAL)
ffffffff81cb9661-ffffffff81cb967c: __bpf_offload_dev_match.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812bde1e)
Location: kernel/bpf/offload.c:546
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
ffffffff812bddf0-ffffffff812bde91: __bpf_offload_dev_match (STB_LOCAL)
ffffffff81e6aa85-ffffffff81e6aaa0: __bpf_offload_dev_match.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff8132137e)
Location: kernel/bpf/offload.c:543
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
ffffffff81321350-ffffffff813213f1: __bpf_offload_dev_match (STB_LOCAL)
ffffffff82061b1a-ffffffff82061b35: __bpf_offload_dev_match.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81350fde)
Location: kernel/bpf/offload.c:684
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
ffffffff81350fb0-ffffffff81351051: __bpf_offload_dev_match (STB_LOCAL)
ffffffff820e1186-ffffffff820e11a1: __bpf_offload_dev_match.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff8137843e)
Location: kernel/bpf/offload.c:694
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
ffffffff81378410-ffffffff813784b1: __bpf_offload_dev_match (STB_LOCAL)
ffffffff821bd9e5-ffffffff821bda00: __bpf_offload_dev_match.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffff80001028a760)
Location: kernel/bpf/offload.c:546
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
ffff80001028a760-ffff80001028a7f0: __bpf_offload_dev_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __bpf_offload_dev_match(struct bpf_prog *prog, struct net_device *netdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c04b95b4)
Location: kernel/bpf/offload.c:546
Inline: False
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
c04b95b4-c04b9648: __bpf_offload_dev_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (c000000000336290)
Location: kernel/bpf/offload.c:546
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
c000000000336290-c00000000033635c: __bpf_offload_dev_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffe0001be774)
Location: kernel/bpf/offload.c:546
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
ffffffe0001be774-ffffffe0001be7e2: __bpf_offload_dev_match.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811fa220)
Location: kernel/bpf/offload.c:546
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
ffffffff811fa220-ffffffff811fa283: __bpf_offload_dev_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811ecf70)
Location: kernel/bpf/offload.c:546
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
ffffffff811ecf70-ffffffff811ecfd3: __bpf_offload_dev_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f7ff0)
Location: kernel/bpf/offload.c:546
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
ffffffff811f7ff0-ffffffff811f8053: __bpf_offload_dev_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812069a0)
Location: kernel/bpf/offload.c:546
Inline: True
Direct callers:
  - kernel/bpf/offload.c:bpf_offload_prog_map_match
  - kernel/bpf/offload.c:bpf_offload_dev_match
```
**Symbols:**

```
ffffffff812069a0-ffffffff81206c9a: __bpf_offload_dev_match.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
