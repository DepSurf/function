# Function: <code>kfence_print_stack</code>

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
void kfence_print_stack(struct seq_file *seq, const struct kfence_metadata *meta, bool show_alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff8133ce30)
Location: mm/kfence/report.c:100
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_object
```
**Symbols:**

```
ffffffff8133ce30-ffffffff8133cfb2: kfence_print_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kfence_print_stack(struct seq_file *seq, const struct kfence_metadata *meta, bool show_alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff813b02d0)
Location: mm/kfence/report.c:100
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_object
```
**Symbols:**

```
ffffffff813b02d0-ffffffff813b046c: kfence_print_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kfence_print_stack(struct seq_file *seq, const struct kfence_metadata *meta, bool show_alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff81430940)
Location: mm/kfence/report.c:106
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_object
```
**Symbols:**

```
ffffffff81430940-ffffffff81430adc: kfence_print_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kfence_print_stack(struct seq_file *seq, const struct kfence_metadata *meta, bool show_alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff814662a0)
Location: mm/kfence/report.c:106
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_object
```
**Symbols:**

```
ffffffff814662a0-ffffffff8146643d: kfence_print_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kfence_print_stack(struct seq_file *seq, const struct kfence_metadata *meta, bool show_alloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff814954b0)
Location: mm/kfence/report.c:105
Inline: False
Direct callers:
  - mm/kfence/report.c:kfence_print_object
  - mm/kfence/report.c:kfence_print_object
```
**Symbols:**

```
ffffffff814954b0-ffffffff8149564d: kfence_print_stack (STB_LOCAL)
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
