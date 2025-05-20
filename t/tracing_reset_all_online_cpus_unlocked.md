# Function: <code>tracing_reset_all_online_cpus_unlocked</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tracing_reset_all_online_cpus_unlocked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:2183
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace_events.c:trace_module_notify
```
**Symbols:**

```
ffffffff8205d5a5-ffffffff8205d5ba: tracing_reset_all_online_cpus_unlocked.cold (STB_LOCAL)
ffffffff8126b1c0-ffffffff8126b221: tracing_reset_all_online_cpus_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tracing_reset_all_online_cpus_unlocked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:2254
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace_events.c:trace_module_notify
```
**Symbols:**

```
ffffffff820dbf5e-ffffffff820dbf73: tracing_reset_all_online_cpus_unlocked.cold (STB_LOCAL)
ffffffff81282330-ffffffff81282391: tracing_reset_all_online_cpus_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tracing_reset_all_online_cpus_unlocked();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:2278
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace_events.c:trace_module_notify
```
**Symbols:**

```
ffffffff821b7dec-ffffffff821b7e01: tracing_reset_all_online_cpus_unlocked.cold (STB_LOCAL)
ffffffff8129d4b0-ffffffff8129d511: tracing_reset_all_online_cpus_unlocked (STB_GLOBAL)
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
