# Function: <code>btf_module_read</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t btf_module_read(struct file *file, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t off, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81223220)
Location: kernel/bpf/btf.c:5770
Inline: False
```
**Symbols:**

```
ffffffff81223220-ffffffff8122324c: btf_module_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t btf_module_read(struct file *file, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t off, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81227cd0)
Location: kernel/bpf/btf.c:5968
Inline: False
```
**Symbols:**

```
ffffffff81227cd0-ffffffff81227cfc: btf_module_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t btf_module_read(struct file *file, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t off, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8125ffc0)
Location: kernel/bpf/btf.c:6021
Inline: False
```
**Symbols:**

```
ffffffff8125ffc0-ffffffff8125ffec: btf_module_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t btf_module_read(struct file *file, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t off, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812aa810)
Location: kernel/bpf/btf.c:6759
Inline: False
```
**Symbols:**

```
ffffffff812aa810-ffffffff812aa84d: btf_module_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t btf_module_read(struct file *file, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t off, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130a400)
Location: kernel/bpf/btf.c:7238
Inline: False
```
**Symbols:**

```
ffffffff8130a400-ffffffff8130a43d: btf_module_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t btf_module_read(struct file *file, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t off, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81339910)
Location: kernel/bpf/btf.c:7337
Inline: False
```
**Symbols:**

```
ffffffff81339910-ffffffff8133994d: btf_module_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t btf_module_read(struct file *file, struct kobject *kobj, struct bin_attribute *bin_attr, char *buf, loff_t off, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8135fa40)
Location: kernel/bpf/btf.c:7401
Inline: False
```
**Symbols:**

```
ffffffff8135fa40-ffffffff8135fa7d: btf_module_read (STB_LOCAL)
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
