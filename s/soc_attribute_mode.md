# Function: <code>soc_attribute_mode</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
umode_t soc_attribute_mode(struct kobject *kobj, struct attribute *attr, int index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (ffffffff81b78320)
Location: drivers/base/soc.c:47
Inline: True
```
**Symbols:**

```
ffffffff81b78320-ffffffff81b7841a: soc_attribute_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
umode_t soc_attribute_mode(struct kobject *kobj, struct attribute *attr, int index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (ffffffff81bcc120)
Location: drivers/base/soc.c:47
Inline: True
```
**Symbols:**

```
ffffffff81bcc120-ffffffff81bcc21a: soc_attribute_mode (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
umode_t soc_attribute_mode(struct kobject *kobj, struct attribute *attr, int index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (ffff80001091e7d8)
Location: drivers/base/soc.c:45
Inline: True
```
**Symbols:**

```
ffff80001091e7d8-ffff80001091e8bc: soc_attribute_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
umode_t soc_attribute_mode(struct kobject *kobj, struct attribute *attr, int index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (c0a03b60)
Location: drivers/base/soc.c:45
Inline: True
```
**Symbols:**

```
c0a03b60-c0a03c20: soc_attribute_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
umode_t soc_attribute_mode(struct kobject *kobj, struct attribute *attr, int index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/soc.c (c0000000009c37b0)
Location: drivers/base/soc.c:45
Inline: True
```
**Symbols:**

```
c0000000009c37b0-c0000000009c38a0: soc_attribute_mode (STB_LOCAL)
```
</details>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
