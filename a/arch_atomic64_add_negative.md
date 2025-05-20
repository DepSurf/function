# Function: <code>arch_atomic64_add_negative</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/pids.c (ffffffff81146cc5)
Location: arch/x86/include/asm/atomic64_64.h:140
Inline: True
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
In kernel/cgroup/pids.c (ffffffff81152845)
Location: arch/x86/include/asm/atomic64_64.h:145
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/pids.c (ffffffff8115eea5)
Location: arch/x86/include/asm/atomic64_64.h:145
Inline: True
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
In kernel/cgroup/pids.c (ffffffff8116ab05)
Location: arch/x86/include/asm/atomic64_64.h:145
Inline: True
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
In kernel/cgroup/pids.c (ffffffff8117c82e)
Location: arch/x86/include/asm/atomic64_64.h:145
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/pids.c (ffffffff811796de)
Location: arch/x86/include/asm/atomic64_64.h:145
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
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
In kernel/cgroup/pids.c (ffffffff8117a23e)
Location: arch/x86/include/asm/atomic64_64.h:145
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/misc.c (ffffffff81180f6e)
Location: arch/x86/include/asm/atomic64_64.h:145
Inline: True
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
In kernel/cgroup/pids.c (ffffffff811a1b5e)
Location: arch/x86/include/asm/atomic64_64.h:145
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/misc.c (ffffffff811a8d95)
Location: arch/x86/include/asm/atomic64_64.h:145
Inline: True
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
In kernel/cgroup/pids.c (ffffffff811d252e)
Location: arch/x86/include/asm/atomic64_64.h:145
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/misc.c (ffffffff811da075)
Location: arch/x86/include/asm/atomic64_64.h:145
Inline: True
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
In kernel/cgroup/pids.c (ffffffff8121628e)
Location: arch/x86/include/asm/atomic64_64.h:145
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/misc.c (ffffffff8121f5e5)
Location: arch/x86/include/asm/atomic64_64.h:145
Inline: True
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
In kernel/cgroup/pids.c (ffffffff8122bbce)
Location: arch/x86/include/asm/atomic64_64.h:71
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/misc.c (ffffffff8123571b)
Location: arch/x86/include/asm/atomic64_64.h:71
Inline: True
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
In kernel/cgroup/pids.c (ffffffff81243bfe)
Location: arch/x86/include/asm/atomic64_64.h:71
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_release
  - kernel/cgroup/pids.c:pids_cancel_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_can_fork
  - kernel/cgroup/pids.c:pids_cancel_attach
  - kernel/cgroup/pids.c:pids_can_attach
```
```
In kernel/cgroup/misc.c (ffffffff8124f36b)
Location: arch/x86/include/asm/atomic64_64.h:71
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/cgroup/pids.c (ffffffff81163125)
Location: arch/x86/include/asm/atomic64_64.h:145
Inline: True
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
In kernel/cgroup/pids.c (ffffffff81156375)
Location: arch/x86/include/asm/atomic64_64.h:145
Inline: True
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
In kernel/cgroup/pids.c (ffffffff81160ef5)
Location: arch/x86/include/asm/atomic64_64.h:145
Inline: True
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
In kernel/cgroup/pids.c (ffffffff8116e345)
Location: arch/x86/include/asm/atomic64_64.h:145
Inline: True
```
</details>
</li>
</ul>

## Differences
