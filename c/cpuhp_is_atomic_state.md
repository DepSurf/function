# Function: <code>cpuhp_is_atomic_state</code>

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
In kernel/cpu.c (ffffffff8108be11)
Location: kernel/cpu.c:257
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (ffffffff8108f641)
Location: kernel/cpu.c:254
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (ffffffff81097941)
Location: kernel/cpu.c:252
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (ffffffff8109bf0c)
Location: kernel/cpu.c:253
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (ffffffff810a248c)
Location: kernel/cpu.c:256
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (ffffffff810a915c)
Location: kernel/cpu.c:257
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (ffffffff810a4bac)
Location: kernel/cpu.c:257
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (ffffffff810a5890)
Location: kernel/cpu.c:262
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (ffffffff810b706f)
Location: kernel/cpu.c:273
Inline: True
Inline callers:
  - kernel/cpu.c:fail_store
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (ffffffff810cd7e6)
Location: kernel/cpu.c:274
Inline: True
Inline callers:
  - kernel/cpu.c:fail_store
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (ffffffff810eb8c6)
Location: kernel/cpu.c:274
Inline: True
Inline callers:
  - kernel/cpu.c:fail_store
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (ffffffff810f75a6)
Location: kernel/cpu.c:277
Inline: True
Inline callers:
  - kernel/cpu.c:fail_store
  - kernel/cpu.c:cpuhp_thread_fun
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81100956)
Location: kernel/cpu.c:277
Inline: True
Inline callers:
  - kernel/cpu.c:fail_store
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (ffff8000100f7560)
Location: kernel/cpu.c:256
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (c0355950)
Location: kernel/cpu.c:256
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (c00000000013dc60)
Location: kernel/cpu.c:256
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (ffffffe0000c3cc4)
Location: kernel/cpu.c:256
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (ffffffff8109bdac)
Location: kernel/cpu.c:256
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (ffffffff8108a7dc)
Location: kernel/cpu.c:256
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (ffffffff8109bd5c)
Location: kernel/cpu.c:256
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:cpuhp_thread_fun
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
In kernel/cpu.c (ffffffff810a395c)
Location: kernel/cpu.c:256
Inline: True
Inline callers:
  - kernel/cpu.c:write_cpuhp_fail
  - kernel/cpu.c:cpuhp_thread_fun
```
</details>
</li>
</ul>

## Differences
