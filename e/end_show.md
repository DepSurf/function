# Function: <code>end_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t end_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff816d0470)
Location: drivers/firmware/memmap.c:383
Inline: False
```
**Symbols:**

```
ffffffff816d0470-ffffffff816d0498: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t end_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81733800)
Location: drivers/firmware/memmap.c:383
Inline: False
```
**Symbols:**

```
ffffffff81733800-ffffffff81733828: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t end_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff817667d0)
Location: drivers/firmware/memmap.c:383
Inline: False
```
**Symbols:**

```
ffffffff817667d0-ffffffff817667f8: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t end_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81784ff0)
Location: drivers/firmware/memmap.c:383
Inline: False
```
**Symbols:**

```
ffffffff81784ff0-ffffffff81785018: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t end_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff817fb360)
Location: drivers/firmware/memmap.c:383
Inline: False
```
**Symbols:**

```
ffffffff817fb360-ffffffff817fb388: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t end_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81844ab0)
Location: drivers/firmware/memmap.c:383
Inline: False
```
**Symbols:**

```
ffffffff81844ab0-ffffffff81844ad8: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t end_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81870ad0)
Location: drivers/firmware/memmap.c:384
Inline: False
```
**Symbols:**

```
ffffffff81870ad0-ffffffff81870af8: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t end_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff818b4d80)
Location: drivers/firmware/memmap.c:375
Inline: False
```
**Symbols:**

```
ffffffff818b4d80-ffffffff818b4da8: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t end_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff818e76a0)
Location: drivers/firmware/memmap.c:375
Inline: False
```
**Symbols:**

```
ffffffff818e76a0-ffffffff818e76c8: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t end_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff819bab00)
Location: drivers/firmware/memmap.c:375
Inline: False
```
**Symbols:**

```
ffffffff819bab00-ffffffff819bab28: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t end_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81833f00)
Location: drivers/dax/bus.c:659
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff819bce70)
Location: drivers/firmware/memmap.c:375
Inline: False
```
**Symbols:**

```
ffffffff81833f00-ffffffff81833fa2: end_show (STB_LOCAL)
ffffffff819bce70-ffffffff819bce98: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t end_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81817040)
Location: drivers/dax/bus.c:660
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff819a1610)
Location: drivers/firmware/memmap.c:375
Inline: False
```
**Symbols:**

```
ffffffff81817040-ffffffff818170e2: end_show (STB_LOCAL)
ffffffff819a1610-ffffffff819a1638: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t end_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff818a1740)
Location: drivers/dax/bus.c:658
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff81a4e5b0)
Location: drivers/firmware/memmap.c:375
Inline: False
```
**Symbols:**

```
ffffffff818a1740-ffffffff818a17e2: end_show (STB_LOCAL)
ffffffff81a4e5b0-ffffffff81a4e5d8: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t end_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff819eaae0)
Location: drivers/dax/bus.c:688
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff81bbd0c0)
Location: drivers/firmware/memmap.c:376
Inline: False
```
**Symbols:**

```
ffffffff819eaae0-ffffffff819eab83: end_show (STB_LOCAL)
ffffffff81bbd0c0-ffffffff81bbd0f4: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t end_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81b678f0)
Location: drivers/dax/bus.c:688
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff81d62b60)
Location: drivers/firmware/memmap.c:376
Inline: False
```
**Symbols:**

```
ffffffff81b678f0-ffffffff81b67993: end_show (STB_LOCAL)
ffffffff81d62b60-ffffffff81d62b94: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t end_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81bbae30)
Location: drivers/dax/bus.c:717
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff81dcdc30)
Location: drivers/firmware/memmap.c:376
Inline: False
```
**Symbols:**

```
ffffffff81bbae30-ffffffff81bbaed3: end_show (STB_LOCAL)
ffffffff81dcdc30-ffffffff81dcdc64: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t end_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81c0eab0)
Location: drivers/dax/bus.c:718
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff81e86770)
Location: drivers/firmware/memmap.c:376
Inline: False
```
**Symbols:**

```
ffffffff81c0eab0-ffffffff81c0eb53: end_show (STB_LOCAL)
ffffffff81e86770-ffffffff81e867a4: end_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t end_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffff800010b4e210)
Location: drivers/firmware/memmap.c:375
Inline: False
```
**Symbols:**

```
ffff800010b4e210-ffff800010b4e254: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t end_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (c0c351d4)
Location: drivers/firmware/memmap.c:375
Inline: False
```
**Symbols:**

```
c0c351d4-c0c35210: end_show (STB_LOCAL)
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t end_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff8188a420)
Location: drivers/firmware/memmap.c:375
Inline: False
```
**Symbols:**

```
ffffffff8188a420-ffffffff8188a448: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t end_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81841da0)
Location: drivers/firmware/memmap.c:375
Inline: False
```
**Symbols:**

```
ffffffff81841da0-ffffffff81841dc8: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t end_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff818dc500)
Location: drivers/firmware/memmap.c:375
Inline: False
```
**Symbols:**

```
ffffffff818dc500-ffffffff818dc528: end_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t end_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff818f9020)
Location: drivers/firmware/memmap.c:375
Inline: False
```
**Symbols:**

```
ffffffff818f9020-ffffffff818f9048: end_show (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param added. </b>
<code>struct device_attribute *attr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct firmware_map_entry *entry</code>
</li>
<li>
<b>Param reordered. </b>
<code>entry, buf</code> ➡️ <code>dev, attr, buf</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
