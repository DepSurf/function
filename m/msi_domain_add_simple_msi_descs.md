# Function: <code>msi_domain_add_simple_msi_descs</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8116f905)
Location: kernel/irq/msi.c:916
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs_descs_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int msi_domain_add_simple_msi_descs(struct device *dev, struct msi_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a4790)
Location: kernel/irq/msi.c:228
Inline: False
Direct callers:
  - kernel/irq/msi.c:__msi_domain_alloc_locked
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff811a4790-ffffffff811a4857: msi_domain_add_simple_msi_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int msi_domain_add_simple_msi_descs(struct device *dev, struct msi_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b64a0)
Location: kernel/irq/msi.c:228
Inline: False
Direct callers:
  - kernel/irq/msi.c:__msi_domain_alloc_locked
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff811b64a0-ffffffff811b6567: msi_domain_add_simple_msi_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int msi_domain_add_simple_msi_descs(struct device *dev, struct msi_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c6350)
Location: kernel/irq/msi.c:228
Inline: False
Direct callers:
  - kernel/irq/msi.c:__msi_domain_alloc_locked
  - kernel/irq/msi.c:msi_domain_populate_irqs
```
**Symbols:**

```
ffffffff811c6350-ffffffff811c6453: msi_domain_add_simple_msi_descs (STB_LOCAL)
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
