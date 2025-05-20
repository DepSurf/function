# Function: <code>proc_hubless_show</code>

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
int proc_hubless_show(struct seq_file *file, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074620)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1445
Inline: False
```
**Symbols:**

```
ffffffff81074620-ffffffff8107463f: proc_hubless_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int proc_hubless_show(struct seq_file *file, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1628
Inline: False
```
**Symbols:**

```
ffffffff81075080-ffffffff810750b8: proc_hubless_show (STB_LOCAL)
ffffffff81bd78f4-ffffffff81bd791c: proc_hubless_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int proc_hubless_show(struct seq_file *file, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1624
Inline: False
```
**Symbols:**

```
ffffffff81075b20-ffffffff81075b58: proc_hubless_show (STB_LOCAL)
ffffffff81bc987b-ffffffff81bc98a3: proc_hubless_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int proc_hubless_show(struct seq_file *file, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1624
Inline: False
```
**Symbols:**

```
ffffffff81083090-ffffffff810830d4: proc_hubless_show (STB_LOCAL)
ffffffff81c9e5ca-ffffffff81c9e606: proc_hubless_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int proc_hubless_show(struct seq_file *file, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1634
Inline: False
```
**Symbols:**

```
ffffffff81092ea0-ffffffff81092ef1: proc_hubless_show (STB_LOCAL)
ffffffff81e4da20-ffffffff81e4da5d: proc_hubless_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int proc_hubless_show(struct seq_file *file, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1634
Inline: False
```
**Symbols:**

```
ffffffff810a8110-ffffffff810a8182: proc_hubless_show (STB_LOCAL)
ffffffff82053e88-ffffffff82053e9d: proc_hubless_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int proc_hubless_show(struct seq_file *file, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1680
Inline: False
```
**Symbols:**

```
ffffffff810ab380-ffffffff810ab3f2: proc_hubless_show (STB_LOCAL)
ffffffff820d24aa-ffffffff820d24bf: proc_hubless_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int proc_hubless_show(struct seq_file *file, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:1640
Inline: False
```
**Symbols:**

```
ffffffff810b21f0-ffffffff810b2262: proc_hubless_show (STB_LOCAL)
ffffffff821ad1db-ffffffff821ad1f0: proc_hubless_show.cold (STB_LOCAL)
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
