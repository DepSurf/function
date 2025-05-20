# Function: <code>counter_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff81489df3)
Location: drivers/acpi/sysfs.c:622
Inline: False
```
**Symbols:**

```
ffffffff81489df3-ffffffff8148a044: counter_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff814d8bec)
Location: drivers/acpi/sysfs.c:619
Inline: False
```
**Symbols:**

```
ffffffff814d8bec-ffffffff814d8e32: counter_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff814fb33b)
Location: drivers/acpi/sysfs.c:638
Inline: False
```
**Symbols:**

```
ffffffff814fb33b-ffffffff814fb5c2: counter_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8150a9f0)
Location: drivers/acpi/sysfs.c:641
Inline: False
```
**Symbols:**

```
ffffffff8150a9f0-ffffffff8150acbb: counter_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff8154d3c0)
Location: drivers/acpi/sysfs.c:730
Inline: False
```
**Symbols:**

```
ffffffff8154d3c0-ffffffff8154d68b: counter_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:730
Inline: False
```
**Symbols:**

```
ffffffff81583b60-ffffffff81583e92: counter_set (STB_LOCAL)
ffffffff815843b7-ffffffff815843cf: counter_set.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:730
Inline: False
```
**Symbols:**

```
ffffffff8159bc90-ffffffff8159bfc2: counter_set (STB_LOCAL)
ffffffff8159c4e7-ffffffff8159c4ff: counter_set.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:733
Inline: False
```
**Symbols:**

```
ffffffff815cd300-ffffffff815cd632: counter_set (STB_LOCAL)
ffffffff815cdb69-ffffffff815cdb81: counter_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:733
Inline: False
```
**Symbols:**

```
ffffffff815ee580-ffffffff815ee8b2: counter_set (STB_LOCAL)
ffffffff815eede9-ffffffff815eee01: counter_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:733
Inline: False
```
**Symbols:**

```
ffffffff8169a3f0-ffffffff8169a722: counter_set (STB_LOCAL)
ffffffff8169ada2-ffffffff8169adba: counter_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:733
Inline: False
```
**Symbols:**

```
ffffffff816b7470-ffffffff816b77a2: counter_set (STB_LOCAL)
ffffffff81c024f1-ffffffff81c02509: counter_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:714
Inline: False
```
**Symbols:**

```
ffffffff81699510-ffffffff81699807: counter_set (STB_LOCAL)
ffffffff81bf3d03-ffffffff81bf3d1b: counter_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:703
Inline: False
```
**Symbols:**

```
ffffffff8170f3a0-ffffffff8170f697: counter_set (STB_LOCAL)
ffffffff81cf0a43-ffffffff81cf0a5b: counter_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:714
Inline: False
```
**Symbols:**

```
ffffffff8183de40-ffffffff8183e15a: counter_set (STB_LOCAL)
ffffffff81eb8899-ffffffff81eb88b1: counter_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff81973ab0)
Location: drivers/acpi/sysfs.c:715
Inline: False
```
**Symbols:**

```
ffffffff81973ab0-ffffffff81973de2: counter_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff819ba270)
Location: drivers/acpi/sysfs.c:732
Inline: False
```
**Symbols:**

```
ffffffff819ba270-ffffffff819ba5a2: counter_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (ffffffff81a048b0)
Location: drivers/acpi/sysfs.c:732
Inline: False
```
**Symbols:**

```
ffffffff81a048b0-ffffffff81a04be2: counter_set (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:733
Inline: False
```
</details>
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:733
Inline: False
```
**Symbols:**

```
ffffffff815dd240-ffffffff815dd572: counter_set (STB_LOCAL)
ffffffff815dda84-ffffffff815dda9c: counter_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:733
Inline: False
```
**Symbols:**

```
ffffffff815c8880-ffffffff815c8bb2: counter_set (STB_LOCAL)
ffffffff815c90c4-ffffffff815c90dc: counter_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:733
Inline: False
```
**Symbols:**

```
ffffffff815e2860-ffffffff815e2b92: counter_set (STB_LOCAL)
ffffffff815e30c9-ffffffff815e30e1: counter_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t counter_set(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/sysfs.c (0)
Location: drivers/acpi/sysfs.c:733
Inline: False
```
**Symbols:**

```
ffffffff815fc720-ffffffff815fca52: counter_set (STB_LOCAL)
ffffffff815fcf89-ffffffff815fcfa1: counter_set.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
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
