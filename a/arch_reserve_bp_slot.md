# Function: <code>arch_reserve_bp_slot</code>

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
int arch_reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81245050)
Location: kernel/events/hw_breakpoint.c:216
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
**Symbols:**

```
ffffffff81245050-ffffffff8124505d: arch_reserve_bp_slot (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8124f6a0)
Location: kernel/events/hw_breakpoint.c:216
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
**Symbols:**

```
ffffffff8124f6a0-ffffffff8124f6ad: arch_reserve_bp_slot (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81253e30)
Location: kernel/events/hw_breakpoint.c:216
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
**Symbols:**

```
ffffffff81253e30-ffffffff81253e3d: arch_reserve_bp_slot (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8128f820)
Location: kernel/events/hw_breakpoint.c:216
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
**Symbols:**

```
ffffffff8128f820-ffffffff8128f82d: arch_reserve_bp_slot (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arch_reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff812e4820)
Location: kernel/events/hw_breakpoint.c:216
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
**Symbols:**

```
ffffffff812e4820-ffffffff812e4831: arch_reserve_bp_slot (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8134e100)
Location: kernel/events/hw_breakpoint.c:526
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
**Symbols:**

```
ffffffff8134e100-ffffffff8134e111: arch_reserve_bp_slot (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_reserve_bp_slot(struct perf_event *bp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8137f320)
Location: kernel/events/hw_breakpoint.c:526
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:__reserve_bp_slot
```
**Symbols:**

```
ffffffff8137f320-ffffffff8137f331: arch_reserve_bp_slot (STB_WEAK)
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
</ul>
