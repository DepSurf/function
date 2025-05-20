# Function: <code>get_eprobe_size</code>

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
int get_eprobe_size(struct trace_probe *tp, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_eprobe.c:340
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
**Symbols:**

```
ffffffff81209180-ffffffff81209803: get_eprobe_size (STB_LOCAL)
ffffffff81cb67dc-ffffffff81cb691c: get_eprobe_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int get_eprobe_size(struct trace_probe *tp, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_eprobe.c:375
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
**Symbols:**

```
ffffffff81245070-ffffffff8124577a: get_eprobe_size (STB_LOCAL)
ffffffff81e677be-ffffffff81e67970: get_eprobe_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int get_eprobe_size(struct trace_probe *tp, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_eprobe.c:381
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
**Symbols:**

```
ffffffff812942e0-ffffffff81294b7c: get_eprobe_size (STB_LOCAL)
ffffffff8205e222-ffffffff8205e37a: get_eprobe_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int get_eprobe_size(struct trace_probe *tp, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_eprobe.c:351
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
**Symbols:**

```
ffffffff812b1ad0-ffffffff812b23a6: get_eprobe_size (STB_LOCAL)
ffffffff820dcdf1-ffffffff820dcfad: get_eprobe_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int get_eprobe_size(struct trace_probe *tp, void *rec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_eprobe.c:355
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
**Symbols:**

```
ffffffff812ce080-ffffffff812ce956: get_eprobe_size (STB_LOCAL)
ffffffff821b8bf5-ffffffff821b8db1: get_eprobe_size.cold (STB_LOCAL)
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
