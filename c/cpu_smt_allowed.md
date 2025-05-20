# Function: <code>cpu_smt_allowed</code>

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
In kernel/cpu.c (ffffffff8108f965)
Location: kernel/cpu.c:397
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff81097c65)
Location: kernel/cpu.c:412
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff8109c258)
Location: kernel/cpu.c:422
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff810a27a9)
Location: kernel/cpu.c:424
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff810a98cd)
Location: kernel/cpu.c:425
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_wait_for_ap
  - kernel/cpu.c:bringup_wait_for_ap
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
In kernel/cpu.c (ffffffff810a52fd)
Location: kernel/cpu.c:425
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_wait_for_ap
  - kernel/cpu.c:bringup_wait_for_ap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a7094)
Location: kernel/cpu.c:437
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b7b8a)
Location: kernel/cpu.c:448
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ce139)
Location: kernel/cpu.c:449
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ec2b9)
Location: kernel/cpu.c:449
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f98e3)
Location: kernel/cpu.c:628
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_bringup_ap
  - kernel/cpu.c:cpuhp_bringup_ap
```
</details>
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
In kernel/cpu.c (0)
Location: kernel/cpu.c:449
Inline: True
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
In kernel/cpu.c (0)
Location: kernel/cpu.c:449
Inline: True
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
In kernel/cpu.c (0)
Location: kernel/cpu.c:449
Inline: True
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
In kernel/cpu.c (0)
Location: kernel/cpu.c:449
Inline: True
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
In kernel/cpu.c (ffffffff8109c0c9)
Location: kernel/cpu.c:424
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff8108aaf9)
Location: kernel/cpu.c:424
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff8109c079)
Location: kernel/cpu.c:424
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff810a3cd9)
Location: kernel/cpu.c:424
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
```
</details>
</li>
</ul>

## Differences
