# Function: <code>proc_hubbed_show</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int proc_hubbed_show(struct seq_file *file, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074600)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1439
Inline: False
```
**Symbols:**

```
ffffffff81074600-ffffffff8107461f: proc_hubbed_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int proc_hubbed_show(struct seq_file *file, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1620
Inline: False
```
**Symbols:**

```
ffffffff81075040-ffffffff81075078: proc_hubbed_show (STB_LOCAL)
ffffffff81bd78cc-ffffffff81bd78f4: proc_hubbed_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int proc_hubbed_show(struct seq_file *file, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1616
Inline: False
```
**Symbols:**

```
ffffffff81075ae0-ffffffff81075b18: proc_hubbed_show (STB_LOCAL)
ffffffff81bc9853-ffffffff81bc987b: proc_hubbed_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int proc_hubbed_show(struct seq_file *file, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1616
Inline: False
```
**Symbols:**

```
ffffffff81083040-ffffffff81083084: proc_hubbed_show (STB_LOCAL)
ffffffff81c9e58e-ffffffff81c9e5ca: proc_hubbed_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int proc_hubbed_show(struct seq_file *file, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1626
Inline: False
```
**Symbols:**

```
ffffffff81092e40-ffffffff81092e91: proc_hubbed_show (STB_LOCAL)
ffffffff81e4d9e3-ffffffff81e4da20: proc_hubbed_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int proc_hubbed_show(struct seq_file *file, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1626
Inline: False
```
**Symbols:**

```
ffffffff810a8080-ffffffff810a80f2: proc_hubbed_show (STB_LOCAL)
ffffffff82053e73-ffffffff82053e88: proc_hubbed_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int proc_hubbed_show(struct seq_file *file, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1672
Inline: False
```
**Symbols:**

```
ffffffff810ab2f0-ffffffff810ab362: proc_hubbed_show (STB_LOCAL)
ffffffff820d2495-ffffffff820d24aa: proc_hubbed_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int proc_hubbed_show(struct seq_file *file, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1632
Inline: False
```
**Symbols:**

```
ffffffff810b2160-ffffffff810b21d2: proc_hubbed_show (STB_LOCAL)
ffffffff821ad1c6-ffffffff821ad1db: proc_hubbed_show.cold (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
