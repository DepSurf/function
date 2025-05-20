# Function: <code>bpf_prog_size</code>

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
In kernel/bpf/syscall.c (0)
Location: include/linux/filter.h:386
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/filter.h:386
Inline: True
```
```
In net/core/filter.c (ffffffff81732b73)
Location: include/linux/filter.h:386
Inline: True
Inline callers:
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_attach_filter
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
In kernel/bpf/core.c (ffffffff8117ea44)
Location: include/linux/filter.h:449
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff81180fc8)
Location: include/linux/filter.h:449
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In net/core/filter.c (ffffffff8179e351)
Location: include/linux/filter.h:449
Inline: True
Inline callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__reuseport_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff8118a8b4)
Location: include/linux/filter.h:530
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff8118d4ea)
Location: include/linux/filter.h:530
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In net/core/filter.c (ffffffff817ccdb1)
Location: include/linux/filter.h:530
Inline: True
Inline callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__reuseport_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff8118efe4)
Location: include/linux/filter.h:583
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff811920d9)
Location: include/linux/filter.h:583
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In net/core/filter.c (ffffffff817ec1eb)
Location: include/linux/filter.h:583
Inline: True
Inline callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__reuseport_attach_prog
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff8119d454)
Location: include/linux/filter.h:588
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff8119f868)
Location: include/linux/filter.h:588
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In net/core/filter.c (ffffffff81867fdb)
Location: include/linux/filter.h:588
Inline: True
Inline callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__reuseport_attach_prog
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff811b1ba4)
Location: include/linux/filter.h:628
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff811b5c20)
Location: include/linux/filter.h:628
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff811bf9eb)
Location: include/linux/filter.h:628
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In net/core/filter.c (ffffffff818b8142)
Location: include/linux/filter.h:628
Inline: True
Inline callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__reuseport_attach_prog
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff811c03e4)
Location: include/linux/filter.h:663
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff811c3842)
Location: include/linux/filter.h:663
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff811d0cd6)
Location: include/linux/filter.h:663
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In net/core/filter.c (ffffffff818def86)
Location: include/linux/filter.h:663
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff811d0db4)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff811d50b0)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff811dfce3)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In net/core/filter.c (ffffffff8192ce89)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff811dd344)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff811e17c0)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff811ec4a3)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In net/core/filter.c (ffffffff8195f189)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff811f9d64)
Location: include/linux/filter.h:750
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff812000db)
Location: include/linux/filter.h:750
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff8120b76f)
Location: include/linux/filter.h:750
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In net/core/filter.c (ffffffff81a32571)
Location: include/linux/filter.h:750
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_migrate_filter
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff811f8d94)
Location: include/linux/filter.h:759
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff811ff56a)
Location: include/linux/filter.h:759
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff8120d990)
Location: include/linux/filter.h:759
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In net/core/filter.c (ffffffff81a348b1)
Location: include/linux/filter.h:759
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_migrate_filter
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff811f9b83)
Location: include/linux/filter.h:802
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff811fff1d)
Location: include/linux/filter.h:802
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff8120f5f1)
Location: include/linux/filter.h:802
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In net/core/filter.c (ffffffff81a1b921)
Location: include/linux/filter.h:802
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff8122b253)
Location: include/linux/filter.h:823
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff81231c52)
Location: include/linux/filter.h:823
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff81243f31)
Location: include/linux/filter.h:823
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In net/core/filter.c (ffffffff81acf001)
Location: include/linux/filter.h:823
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff8126cc77)
Location: include/linux/filter.h:826
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff81274efd)
Location: include/linux/filter.h:826
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff812898ef)
Location: include/linux/filter.h:826
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In net/core/filter.c (ffffffff81c4c6fe)
Location: include/linux/filter.h:826
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff812c1d9e)
Location: include/linux/filter.h:798
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff812ca3b2)
Location: include/linux/filter.h:798
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff812e0308)
Location: include/linux/filter.h:798
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In net/core/filter.c (ffffffff81e014de)
Location: include/linux/filter.h:798
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff812e8c3e)
Location: include/linux/filter.h:798
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff812f1a76)
Location: include/linux/filter.h:798
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff8130a49f)
Location: include/linux/filter.h:798
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In net/core/filter.c (ffffffff81e72f9e)
Location: include/linux/filter.h:798
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff81306fae)
Location: include/linux/filter.h:832
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff813108e8)
Location: include/linux/filter.h:832
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff8132cfa4)
Location: include/linux/filter.h:832
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In net/core/filter.c (ffffffff81f32719)
Location: include/linux/filter.h:832
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:bpf_prepare_filter
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffff80001025de94)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffff80001026484c)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffff80001026fd2c)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In net/core/filter.c (ffff800010c02660)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (c0491590)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (c04969fc)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (c04a1fd8)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In net/core/filter.c (c0d1bb38)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:__sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (c000000000302a3c)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (c000000000309238)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (c000000000316bc8)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In net/core/filter.c (c000000000ceba9c)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffe00019c35a)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffe0001a04d8)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffe0001a9580)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In net/core/filter.c (ffffffe000781a10)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff811d5964)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff811d9de0)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff811e4ac3)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In net/core/filter.c (ffffffff818ff159)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff811c8724)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff811ccba0)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff811d7883)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In net/core/filter.c (ffffffff818b8f89)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff811d3734)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff811d7bb0)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff811e2893)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In net/core/filter.c (ffffffff81950189)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
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
In kernel/bpf/core.c (ffffffff811e1a24)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
```
In kernel/bpf/syscall.c (ffffffff811e5f50)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In kernel/bpf/verifier.c (ffffffff811f0b12)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
```
In net/core/filter.c (ffffffff81971b59)
Location: include/linux/filter.h:719
Inline: True
Inline callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create
  - net/core/filter.c:sk_filter_charge
  - net/core/filter.c:sk_filter_uncharge
```
</details>
</li>
</ul>

## Differences
