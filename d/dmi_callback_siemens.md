# Function: <code>dmi_callback_siemens</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dmi_callback_siemens(const struct dmi_system_id *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/pmc_atom.c (0)
Location: drivers/platform/x86/pmc_atom.c:362
Inline: False
```
**Symbols:**

```
ffffffff81bc8390-ffffffff81bc840c: dmi_callback_siemens (STB_LOCAL)
ffffffff81efd4d7-ffffffff81efd4e4: dmi_callback_siemens.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dmi_callback_siemens(const struct dmi_system_id *d);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/pmc_atom.c (ffffffff81d71180)
Location: drivers/platform/x86/pmc_atom.c:362
Inline: True
```
**Symbols:**

```
ffffffff81d71180-ffffffff81d71208: dmi_callback_siemens (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dmi_callback_siemens(const struct dmi_system_id *d);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/pmc_atom.c (ffffffff81ddee50)
Location: drivers/platform/x86/pmc_atom.c:362
Inline: True
```
**Symbols:**

```
ffffffff81ddee50-ffffffff81ddeed8: dmi_callback_siemens (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int dmi_callback_siemens(const struct dmi_system_id *d);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/pmc_atom.c (ffffffff81e94d60)
Location: drivers/platform/x86/pmc_atom.c:362
Inline: True
```
**Symbols:**

```
ffffffff81e94d60-ffffffff81e94de8: dmi_callback_siemens (STB_LOCAL)
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
