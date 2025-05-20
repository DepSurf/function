# Function: <code>update_prog_stats</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void update_prog_stats(struct bpf_prog *prog, u64 start);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81226db0)
Location: kernel/bpf/trampoline.c:570
Inline: True
Direct callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit
```
**Symbols:**

```
ffffffff81226db0-ffffffff81226df0: update_prog_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void update_prog_stats(struct bpf_prog *prog, u64 start);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8125eeb0)
Location: kernel/bpf/trampoline.c:577
Inline: True
Direct callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit
```
**Symbols:**

```
ffffffff8125eeb0-ffffffff8125eeec: update_prog_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void update_prog_stats(struct bpf_prog *prog, u64 start);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff812a9460)
Location: kernel/bpf/trampoline.c:595
Inline: True
Direct callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit
```
**Symbols:**

```
ffffffff812a9460-ffffffff812a94ba: update_prog_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void update_prog_stats(struct bpf_prog *prog, u64 start);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81308260)
Location: kernel/bpf/trampoline.c:885
Inline: True
Direct callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_exit_recur
```
**Symbols:**

```
ffffffff81308260-ffffffff813082b1: update_prog_stats (STB_LOCAL)
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
In kernel/bpf/trampoline.c (ffffffff8133759b)
Location: kernel/bpf/trampoline.c:863
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit
  - kernel/bpf/trampoline.c:__bpf_prog_exit
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_exit_recur
  - kernel/bpf/trampoline.c:__bpf_prog_exit_recur
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
In kernel/bpf/trampoline.c (ffffffff8135d3db)
Location: kernel/bpf/trampoline.c:874
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:__bpf_prog_exit
  - kernel/bpf/trampoline.c:__bpf_prog_exit
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_exit_sleepable_recur
  - kernel/bpf/trampoline.c:__bpf_prog_exit_recur
  - kernel/bpf/trampoline.c:__bpf_prog_exit_recur
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
