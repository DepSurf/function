# Function: <code>target_show</code>

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
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t target_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b7190)
Location: kernel/cpu.c:2314
Inline: False
```
```
In drivers/xen/xen-balloon.c (ffffffff817a1bc0)
Location: drivers/xen/xen-balloon.c:180
Inline: False
```
**Symbols:**

```
ffffffff810b7190-ffffffff810b71ed: target_show (STB_LOCAL)
ffffffff817a1bc0-ffffffff817a1be7: target_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t target_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cd910)
Location: kernel/cpu.c:2336
Inline: False
```
```
In drivers/xen/xen-balloon.c (ffffffff818dbc20)
Location: drivers/xen/xen-balloon.c:180
Inline: False
```
**Symbols:**

```
ffffffff810cd910-ffffffff810cd978: target_show (STB_LOCAL)
ffffffff818dbc20-ffffffff818dbc51: target_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t target_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810eba10)
Location: kernel/cpu.c:2362
Inline: False
```
```
In drivers/xen/xen-balloon.c (ffffffff81a2edc0)
Location: drivers/xen/xen-balloon.c:180
Inline: False
```
**Symbols:**

```
ffffffff810eba10-ffffffff810eba78: target_show (STB_LOCAL)
ffffffff81a2edc0-ffffffff81a2edf1: target_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t target_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f76f0)
Location: kernel/cpu.c:2747
Inline: False
```
```
In drivers/xen/xen-balloon.c (ffffffff81a78580)
Location: drivers/xen/xen-balloon.c:180
Inline: False
```
**Symbols:**

```
ffffffff810f76f0-ffffffff810f7758: target_show (STB_LOCAL)
ffffffff81a78580-ffffffff81a785b1: target_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t target_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81100aa0)
Location: kernel/cpu.c:2801
Inline: False
```
```
In drivers/xen/xen-balloon.c (ffffffff81aca8a0)
Location: drivers/xen/xen-balloon.c:180
Inline: False
```
**Symbols:**

```
ffffffff81100aa0-ffffffff81100b08: target_show (STB_LOCAL)
ffffffff81aca8a0-ffffffff81aca8d1: target_show (STB_LOCAL)
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
