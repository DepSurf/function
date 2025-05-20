# Function: <code>uncore_pci_sub_bus_notify</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uncore_pci_sub_bus_notify(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101ad60)
Location: arch/x86/events/intel/uncore.c:1272
Inline: False
```
**Symbols:**

```
ffffffff8101ad60-ffffffff8101add4: uncore_pci_sub_bus_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uncore_pci_sub_bus_notify(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101d660)
Location: arch/x86/events/intel/uncore.c:1279
Inline: False
```
**Symbols:**

```
ffffffff8101d660-ffffffff8101d6d4: uncore_pci_sub_bus_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uncore_pci_sub_bus_notify(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101ffa0)
Location: arch/x86/events/intel/uncore.c:1279
Inline: False
```
**Symbols:**

```
ffffffff8101ffa0-ffffffff81020084: uncore_pci_sub_bus_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uncore_pci_sub_bus_notify(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81024820)
Location: arch/x86/events/intel/uncore.c:1279
Inline: False
```
**Symbols:**

```
ffffffff81024820-ffffffff81024904: uncore_pci_sub_bus_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uncore_pci_sub_bus_notify(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81024580)
Location: arch/x86/events/intel/uncore.c:1300
Inline: False
```
**Symbols:**

```
ffffffff81024580-ffffffff81024664: uncore_pci_sub_bus_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uncore_pci_sub_bus_notify(struct notifier_block *nb, long unsigned int action, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8102a6b0)
Location: arch/x86/events/intel/uncore.c:1300
Inline: False
```
**Symbols:**

```
ffffffff8102a6b0-ffffffff8102a794: uncore_pci_sub_bus_notify (STB_LOCAL)
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
