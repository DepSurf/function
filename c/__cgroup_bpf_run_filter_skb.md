# Function: <code>__cgroup_bpf_run_filter_skb</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811975d0)
Location: kernel/bpf/cgroup.c:170
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
```
**Symbols:**

```
ffffffff811975d0-ffffffff81197818: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8119f250)
Location: kernel/bpf/cgroup.c:170
Inline: True
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff8119f250-ffffffff8119f3d8: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811b2440)
Location: kernel/bpf/cgroup.c:446
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff811b2440-ffffffff811b261d: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811d1ad0)
Location: kernel/bpf/cgroup.c:499
Inline: False
Direct callers:
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff811d1ad0-ffffffff811d1c9a: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811e17f0)
Location: kernel/bpf/cgroup.c:550
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff811e17f0-ffffffff811e19ef: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f88d0)
Location: kernel/bpf/cgroup.c:616
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff811f88d0-ffffffff811f8c85: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81205900)
Location: kernel/bpf/cgroup.c:626
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81205900-ffffffff81205cb5: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122cb30)
Location: kernel/bpf/cgroup.c:963
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff8122cb30-ffffffff8122cd09: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81234fb0)
Location: kernel/bpf/cgroup.c:987
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81234fb0-ffffffff812351b8: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81239680)
Location: kernel/bpf/cgroup.c:987
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81239680-ffffffff81239b96: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (0)
Location: kernel/bpf/cgroup.c:1017
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81cb9747-ffffffff81cb976f: __cgroup_bpf_run_filter_skb.cold (STB_LOCAL)
ffffffff81273e90-ffffffff81274308: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (0)
Location: kernel/bpf/cgroup.c:1142
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81e6ab5d-ffffffff81e6ab83: __cgroup_bpf_run_filter_skb.cold (STB_LOCAL)
ffffffff812c20d0-ffffffff812c23ac: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (0)
Location: kernel/bpf/cgroup.c:1356
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff82061c1b-ffffffff82061c41: __cgroup_bpf_run_filter_skb.cold (STB_LOCAL)
ffffffff813268d0-ffffffff81326bac: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (0)
Location: kernel/bpf/cgroup.c:1356
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff820e1360-ffffffff820e1379: __cgroup_bpf_run_filter_skb.cold (STB_LOCAL)
ffffffff81356c20-ffffffff81356ef6: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (0)
Location: kernel/bpf/cgroup.c:1357
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff821bdd6f-ffffffff821bdd88: __cgroup_bpf_run_filter_skb.cold (STB_LOCAL)
ffffffff8137f750-ffffffff8137fa26: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
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
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028e860)
Location: kernel/bpf/cgroup.c:626
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffff80001028e860-ffff80001028ec28: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bda58)
Location: kernel/bpf/cgroup.c:626
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
c04bda58-c04bdf98: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c00000000033b0b0)
Location: kernel/bpf/cgroup.c:626
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
c00000000033b0b0-c00000000033b68c: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c1a26)
Location: kernel/bpf/cgroup.c:626
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffe0001c1a26-ffffffe0001c1e0c: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
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
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fdf20)
Location: kernel/bpf/cgroup.c:626
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff811fdf20-ffffffff811fe2d5: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f0c70)
Location: kernel/bpf/cgroup.c:626
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff811f0c70-ffffffff811f1025: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fbcf0)
Location: kernel/bpf/cgroup.c:626
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff811fbcf0-ffffffff811fc0a5: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __cgroup_bpf_run_filter_skb(struct sock *sk, struct sk_buff *skb, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8120a8d0)
Location: kernel/bpf/cgroup.c:626
Inline: False
Direct callers:
  - net/core/filter.c:sk_filter_trim_cap
  - net/ipv4/ip_output.c:ip_mc_finish_output
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff8120a8d0-ffffffff8120acd0: __cgroup_bpf_run_filter_skb (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum cgroup_bpf_attach_type atype</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_attach_type type</code>
</li>
</ul>
</details>
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
