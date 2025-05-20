# Function: <code>bpf_ctx_record_field_size</code>

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
In kernel/trace/bpf_trace.c (ffffffff8118227c)
Location: include/linux/bpf.h:162
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:pe_prog_is_valid_access
```
```
In net/core/filter.c (ffffffff817e7bcd)
Location: include/linux/bpf.h:162
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
In kernel/trace/bpf_trace.c (ffffffff8118fc3c)
Location: include/linux/bpf.h:169
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:pe_prog_is_valid_access
```
```
In kernel/bpf/cgroup.c (ffffffff811b264a)
Location: include/linux/bpf.h:169
Inline: True
```
```
In net/core/filter.c (ffffffff81862b2a)
Location: include/linux/bpf.h:169
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
In kernel/trace/bpf_trace.c (ffffffff811a4661)
Location: include/linux/bpf.h:219
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:pe_prog_is_valid_access
```
```
In kernel/bpf/cgroup.c (ffffffff811d1cd0)
Location: include/linux/bpf.h:219
Inline: True
```
```
In net/core/filter.c (ffffffff818aed14)
Location: include/linux/bpf.h:219
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
In kernel/trace/bpf_trace.c (ffffffff811b37d1)
Location: include/linux/bpf.h:238
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff811e1a18)
Location: include/linux/bpf.h:238
Inline: True
```
```
In net/core/filter.c (ffffffff818d7673)
Location: include/linux/bpf.h:238
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
In kernel/trace/bpf_trace.c (ffffffff811c2511)
Location: include/linux/bpf.h:292
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff811f7ad8)
Location: include/linux/bpf.h:292
Inline: True
```
```
In net/core/filter.c (ffffffff819201a1)
Location: include/linux/bpf.h:292
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
In kernel/trace/bpf_trace.c (ffffffff811cdc81)
Location: include/linux/bpf.h:295
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff81204a78)
Location: include/linux/bpf.h:295
Inline: True
```
```
In net/core/filter.c (ffffffff819523d1)
Location: include/linux/bpf.h:295
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
In kernel/trace/bpf_trace.c (ffffffff811e99ac)
Location: include/linux/bpf.h:348
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff8122c8f8)
Location: include/linux/bpf.h:348
Inline: True
```
```
In net/core/filter.c (ffffffff81a23616)
Location: include/linux/bpf.h:348
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
In kernel/trace/bpf_trace.c (ffffffff811e6dac)
Location: include/linux/bpf.h:434
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff81234d78)
Location: include/linux/bpf.h:434
Inline: True
```
```
In net/core/filter.c (ffffffff81a239f6)
Location: include/linux/bpf.h:434
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
In kernel/trace/bpf_trace.c (ffffffff811e804c)
Location: include/linux/bpf.h:451
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff812386e8)
Location: include/linux/bpf.h:451
Inline: True
```
```
In net/core/filter.c (ffffffff81a0adc2)
Location: include/linux/bpf.h:451
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
In kernel/trace/bpf_trace.c (ffffffff81218ccc)
Location: include/linux/bpf.h:478
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff81272cc8)
Location: include/linux/bpf.h:478
Inline: True
```
```
In net/core/filter.c (ffffffff81abd112)
Location: include/linux/bpf.h:478
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
In kernel/trace/bpf_trace.c (ffffffff81255e2e)
Location: include/linux/bpf.h:622
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:pe_prog_is_valid_access
```
```
In kernel/bpf/cgroup.c (ffffffff812c1798)
Location: include/linux/bpf.h:622
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_dev_is_valid_access
```
```
In net/core/filter.c (ffffffff81c37d9f)
Location: include/linux/bpf.h:622
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
In kernel/trace/bpf_trace.c (ffffffff812a541e)
Location: include/linux/bpf.h:818
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:pe_prog_is_valid_access
```
```
In kernel/bpf/cgroup.c (ffffffff81325e08)
Location: include/linux/bpf.h:818
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_dev_is_valid_access
```
```
In net/core/filter.c (ffffffff81deb76f)
Location: include/linux/bpf.h:818
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
In kernel/trace/bpf_trace.c (ffffffff812c78ce)
Location: include/linux/bpf.h:887
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:pe_prog_is_valid_access
```
```
In kernel/bpf/cgroup.c (ffffffff81355fd8)
Location: include/linux/bpf.h:887
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_dev_is_valid_access
```
```
In net/core/filter.c (ffffffff81e5cf75)
Location: include/linux/bpf.h:887
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
In kernel/trace/bpf_trace.c (ffffffff812e424e)
Location: include/linux/bpf.h:919
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:pe_prog_is_valid_access
```
```
In kernel/bpf/cgroup.c (ffffffff8137eb08)
Location: include/linux/bpf.h:919
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_dev_is_valid_access
```
```
In net/core/filter.c (ffffffff81f1c365)
Location: include/linux/bpf.h:919
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
In kernel/trace/bpf_trace.c (ffff80001024cd10)
Location: include/linux/bpf.h:295
Inline: True
```
```
In kernel/bpf/cgroup.c (ffff80001028cee4)
Location: include/linux/bpf.h:295
Inline: True
```
```
In net/core/filter.c (ffff800010bf4748)
Location: include/linux/bpf.h:295
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
In kernel/trace/bpf_trace.c (c0480848)
Location: include/linux/bpf.h:295
Inline: True
```
```
In kernel/bpf/cgroup.c (c04bce68)
Location: include/linux/bpf.h:295
Inline: True
```
```
In net/core/filter.c (c0d0cf88)
Location: include/linux/bpf.h:295
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
In kernel/trace/bpf_trace.c (c0000000002e9898)
Location: include/linux/bpf.h:295
Inline: True
```
```
In kernel/bpf/cgroup.c (c00000000033959c)
Location: include/linux/bpf.h:295
Inline: True
```
```
In net/core/filter.c (c000000000cd9890)
Location: include/linux/bpf.h:295
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
In kernel/bpf/cgroup.c (ffffffe0001c0fc2)
Location: include/linux/bpf.h:295
Inline: True
```
```
In net/core/filter.c (ffffffe000775b10)
Location: include/linux/bpf.h:295
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
In kernel/trace/bpf_trace.c (ffffffff811c62a1)
Location: include/linux/bpf.h:295
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff811fd098)
Location: include/linux/bpf.h:295
Inline: True
```
```
In net/core/filter.c (ffffffff818f23a1)
Location: include/linux/bpf.h:295
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
In kernel/trace/bpf_trace.c (ffffffff811b9081)
Location: include/linux/bpf.h:295
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff811efde8)
Location: include/linux/bpf.h:295
Inline: True
```
```
In net/core/filter.c (ffffffff818ac1d1)
Location: include/linux/bpf.h:295
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
In kernel/trace/bpf_trace.c (ffffffff811c4071)
Location: include/linux/bpf.h:295
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff811fae68)
Location: include/linux/bpf.h:295
Inline: True
```
```
In net/core/filter.c (ffffffff819433d1)
Location: include/linux/bpf.h:295
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
In kernel/trace/bpf_trace.c (ffffffff811d1951)
Location: include/linux/bpf.h:295
Inline: True
```
```
In kernel/bpf/cgroup.c (ffffffff812099d8)
Location: include/linux/bpf.h:295
Inline: True
```
```
In net/core/filter.c (ffffffff81964cc1)
Location: include/linux/bpf.h:295
Inline: True
Inline callers:
  - net/core/filter.c:sock_addr_is_valid_access
```
</details>
</li>
</ul>

## Differences
