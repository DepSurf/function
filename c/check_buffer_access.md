# Function: <code>check_buffer_access</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120f280)
Location: kernel/bpf/verifier.c:3206
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff8120f280-ffffffff8120f351: check_buffer_access.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81210bf0)
Location: kernel/bpf/verifier.c:3749
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81210bf0-ffffffff81210cbe: check_buffer_access.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81245710)
Location: kernel/bpf/verifier.c:3835
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81245710-ffffffff812457de: check_buffer_access.constprop.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff8127e982)
Location: kernel/bpf/verifier.c:4362
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff812e8413)
Location: kernel/bpf/verifier.c:4817
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff8131384a)
Location: kernel/bpf/verifier.c:5761
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff81333bfa)
Location: kernel/bpf/verifier.c:5992
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
  - kernel/bpf/verifier.c:check_mem_access
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
