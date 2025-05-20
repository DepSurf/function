# Function: <code>bpf_prog_get_stats</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d2520)
Location: kernel/bpf/syscall.c:1354
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_show_fdinfo
```
**Symbols:**

```
ffffffff811d2520-ffffffff811d258d: bpf_prog_get_stats.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811deb00)
Location: kernel/bpf/syscall.c:1375
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_show_fdinfo
```
**Symbols:**

```
ffffffff811deb00-ffffffff811deb6d: bpf_prog_get_stats.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_prog_get_stats(const struct bpf_prog *prog, struct bpf_prog_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fb9a0)
Location: kernel/bpf/syscall.c:1762
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_show_fdinfo
```
**Symbols:**

```
ffffffff811fb9a0-ffffffff811fba08: bpf_prog_get_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_prog_get_stats(const struct bpf_prog *prog, struct bpf_prog_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811faa60)
Location: kernel/bpf/syscall.c:1736
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_show_fdinfo
```
**Symbols:**

```
ffffffff811faa60-ffffffff811faac8: bpf_prog_get_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_prog_get_stats(const struct bpf_prog *prog, struct bpf_prog_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fb9b0)
Location: kernel/bpf/syscall.c:1739
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_show_fdinfo
```
**Symbols:**

```
ffffffff811fb9b0-ffffffff811fba2f: bpf_prog_get_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_prog_get_stats(const struct bpf_prog *prog, struct bpf_prog_kstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122d100)
Location: kernel/bpf/syscall.c:1833
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_show_fdinfo
```
**Symbols:**

```
ffffffff8122d100-ffffffff8122d1bd: bpf_prog_get_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_prog_get_stats(const struct bpf_prog *prog, struct bpf_prog_kstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8126f560)
Location: kernel/bpf/syscall.c:2077
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_show_fdinfo
```
**Symbols:**

```
ffffffff8126f560-ffffffff8126f628: bpf_prog_get_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_prog_get_stats(const struct bpf_prog *prog, struct bpf_prog_kstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c5a50)
Location: kernel/bpf/syscall.c:2111
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_show_fdinfo
```
**Symbols:**

```
ffffffff812c5a50-ffffffff812c5b2e: bpf_prog_get_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_prog_get_stats(const struct bpf_prog *prog, struct bpf_prog_kstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812ecb60)
Location: kernel/bpf/syscall.c:2190
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_show_fdinfo
```
**Symbols:**

```
ffffffff812ecb60-ffffffff812ecc3e: bpf_prog_get_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_prog_get_stats(const struct bpf_prog *prog, struct bpf_prog_kstats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130b310)
Location: kernel/bpf/syscall.c:2230
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_show_fdinfo
```
**Symbols:**

```
ffffffff8130b310-ffffffff8130b3ee: bpf_prog_get_stats (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffff80001025fb88)
Location: kernel/bpf/syscall.c:1375
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_show_fdinfo
```
**Symbols:**

```
ffff80001025fb88-ffff80001025fc30: bpf_prog_get_stats.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_prog_get_stats(const struct bpf_prog *prog, struct bpf_prog_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0492f70)
Location: kernel/bpf/syscall.c:1375
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
  - kernel/bpf/syscall.c:bpf_prog_show_fdinfo
```
**Symbols:**

```
c0492f70-c0493080: bpf_prog_get_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (c000000000304c80)
Location: kernel/bpf/syscall.c:1375
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_show_fdinfo
```
**Symbols:**

```
c000000000304c80-c000000000304d6c: bpf_prog_get_stats.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019dbbe)
Location: kernel/bpf/syscall.c:1375
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_show_fdinfo
```
**Symbols:**

```
ffffffe00019dbbe-ffffffe00019dc58: bpf_prog_get_stats.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d7120)
Location: kernel/bpf/syscall.c:1375
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_show_fdinfo
```
**Symbols:**

```
ffffffff811d7120-ffffffff811d718d: bpf_prog_get_stats.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c9ee0)
Location: kernel/bpf/syscall.c:1375
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_show_fdinfo
```
**Symbols:**

```
ffffffff811c9ee0-ffffffff811c9f4d: bpf_prog_get_stats.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d4ef0)
Location: kernel/bpf/syscall.c:1375
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_show_fdinfo
```
**Symbols:**

```
ffffffff811d4ef0-ffffffff811d4f5d: bpf_prog_get_stats.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e3220)
Location: kernel/bpf/syscall.c:1375
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_show_fdinfo
```
**Symbols:**

```
ffffffff811e3220-ffffffff811e328d: bpf_prog_get_stats.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bpf_prog_stats *stats</code> ➡️ <code>struct bpf_prog_kstats *stats</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
