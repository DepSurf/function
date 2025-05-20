# Function: <code>cxl_mem_active</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
bool cxl_mem_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cxl/core/suspend.c (ffffffff819f63c0)
Location: drivers/cxl/core/suspend.c:9
Inline: False
Direct callers:
  - kernel/power/main.c:mem_sleep_show
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff819f63c0-ffffffff819f63da: cxl_mem_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool cxl_mem_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cxl/core/suspend.c (ffffffff81b739d0)
Location: drivers/cxl/core/suspend.c:9
Inline: False
Direct callers:
  - kernel/power/main.c:mem_sleep_show
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff81b739d0-ffffffff81b739ea: cxl_mem_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool cxl_mem_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cxl/core/suspend.c (ffffffff81bc7140)
Location: drivers/cxl/core/suspend.c:9
Inline: False
Direct callers:
  - kernel/power/main.c:mem_sleep_show
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume_initcall
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff81bc7140-ffffffff81bc715a: cxl_mem_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool cxl_mem_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cxl/core/suspend.c (ffffffff81c1bcb0)
Location: drivers/cxl/core/suspend.c:9
Inline: False
Direct callers:
  - kernel/power/main.c:mem_sleep_show
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:resume_store
  - kernel/power/hibernate.c:disk_store
  - kernel/power/hibernate.c:software_resume_initcall
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff81c1bcb0-ffffffff81c1bcca: cxl_mem_active (STB_GLOBAL)
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
