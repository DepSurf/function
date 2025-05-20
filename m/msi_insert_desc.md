# Function: <code>msi_insert_desc</code>

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
In kernel/irq/msi.c (ffffffff8116ef5e)
Location: kernel/irq/msi.c:61
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_add_simple_msi_descs
  - kernel/irq/msi.c:msi_add_msi_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int msi_insert_desc(struct device *dev, struct msi_desc *desc, unsigned int domid, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a4080)
Location: kernel/irq/msi.c:84
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_alloc_irq_at
  - kernel/irq/msi.c:msi_domain_add_simple_msi_descs
  - kernel/irq/msi.c:msi_domain_insert_msi_desc
```
**Symbols:**

```
ffffffff811a4080-ffffffff811a41ea: msi_insert_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int msi_insert_desc(struct device *dev, struct msi_desc *desc, unsigned int domid, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b62e0)
Location: kernel/irq/msi.c:84
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_alloc_irq_at
  - kernel/irq/msi.c:msi_domain_add_simple_msi_descs
  - kernel/irq/msi.c:msi_domain_insert_msi_desc
```
**Symbols:**

```
ffffffff811b62e0-ffffffff811b6483: msi_insert_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int msi_insert_desc(struct device *dev, struct msi_desc *desc, unsigned int domid, unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c6190)
Location: kernel/irq/msi.c:84
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_alloc_irq_at
  - kernel/irq/msi.c:msi_domain_add_simple_msi_descs
  - kernel/irq/msi.c:msi_domain_insert_msi_desc
```
**Symbols:**

```
ffffffff811c6190-ffffffff811c6333: msi_insert_desc (STB_LOCAL)
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
