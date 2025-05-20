# Function: <code>xen_get_runstate_snapshot_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81517f10)
Location: drivers/xen/time.c:50
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
**Symbols:**

```
ffffffff81517f10-ffffffff81517fc7: xen_get_runstate_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81544420)
Location: drivers/xen/time.c:50
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
**Symbols:**

```
ffffffff81544420-ffffffff815444d7: xen_get_runstate_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff815582b0)
Location: drivers/xen/time.c:50
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
**Symbols:**

```
ffffffff815582b0-ffffffff81558367: xen_get_runstate_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff815bc500)
Location: drivers/xen/time.c:73
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
**Symbols:**

```
ffffffff815bc500-ffffffff815bc54f: xen_get_runstate_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff815f4bb0)
Location: drivers/xen/time.c:73
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
**Symbols:**

```
ffffffff815f4bb0-ffffffff815f4bff: xen_get_runstate_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff8160fa10)
Location: drivers/xen/time.c:73
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
**Symbols:**

```
ffffffff8160fa10-ffffffff8160fa5f: xen_get_runstate_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81643820)
Location: drivers/xen/time.c:73
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
**Symbols:**

```
ffffffff81643820-ffffffff81643869: xen_get_runstate_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81665dd0)
Location: drivers/xen/time.c:73
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
**Symbols:**

```
ffffffff81665dd0-ffffffff81665e19: xen_get_runstate_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff817154f5)
Location: drivers/xen/time.c:73
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81731ee5)
Location: drivers/xen/time.c:73
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff817159b5)
Location: drivers/xen/time.c:74
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81792a98)
Location: drivers/xen/time.c:74
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff818cb35c)
Location: drivers/xen/time.c:74
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81a1c62c)
Location: drivers/xen/time.c:74
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81a657cc)
Location: drivers/xen/time.c:74
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81ab802c)
Location: drivers/xen/time.c:74
Inline: True
Inline callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
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
void xen_get_runstate_snapshot_cpu(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffff80001082f868)
Location: drivers/xen/time.c:73
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
**Symbols:**

```
ffff80001082f868-ffff80001082f8e0: xen_get_runstate_snapshot_cpu (STB_LOCAL)
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
void xen_get_runstate_snapshot_cpu(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff8162ba20)
Location: drivers/xen/time.c:75
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_restore_steal_clock
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
**Symbols:**

```
ffffffff8162ba20-ffffffff8162ba69: xen_get_runstate_snapshot_cpu (STB_LOCAL)
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
void xen_get_runstate_snapshot_cpu(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff81659c10)
Location: drivers/xen/time.c:73
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
**Symbols:**

```
ffffffff81659c10-ffffffff81659c59: xen_get_runstate_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_get_runstate_snapshot_cpu(struct vcpu_runstate_info *res, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/time.c (ffffffff816741e0)
Location: drivers/xen/time.c:73
Inline: False
Direct callers:
  - drivers/xen/time.c:xen_steal_clock
  - drivers/xen/time.c:xen_get_runstate_snapshot
```
**Symbols:**

```
ffffffff816741e0-ffffffff81674229: xen_get_runstate_snapshot_cpu (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
