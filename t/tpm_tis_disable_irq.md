# Function: <code>tpm_tis_disable_irq</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_tis_disable_irq(const struct dmi_system_id *d);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81c0b0bb)
Location: drivers/char/tpm/tpm_tis.c:67
Inline: True
```
**Symbols:**

```
ffffffff817a2340-ffffffff817a235a: tpm_tis_disable_irq (STB_LOCAL)
ffffffff81c0b0bb-ffffffff81c0b0da: tpm_tis_disable_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_tis_disable_irq(const struct dmi_system_id *d);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81bfcb37)
Location: drivers/char/tpm/tpm_tis.c:67
Inline: True
```
**Symbols:**

```
ffffffff81785040-ffffffff81785055: tpm_tis_disable_irq (STB_LOCAL)
ffffffff81bfcb37-ffffffff81bfcb59: tpm_tis_disable_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_tis_disable_irq(const struct dmi_system_id *d);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81cfd8ed)
Location: drivers/char/tpm/tpm_tis.c:67
Inline: True
```
**Symbols:**

```
ffffffff8180bb70-ffffffff8180bb85: tpm_tis_disable_irq (STB_LOCAL)
ffffffff81cfd8ed-ffffffff81cfd90f: tpm_tis_disable_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tpm_tis_disable_irq(const struct dmi_system_id *d);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81ec61eb)
Location: drivers/char/tpm/tpm_tis.c:67
Inline: True
```
**Symbols:**

```
ffffffff8194c0f0-ffffffff8194c10d: tpm_tis_disable_irq (STB_LOCAL)
ffffffff81ec61eb-ffffffff81ec6213: tpm_tis_disable_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int tpm_tis_disable_irq(const struct dmi_system_id *d);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81ab01d0)
Location: drivers/char/tpm/tpm_tis.c:67
Inline: True
```
**Symbols:**

```
ffffffff81ab01d0-ffffffff81ab0213: tpm_tis_disable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int tpm_tis_disable_irq(const struct dmi_system_id *d);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81afc020)
Location: drivers/char/tpm/tpm_tis.c:106
Inline: True
```
**Symbols:**

```
ffffffff81afc020-ffffffff81afc063: tpm_tis_disable_irq (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
