# Function: <code>devlink_to_dev</code>

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
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct device *devlink_to_dev(const struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c74634)
Location: net/core/devlink.c:133
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_trap_report
  - net/core/devlink.c:perf_trace_devlink_trap_report
  - net/core/devlink.c:perf_trace_devlink_trap_report
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_trap_report
  - net/core/devlink.c:trace_event_raw_event_devlink_trap_report
  - net/core/devlink.c:trace_event_raw_event_devlink_trap_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_reporter_state_update
  - net/core/devlink.c:trace_event_raw_event_devlink_health_reporter_state_update
  - net/core/devlink.c:trace_event_raw_event_devlink_health_reporter_state_update
  - net/core/devlink.c:trace_event_raw_event_devlink_health_recover_aborted
  - net/core/devlink.c:trace_event_raw_event_devlink_health_recover_aborted
  - net/core/devlink.c:trace_event_raw_event_devlink_health_recover_aborted
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_hwerr
  - net/core/devlink.c:trace_event_raw_event_devlink_hwerr
  - net/core/devlink.c:trace_event_raw_event_devlink_hwerr
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
```
**Symbols:**

```
ffffffff81c72420-ffffffff81c72438: devlink_to_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct device *devlink_to_dev(const struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2d252)
Location: net/core/devlink.c:137
Inline: True
Inline callers:
  - net/core/devlink.c:perf_trace_devlink_trap_report
  - net/core/devlink.c:perf_trace_devlink_trap_report
  - net/core/devlink.c:perf_trace_devlink_trap_report
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_reporter_state_update
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_recover_aborted
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_health_report
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwerr
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:perf_trace_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_trap_report
  - net/core/devlink.c:trace_event_raw_event_devlink_trap_report
  - net/core/devlink.c:trace_event_raw_event_devlink_trap_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_reporter_state_update
  - net/core/devlink.c:trace_event_raw_event_devlink_health_reporter_state_update
  - net/core/devlink.c:trace_event_raw_event_devlink_health_reporter_state_update
  - net/core/devlink.c:trace_event_raw_event_devlink_health_recover_aborted
  - net/core/devlink.c:trace_event_raw_event_devlink_health_recover_aborted
  - net/core/devlink.c:trace_event_raw_event_devlink_health_recover_aborted
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_health_report
  - net/core/devlink.c:trace_event_raw_event_devlink_hwerr
  - net/core/devlink.c:trace_event_raw_event_devlink_hwerr
  - net/core/devlink.c:trace_event_raw_event_devlink_hwerr
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
  - net/core/devlink.c:trace_event_raw_event_devlink_hwmsg
  - net/core/devlink.c:trace_event_get_offsets_devlink_health_report
  - net/core/devlink.c:trace_event_get_offsets_devlink_health_report
  - net/core/devlink.c:trace_event_get_offsets_devlink_health_report
```
**Symbols:**

```
ffffffff81e2a650-ffffffff81e2a668: devlink_to_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct device *devlink_to_dev(const struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/core.c (ffffffff82041cf0)
Location: net/devlink/core.c:25
Inline: False
Direct callers:
  - net/devlink/leftover.c:perf_trace_devlink_trap_report
  - net/devlink/leftover.c:perf_trace_devlink_trap_report
  - net/devlink/leftover.c:perf_trace_devlink_trap_report
  - net/devlink/leftover.c:perf_trace_devlink_trap_report
  - net/devlink/leftover.c:perf_trace_devlink_trap_report
  - net/devlink/leftover.c:perf_trace_devlink_trap_report
  - net/devlink/leftover.c:perf_trace_devlink_health_reporter_state_update
  - net/devlink/leftover.c:perf_trace_devlink_health_reporter_state_update
  - net/devlink/leftover.c:perf_trace_devlink_health_reporter_state_update
  - net/devlink/leftover.c:perf_trace_devlink_health_reporter_state_update
  - net/devlink/leftover.c:perf_trace_devlink_health_reporter_state_update
  - net/devlink/leftover.c:perf_trace_devlink_health_reporter_state_update
  - net/devlink/leftover.c:perf_trace_devlink_health_recover_aborted
  - net/devlink/leftover.c:perf_trace_devlink_health_recover_aborted
  - net/devlink/leftover.c:perf_trace_devlink_health_recover_aborted
  - net/devlink/leftover.c:perf_trace_devlink_health_recover_aborted
  - net/devlink/leftover.c:perf_trace_devlink_health_recover_aborted
  - net/devlink/leftover.c:perf_trace_devlink_health_recover_aborted
  - net/devlink/leftover.c:perf_trace_devlink_health_report
  - net/devlink/leftover.c:perf_trace_devlink_health_report
  - net/devlink/leftover.c:perf_trace_devlink_health_report
  - net/devlink/leftover.c:perf_trace_devlink_health_report
  - net/devlink/leftover.c:perf_trace_devlink_health_report
  - net/devlink/leftover.c:perf_trace_devlink_health_report
  - net/devlink/leftover.c:perf_trace_devlink_hwerr
  - net/devlink/leftover.c:perf_trace_devlink_hwerr
  - net/devlink/leftover.c:perf_trace_devlink_hwerr
  - net/devlink/leftover.c:perf_trace_devlink_hwerr
  - net/devlink/leftover.c:perf_trace_devlink_hwerr
  - net/devlink/leftover.c:perf_trace_devlink_hwerr
  - net/devlink/leftover.c:perf_trace_devlink_hwmsg
  - net/devlink/leftover.c:perf_trace_devlink_hwmsg
  - net/devlink/leftover.c:perf_trace_devlink_hwmsg
  - net/devlink/leftover.c:perf_trace_devlink_hwmsg
  - net/devlink/leftover.c:perf_trace_devlink_hwmsg
  - net/devlink/leftover.c:perf_trace_devlink_hwmsg
  - net/devlink/leftover.c:trace_event_raw_event_devlink_trap_report
  - net/devlink/leftover.c:trace_event_raw_event_devlink_trap_report
  - net/devlink/leftover.c:trace_event_raw_event_devlink_trap_report
  - net/devlink/leftover.c:trace_event_raw_event_devlink_trap_report
  - net/devlink/leftover.c:trace_event_raw_event_devlink_trap_report
  - net/devlink/leftover.c:trace_event_raw_event_devlink_trap_report
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_reporter_state_update
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_reporter_state_update
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_reporter_state_update
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_reporter_state_update
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_reporter_state_update
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_reporter_state_update
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_recover_aborted
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_recover_aborted
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_recover_aborted
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_recover_aborted
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_recover_aborted
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_recover_aborted
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_report
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_report
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_report
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_report
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_report
  - net/devlink/leftover.c:trace_event_raw_event_devlink_health_report
  - net/devlink/leftover.c:trace_event_raw_event_devlink_hwerr
  - net/devlink/leftover.c:trace_event_raw_event_devlink_hwerr
  - net/devlink/leftover.c:trace_event_raw_event_devlink_hwerr
  - net/devlink/leftover.c:trace_event_raw_event_devlink_hwerr
  - net/devlink/leftover.c:trace_event_raw_event_devlink_hwerr
  - net/devlink/leftover.c:trace_event_raw_event_devlink_hwerr
  - net/devlink/leftover.c:trace_event_raw_event_devlink_hwmsg
  - net/devlink/leftover.c:trace_event_raw_event_devlink_hwmsg
  - net/devlink/leftover.c:trace_event_raw_event_devlink_hwmsg
  - net/devlink/leftover.c:trace_event_raw_event_devlink_hwmsg
  - net/devlink/leftover.c:trace_event_raw_event_devlink_hwmsg
  - net/devlink/leftover.c:trace_event_raw_event_devlink_hwmsg
  - net/devlink/leftover.c:trace_event_get_offsets_devlink_health_report
  - net/devlink/leftover.c:trace_event_get_offsets_devlink_health_report
  - net/devlink/leftover.c:trace_event_get_offsets_devlink_health_report
  - net/devlink/leftover.c:trace_event_get_offsets_devlink_health_report
  - net/devlink/leftover.c:trace_event_get_offsets_devlink_health_report
  - net/devlink/leftover.c:trace_event_get_offsets_devlink_health_report
```
**Symbols:**

```
ffffffff82041cf0-ffffffff82041d08: devlink_to_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct device *devlink_to_dev(const struct devlink *devlink);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/devlink/core.c (ffffffff820ff1b9)
Location: net/devlink/core.c:247
Inline: True
Inline callers:
  - net/devlink/core.c:perf_trace_devlink_trap_report
  - net/devlink/core.c:perf_trace_devlink_trap_report
  - net/devlink/core.c:perf_trace_devlink_trap_report
  - net/devlink/core.c:perf_trace_devlink_health_reporter_state_update
  - net/devlink/core.c:perf_trace_devlink_health_reporter_state_update
  - net/devlink/core.c:perf_trace_devlink_health_reporter_state_update
  - net/devlink/core.c:perf_trace_devlink_health_recover_aborted
  - net/devlink/core.c:perf_trace_devlink_health_recover_aborted
  - net/devlink/core.c:perf_trace_devlink_health_recover_aborted
  - net/devlink/core.c:perf_trace_devlink_health_report
  - net/devlink/core.c:perf_trace_devlink_health_report
  - net/devlink/core.c:perf_trace_devlink_health_report
  - net/devlink/core.c:perf_trace_devlink_hwerr
  - net/devlink/core.c:perf_trace_devlink_hwerr
  - net/devlink/core.c:perf_trace_devlink_hwerr
  - net/devlink/core.c:perf_trace_devlink_hwmsg
  - net/devlink/core.c:perf_trace_devlink_hwmsg
  - net/devlink/core.c:perf_trace_devlink_hwmsg
  - net/devlink/core.c:trace_event_raw_event_devlink_trap_report
  - net/devlink/core.c:trace_event_raw_event_devlink_trap_report
  - net/devlink/core.c:trace_event_raw_event_devlink_trap_report
  - net/devlink/core.c:trace_event_raw_event_devlink_health_reporter_state_update
  - net/devlink/core.c:trace_event_raw_event_devlink_health_reporter_state_update
  - net/devlink/core.c:trace_event_raw_event_devlink_health_reporter_state_update
  - net/devlink/core.c:trace_event_raw_event_devlink_health_recover_aborted
  - net/devlink/core.c:trace_event_raw_event_devlink_health_recover_aborted
  - net/devlink/core.c:trace_event_raw_event_devlink_health_recover_aborted
  - net/devlink/core.c:trace_event_raw_event_devlink_health_report
  - net/devlink/core.c:trace_event_raw_event_devlink_health_report
  - net/devlink/core.c:trace_event_raw_event_devlink_health_report
  - net/devlink/core.c:trace_event_raw_event_devlink_hwerr
  - net/devlink/core.c:trace_event_raw_event_devlink_hwerr
  - net/devlink/core.c:trace_event_raw_event_devlink_hwerr
  - net/devlink/core.c:trace_event_raw_event_devlink_hwmsg
  - net/devlink/core.c:trace_event_raw_event_devlink_hwmsg
  - net/devlink/core.c:trace_event_raw_event_devlink_hwmsg
  - net/devlink/core.c:trace_event_get_offsets_devlink_health_report
  - net/devlink/core.c:trace_event_get_offsets_devlink_health_report
  - net/devlink/core.c:trace_event_get_offsets_devlink_health_report
```
**Symbols:**

```
ffffffff820fde30-ffffffff820fde48: devlink_to_dev (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
