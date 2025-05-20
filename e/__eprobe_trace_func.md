# Function: <code>__eprobe_trace_func</code>

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
void __eprobe_trace_func(struct eprobe_data *edata, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_eprobe.c:479
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_trigger_func
```
**Symbols:**

```
ffffffff81209ef0-ffffffff8120a11d: __eprobe_trace_func (STB_LOCAL)
ffffffff81cb6a48-ffffffff81cb6a9b: __eprobe_trace_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __eprobe_trace_func(struct eprobe_data *edata, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_eprobe.c:556
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_trigger_func
```
**Symbols:**

```
ffffffff81245dd0-ffffffff81245fb8: __eprobe_trace_func (STB_LOCAL)
ffffffff81e67a9e-ffffffff81e67aec: __eprobe_trace_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __eprobe_trace_func(struct eprobe_data *edata, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_eprobe.c:511
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_trigger_func
```
**Symbols:**

```
ffffffff81295470-ffffffff81295658: __eprobe_trace_func (STB_LOCAL)
ffffffff8205e506-ffffffff8205e554: __eprobe_trace_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __eprobe_trace_func(struct eprobe_data *edata, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_eprobe.c:415
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_trigger_func
```
**Symbols:**

```
ffffffff812b23c0-ffffffff812b2567: __eprobe_trace_func (STB_LOCAL)
ffffffff820dcfad-ffffffff820dd009: __eprobe_trace_func.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __eprobe_trace_func(struct eprobe_data *edata, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_eprobe.c:419
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_trigger_func
```
**Symbols:**

```
ffffffff812ce970-ffffffff812ceb17: __eprobe_trace_func (STB_LOCAL)
ffffffff821b8db1-ffffffff821b8e0d: __eprobe_trace_func.cold (STB_LOCAL)
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
