# Function: <code>die_cpus_list_read</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t die_cpus_list_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (ffffffff81842060)
Location: drivers/base/topology.c:66
Inline: False
```
**Symbols:**

```
ffffffff81842060-ffffffff818420dd: die_cpus_list_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t die_cpus_list_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (ffffffff819857e0)
Location: drivers/base/topology.c:83
Inline: False
```
**Symbols:**

```
ffffffff819857e0-ffffffff8198586f: die_cpus_list_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t die_cpus_list_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (ffffffff81af3c40)
Location: drivers/base/topology.c:83
Inline: False
```
**Symbols:**

```
ffffffff81af3c40-ffffffff81af3ccf: die_cpus_list_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t die_cpus_list_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (ffffffff81b41e50)
Location: drivers/base/topology.c:83
Inline: False
```
**Symbols:**

```
ffffffff81b41e50-ffffffff81b41edf: die_cpus_list_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t die_cpus_list_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (ffffffff81b99d20)
Location: drivers/base/topology.c:83
Inline: False
```
**Symbols:**

```
ffffffff81b99d20-ffffffff81b99daf: die_cpus_list_read (STB_LOCAL)
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
