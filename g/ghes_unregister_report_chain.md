# Function: <code>ghes_unregister_report_chain</code>

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
void ghes_unregister_report_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff819e7600)
Location: drivers/acpi/apei/ghes.c:1559
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_exit
```
**Symbols:**

```
ffffffff819e7600-ffffffff819e7624: ghes_unregister_report_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ghes_unregister_report_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a2fd10)
Location: drivers/acpi/apei/ghes.c:1559
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_exit
```
**Symbols:**

```
ffffffff81a2fd10-ffffffff81a2fd34: ghes_unregister_report_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ghes_unregister_report_chain(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (ffffffff81a7b090)
Location: drivers/acpi/apei/ghes.c:1597
Inline: False
Direct callers:
  - drivers/edac/ghes_edac.c:ghes_edac_exit
```
**Symbols:**

```
ffffffff81a7b090-ffffffff81a7b0b4: ghes_unregister_report_chain (STB_GLOBAL)
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
