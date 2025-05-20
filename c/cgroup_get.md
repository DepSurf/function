# Function: <code>cgroup_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cgroup_get(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81114630)
Location: kernel/cgroup.c:445
Inline: False
Direct callers:
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff81114630-ffffffff81114688: cgroup_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cgroup_get(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111b030)
Location: kernel/cgroup.c:487
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup.c:cgroup_get_from_path
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff8111b030-ffffffff8111b088: cgroup_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cgroup_get(struct cgroup *cgrp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81123370)
Location: kernel/cgroup.c:490
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup.c:cgroup_get_from_path
  - kernel/cgroup.c:init_and_link_css
  - kernel/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup.c:cgroup_mount
```
**Symbols:**

```
ffffffff81123370-ffffffff811233c8: cgroup_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81128aa7)
Location: kernel/cgroup/cgroup.c:439
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81135116)
Location: include/linux/cgroup.h:403
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114384d)
Location: include/linux/cgroup.h:403
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114f36d)
Location: include/linux/cgroup.h:405
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
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
In kernel/cgroup/cgroup.c (ffffffff8115b1c0)
Location: include/linux/cgroup.h:412
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
```
In kernel/bpf/cgroup.c (ffffffff811f8c95)
Location: include/linux/cgroup.h:412
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
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
In kernel/cgroup/cgroup.c (ffffffff81166e7e)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
```
In kernel/bpf/cgroup.c (ffffffff81205cc5)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
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
In kernel/cgroup/cgroup.c (ffffffff811785da)
Location: include/linux/cgroup.h:420
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
```
In kernel/bpf/cgroup.c (ffffffff8122d445)
Location: include/linux/cgroup.h:420
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
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
In kernel/cgroup/cgroup.c (ffffffff8117536e)
Location: include/linux/cgroup.h:420
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
```
In kernel/bpf/cgroup.c (ffffffff81235955)
Location: include/linux/cgroup.h:420
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
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
In kernel/cgroup/cgroup.c (ffffffff81175eee)
Location: include/linux/cgroup.h:420
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
```
In kernel/bpf/cgroup.c (ffffffff81239ba5)
Location: include/linux/cgroup.h:420
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
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
In kernel/cgroup/cgroup.c (ffffffff8119d4cd)
Location: include/linux/cgroup.h:420
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
```
In kernel/bpf/cgroup.c (ffffffff81274315)
Location: include/linux/cgroup.h:420
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
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
In kernel/cgroup/cgroup.c (ffffffff811cd7ed)
Location: include/linux/cgroup.h:420
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
```
In kernel/bpf/cgroup.c (ffffffff812c49b5)
Location: include/linux/cgroup.h:420
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
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
In kernel/cgroup/cgroup.c (ffffffff81210e8d)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:pressure_write
```
```
In kernel/bpf/helpers.c (ffffffff812f44a1)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_cgroup_ancestor
  - kernel/bpf/helpers.c:bpf_cgroup_acquire
```
```
In kernel/bpf/cgroup.c (ffffffff81329e85)
Location: include/linux/cgroup.h:351
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
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
In kernel/cgroup/cgroup.c (ffffffff8122687d)
Location: include/linux/cgroup.h:350
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
```
```
In kernel/bpf/cgroup.c (ffffffff81359fc5)
Location: include/linux/cgroup.h:350
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
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
In kernel/cgroup/cgroup.c (ffffffff8123e50d)
Location: include/linux/cgroup.h:349
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_clone
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:pressure_write
  - kernel/cgroup/cgroup.c:cgroup_lock_and_drain_offline
  - kernel/cgroup/cgroup.c:cgroup_get_tree
```
```
In kernel/bpf/cgroup.c (ffffffff81382b75)
Location: include/linux/cgroup.h:349
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
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
In kernel/cgroup/cgroup.c (ffff8000101d8d10)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
```
In kernel/bpf/cgroup.c (ffff80001028ef28)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
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
In kernel/cgroup/cgroup.c (c041ba94)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
```
In kernel/bpf/cgroup.c (c04be780)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
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
In kernel/cgroup/cgroup.c (c000000000246128)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
```
In kernel/bpf/cgroup.c (c00000000033bad0)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
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
In kernel/cgroup/cgroup.c (ffffffe000151c98)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
```
In kernel/bpf/cgroup.c (ffffffe0001c20ba)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
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
In kernel/cgroup/cgroup.c (ffffffff8115f49e)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
```
In kernel/bpf/cgroup.c (ffffffff811fe2e5)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
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
In kernel/cgroup/cgroup.c (ffffffff8115272e)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
```
In kernel/bpf/cgroup.c (ffffffff811f1035)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
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
In kernel/cgroup/cgroup.c (ffffffff8115d26e)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
```
In kernel/bpf/cgroup.c (ffffffff811fc0b5)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
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
In kernel/cgroup/cgroup.c (ffffffff8116a3f1)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_sk_alloc
  - kernel/cgroup/cgroup.c:cgroup_pressure_write
```
```
In kernel/bpf/cgroup.c (ffffffff8120acd5)
Location: include/linux/cgroup.h:414
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_offline
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
