# Function: <code>psci_features</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int psci_features(u32 psci_func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/psci/psci.c (ffff8000114a48a0)
Location: drivers/firmware/psci/psci.c:273
Inline: False
Direct callers:
  - drivers/firmware/psci/psci.c:psci_probe
  - drivers/firmware/psci/psci.c:psci_probe
  - drivers/firmware/psci/psci.c:psci_probe
  - drivers/firmware/psci/psci.c:psci_probe
```
**Symbols:**

```
ffff8000114a48a0-ffff8000114a48e4: psci_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int psci_features(u32 psci_func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/psci/psci.c (c15a700c)
Location: drivers/firmware/psci/psci.c:273
Inline: False
Direct callers:
  - drivers/firmware/psci/psci.c:psci_0_2_init
  - drivers/firmware/psci/psci.c:psci_0_2_init
  - drivers/firmware/psci/psci.c:psci_0_2_init
  - drivers/firmware/psci/psci.c:psci_0_2_init
```
**Symbols:**

```
c15a700c-c15a7048: psci_features (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
