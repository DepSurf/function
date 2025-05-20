# Function: <code>pmc_core_lpm_latch_mode_write</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t pmc_core_lpm_latch_mode_write(struct file *file, const char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/platform/x86/intel_pmc_core.c (ffffffff819a9200)
Location: drivers/platform/x86/intel_pmc_core.c:1355
Inline: False
```
**Symbols:**

```
ffffffff819a9200-ffffffff819a93ce: pmc_core_lpm_latch_mode_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t pmc_core_lpm_latch_mode_write(struct file *file, const char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:1655
Inline: False
```
**Symbols:**

```
ffffffff81a56500-ffffffff81a566eb: pmc_core_lpm_latch_mode_write (STB_LOCAL)
ffffffff81d30e25-ffffffff81d30e44: pmc_core_lpm_latch_mode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t pmc_core_lpm_latch_mode_write(struct file *file, const char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:1655
Inline: False
```
**Symbols:**

```
ffffffff81bc69f0-ffffffff81bc6be9: pmc_core_lpm_latch_mode_write (STB_LOCAL)
ffffffff81efd3e2-ffffffff81efd401: pmc_core_lpm_latch_mode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t pmc_core_lpm_latch_mode_write(struct file *file, const char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:763
Inline: False
```
**Symbols:**

```
ffffffff81d6ec60-ffffffff81d6ee5f: pmc_core_lpm_latch_mode_write (STB_LOCAL)
ffffffff820aa100-ffffffff820aa11f: pmc_core_lpm_latch_mode_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t pmc_core_lpm_latch_mode_write(struct file *file, const char *userbuf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/platform/x86/intel/pmc/core.c (0)
Location: drivers/platform/x86/intel/pmc/core.c:841
Inline: False
```
**Symbols:**

```
ffffffff81ddb4f0-ffffffff81ddb71d: pmc_core_lpm_latch_mode_write (STB_LOCAL)
ffffffff8212b577-ffffffff8212b596: pmc_core_lpm_latch_mode_write.cold (STB_LOCAL)
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
