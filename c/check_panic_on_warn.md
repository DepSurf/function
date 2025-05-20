# Function: <code>check_panic_on_warn</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void check_panic_on_warn(const char *origin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810ea7d0)
Location: kernel/panic.c:231
Inline: True
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:__warn
  - kernel/sched/core.c:__schedule_bug
  - mm/kfence/report.c:kfence_report_error
  - lib/ubsan.c:__ubsan_handle_alignment_assumption
  - lib/ubsan.c:__ubsan_handle_load_invalid_value
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
  - lib/ubsan.c:__ubsan_handle_out_of_bounds
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:__ubsan_handle_divrem_overflow
```
**Symbols:**

```
ffffffff810ea7d0-ffffffff810ea82e: check_panic_on_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void check_panic_on_warn(const char *origin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810f63b0)
Location: kernel/panic.c:231
Inline: True
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:__warn
  - kernel/sched/core.c:__schedule_bug
  - mm/kfence/report.c:kfence_report_error
  - lib/ubsan.c:__ubsan_handle_alignment_assumption
  - lib/ubsan.c:__ubsan_handle_load_invalid_value
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
  - lib/ubsan.c:__ubsan_handle_out_of_bounds
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:__ubsan_handle_divrem_overflow
```
**Symbols:**

```
ffffffff810f63b0-ffffffff810f640e: check_panic_on_warn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void check_panic_on_warn(const char *origin);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810ff760)
Location: kernel/panic.c:232
Inline: True
Direct callers:
  - kernel/panic.c:__warn
  - kernel/panic.c:__warn
  - kernel/sched/core.c:__schedule_bug
  - mm/kfence/report.c:kfence_report_error
  - lib/ubsan.c:__ubsan_handle_alignment_assumption
  - lib/ubsan.c:__ubsan_handle_load_invalid_value
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
  - lib/ubsan.c:__ubsan_handle_out_of_bounds
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:__ubsan_handle_divrem_overflow
```
**Symbols:**

```
ffffffff810ff760-ffffffff810ff7be: check_panic_on_warn (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
