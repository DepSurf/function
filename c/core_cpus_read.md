# Function: <code>core_cpus_read</code>

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
ssize_t core_cpus_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (0)
Location: drivers/base/topology.c:58
Inline: False
```
**Symbols:**

```
ffffffff81842550-ffffffff818425cd: core_cpus_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t core_cpus_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (0)
Location: drivers/base/topology.c:68
Inline: False
```
**Symbols:**

```
ffffffff81985ef0-ffffffff81985f7f: core_cpus_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t core_cpus_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (0)
Location: drivers/base/topology.c:68
Inline: False
```
**Symbols:**

```
ffffffff81af4440-ffffffff81af44cf: core_cpus_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t core_cpus_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (0)
Location: drivers/base/topology.c:68
Inline: False
```
**Symbols:**

```
ffffffff81b42650-ffffffff81b426df: core_cpus_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t core_cpus_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (0)
Location: drivers/base/topology.c:68
Inline: False
```
**Symbols:**

```
ffffffff81b9a520-ffffffff81b9a5af: core_cpus_read (STB_LOCAL)
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
