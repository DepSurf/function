# Function: <code>resctrl_arch_rmid_read</code>

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
int resctrl_arch_rmid_read(struct rdt_resource *r, struct rdt_domain *d, u32 rmid, enum resctrl_event_id eventid, u64 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:215
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
**Symbols:**

```
ffffffff820535e8-ffffffff82053634: resctrl_arch_rmid_read.cold (STB_LOCAL)
ffffffff8108a6b0-ffffffff8108a7f9: resctrl_arch_rmid_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int resctrl_arch_rmid_read(struct rdt_resource *r, struct rdt_domain *d, u32 rmid, enum resctrl_event_id eventid, u64 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:232
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
**Symbols:**

```
ffffffff820d1bfa-ffffffff820d1c42: resctrl_arch_rmid_read.cold (STB_LOCAL)
ffffffff8108d790-ffffffff8108d8cc: resctrl_arch_rmid_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int resctrl_arch_rmid_read(struct rdt_resource *r, struct rdt_domain *d, u32 rmid, enum resctrl_event_id eventid, u64 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: arch/x86/kernel/cpu/resctrl/monitor.c:232
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/monitor.c:__mon_event_count
  - arch/x86/kernel/cpu/resctrl/monitor.c:add_rmid_to_limbo
  - arch/x86/kernel/cpu/resctrl/monitor.c:__check_limbo
```
**Symbols:**

```
ffffffff821ac85e-ffffffff821ac8a6: resctrl_arch_rmid_read.cold (STB_LOCAL)
ffffffff81094b20-ffffffff81094c5c: resctrl_arch_rmid_read (STB_GLOBAL)
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
