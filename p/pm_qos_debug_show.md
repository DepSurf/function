# Function: <code>pm_qos_debug_show</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pm_qos_debug_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffff810f20f0)
Location: kernel/power/qos.c:187
Inline: False
```
**Symbols:**

```
ffffffff810f20f0-ffffffff810f22a9: pm_qos_debug_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pm_qos_debug_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (0)
Location: kernel/power/qos.c:188
Inline: False
```
**Symbols:**

```
ffffffff810fa5d0-ffffffff810fa757: pm_qos_debug_show (STB_LOCAL)
ffffffff810fb1dd-ffffffff810fb217: pm_qos_debug_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pm_qos_debug_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (0)
Location: kernel/power/qos.c:140
Inline: False
```
**Symbols:**

```
ffffffff811063b0-ffffffff81106537: pm_qos_debug_show (STB_LOCAL)
ffffffff8110730a-ffffffff81107344: pm_qos_debug_show.cold (STB_LOCAL)
```
</details>
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
int pm_qos_debug_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffff80001016ced8)
Location: kernel/power/qos.c:140
Inline: False
```
**Symbols:**

```
ffff80001016ced8-ffff80001016d178: pm_qos_debug_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pm_qos_debug_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c03b7e00)
Location: kernel/power/qos.c:140
Inline: False
```
**Symbols:**

```
c03b7e00-c03b7ff4: pm_qos_debug_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pm_qos_debug_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (c0000000001c4220)
Location: kernel/power/qos.c:140
Inline: False
```
**Symbols:**

```
c0000000001c4220-c0000000001c4530: pm_qos_debug_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pm_qos_debug_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/qos.c (ffffffe00010c73c)
Location: kernel/power/qos.c:140
Inline: False
```
**Symbols:**

```
ffffffe00010c73c-ffffffe00010c8f4: pm_qos_debug_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int pm_qos_debug_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (0)
Location: kernel/power/qos.c:140
Inline: False
```
**Symbols:**

```
ffffffff810ff6c0-ffffffff810ff847: pm_qos_debug_show (STB_LOCAL)
ffffffff8110061a-ffffffff81100654: pm_qos_debug_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pm_qos_debug_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (0)
Location: kernel/power/qos.c:140
Inline: False
```
**Symbols:**

```
ffffffff810ef8b0-ffffffff810efa37: pm_qos_debug_show (STB_LOCAL)
ffffffff810f080a-ffffffff810f0844: pm_qos_debug_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pm_qos_debug_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (0)
Location: kernel/power/qos.c:140
Inline: False
```
**Symbols:**

```
ffffffff810fc880-ffffffff810fca07: pm_qos_debug_show (STB_LOCAL)
ffffffff810fd7da-ffffffff810fd814: pm_qos_debug_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pm_qos_debug_show(struct seq_file *s, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/qos.c (0)
Location: kernel/power/qos.c:140
Inline: False
```
**Symbols:**

```
ffffffff81107ab0-ffffffff81107c37: pm_qos_debug_show (STB_LOCAL)
ffffffff81108a9a-ffffffff81108ad4: pm_qos_debug_show.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
