# Function: <code>__rv_disable_monitor</code>

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
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __rv_disable_monitor(struct rv_monitor_def *mdef, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/rv/rv.c (ffffffff812bc4da)
Location: kernel/trace/rv/rv.c:226
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:enabled_monitors_open
  - kernel/trace/rv/rv.c:enabled_monitors_open
Direct callers:
  - kernel/trace/rv/rv.c:rv_unregister_monitor
  - kernel/trace/rv/rv.c:enabled_monitors_write
  - kernel/trace/rv/rv.c:monitor_enable_write_data
```
**Symbols:**

```
ffffffff812bc160-ffffffff812bc1df: __rv_disable_monitor (STB_LOCAL)
ffffffff8205f3e0-ffffffff8205f3f5: __rv_disable_monitor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __rv_disable_monitor(struct rv_monitor_def *mdef, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/rv/rv.c (ffffffff812e2d8e)
Location: kernel/trace/rv/rv.c:226
Inline: True
Direct callers:
  - kernel/trace/rv/rv.c:rv_unregister_monitor
  - kernel/trace/rv/rv.c:enabled_monitors_write
  - kernel/trace/rv/rv.c:enabled_monitors_open
  - kernel/trace/rv/rv.c:monitor_enable_write_data
```
**Symbols:**

```
ffffffff812e2d50-ffffffff812e2dcf: __rv_disable_monitor (STB_LOCAL)
ffffffff820de326-ffffffff820de33b: __rv_disable_monitor.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __rv_disable_monitor(struct rv_monitor_def *mdef, bool sync);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/rv/rv.c (ffffffff81300dde)
Location: kernel/trace/rv/rv.c:226
Inline: True
Direct callers:
  - kernel/trace/rv/rv.c:rv_unregister_monitor
  - kernel/trace/rv/rv.c:enabled_monitors_write
  - kernel/trace/rv/rv.c:enabled_monitors_open
  - kernel/trace/rv/rv.c:monitor_enable_write_data
```
**Symbols:**

```
ffffffff81300da0-ffffffff81300e1f: __rv_disable_monitor (STB_LOCAL)
ffffffff821ba1a4-ffffffff821ba1b9: __rv_disable_monitor.cold (STB_LOCAL)
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
