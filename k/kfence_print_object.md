# Function: <code>kfence_print_object</code>

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
void kfence_print_object(struct seq_file *seq, const struct kfence_metadata *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff8133cfc0)
Location: mm/kfence/report.c:124
Inline: False
Direct callers:
  - mm/kfence/core.c:show_object
  - mm/kfence/report.c:kfence_report_error
```
**Symbols:**

```
ffffffff8133cfc0-ffffffff8133d0a6: kfence_print_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kfence_print_object(struct seq_file *seq, const struct kfence_metadata *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff813b0500)
Location: mm/kfence/report.c:124
Inline: False
Direct callers:
  - mm/kfence/core.c:show_object
  - mm/kfence/report.c:kfence_report_error
```
**Symbols:**

```
ffffffff813b0500-ffffffff813b061a: kfence_print_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kfence_print_object(struct seq_file *seq, const struct kfence_metadata *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff81430b90)
Location: mm/kfence/report.c:130
Inline: False
Direct callers:
  - mm/kfence/core.c:show_object
  - mm/kfence/report.c:kfence_report_error
```
**Symbols:**

```
ffffffff81430b90-ffffffff81430caa: kfence_print_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kfence_print_object(struct seq_file *seq, const struct kfence_metadata *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff81466520)
Location: mm/kfence/report.c:130
Inline: False
Direct callers:
  - mm/kfence/core.c:show_object
  - mm/kfence/report.c:kfence_report_error
```
**Symbols:**

```
ffffffff81466520-ffffffff8146663a: kfence_print_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kfence_print_object(struct seq_file *seq, const struct kfence_metadata *meta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff81495730)
Location: mm/kfence/report.c:129
Inline: False
Direct callers:
  - mm/kfence/core.c:show_object
  - mm/kfence/report.c:kfence_report_error
```
**Symbols:**

```
ffffffff81495730-ffffffff8149584a: kfence_print_object (STB_GLOBAL)
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
