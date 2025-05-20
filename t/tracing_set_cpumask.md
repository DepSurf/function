# Function: <code>tracing_set_cpumask</code>

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
int tracing_set_cpumask(struct trace_array *tr, cpumask_var_t tracing_cpumask_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c3950)
Location: kernel/trace/trace.c:4657
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811c3950-ffffffff811c3a6e: tracing_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tracing_set_cpumask(struct trace_array *tr, cpumask_var_t tracing_cpumask_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c1560)
Location: kernel/trace/trace.c:4725
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811c1560-ffffffff811c167e: tracing_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tracing_set_cpumask(struct trace_array *tr, cpumask_var_t tracing_cpumask_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c2590)
Location: kernel/trace/trace.c:5063
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811c2590-ffffffff811c26ae: tracing_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tracing_set_cpumask(struct trace_array *tr, cpumask_var_t tracing_cpumask_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ed200)
Location: kernel/trace/trace.c:5137
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811ed200-ffffffff811ed382: tracing_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tracing_set_cpumask(struct trace_array *tr, cpumask_var_t tracing_cpumask_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81225370)
Location: kernel/trace/trace.c:5138
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff81225370-ffffffff81225531: tracing_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tracing_set_cpumask(struct trace_array *tr, cpumask_var_t tracing_cpumask_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81270570)
Location: kernel/trace/trace.c:5162
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff81270570-ffffffff8127073e: tracing_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tracing_set_cpumask(struct trace_array *tr, cpumask_var_t tracing_cpumask_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:5268
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff820dc0bf-ffffffff820dc0d4: tracing_set_cpumask.cold (STB_LOCAL)
ffffffff812877d0-ffffffff81287a0f: tracing_set_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tracing_set_cpumask(struct trace_array *tr, cpumask_var_t tracing_cpumask_new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:5286
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_cpumask_write
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff821b7f4f-ffffffff821b7f64: tracing_set_cpumask.cold (STB_LOCAL)
ffffffff812a2ae0-ffffffff812a2d1f: tracing_set_cpumask (STB_GLOBAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
