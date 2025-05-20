# Function: <code>pm_runtime_disable_action</code>

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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_disable_action(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff8184bb9e)
Location: drivers/base/power/runtime.c:1471
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
**Symbols:**

```
ffffffff8184bb50-ffffffff8184bb65: pm_runtime_disable_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_disable_action(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff819918bf)
Location: drivers/base/power/runtime.c:1502
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
**Symbols:**

```
ffffffff81991820-ffffffff8199188a: pm_runtime_disable_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_disable_action(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b01ccf)
Location: drivers/base/power/runtime.c:1515
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
**Symbols:**

```
ffffffff81b01c20-ffffffff81b01c8a: pm_runtime_disable_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_disable_action(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81b4fdc6)
Location: drivers/base/power/runtime.c:1515
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
**Symbols:**

```
ffffffff81b4fd10-ffffffff81b4fd7a: pm_runtime_disable_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pm_runtime_disable_action(void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/runtime.c (ffffffff81ba8346)
Location: drivers/base/power/runtime.c:1516
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:devm_pm_runtime_enable
```
**Symbols:**

```
ffffffff81ba8290-ffffffff81ba82fa: pm_runtime_disable_action (STB_LOCAL)
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
