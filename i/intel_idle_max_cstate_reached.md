# Function: <code>intel_idle_max_cstate_reached</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool intel_idle_max_cstate_reached(int cstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff82d0ec75)
Location: drivers/idle/intel_idle.c:1127
Inline: False
```
**Symbols:**

```
ffffffff82d0ec75-ffffffff82d0ec9d: intel_idle_max_cstate_reached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool intel_idle_max_cstate_reached(int cstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff82ffc67f)
Location: drivers/idle/intel_idle.c:1173
Inline: False
```
**Symbols:**

```
ffffffff82ffc67f-ffffffff82ffc6a7: intel_idle_max_cstate_reached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool intel_idle_max_cstate_reached(int cstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff832073d0)
Location: drivers/idle/intel_idle.c:1174
Inline: False
```
**Symbols:**

```
ffffffff832073d0-ffffffff832073f8: intel_idle_max_cstate_reached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool intel_idle_max_cstate_reached(int cstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff832ef20f)
Location: drivers/idle/intel_idle.c:1174
Inline: False
```
**Symbols:**

```
ffffffff832ef20f-ffffffff832ef237: intel_idle_max_cstate_reached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool intel_idle_max_cstate_reached(int cstate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/idle/intel_idle.c (ffffffff834a7230)
Location: drivers/idle/intel_idle.c:1379
Inline: False
```
**Symbols:**

```
ffffffff834a7230-ffffffff834a7268: intel_idle_max_cstate_reached (STB_LOCAL)
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
In drivers/idle/intel_idle.c (ffffffff83ede2b9)
Location: drivers/idle/intel_idle.c:1441
Inline: True
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
In drivers/idle/intel_idle.c (ffffffff83703dae)
Location: drivers/idle/intel_idle.c:1443
Inline: True
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
In drivers/idle/intel_idle.c (ffffffff839373be)
Location: drivers/idle/intel_idle.c:1552
Inline: True
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
</ul>
