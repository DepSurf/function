# Function: <code>rv_disable_monitor</code>

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
int rv_disable_monitor(struct rv_monitor_def *mdef);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/rv/rv.c (ffffffff812bccc1)
Location: kernel/trace/rv/rv.c:251
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:rv_unregister_monitor
  - kernel/trace/rv/rv.c:enabled_monitors_write
  - kernel/trace/rv/rv.c:monitor_enable_write_data
Direct callers:
  - kernel/trace/rv/rv_reactors.c:monitor_reactors_write
```
**Symbols:**

```
ffffffff8205f4de-ffffffff8205f4f3: rv_disable_monitor.cold (STB_LOCAL)
ffffffff812bc6f0-ffffffff812bc74d: rv_disable_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int rv_disable_monitor(struct rv_monitor_def *mdef);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/rv/rv.c (ffffffff812e3891)
Location: kernel/trace/rv/rv.c:251
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:rv_unregister_monitor
  - kernel/trace/rv/rv.c:enabled_monitors_write
  - kernel/trace/rv/rv.c:monitor_enable_write_data
Direct callers:
  - kernel/trace/rv/rv_reactors.c:monitor_reactors_write
```
**Symbols:**

```
ffffffff820de40f-ffffffff820de424: rv_disable_monitor.cold (STB_LOCAL)
ffffffff812e32b0-ffffffff812e330d: rv_disable_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int rv_disable_monitor(struct rv_monitor_def *mdef);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/rv/rv.c (ffffffff81301911)
Location: kernel/trace/rv/rv.c:251
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:rv_unregister_monitor
  - kernel/trace/rv/rv.c:enabled_monitors_write
  - kernel/trace/rv/rv.c:monitor_enable_write_data
Direct callers:
  - kernel/trace/rv/rv_reactors.c:monitor_reactors_write
```
**Symbols:**

```
ffffffff821ba28d-ffffffff821ba2a2: rv_disable_monitor.cold (STB_LOCAL)
ffffffff81301300-ffffffff8130135d: rv_disable_monitor (STB_GLOBAL)
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
