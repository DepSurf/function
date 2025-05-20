# Function: <code>bpf_ctx_narrow_access_ok</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81182279)
Location: include/linux/filter.h:600
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:pe_prog_is_valid_access
```
```
In net/core/filter.c (ffffffff817e7bca)
Location: include/linux/filter.h:600
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8118fc39)
Location: include/linux/filter.h:605
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:pe_prog_is_valid_access
```
```
In kernel/bpf/cgroup.c (ffffffff811b2648)
Location: include/linux/filter.h:605
Inline: True
```
```
In net/core/filter.c (ffffffff81862b27)
Location: include/linux/filter.h:605
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a4669)
Location: include/linux/filter.h:668
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:pe_prog_is_valid_access
```
```
In kernel/bpf/cgroup.c (ffffffff811d1cd8)
Location: include/linux/filter.h:668
Inline: True
```
```
In net/core/filter.c (ffffffff818aed1c)
Location: include/linux/filter.h:668
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
  - net/core/filter.c:sock_filter_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b37d9)
Location: include/linux/filter.h:690
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff811e1a20)
Location: include/linux/filter.h:690
Inline: True
```
```
In net/core/filter.c (ffffffff818d767a)
Location: include/linux/filter.h:690
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c2519)
Location: include/linux/filter.h:746
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff811f7ae0)
Location: include/linux/filter.h:746
Inline: True
```
```
In net/core/filter.c (ffffffff819201fc)
Location: include/linux/filter.h:746
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811cdc89)
Location: include/linux/filter.h:746
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff81204a80)
Location: include/linux/filter.h:746
Inline: True
```
```
In net/core/filter.c (ffffffff8195242c)
Location: include/linux/filter.h:746
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e99b4)
Location: include/linux/filter.h:777
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff8122c900)
Location: include/linux/filter.h:777
Inline: True
```
```
In net/core/filter.c (ffffffff81a2364c)
Location: include/linux/filter.h:777
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e6db4)
Location: include/linux/filter.h:786
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff81234d80)
Location: include/linux/filter.h:786
Inline: True
```
```
In net/core/filter.c (ffffffff81a23a2c)
Location: include/linux/filter.h:786
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e8054)
Location: include/linux/filter.h:829
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff812386f0)
Location: include/linux/filter.h:829
Inline: True
```
```
In net/core/filter.c (ffffffff81a0adf8)
Location: include/linux/filter.h:829
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81218cd4)
Location: include/linux/filter.h:850
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff81272cd0)
Location: include/linux/filter.h:850
Inline: True
```
```
In net/core/filter.c (ffffffff81abd148)
Location: include/linux/filter.h:850
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81255e36)
Location: include/linux/filter.h:853
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:pe_prog_is_valid_access
  - kernel/trace/bpf_trace.c:pe_prog_is_valid_access
```
```
In kernel/bpf/cgroup.c (ffffffff812c17a0)
Location: include/linux/filter.h:853
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_dev_is_valid_access
```
```
In net/core/filter.c (ffffffff81c37df9)
Location: include/linux/filter.h:853
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a5426)
Location: include/linux/filter.h:825
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:pe_prog_is_valid_access
  - kernel/trace/bpf_trace.c:pe_prog_is_valid_access
```
```
In kernel/bpf/cgroup.c (ffffffff81325e10)
Location: include/linux/filter.h:825
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_dev_is_valid_access
```
```
In net/core/filter.c (ffffffff81deb7c9)
Location: include/linux/filter.h:825
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c78d6)
Location: include/linux/filter.h:825
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:pe_prog_is_valid_access
  - kernel/trace/bpf_trace.c:pe_prog_is_valid_access
```
```
In kernel/bpf/cgroup.c (ffffffff81355fe0)
Location: include/linux/filter.h:825
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_dev_is_valid_access
```
```
In net/core/filter.c (ffffffff81e5cf7d)
Location: include/linux/filter.h:825
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e4256)
Location: include/linux/filter.h:859
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:pe_prog_is_valid_access
  - kernel/trace/bpf_trace.c:pe_prog_is_valid_access
```
```
In kernel/bpf/cgroup.c (ffffffff8137eb10)
Location: include/linux/filter.h:859
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_dev_is_valid_access
```
```
In net/core/filter.c (ffffffff81f1c36d)
Location: include/linux/filter.h:859
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024cd18)
Location: include/linux/filter.h:746
Inline: True
```
```
In kernel/bpf/cgroup.c (ffff80001028ceec)
Location: include/linux/filter.h:746
Inline: True
```
```
In net/core/filter.c (ffff800010bf47bc)
Location: include/linux/filter.h:746
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0480858)
Location: include/linux/filter.h:746
Inline: True
```
```
In kernel/bpf/cgroup.c (c04bce78)
Location: include/linux/filter.h:746
Inline: True
```
```
In net/core/filter.c (c0d0d008)
Location: include/linux/filter.h:746
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002e98a8)
Location: include/linux/filter.h:746
Inline: True
```
```
In kernel/bpf/cgroup.c (c0000000003395ac)
Location: include/linux/filter.h:746
Inline: True
```
```
In net/core/filter.c (c000000000cd98a8)
Location: include/linux/filter.h:746
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c0fc8)
Location: include/linux/filter.h:746
Inline: True
```
```
In net/core/filter.c (ffffffe000775b1c)
Location: include/linux/filter.h:746
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c62a9)
Location: include/linux/filter.h:746
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff811fd0a0)
Location: include/linux/filter.h:746
Inline: True
```
```
In net/core/filter.c (ffffffff818f23fc)
Location: include/linux/filter.h:746
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b9089)
Location: include/linux/filter.h:746
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff811efdf0)
Location: include/linux/filter.h:746
Inline: True
```
```
In net/core/filter.c (ffffffff818ac22c)
Location: include/linux/filter.h:746
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c4079)
Location: include/linux/filter.h:746
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff811fae70)
Location: include/linux/filter.h:746
Inline: True
```
```
In net/core/filter.c (ffffffff8194342c)
Location: include/linux/filter.h:746
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d1959)
Location: include/linux/filter.h:746
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff812099e0)
Location: include/linux/filter.h:746
Inline: True
```
```
In net/core/filter.c (ffffffff81964d1c)
Location: include/linux/filter.h:746
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
</ul>

## Differences
