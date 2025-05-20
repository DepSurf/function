# Function: <code>pcs_irq_handle</code>

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
int pcs_irq_handle(struct pcs_soc_data *pcs_soc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (ffff80001069dad0)
Location: drivers/pinctrl/pinctrl-single.c:1447
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_handler
```
**Symbols:**

```
ffff80001069dad0-ffff80001069dbfc: pcs_irq_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pcs_irq_handle(struct pcs_soc_data *pcs_soc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (c083f310)
Location: drivers/pinctrl/pinctrl-single.c:1447
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_handler
```
**Symbols:**

```
c083f310-c083f3bc: pcs_irq_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pcs_irq_handle(struct pcs_soc_data *pcs_soc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (c000000000833dc0)
Location: drivers/pinctrl/pinctrl-single.c:1447
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_handler
```
**Symbols:**

```
c000000000833dc0-c000000000833f1c: pcs_irq_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pcs_irq_handle(struct pcs_soc_data *pcs_soc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a135a)
Location: drivers/pinctrl/pinctrl-single.c:1447
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_chain_handler
  - drivers/pinctrl/pinctrl-single.c:pcs_irq_handler
```
**Symbols:**

```
ffffffe0004a135a-ffffffe0004a1430: pcs_irq_handle (STB_LOCAL)
```
</details>
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
