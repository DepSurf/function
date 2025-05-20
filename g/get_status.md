# Function: <code>get_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int get_status(u32 index, acpi_event_status *status, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff81489c3e)
Location: drivers/acpi/sysfs.c:555
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:counter_show
  - drivers/acpi/sysfs.c:counter_set
```
**Symbols:**

```
ffffffff81489c3e-ffffffff81489cbd: get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int get_status(u32 index, acpi_event_status *status, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff814d8a34)
Location: drivers/acpi/sysfs.c:553
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff814d8a34-ffffffff814d8ab6: get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int get_status(u32 index, acpi_event_status *status, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff814fb113)
Location: drivers/acpi/sysfs.c:559
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff814fb113-ffffffff814fb195: get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int get_status(u32 index, acpi_event_status *status, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8150a710)
Location: drivers/acpi/sysfs.c:562
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff8150a710-ffffffff8150a7af: get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int get_status(u32 index, acpi_event_status *status, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8154d0e0)
Location: drivers/acpi/sysfs.c:651
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff8154d0e0-ffffffff8154d17f: get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int get_status(u32 index, acpi_event_status *status, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff81583830)
Location: drivers/acpi/sysfs.c:651
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff81583830-ffffffff815838cf: get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int get_status(u32 index, acpi_event_status *status, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8159b960)
Location: drivers/acpi/sysfs.c:651
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff8159b960-ffffffff8159b9ff: get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int get_status(u32 index, acpi_event_status *ret, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff815ccfe0)
Location: drivers/acpi/sysfs.c:651
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff815ccfe0-ffffffff815cd06a: get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int get_status(u32 index, acpi_event_status *ret, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff815ee260)
Location: drivers/acpi/sysfs.c:651
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff815ee260-ffffffff815ee2ea: get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_status(u32 index, acpi_event_status *ret, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8169a0d0)
Location: drivers/acpi/sysfs.c:651
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff8169a0d0-ffffffff8169a15a: get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_status(u32 index, acpi_event_status *ret, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff816b7150)
Location: drivers/acpi/sysfs.c:651
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff816b7150-ffffffff816b71da: get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int get_status(u32 index, acpi_event_status *ret, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:633
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff81699210-ffffffff81699274: get_status (STB_LOCAL)
ffffffff81bf3cea-ffffffff81bf3d03: get_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int get_status(u32 index, acpi_event_status *ret, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:622
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff8170f0a0-ffffffff8170f104: get_status (STB_LOCAL)
ffffffff81cf0a2a-ffffffff81cf0a43: get_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int get_status(u32 index, acpi_event_status *ret, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:633
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff8183db30-ffffffff8183db9f: get_status (STB_LOCAL)
ffffffff81eb8881-ffffffff81eb8899: get_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_status(u32 index, acpi_event_status *ret, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff81973770)
Location: drivers/acpi/sysfs.c:634
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff81973770-ffffffff819737f0: get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_status(u32 index, acpi_event_status *ret, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff819b9f30)
Location: drivers/acpi/sysfs.c:651
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff819b9f30-ffffffff819b9fb0: get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_status(u32 index, acpi_event_status *ret, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff81a04570)
Location: drivers/acpi/sysfs.c:651
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff81a04570-ffffffff81a045f0: get_status (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:651
Inline: True
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int get_status(u32 index, acpi_event_status *ret, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff815dcf20)
Location: drivers/acpi/sysfs.c:651
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff815dcf20-ffffffff815dcfaa: get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int get_status(u32 index, acpi_event_status *ret, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff815c8560)
Location: drivers/acpi/sysfs.c:651
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff815c8560-ffffffff815c85ea: get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int get_status(u32 index, acpi_event_status *ret, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff815e2540)
Location: drivers/acpi/sysfs.c:651
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff815e2540-ffffffff815e25ca: get_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int get_status(u32 index, acpi_event_status *ret, acpi_handle *handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff815fc400)
Location: drivers/acpi/sysfs.c:651
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:counter_set
  - drivers/acpi/sysfs.c:counter_show
```
**Symbols:**

```
ffffffff815fc400-ffffffff815fc48a: get_status (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>acpi_event_status *ret</code>
</li>
<li>
<b>Param removed. </b>
<code>acpi_event_status *status</code>
</li>
</ul>
</details>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
