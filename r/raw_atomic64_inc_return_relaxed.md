# Function: <code>raw_atomic64_inc_return_relaxed</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8111e2cb)
Location: include/linux/atomic/atomic-arch-fallback.h:3193
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_cpu_intensive_report
```
```
In drivers/regulator/core.c (ffffffff81a822fc)
Location: include/linux/atomic/atomic-arch-fallback.h:3193
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_lock_dependent
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81127ffb)
Location: include/linux/atomic/atomic-arch-fallback.h:3198
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_cpu_intensive_report
```
```
In drivers/regulator/core.c (ffffffff81ad48dc)
Location: include/linux/atomic/atomic-arch-fallback.h:3198
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_summary_show
  - drivers/regulator/core.c:regulator_resolve_supply
  - drivers/regulator/core.c:regulator_lock_dependent
```
```
In drivers/gpu/drm/drm_gem.c (ffffffff81c9baf1)
Location: include/linux/atomic/atomic-arch-fallback.h:3198
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem.c:drm_gem_lock_reservations
```
```
In drivers/gpu/drm/drm_modeset_lock.c (ffffffff81ca891f)
Location: include/linux/atomic/atomic-arch-fallback.h:3198
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_acquire_init
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
