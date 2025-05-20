# Function: <code>raw_read_seqcount_latch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f54e3)
Location: include/linux/seqlock.h:278
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffffffff811067b3)
Location: include/linux/seqlock.h:278
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fc679)
Location: include/linux/seqlock.h:278
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffffffff8110df7a)
Location: include/linux/seqlock.h:278
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810ff57d)
Location: include/linux/seqlock.h:278
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffffffff8111595a)
Location: include/linux/seqlock.h:278
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110186d)
Location: include/linux/seqlock.h:278
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffffffff811166aa)
Location: include/linux/seqlock.h:278
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8118def7)
Location: include/linux/seqlock.h:278
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_find
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
In kernel/time/timekeeping.c (ffffffff8110c69d)
Location: include/linux/seqlock.h:279
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffffffff81121caa)
Location: include/linux/seqlock.h:279
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8119c1a6)
Location: include/linux/seqlock.h:279
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_kallsyms_find
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
In kernel/time/timekeeping.c (ffffffff8111820d)
Location: include/linux/seqlock.h:279
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffffffff8112f7ac)
Location: include/linux/seqlock.h:279
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811b128d)
Location: include/linux/seqlock.h:279
Inline: True
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
In kernel/time/timekeeping.c (ffffffff8112382d)
Location: include/linux/seqlock.h:279
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffffffff8113b27f)
Location: include/linux/seqlock.h:279
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811bf90d)
Location: include/linux/seqlock.h:279
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
In kernel/time/timekeeping.c (ffffffff8112e012)
Location: include/linux/seqlock.h:279
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffffffff811468bf)
Location: include/linux/seqlock.h:279
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811cfed4)
Location: include/linux/seqlock.h:279
Inline: True
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
In kernel/time/timekeeping.c (ffffffff81139fc2)
Location: include/linux/seqlock.h:279
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffffffff8115249f)
Location: include/linux/seqlock.h:279
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811dc484)
Location: include/linux/seqlock.h:279
Inline: True
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
In kernel/time/timekeeping.c (ffffffff81148782)
Location: include/linux/seqlock.h:310
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffffffff8116214e)
Location: include/linux/seqlock.h:310
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811f8e2e)
Location: include/linux/seqlock.h:310
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
```
```
In mm/swap.c (ffffffff81260603)
Location: include/linux/seqlock.h:310
Inline: True
Inline callers:
  - mm/swap.c:lru_add_drain_all
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
In kernel/time/timekeeping.c (ffffffff811461ea)
Location: include/linux/seqlock.h:680
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffffffff811640ee)
Location: include/linux/seqlock.h:680
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811f7e6e)
Location: include/linux/seqlock.h:680
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
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
In kernel/printk/printk.c (ffffffff81119445)
Location: include/linux/seqlock.h:680
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_llseek
```
```
In kernel/time/timekeeping.c (ffffffff8114724a)
Location: include/linux/seqlock.h:680
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffffffff81164ebe)
Location: include/linux/seqlock.h:680
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811f8c4e)
Location: include/linux/seqlock.h:680
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
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
In kernel/printk/printk.c (ffffffff8113841d)
Location: include/linux/seqlock.h:680
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_llseek
```
```
In kernel/time/timekeeping.c (ffffffff8116ad3a)
Location: include/linux/seqlock.h:680
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffffffff811846a9)
Location: include/linux/seqlock.h:680
Inline: True
```
```
In kernel/bpf/core.c (ffffffff8122a2de)
Location: include/linux/seqlock.h:680
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
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
In kernel/printk/printk.c (ffffffff8115accd)
Location: include/linux/seqlock.h:676
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_llseek
```
```
In kernel/module/tree_lookup.c (ffffffff81190e91)
Location: include/linux/seqlock.h:676
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_find
```
```
In kernel/time/timekeeping.c (ffffffff8119eb6d)
Location: include/linux/seqlock.h:676
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/bpf/core.c (ffffffff8126bd8e)
Location: include/linux/seqlock.h:676
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
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
In kernel/printk/printk.c (ffffffff8118d1ed)
Location: include/linux/seqlock.h:676
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_llseek
```
```
In kernel/module/tree_lookup.c (ffffffff811ce491)
Location: include/linux/seqlock.h:676
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_find
```
```
In kernel/time/timekeeping.c (ffffffff811dd78d)
Location: include/linux/seqlock.h:676
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/bpf/core.c (ffffffff812c0f4e)
Location: include/linux/seqlock.h:676
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
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
In kernel/printk/printk.c (ffffffff8119e9ad)
Location: include/linux/seqlock.h:676
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_llseek
```
```
In kernel/module/tree_lookup.c (ffffffff811e260c)
Location: include/linux/seqlock.h:676
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_find
```
```
In kernel/time/timekeeping.c (ffffffff811f1c6c)
Location: include/linux/seqlock.h:676
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/bpf/core.c (ffffffff812e5a59)
Location: include/linux/seqlock.h:676
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
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
In kernel/printk/printk.c (ffffffff811adb6d)
Location: include/linux/seqlock.h:630
Inline: True
Inline callers:
  - kernel/printk/printk.c:kmsg_dump_rewind
  - kernel/printk/printk.c:kmsg_dump_get_buffer
  - kernel/printk/printk.c:kmsg_dump_get_line
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:devkmsg_llseek
```
```
In kernel/module/tree_lookup.c (ffffffff811f839c)
Location: include/linux/seqlock.h:630
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_find
```
```
In kernel/time/timekeeping.c (ffffffff81207dac)
Location: include/linux/seqlock.h:630
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_fast_timestamps
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/bpf/core.c (ffffffff81303b69)
Location: include/linux/seqlock.h:630
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_ksym_find
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
In kernel/time/timekeeping.c (ffff8000101a3eb0)
Location: include/linux/seqlock.h:279
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffff8000101c108c)
Location: include/linux/seqlock.h:279
Inline: True
```
```
In kernel/bpf/core.c (ffff80001025c550)
Location: include/linux/seqlock.h:279
Inline: True
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
In kernel/time/timekeeping.c (c03edbdc)
Location: include/linux/seqlock.h:279
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (c040883c)
Location: include/linux/seqlock.h:279
Inline: True
```
```
In kernel/bpf/core.c (c049060c)
Location: include/linux/seqlock.h:279
Inline: True
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
In kernel/time/timekeeping.c (c000000000205de0)
Location: include/linux/seqlock.h:279
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (c000000000227974)
Location: include/linux/seqlock.h:279
Inline: True
```
```
In kernel/bpf/core.c (c000000000301570)
Location: include/linux/seqlock.h:279
Inline: True
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
In kernel/time/timekeeping.c (ffffffe000130a8e)
Location: include/linux/seqlock.h:279
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffffffe0001433c2)
Location: include/linux/seqlock.h:279
Inline: True
```
```
In kernel/bpf/core.c (ffffffe00019b636)
Location: include/linux/seqlock.h:279
Inline: True
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
In kernel/time/timekeeping.c (ffffffff81132772)
Location: include/linux/seqlock.h:279
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffffffff8114aabf)
Location: include/linux/seqlock.h:279
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d4aa4)
Location: include/linux/seqlock.h:279
Inline: True
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
In kernel/time/timekeeping.c (ffffffff811251d2)
Location: include/linux/seqlock.h:279
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffffffff8113dd6f)
Location: include/linux/seqlock.h:279
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811c7864)
Location: include/linux/seqlock.h:279
Inline: True
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
In kernel/time/timekeeping.c (ffffffff81130492)
Location: include/linux/seqlock.h:279
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffffffff8114896f)
Location: include/linux/seqlock.h:279
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811d2874)
Location: include/linux/seqlock.h:279
Inline: True
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
In kernel/time/timekeeping.c (ffffffff8113ceb2)
Location: include/linux/seqlock.h:279
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:ktime_get_real_fast_ns
  - kernel/time/timekeeping.c:ktime_get_raw_fast_ns
  - kernel/time/timekeeping.c:ktime_get_mono_fast_ns
```
```
In kernel/module.c (ffffffff811555df)
Location: include/linux/seqlock.h:279
Inline: True
```
```
In kernel/bpf/core.c (ffffffff811e0b64)
Location: include/linux/seqlock.h:279
Inline: True
```
</details>
</li>
</ul>

## Differences
