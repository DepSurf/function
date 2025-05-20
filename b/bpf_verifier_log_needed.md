# Function: <code>bpf_verifier_log_needed</code>

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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b7a91)
Location: include/linux/bpf_verifier.h:170
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff811c89b6)
Location: include/linux/bpf_verifier.h:170
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (ffffffff811cd21f)
Location: include/linux/bpf_verifier.h:209
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff811dc927)
Location: include/linux/bpf_verifier.h:209
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (ffffffff811dffaf)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff811ef6f9)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (ffffffff811ec76f)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff811fbe19)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (ffffffff81212e85)
Location: include/linux/bpf_verifier.h:348
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:bpf_log
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff81220da5)
Location: include/linux/bpf_verifier.h:348
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (ffffffff81213c03)
Location: include/linux/bpf_verifier.h:366
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:bpf_log
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff81223cc5)
Location: include/linux/bpf_verifier.h:366
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_verifier_log_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (ffffffff812160cb)
Location: include/linux/bpf_verifier.h:378
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:bpf_log
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff81228459)
Location: include/linux/bpf_verifier.h:378
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (ffffffff8124c7e0)
Location: include/linux/bpf_verifier.h:392
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:pop_stack
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:bpf_log
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff81260729)
Location: include/linux/bpf_verifier.h:392
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (ffffffff8127b060)
Location: include/linux/bpf_verifier.h:416
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:pop_stack
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:bpf_log
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff812ab738)
Location: include/linux/bpf_verifier.h:416
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (ffffffff812d1b6e)
Location: include/linux/bpf_verifier.h:485
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:pop_stack
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:bpf_log
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff8130b148)
Location: include/linux/bpf_verifier.h:485
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (ffffffff812fc075)
Location: include/linux/bpf_verifier.h:528
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
```
```
In kernel/bpf/log.c (ffffffff8132284b)
Location: include/linux/bpf_verifier.h:528
Inline: True
Inline callers:
  - kernel/bpf/log.c:bpf_log
  - kernel/bpf/log.c:bpf_verifier_log_write
  - kernel/bpf/log.c:bpf_vlog_reset
```
```
In kernel/bpf/btf.c (ffffffff81339a68)
Location: include/linux/bpf_verifier.h:528
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (ffffffff8131538e)
Location: include/linux/bpf_verifier.h:602
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verbose
```
```
In kernel/bpf/log.c (ffffffff81345822)
Location: include/linux/bpf_verifier.h:602
Inline: True
Inline callers:
  - kernel/bpf/log.c:verbose_linfo
  - kernel/bpf/log.c:bpf_log
  - kernel/bpf/log.c:bpf_verifier_log_write
  - kernel/bpf/log.c:bpf_vlog_reset
```
```
In kernel/bpf/btf.c (ffffffff8135fb98)
Location: include/linux/bpf_verifier.h:602
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (ffff800010270060)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffff800010282300)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (c04a2334)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (c04b1f60)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (c000000000316f34)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (c00000000032c938)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (ffffffe0001a9806)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffe0001b840c)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (ffffffff811e4d8f)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff811f4439)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (ffffffff811d7b4f)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff811e7189)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (ffffffff811e2b5f)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff811f2209)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
In kernel/bpf/verifier.c (ffffffff811f0f2f)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff81200719)
Location: include/linux/bpf_verifier.h:334
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
```
</details>
</li>
</ul>

## Differences
