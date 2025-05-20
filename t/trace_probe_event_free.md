# Function: <code>trace_probe_event_free</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void trace_probe_event_free(struct trace_probe_event *tpe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811d5a00)
Location: kernel/trace/trace_probe.c:947
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
**Symbols:**

```
ffffffff811d5a00-ffffffff811d5a35: trace_probe_event_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f41b5)
Location: kernel/trace/trace_probe.c:947
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f2b65)
Location: kernel/trace/trace_probe.c:947
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f39f5)
Location: kernel/trace/trace_probe.c:947
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81224cb5)
Location: kernel/trace/trace_probe.c:979
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81264b2f)
Location: kernel/trace/trace_probe.c:986
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812b669f)
Location: kernel/trace/trace_probe.c:1009
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812d9b8f)
Location: kernel/trace/trace_probe.c:1490
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812f7aef)
Location: kernel/trace/trace_probe.c:1727
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void trace_probe_event_free(struct trace_probe_event *tpe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffff800010255dd8)
Location: kernel/trace/trace_probe.c:947
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
**Symbols:**

```
ffff800010255dd8-ffff800010255e14: trace_probe_event_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void trace_probe_event_free(struct trace_probe_event *tpe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c0488f00)
Location: kernel/trace/trace_probe.c:947
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
**Symbols:**

```
c0488f00-c0488f34: trace_probe_event_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void trace_probe_event_free(struct trace_probe_event *tpe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (c0000000002f60c0)
Location: kernel/trace/trace_probe.c:947
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
**Symbols:**

```
c0000000002f60c0-c0000000002f6120: trace_probe_event_free (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void trace_probe_event_free(struct trace_probe_event *tpe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811ce020)
Location: kernel/trace/trace_probe.c:947
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
**Symbols:**

```
ffffffff811ce020-ffffffff811ce055: trace_probe_event_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void trace_probe_event_free(struct trace_probe_event *tpe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811c0df0)
Location: kernel/trace/trace_probe.c:947
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
**Symbols:**

```
ffffffff811c0df0-ffffffff811c0e25: trace_probe_event_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void trace_probe_event_free(struct trace_probe_event *tpe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811cbdf0)
Location: kernel/trace/trace_probe.c:947
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
**Symbols:**

```
ffffffff811cbdf0-ffffffff811cbe25: trace_probe_event_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void trace_probe_event_free(struct trace_probe_event *tpe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811da050)
Location: kernel/trace/trace_probe.c:947
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
```
**Symbols:**

```
ffffffff811da050-ffffffff811da085: trace_probe_event_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
