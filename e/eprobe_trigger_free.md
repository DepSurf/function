# Function: <code>eprobe_trigger_free</code>

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
void eprobe_trigger_free(struct event_trigger_ops *ops, struct event_trigger_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff81208f70)
Location: kernel/trace/trace_eprobe.c:528
Inline: False
```
**Symbols:**

```
ffffffff81208f70-ffffffff81208f71: eprobe_trigger_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void eprobe_trigger_free(struct event_trigger_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff81244dd0)
Location: kernel/trace/trace_eprobe.c:594
Inline: False
```
**Symbols:**

```
ffffffff81244dd0-ffffffff81244dd5: eprobe_trigger_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void eprobe_trigger_free(struct event_trigger_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff81292bd0)
Location: kernel/trace/trace_eprobe.c:549
Inline: False
```
**Symbols:**

```
ffffffff81292bd0-ffffffff81292bd5: eprobe_trigger_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void eprobe_trigger_free(struct event_trigger_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff812afe30)
Location: kernel/trace/trace_eprobe.c:453
Inline: False
```
**Symbols:**

```
ffffffff812afe30-ffffffff812afe35: eprobe_trigger_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void eprobe_trigger_free(struct event_trigger_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff812cc3a0)
Location: kernel/trace/trace_eprobe.c:457
Inline: False
```
**Symbols:**

```
ffffffff812cc3a0-ffffffff812cc3a5: eprobe_trigger_free (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct event_trigger_ops *ops</code>
</li>
<li>
<b>Param reordered. </b>
<code>ops, data</code> ➡️ <code>data</code>
</li>
</ul>
</details>
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
