# Function: <code>rv_enable_monitor</code>

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
int rv_enable_monitor(struct rv_monitor_def *mdef);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/rv/rv.c (ffffffff812bc788)
Location: kernel/trace/rv/rv.c:262
Inline: True
Direct callers:
  - kernel/trace/rv/rv.c:enabled_monitors_write
  - kernel/trace/rv/rv.c:monitor_enable_write_data
  - kernel/trace/rv/rv_reactors.c:monitor_reactors_write
```
**Symbols:**

```
ffffffff8205f4f3-ffffffff8205f508: rv_enable_monitor.cold (STB_LOCAL)
ffffffff812bc760-ffffffff812bc7b0: rv_enable_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int rv_enable_monitor(struct rv_monitor_def *mdef);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/rv/rv.c (ffffffff812e334a)
Location: kernel/trace/rv/rv.c:262
Inline: True
Direct callers:
  - kernel/trace/rv/rv.c:enabled_monitors_write
  - kernel/trace/rv/rv.c:monitor_enable_write_data
  - kernel/trace/rv/rv_reactors.c:monitor_reactors_write
```
**Symbols:**

```
ffffffff820de424-ffffffff820de439: rv_enable_monitor.cold (STB_LOCAL)
ffffffff812e3320-ffffffff812e3372: rv_enable_monitor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int rv_enable_monitor(struct rv_monitor_def *mdef);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/rv/rv.c (ffffffff8130139a)
Location: kernel/trace/rv/rv.c:262
Inline: True
Direct callers:
  - kernel/trace/rv/rv.c:enabled_monitors_write
  - kernel/trace/rv/rv.c:monitor_enable_write_data
  - kernel/trace/rv/rv_reactors.c:monitor_reactors_write
```
**Symbols:**

```
ffffffff821ba2a2-ffffffff821ba2b7: rv_enable_monitor.cold (STB_LOCAL)
ffffffff81301370-ffffffff813013c2: rv_enable_monitor (STB_GLOBAL)
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
