# Function: <code>bpf_verifier_log_full</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a8270)
Location: include/linux/bpf_verifier.h:133
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:verbose
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
In kernel/bpf/verifier.c (ffffffff811bed31)
Location: include/linux/bpf_verifier.h:165
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff811c8bc0)
Location: include/linux/bpf_verifier.h:165
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/verifier.c (ffffffff811cfb04)
Location: include/linux/bpf_verifier.h:204
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff811dc946)
Location: include/linux/bpf_verifier.h:204
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/verifier.c (ffffffff811e4598)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff811f228f)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/verifier.c (ffffffff811f0df8)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff811fe99f)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/verifier.c (ffffffff8121355a)
Location: include/linux/bpf_verifier.h:336
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:bpf_log
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff812247dd)
Location: include/linux/bpf_verifier.h:336
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse
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
In kernel/bpf/verifier.c (ffffffff81214e38)
Location: include/linux/bpf_verifier.h:354
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:bpf_log
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff8122b05d)
Location: include/linux/bpf_verifier.h:354
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse
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
In kernel/bpf/verifier.c (ffffffff812175c2)
Location: include/linux/bpf_verifier.h:366
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:bpf_log
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff8122fa47)
Location: include/linux/bpf_verifier.h:366
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse
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
In kernel/bpf/verifier.c (ffffffff8124dc5b)
Location: include/linux/bpf_verifier.h:380
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:pop_stack
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:bpf_log
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff8126879b)
Location: include/linux/bpf_verifier.h:380
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse
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
In kernel/bpf/verifier.c (ffffffff81294c3e)
Location: include/linux/bpf_verifier.h:402
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:pop_stack
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:bpf_log
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff812b5a69)
Location: include/linux/bpf_verifier.h:402
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse
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
In kernel/bpf/verifier.c (ffffffff812ef891)
Location: include/linux/bpf_verifier.h:471
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:pop_stack
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:bpf_log
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff8131aaa3)
Location: include/linux/bpf_verifier.h:471
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse_hdr
  - kernel/bpf/btf.c:btf_verifier_log_vsi
  - kernel/bpf/btf.c:btf_verifier_log_member
  - kernel/bpf/btf.c:__btf_verifier_log_type
  - kernel/bpf/btf.c:btf_verifier_log
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010274538)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffff800010285a38)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/verifier.c (c04a6be4)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (c04b6038)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/verifier.c (c00000000031c2d4)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (c000000000330944)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/verifier.c (ffffffe0001aceea)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffe0001bad56)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/verifier.c (ffffffff811e9418)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff811f6fbf)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/verifier.c (ffffffff811dc1d8)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff811e9d0f)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/verifier.c (ffffffff811e71e8)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff811f4d8f)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/verifier.c (ffffffff811f5598)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:verbose_linfo
  - kernel/bpf/verifier.c:verbose
  - kernel/bpf/verifier.c:bpf_verifier_log_write
```
```
In kernel/bpf/btf.c (ffffffff812032af)
Location: include/linux/bpf_verifier.h:323
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
