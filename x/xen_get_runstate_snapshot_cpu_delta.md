# Function: <code>xen_get_runstate_snapshot_cpu_delta</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu_delta(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff815bc440)
Location: drivers/xen/time.c:54
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu
```
**Symbols:**

```
ffffffff815bc440-ffffffff815bc4f7: xen_get_runstate_snapshot_cpu_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu_delta(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff815f4af0)
Location: drivers/xen/time.c:54
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu
```
**Symbols:**

```
ffffffff815f4af0-ffffffff815f4ba7: xen_get_runstate_snapshot_cpu_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu_delta(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff8160f950)
Location: drivers/xen/time.c:54
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu
```
**Symbols:**

```
ffffffff8160f950-ffffffff8160fa07: xen_get_runstate_snapshot_cpu_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu_delta(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81643760)
Location: drivers/xen/time.c:54
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu
```
**Symbols:**

```
ffffffff81643760-ffffffff81643817: xen_get_runstate_snapshot_cpu_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu_delta(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81665d10)
Location: drivers/xen/time.c:54
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu
```
**Symbols:**

```
ffffffff81665d10-ffffffff81665dc7: xen_get_runstate_snapshot_cpu_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu_delta(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81715460)
Location: drivers/xen/time.c:54
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
  - drivers/xen/time.c:xen_manage_runstate_time
```
**Symbols:**

```
ffffffff81715460-ffffffff817154c2: xen_get_runstate_snapshot_cpu_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu_delta(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81731e50)
Location: drivers/xen/time.c:54
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
  - drivers/xen/time.c:xen_manage_runstate_time
```
**Symbols:**

```
ffffffff81731e50-ffffffff81731eb2: xen_get_runstate_snapshot_cpu_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu_delta(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81715920)
Location: drivers/xen/time.c:55
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
  - drivers/xen/time.c:xen_manage_runstate_time
```
**Symbols:**

```
ffffffff81715920-ffffffff81715982: xen_get_runstate_snapshot_cpu_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu_delta(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff817929c0)
Location: drivers/xen/time.c:55
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
  - drivers/xen/time.c:xen_manage_runstate_time
```
**Symbols:**

```
ffffffff817929c0-ffffffff81792a55: xen_get_runstate_snapshot_cpu_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu_delta(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff818cb250)
Location: drivers/xen/time.c:55
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
  - drivers/xen/time.c:xen_manage_runstate_time
```
**Symbols:**

```
ffffffff818cb250-ffffffff818cb315: xen_get_runstate_snapshot_cpu_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu_delta(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81a1c510)
Location: drivers/xen/time.c:55
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
  - drivers/xen/time.c:xen_manage_runstate_time
```
**Symbols:**

```
ffffffff81a1c510-ffffffff81a1c5dc: xen_get_runstate_snapshot_cpu_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu_delta(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81a656b0)
Location: drivers/xen/time.c:55
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
  - drivers/xen/time.c:xen_manage_runstate_time
```
**Symbols:**

```
ffffffff81a656b0-ffffffff81a6577c: xen_get_runstate_snapshot_cpu_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu_delta(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81ab7f10)
Location: drivers/xen/time.c:55
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
  - drivers/xen/time.c:xen_manage_runstate_time
```
**Symbols:**

```
ffffffff81ab7f10-ffffffff81ab7fdc: xen_get_runstate_snapshot_cpu_delta (STB_LOCAL)
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
void xen_get_runstate_snapshot_cpu_delta(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffff80001082f7a0)
Location: drivers/xen/time.c:54
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu
```
**Symbols:**

```
ffff80001082f7a0-ffff80001082f864: xen_get_runstate_snapshot_cpu_delta (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu_delta(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff8162b960)
Location: drivers/xen/time.c:56
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu
```
**Symbols:**

```
ffffffff8162b960-ffffffff8162ba17: xen_get_runstate_snapshot_cpu_delta (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu_delta(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81659b50)
Location: drivers/xen/time.c:54
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu
```
**Symbols:**

```
ffffffff81659b50-ffffffff81659c07: xen_get_runstate_snapshot_cpu_delta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu_delta(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81674100)
Location: drivers/xen/time.c:54
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_manage_runstate_time
  - drivers/xen/time.c:xen_get_runstate_snapshot_cpu
```
**Symbols:**

```
ffffffff81674100-ffffffff816741db: xen_get_runstate_snapshot_cpu_delta (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
