# Function: <code>notify_on_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81111f2c)
Location: kernel/cgroup.c:500
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_read_notify_on_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111965c)
Location: kernel/cgroup.c:518
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_read_notify_on_release
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81120e2c)
Location: kernel/cgroup.c:521
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffff81127cc0)
Location: kernel/cgroup/cgroup-internal.h:125
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8112a695)
Location: kernel/cgroup/cgroup-internal.h:125
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffff81134200)
Location: kernel/cgroup/cgroup-internal.h:126
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81137415)
Location: kernel/cgroup/cgroup-internal.h:126
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffff81142831)
Location: kernel/cgroup/cgroup-internal.h:126
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81145cc5)
Location: kernel/cgroup/cgroup-internal.h:126
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffff8114e2cb)
Location: kernel/cgroup/cgroup-internal.h:154
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81151885)
Location: kernel/cgroup/cgroup-internal.h:154
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffff81157a53)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115d245)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffff811636c3)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81168e45)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffff8117495c)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117abf5)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffff8117164a)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811779f5)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffff81172278)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178555)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffff81198d68)
Location: kernel/cgroup/cgroup-internal.h:192
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8119feb5)
Location: kernel/cgroup/cgroup-internal.h:192
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffff811c8eec)
Location: kernel/cgroup/cgroup-internal.h:191
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0575)
Location: kernel/cgroup/cgroup-internal.h:191
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffff8120bf81)
Location: kernel/cgroup/cgroup-internal.h:189
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81214025)
Location: kernel/cgroup/cgroup-internal.h:189
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffff81221591)
Location: kernel/cgroup/cgroup-internal.h:189
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81229955)
Location: kernel/cgroup/cgroup-internal.h:189
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffff81239287)
Location: kernel/cgroup/cgroup-internal.h:189
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812417a5)
Location: kernel/cgroup/cgroup-internal.h:189
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffff8000101d4e7c)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dbf58)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (c04179dc)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/cgroup/cgroup-v1.c (c041e288)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (c0000000002441c4)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mkdir
```
```
In kernel/cgroup/cgroup-v1.c (c000000000249670)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffe00014e24a)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe000154032)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffff8115bce3)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81161465)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffff8114efcd)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811546c5)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffff81159ab3)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115f235)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
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
In kernel/cgroup/cgroup.c (ffffffff81166b1a)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116c4d5)
Location: kernel/cgroup/cgroup-internal.h:173
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_check_for_release
  - kernel/cgroup/cgroup-v1.c:cgroup_read_notify_on_release
```
</details>
</li>
</ul>

## Differences
