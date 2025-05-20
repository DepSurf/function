# Function: <code>kfence_report_error</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void kfence_report_error(long unsigned int address, bool is_write, struct pt_regs *regs, const struct kfence_metadata *meta, enum kfence_error_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/kfence/report.c (0)
Location: mm/kfence/report.c:180
Inline: False
Direct callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
```
**Symbols:**

```
ffffffff81cc1ebf-ffffffff81cc2536: kfence_report_error.cold (STB_LOCAL)
ffffffff8133d0b0-ffffffff8133d1b8: kfence_report_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void kfence_report_error(long unsigned int address, bool is_write, struct pt_regs *regs, const struct kfence_metadata *meta, enum kfence_error_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/kfence/report.c (0)
Location: mm/kfence/report.c:180
Inline: False
Direct callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_check_all_canary
  - mm/kfence/core.c:kfence_check_all_canary
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
```
**Symbols:**

```
ffffffff81e74447-ffffffff81e74b07: kfence_report_error.cold (STB_LOCAL)
ffffffff813b0620-ffffffff813b0747: kfence_report_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void kfence_report_error(long unsigned int address, bool is_write, struct pt_regs *regs, const struct kfence_metadata *meta, enum kfence_error_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/kfence/report.c (0)
Location: mm/kfence/report.c:186
Inline: False
Direct callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_check_all_canary
  - mm/kfence/core.c:kfence_check_all_canary
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
```
**Symbols:**

```
ffffffff8206797a-ffffffff820679af: kfence_report_error.cold (STB_LOCAL)
ffffffff81430cc0-ffffffff81431294: kfence_report_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void kfence_report_error(long unsigned int address, bool is_write, struct pt_regs *regs, const struct kfence_metadata *meta, enum kfence_error_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/kfence/report.c (0)
Location: mm/kfence/report.c:186
Inline: False
Direct callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:check_canary
  - mm/kfence/core.c:check_canary
```
**Symbols:**

```
ffffffff820e72a8-ffffffff820e72dd: kfence_report_error.cold (STB_LOCAL)
ffffffff81466650-ffffffff81466c14: kfence_report_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void kfence_report_error(long unsigned int address, bool is_write, struct pt_regs *regs, const struct kfence_metadata *meta, enum kfence_error_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/kfence/report.c (0)
Location: mm/kfence/report.c:185
Inline: False
Direct callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:check_canary
  - mm/kfence/core.c:check_canary
```
**Symbols:**

```
ffffffff821c3e6e-ffffffff821c3ea3: kfence_report_error.cold (STB_LOCAL)
ffffffff81495860-ffffffff81495e25: kfence_report_error (STB_GLOBAL)
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
