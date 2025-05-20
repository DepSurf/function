# Function: <code>bpf_trampoline_get_progs</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_tramp_progs *bpf_trampoline_get_progs(const struct bpf_trampoline *tr, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8121ece0)
Location: kernel/bpf/trampoline.c:163
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff8121ece0-ffffffff8121ed86: bpf_trampoline_get_progs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_tramp_progs *bpf_trampoline_get_progs(const struct bpf_trampoline *tr, int *total);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81222420)
Location: kernel/bpf/trampoline.c:145
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff81222420-ffffffff812224cb: bpf_trampoline_get_progs (STB_LOCAL)
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
In kernel/bpf/trampoline.c (ffffffff8122741f)
Location: kernel/bpf/trampoline.c:175
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
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
In kernel/bpf/trampoline.c (ffffffff8125f51e)
Location: kernel/bpf/trampoline.c:175
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
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
In kernel/bpf/trampoline.c (ffffffff812a9c8f)
Location: kernel/bpf/trampoline.c:175
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
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
In kernel/bpf/trampoline.c (ffffffff81308df4)
Location: kernel/bpf/trampoline.c:257
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
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
In kernel/bpf/trampoline.c (ffffffff81337d14)
Location: kernel/bpf/trampoline.c:229
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
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
In kernel/bpf/trampoline.c (ffffffff8135ddb2)
Location: kernel/bpf/trampoline.c:229
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
