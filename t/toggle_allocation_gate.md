# Function: <code>toggle_allocation_gate</code>

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
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void toggle_allocation_gate(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (ffffffff8133bd2f)
Location: mm/kfence/core.c:620
Inline: True
```
**Symbols:**

```
ffffffff8133bd10-ffffffff8133bd65: toggle_allocation_gate (STB_LOCAL)
ffffffff81cc1e68-ffffffff81cc1e7c: toggle_allocation_gate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void toggle_allocation_gate(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (ffffffff813ae6df)
Location: mm/kfence/core.c:803
Inline: True
```
**Symbols:**

```
ffffffff813ae6c0-ffffffff813ae723: toggle_allocation_gate (STB_LOCAL)
ffffffff81e74372-ffffffff81e74386: toggle_allocation_gate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void toggle_allocation_gate(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (ffffffff8142eb6f)
Location: mm/kfence/core.c:791
Inline: True
```
**Symbols:**

```
ffffffff8142eb50-ffffffff8142ebb3: toggle_allocation_gate (STB_LOCAL)
ffffffff820678d2-ffffffff820678e6: toggle_allocation_gate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void toggle_allocation_gate(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (ffffffff8146431f)
Location: mm/kfence/core.c:823
Inline: True
```
**Symbols:**

```
ffffffff81464300-ffffffff81464363: toggle_allocation_gate (STB_LOCAL)
ffffffff820e71f2-ffffffff820e7206: toggle_allocation_gate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void toggle_allocation_gate(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (ffffffff8149369f)
Location: mm/kfence/core.c:818
Inline: True
```
**Symbols:**

```
ffffffff81493680-ffffffff814936e3: toggle_allocation_gate (STB_LOCAL)
ffffffff821c3daa-ffffffff821c3dbe: toggle_allocation_gate.cold (STB_LOCAL)
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
