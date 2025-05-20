# Function: <code>btf_type_var_secinfo</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811ee259)
Location: kernel/bpf/btf.c:513
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fa999)
Location: kernel/bpf/btf.c:513
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122005a)
Location: kernel/bpf/btf.c:528
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_check_meta
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
In kernel/bpf/verifier.c (ffffffff81205e97)
Location: include/linux/btf.h:204
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
```
In kernel/bpf/btf.c (ffffffff81226614)
Location: include/linux/btf.h:204
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_check_meta
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
In kernel/bpf/verifier.c (ffffffff81207ce6)
Location: include/linux/btf.h:214
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
```
In kernel/bpf/btf.c (ffffffff8122b110)
Location: include/linux/btf.h:214
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_check_meta
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
In kernel/bpf/verifier.c (ffffffff8123b57b)
Location: include/linux/btf.h:215
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
```
In kernel/bpf/btf.c (ffffffff812638e0)
Location: include/linux/btf.h:215
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_find_field
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
In kernel/bpf/verifier.c (ffffffff812810b1)
Location: include/linux/btf.h:335
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
```
In kernel/bpf/btf.c (ffffffff812afdd9)
Location: include/linux/btf.h:335
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_check_meta
  - kernel/bpf/btf.c:btf_find_field
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
In kernel/bpf/verifier.c (ffffffff812d8e21)
Location: include/linux/btf.h:442
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
```
In kernel/bpf/btf.c (ffffffff8130fb89)
Location: include/linux/btf.h:442
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_check_meta
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
In kernel/bpf/verifier.c (ffffffff812f7f05)
Location: include/linux/btf.h:458
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
```
In kernel/bpf/btf.c (ffffffff8133f509)
Location: include/linux/btf.h:458
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_check_meta
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
In kernel/bpf/verifier.c (ffffffff813163a5)
Location: include/linux/btf.h:469
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_pseudo_btf_id
```
```
In kernel/bpf/btf.c (ffffffff81365519)
Location: include/linux/btf.h:469
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_show
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff80001028097c)
Location: kernel/bpf/btf.c:513
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b3ccc)
Location: kernel/bpf/btf.c:513
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032ad90)
Location: kernel/bpf/btf.c:513
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001b70c2)
Location: kernel/bpf/btf.c:513
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f2fb9)
Location: kernel/bpf/btf.c:513
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e5d09)
Location: kernel/bpf/btf.c:513
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f0d89)
Location: kernel/bpf/btf.c:513
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811ff299)
Location: kernel/bpf/btf.c:513
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_datasec_seq_show
  - kernel/bpf/btf.c:btf_datasec_check_meta
```
</details>
</li>
</ul>

## Differences
