# Function: <code>cpu_map_generic_redirect</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpu_map_generic_redirect(struct bpf_cpu_map_entry *rcpu, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8126e620)
Location: kernel/bpf/cpumap.c:765
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff8126e620-ffffffff8126e75e: cpu_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpu_map_generic_redirect(struct bpf_cpu_map_entry *rcpu, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff812bd530)
Location: kernel/bpf/cpumap.c:761
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff812bd530-ffffffff812bd687: cpu_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpu_map_generic_redirect(struct bpf_cpu_map_entry *rcpu, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff813209d0)
Location: kernel/bpf/cpumap.c:760
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff813209d0-ffffffff81320b22: cpu_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpu_map_generic_redirect(struct bpf_cpu_map_entry *rcpu, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81350880)
Location: kernel/bpf/cpumap.c:781
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81350880-ffffffff813509d2: cpu_map_generic_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpu_map_generic_redirect(struct bpf_cpu_map_entry *rcpu, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81377cb0)
Location: kernel/bpf/cpumap.c:735
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_generic_redirect
```
**Symbols:**

```
ffffffff81377cb0-ffffffff81377e02: cpu_map_generic_redirect (STB_GLOBAL)
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
