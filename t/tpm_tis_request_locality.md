# Function: <code>tpm_tis_request_locality</code>

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
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int tpm_tis_request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81afb5fc)
Location: drivers/char/tpm/tpm_tis_core.c:232
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:probe_itpm
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81af9490-ffffffff81af94fd: tpm_tis_request_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int tpm_tis_request_locality(struct tpm_chip *chip, int l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4ec8c)
Location: drivers/char/tpm/tpm_tis_core.c:232
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_probe_irq_single
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:tis_int_handler
  - drivers/char/tpm/tpm_tis_core.c:probe_itpm
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
```
**Symbols:**

```
ffffffff81b4cab0-ffffffff81b4cb1d: tpm_tis_request_locality (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
