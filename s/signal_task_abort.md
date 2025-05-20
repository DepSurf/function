# Function: <code>signal_task_abort</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void signal_task_abort(struct pci_doe_task *task, int rv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/doe.c (ffffffff8191fe80)
Location: drivers/pci/doe.c:229
Inline: False
Direct callers:
  - drivers/pci/doe.c:doe_statemachine_work
  - drivers/pci/doe.c:doe_statemachine_work
```
**Symbols:**

```
ffffffff8191fe80-ffffffff8191feef: signal_task_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void signal_task_abort(struct pci_doe_task *task, int rv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/doe.c (ffffffff819635e0)
Location: drivers/pci/doe.c:300
Inline: False
Direct callers:
  - drivers/pci/doe.c:doe_statemachine_work
  - drivers/pci/doe.c:doe_statemachine_work
  - drivers/pci/doe.c:doe_statemachine_work
```
**Symbols:**

```
ffffffff819635e0-ffffffff8196364f: signal_task_abort (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void signal_task_abort(struct pci_doe_task *task, int rv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/doe.c (ffffffff819acc60)
Location: drivers/pci/doe.c:300
Inline: False
Direct callers:
  - drivers/pci/doe.c:doe_statemachine_work
  - drivers/pci/doe.c:doe_statemachine_work
  - drivers/pci/doe.c:doe_statemachine_work
```
**Symbols:**

```
ffffffff819acc60-ffffffff819acccf: signal_task_abort (STB_LOCAL)
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
