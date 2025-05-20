# Function: <code>seq_con_printf</code>

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
void seq_con_printf(struct seq_file *seq, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff8133cbc0)
Location: mm/kfence/report.c:33
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_stack
  - mm/kfence/report.c:kfence_print_stack
  - mm/kfence/report.c:kfence_print_stack
  - mm/kfence/report.c:kfence_print_stack
```
**Symbols:**

```
ffffffff8133cbc0-ffffffff8133cc3f: seq_con_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void seq_con_printf(struct seq_file *seq, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff813b0040)
Location: mm/kfence/report.c:33
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_stack
  - mm/kfence/report.c:kfence_print_stack
  - mm/kfence/report.c:kfence_print_stack
  - mm/kfence/report.c:kfence_print_stack
```
**Symbols:**

```
ffffffff813b0040-ffffffff813b00db: seq_con_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void seq_con_printf(struct seq_file *seq, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff81430650)
Location: mm/kfence/report.c:33
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_stack
  - mm/kfence/report.c:kfence_print_stack
  - mm/kfence/report.c:kfence_print_stack
  - mm/kfence/report.c:kfence_print_stack
```
**Symbols:**

```
ffffffff81430650-ffffffff814306eb: seq_con_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void seq_con_printf(struct seq_file *seq, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff81465fb0)
Location: mm/kfence/report.c:33
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_stack
  - mm/kfence/report.c:kfence_print_stack
  - mm/kfence/report.c:kfence_print_stack
  - mm/kfence/report.c:kfence_print_stack
```
**Symbols:**

```
ffffffff81465fb0-ffffffff8146604b: seq_con_printf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void seq_con_printf(struct seq_file *seq, const char *fmt, void (anon));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff814951c0)
Location: mm/kfence/report.c:32
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_stack
  - mm/kfence/report.c:kfence_print_stack
  - mm/kfence/report.c:kfence_print_stack
  - mm/kfence/report.c:kfence_print_stack
```
**Symbols:**

```
ffffffff814951c0-ffffffff8149525b: seq_con_printf (STB_LOCAL)
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
