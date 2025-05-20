# Function: <code>pcc_chan_reg_init</code>

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
int pcc_chan_reg_init(struct pcc_chan_reg *reg, struct acpi_generic_address *gas, u64 preserve_mask, u64 set_mask, u64 status_mask, char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/pcc.c (0)
Location: drivers/mailbox/pcc.c:406
Inline: False
Direct callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff81bca8d0-ffffffff81bca974: pcc_chan_reg_init (STB_LOCAL)
ffffffff81efd9b6-ffffffff81efd9e5: pcc_chan_reg_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pcc_chan_reg_init(struct pcc_chan_reg *reg, struct acpi_generic_address *gas, u64 preserve_mask, u64 set_mask, u64 status_mask, char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81d73fa0)
Location: drivers/mailbox/pcc.c:406
Inline: False
Direct callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff81d73fa0-ffffffff81d74060: pcc_chan_reg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pcc_chan_reg_init(struct pcc_chan_reg *reg, struct acpi_generic_address *gas, u64 preserve_mask, u64 set_mask, u64 status_mask, char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81de1fc0)
Location: drivers/mailbox/pcc.c:412
Inline: False
Direct callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff81de1fc0-ffffffff81de2080: pcc_chan_reg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pcc_chan_reg_init(struct pcc_chan_reg *reg, struct acpi_generic_address *gas, u64 preserve_mask, u64 set_mask, u64 status_mask, char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/pcc.c (ffffffff81e97f90)
Location: drivers/mailbox/pcc.c:473
Inline: False
Direct callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff81e97f90-ffffffff81e98050: pcc_chan_reg_init (STB_LOCAL)
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
