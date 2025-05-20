# Function: <code>bpf_uncharge_memlock</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c5572)
Location: kernel/bpf/syscall.c:195
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
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
In kernel/bpf/syscall.c (ffffffff811d3ffa)
Location: kernel/bpf/syscall.c:194
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
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
In kernel/bpf/syscall.c (ffffffff811e038a)
Location: kernel/bpf/syscall.c:197
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
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
In kernel/bpf/syscall.c (ffffffff811feef6)
Location: kernel/bpf/syscall.c:351
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff8000102629c0)
Location: kernel/bpf/syscall.c:197
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
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
In kernel/bpf/syscall.c (c04954f0)
Location: kernel/bpf/syscall.c:197
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
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
In kernel/bpf/syscall.c (c0000000003076dc)
Location: kernel/bpf/syscall.c:197
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
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
In kernel/bpf/syscall.c (ffffffe00019fa8e)
Location: kernel/bpf/syscall.c:197
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
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
In kernel/bpf/syscall.c (ffffffff811d89aa)
Location: kernel/bpf/syscall.c:197
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
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
In kernel/bpf/syscall.c (ffffffff811cb76a)
Location: kernel/bpf/syscall.c:197
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
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
In kernel/bpf/syscall.c (ffffffff811d677a)
Location: kernel/bpf/syscall.c:197
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
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
In kernel/bpf/syscall.c (ffffffff811e4aea)
Location: kernel/bpf/syscall.c:197
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_uncharge_memlock
  - kernel/bpf/syscall.c:bpf_map_charge_finish
```
</details>
</li>
</ul>

## Differences
