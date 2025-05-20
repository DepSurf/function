# Function: <code>perf_callchain_user32</code>

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
In arch/x86/events/core.c (ffffffff810076cd)
Location: arch/x86/events/core.c:2239
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
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
In arch/x86/events/core.c (ffffffff8100785c)
Location: arch/x86/events/core.c:2327
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
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
In arch/x86/events/core.c (ffffffff810078ee)
Location: arch/x86/events/core.c:2343
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
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
In arch/x86/events/core.c (ffffffff81007680)
Location: arch/x86/events/core.c:2362
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
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
In arch/x86/events/core.c (ffffffff81007ab6)
Location: arch/x86/events/core.c:2397
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
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
In arch/x86/events/core.c (ffffffff810080ea)
Location: arch/x86/events/core.c:2403
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
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
In arch/x86/events/core.c (ffffffff81007fca)
Location: arch/x86/events/core.c:2419
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int perf_callchain_user32(struct pt_regs *regs, struct perf_callchain_entry_ctx *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005a00)
Location: arch/x86/events/core.c:2385
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_user
```
**Symbols:**

```
ffffffff81005a00-ffffffff81005b1e: perf_callchain_user32 (STB_LOCAL)
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
In arch/x86/events/core.c (ffffffff810084dd)
Location: arch/x86/events/core.c:2474
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perf_callchain_user32(struct pt_regs *regs, struct perf_callchain_entry_ctx *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810075e0)
Location: arch/x86/events/core.c:2487
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_user
```
**Symbols:**

```
ffffffff810075e0-ffffffff8100771b: perf_callchain_user32 (STB_LOCAL)
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
In arch/x86/events/core.c (ffffffff810085ec)
Location: arch/x86/events/core.c:2598
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
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
In arch/x86/events/core.c (ffffffff81008fb5)
Location: arch/x86/events/core.c:2828
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
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
In arch/x86/events/core.c (ffffffff81009e84)
Location: arch/x86/events/core.c:2828
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
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
In arch/x86/events/core.c (ffffffff810095d6)
Location: arch/x86/events/core.c:2841
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
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
In arch/x86/events/core.c (ffffffff8100aa76)
Location: arch/x86/events/core.c:2825
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
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
In arch/x86/events/core.c (ffffffff8100a2c6)
Location: arch/x86/events/core.c:2823
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
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
In arch/x86/events/core.c (ffffffff8100f9e6)
Location: arch/x86/events/core.c:2820
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
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
In arch/x86/events/core.c (ffffffff810084dd)
Location: arch/x86/events/core.c:2474
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
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
In arch/x86/events/core.c (ffffffff81006ccd)
Location: arch/x86/events/core.c:2474
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
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
In arch/x86/events/core.c (ffffffff8100849d)
Location: arch/x86/events/core.c:2474
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
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
In arch/x86/events/core.c (ffffffff810085fd)
Location: arch/x86/events/core.c:2474
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
