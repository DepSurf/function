# Function: <code>msi_sysfs_remove_desc</code>

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
void msi_sysfs_remove_desc(struct device *dev, struct msi_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8116e7f0)
Location: kernel/irq/msi.c:372
Inline: False
Direct callers:
  - kernel/irq/msi.c:__msi_domain_free_irqs
  - kernel/irq/msi.c:msi_sysfs_populate_desc
```
**Symbols:**

```
ffffffff8116e7f0-ffffffff8116e878: msi_sysfs_remove_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void msi_sysfs_remove_desc(struct device *dev, struct msi_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a3e10)
Location: kernel/irq/msi.c:494
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_sysfs_populate_desc
```
**Symbols:**

```
ffffffff811a3e10-ffffffff811a3e98: msi_sysfs_remove_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void msi_sysfs_remove_desc(struct device *dev, struct msi_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b5800)
Location: kernel/irq/msi.c:494
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_device_destroy_sysfs
  - kernel/irq/msi.c:msi_sysfs_populate_desc
```
**Symbols:**

```
ffffffff811b5800-ffffffff811b5888: msi_sysfs_remove_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void msi_sysfs_remove_desc(struct device *dev, struct msi_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c5680)
Location: kernel/irq/msi.c:494
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_device_destroy_sysfs
  - kernel/irq/msi.c:msi_sysfs_populate_desc
```
**Symbols:**

```
ffffffff811c5680-ffffffff811c5708: msi_sysfs_remove_desc (STB_LOCAL)
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
