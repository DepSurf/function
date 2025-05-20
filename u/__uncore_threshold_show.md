# Function: <code>__uncore_threshold_show</code>

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
ssize_t __uncore_threshold_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101d480)
Location: arch/x86/events/intel/uncore_snb.c:162
Inline: False
```
**Symbols:**

```
ffffffff8101d480-ffffffff8101d4ad: __uncore_threshold_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t __uncore_threshold_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff81020580)
Location: arch/x86/events/intel/uncore_snb.c:162
Inline: False
```
**Symbols:**

```
ffffffff81020580-ffffffff810205ad: __uncore_threshold_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t __uncore_threshold_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff81023610)
Location: arch/x86/events/intel/uncore_snb.c:215
Inline: False
```
**Symbols:**

```
ffffffff81023610-ffffffff81023641: __uncore_threshold_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t __uncore_threshold_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff810283a0)
Location: arch/x86/events/intel/uncore_snb.c:254
Inline: False
```
**Symbols:**

```
ffffffff810283a0-ffffffff810283d1: __uncore_threshold_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t __uncore_threshold_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff810283d0)
Location: arch/x86/events/intel/uncore_snb.c:254
Inline: False
```
**Symbols:**

```
ffffffff810283d0-ffffffff81028401: __uncore_threshold_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t __uncore_threshold_show(struct device *dev, struct device_attribute *attr, char *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff8102e530)
Location: arch/x86/events/intel/uncore_snb.c:254
Inline: False
```
**Symbols:**

```
ffffffff8102e530-ffffffff8102e561: __uncore_threshold_show (STB_LOCAL)
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
