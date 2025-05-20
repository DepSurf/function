# Function: <code>kallsyms_lookup_names</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
int kallsyms_lookup_names(const char *name, unsigned int *start, unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811fb980)
Location: kernel/kallsyms.c:214
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_on_each_match_symbol
  - kernel/kallsyms.c:kallsyms_lookup_name
```
**Symbols:**

```
ffffffff811fb980-ffffffff811fbba2: kallsyms_lookup_names (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kallsyms_lookup_names(const char *name, unsigned int *start, unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81210e80)
Location: kernel/kallsyms.c:210
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_on_each_match_symbol
  - kernel/kallsyms.c:kallsyms_lookup_name
```
**Symbols:**

```
ffffffff81210e80-ffffffff812110a2: kallsyms_lookup_names (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kallsyms_lookup_names(const char *name, unsigned int *start, unsigned int *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81228500)
Location: kernel/kallsyms.c:208
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_on_each_match_symbol
  - kernel/kallsyms.c:kallsyms_lookup_name
```
**Symbols:**

```
ffffffff81228500-ffffffff81228722: kallsyms_lookup_names (STB_LOCAL)
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
