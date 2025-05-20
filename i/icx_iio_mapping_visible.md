# Function: <code>icx_iio_mapping_visible</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
umode_t icx_iio_mapping_visible(struct kobject *kobj, struct attribute *attr, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: arch/x86/events/intel/uncore_snbep.c:5099
Inline: False
```
**Symbols:**

```
ffffffff81023b20-ffffffff81023b97: icx_iio_mapping_visible (STB_LOCAL)
ffffffff81c96d49-ffffffff81c96d66: icx_iio_mapping_visible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
umode_t icx_iio_mapping_visible(struct kobject *kobj, struct attribute *attr, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: arch/x86/events/intel/uncore_snbep.c:5099
Inline: False
```
**Symbols:**

```
ffffffff810279c0-ffffffff81027a4f: icx_iio_mapping_visible (STB_LOCAL)
ffffffff81e4617d-ffffffff81e4619a: icx_iio_mapping_visible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
umode_t icx_iio_mapping_visible(struct kobject *kobj, struct attribute *attr, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102e230)
Location: arch/x86/events/intel/uncore_snbep.c:5355
Inline: False
```
**Symbols:**

```
ffffffff8102e230-ffffffff8102e251: icx_iio_mapping_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
umode_t icx_iio_mapping_visible(struct kobject *kobj, struct attribute *attr, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102e210)
Location: arch/x86/events/intel/uncore_snbep.c:5345
Inline: False
```
**Symbols:**

```
ffffffff8102e210-ffffffff8102e231: icx_iio_mapping_visible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
umode_t icx_iio_mapping_visible(struct kobject *kobj, struct attribute *attr, int die);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81033fd0)
Location: arch/x86/events/intel/uncore_snbep.c:5353
Inline: False
```
**Symbols:**

```
ffffffff81033fd0-ffffffff81033ff1: icx_iio_mapping_visible (STB_LOCAL)
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
