# Function: <code>get_stack_skipnr</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_stack_skipnr(const long unsigned int *stack_entries, int num_entries, const enum kfence_error_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff8133cc40)
Location: mm/kfence/report.c:49
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_report_error
  - mm/kfence/report.c:kfence_print_stack
```
**Symbols:**

```
ffffffff8133cc40-ffffffff8133ce26: get_stack_skipnr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_stack_skipnr(const long unsigned int *stack_entries, int num_entries, const enum kfence_error_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff813b00e0)
Location: mm/kfence/report.c:49
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_to_kp_stack
  - mm/kfence/report.c:kfence_report_error
  - mm/kfence/report.c:kfence_print_stack
```
**Symbols:**

```
ffffffff813b00e0-ffffffff813b02ce: get_stack_skipnr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_stack_skipnr(const long unsigned int *stack_entries, int num_entries, const enum kfence_error_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff81430700)
Location: mm/kfence/report.c:49
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_to_kp_stack
  - mm/kfence/report.c:kfence_report_error
  - mm/kfence/report.c:kfence_print_stack
```
**Symbols:**

```
ffffffff81430700-ffffffff81430922: get_stack_skipnr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_stack_skipnr(const long unsigned int *stack_entries, int num_entries, const enum kfence_error_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff81466060)
Location: mm/kfence/report.c:49
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_to_kp_stack
  - mm/kfence/report.c:kfence_report_error
  - mm/kfence/report.c:kfence_print_stack
```
**Symbols:**

```
ffffffff81466060-ffffffff81466282: get_stack_skipnr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_stack_skipnr(const long unsigned int *stack_entries, int num_entries, const enum kfence_error_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff81495270)
Location: mm/kfence/report.c:48
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_to_kp_stack
  - mm/kfence/report.c:kfence_report_error
  - mm/kfence/report.c:kfence_print_stack
```
**Symbols:**

```
ffffffff81495270-ffffffff81495492: get_stack_skipnr (STB_LOCAL)
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
