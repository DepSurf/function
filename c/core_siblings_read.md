# Function: <code>core_siblings_read</code>

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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t core_siblings_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (ffffffff81842260)
Location: drivers/base/topology.c:62
Inline: True
```
**Symbols:**

```
ffffffff81842260-ffffffff818422dd: core_siblings_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t core_siblings_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (ffffffff81985a20)
Location: drivers/base/topology.c:72
Inline: True
```
**Symbols:**

```
ffffffff81985a20-ffffffff81985aaf: core_siblings_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t core_siblings_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (ffffffff81af3ec0)
Location: drivers/base/topology.c:72
Inline: True
```
**Symbols:**

```
ffffffff81af3ec0-ffffffff81af3f4f: core_siblings_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t core_siblings_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (ffffffff81b420d0)
Location: drivers/base/topology.c:72
Inline: True
```
**Symbols:**

```
ffffffff81b420d0-ffffffff81b4215f: core_siblings_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t core_siblings_read(struct file *file, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (ffffffff81b99fa0)
Location: drivers/base/topology.c:72
Inline: True
```
**Symbols:**

```
ffffffff81b99fa0-ffffffff81b9a02f: core_siblings_read (STB_LOCAL)
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
