# Function: <code>start_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t start_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff816d04a0)
Location: drivers/firmware/memmap.c:377
Inline: False
```
**Symbols:**

```
ffffffff816d04a0-ffffffff816d04c7: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t start_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81733830)
Location: drivers/firmware/memmap.c:377
Inline: False
```
**Symbols:**

```
ffffffff81733830-ffffffff81733857: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t start_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81766800)
Location: drivers/firmware/memmap.c:377
Inline: False
```
**Symbols:**

```
ffffffff81766800-ffffffff81766827: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t start_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81785020)
Location: drivers/firmware/memmap.c:377
Inline: False
```
**Symbols:**

```
ffffffff81785020-ffffffff81785047: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t start_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff817fb390)
Location: drivers/firmware/memmap.c:377
Inline: False
```
**Symbols:**

```
ffffffff817fb390-ffffffff817fb3b7: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t start_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81844ae0)
Location: drivers/firmware/memmap.c:377
Inline: False
```
**Symbols:**

```
ffffffff81844ae0-ffffffff81844b07: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t start_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81870b00)
Location: drivers/firmware/memmap.c:378
Inline: False
```
**Symbols:**

```
ffffffff81870b00-ffffffff81870b27: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t start_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff818b4db0)
Location: drivers/firmware/memmap.c:369
Inline: False
```
**Symbols:**

```
ffffffff818b4db0-ffffffff818b4dd7: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t start_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff818e76d0)
Location: drivers/firmware/memmap.c:369
Inline: False
```
**Symbols:**

```
ffffffff818e76d0-ffffffff818e76f7: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t start_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff819bab30)
Location: drivers/firmware/memmap.c:369
Inline: False
```
**Symbols:**

```
ffffffff819bab30-ffffffff819bab57: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
ssize_t start_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81833bd0)
Location: drivers/dax/bus.c:643
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff819bcea0)
Location: drivers/firmware/memmap.c:369
Inline: False
```
**Symbols:**

```
ffffffff81833bd0-ffffffff81833c72: start_show (STB_LOCAL)
ffffffff819bcea0-ffffffff819bcec7: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
ssize_t start_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81816dc0)
Location: drivers/dax/bus.c:644
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff819a1640)
Location: drivers/firmware/memmap.c:369
Inline: False
```
**Symbols:**

```
ffffffff81816dc0-ffffffff81816e62: start_show (STB_LOCAL)
ffffffff819a1640-ffffffff819a1667: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
ssize_t start_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff818a1410)
Location: drivers/dax/bus.c:642
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff81a4e5e0)
Location: drivers/firmware/memmap.c:369
Inline: False
```
**Symbols:**

```
ffffffff818a1410-ffffffff818a14b2: start_show (STB_LOCAL)
ffffffff81a4e5e0-ffffffff81a4e607: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
ssize_t start_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff819eae70)
Location: drivers/dax/bus.c:672
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff81bbd100)
Location: drivers/firmware/memmap.c:370
Inline: False
```
**Symbols:**

```
ffffffff819eae70-ffffffff819eaf13: start_show (STB_LOCAL)
ffffffff81bbd100-ffffffff81bbd133: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
ssize_t start_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81b675c0)
Location: drivers/dax/bus.c:672
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff81d62bb0)
Location: drivers/firmware/memmap.c:370
Inline: False
```
**Symbols:**

```
ffffffff81b675c0-ffffffff81b67663: start_show (STB_LOCAL)
ffffffff81d62bb0-ffffffff81d62be3: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
ssize_t start_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81bbaf90)
Location: drivers/dax/bus.c:701
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff81dcdc80)
Location: drivers/firmware/memmap.c:370
Inline: False
```
**Symbols:**

```
ffffffff81bbaf90-ffffffff81bbb033: start_show (STB_LOCAL)
ffffffff81dcdc80-ffffffff81dcdcb3: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
ssize_t start_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81c0f790)
Location: drivers/dax/bus.c:702
Inline: False
```
```
In drivers/firmware/memmap.c (ffffffff81e867c0)
Location: drivers/firmware/memmap.c:370
Inline: False
```
**Symbols:**

```
ffffffff81c0f790-ffffffff81c0f833: start_show (STB_LOCAL)
ffffffff81e867c0-ffffffff81e867f3: start_show (STB_LOCAL)
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
ssize_t start_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffff800010b4e258)
Location: drivers/firmware/memmap.c:369
Inline: False
```
**Symbols:**

```
ffff800010b4e258-ffff800010b4e29c: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t start_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (c0c35210)
Location: drivers/firmware/memmap.c:369
Inline: False
```
**Symbols:**

```
c0c35210-c0c3524c: start_show (STB_LOCAL)
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
ssize_t start_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff8188a450)
Location: drivers/firmware/memmap.c:369
Inline: False
```
**Symbols:**

```
ffffffff8188a450-ffffffff8188a477: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t start_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff81841dd0)
Location: drivers/firmware/memmap.c:369
Inline: False
```
**Symbols:**

```
ffffffff81841dd0-ffffffff81841df7: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t start_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff818dc530)
Location: drivers/firmware/memmap.c:369
Inline: False
```
**Symbols:**

```
ffffffff818dc530-ffffffff818dc557: start_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t start_show(struct firmware_map_entry *entry, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/memmap.c (ffffffff818f9050)
Location: drivers/firmware/memmap.c:369
Inline: False
```
**Symbols:**

```
ffffffff818f9050-ffffffff818f9077: start_show (STB_LOCAL)
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
