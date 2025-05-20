# Function: <code>irqchip_fwnode_get_name</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *irqchip_fwnode_get_name(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81125140)
Location: kernel/irq/irqdomain.c:45
Inline: False
```
**Symbols:**

```
ffffffff81125140-ffffffff8112514f: irqchip_fwnode_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *irqchip_fwnode_get_name(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811254a0)
Location: kernel/irq/irqdomain.c:45
Inline: False
```
**Symbols:**

```
ffffffff811254a0-ffffffff811254af: irqchip_fwnode_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *irqchip_fwnode_get_name(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81145b40)
Location: kernel/irq/irqdomain.c:45
Inline: False
```
**Symbols:**

```
ffffffff81145b40-ffffffff81145b4f: irqchip_fwnode_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *irqchip_fwnode_get_name(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81169c60)
Location: kernel/irq/irqdomain.c:45
Inline: False
```
**Symbols:**

```
ffffffff81169c60-ffffffff81169c75: irqchip_fwnode_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *irqchip_fwnode_get_name(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119e610)
Location: kernel/irq/irqdomain.c:48
Inline: False
```
**Symbols:**

```
ffffffff8119e610-ffffffff8119e625: irqchip_fwnode_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *irqchip_fwnode_get_name(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b04d0)
Location: kernel/irq/irqdomain.c:48
Inline: False
```
**Symbols:**

```
ffffffff811b04d0-ffffffff811b04e5: irqchip_fwnode_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *irqchip_fwnode_get_name(const struct fwnode_handle *fwnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c0250)
Location: kernel/irq/irqdomain.c:48
Inline: False
```
**Symbols:**

```
ffffffff811c0250-ffffffff811c0265: irqchip_fwnode_get_name (STB_LOCAL)
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
