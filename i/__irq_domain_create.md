# Function: <code>__irq_domain_create</code>

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
struct irq_domain *__irq_domain_create(struct fwnode_handle *fwnode, unsigned int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119eef0)
Location: kernel/irq/irqdomain.c:129
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_create_simple
```
**Symbols:**

```
ffffffff8119eef0-ffffffff8119f102: __irq_domain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct irq_domain *__irq_domain_create(struct fwnode_handle *fwnode, unsigned int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b0dd0)
Location: kernel/irq/irqdomain.c:129
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_create_simple
```
**Symbols:**

```
ffffffff811b0dd0-ffffffff811b0fef: __irq_domain_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct irq_domain *__irq_domain_create(struct fwnode_handle *fwnode, unsigned int size, irq_hw_number_t hwirq_max, int direct_max, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c0b50)
Location: kernel/irq/irqdomain.c:129
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_create_hierarchy
  - kernel/irq/irqdomain.c:irq_domain_add_legacy
  - kernel/irq/irqdomain.c:irq_domain_create_simple
```
**Symbols:**

```
ffffffff811c0b50-ffffffff811c0d6f: __irq_domain_create (STB_LOCAL)
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
