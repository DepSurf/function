# Function: <code>inhibited_store</code>

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
ssize_t inhibited_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff81932100)
Location: drivers/input/input.c:1435
Inline: False
```
**Symbols:**

```
ffffffff81932100-ffffffff81932287: inhibited_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t inhibited_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input.c (ffffffff819162b0)
Location: drivers/input/input.c:1435
Inline: False
```
**Symbols:**

```
ffffffff819162b0-ffffffff81916437: inhibited_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t inhibited_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:1435
Inline: False
```
**Symbols:**

```
ffffffff819b84f0-ffffffff819b86a8: inhibited_store (STB_LOCAL)
ffffffff81d232f3-ffffffff81d23332: inhibited_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t inhibited_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:1482
Inline: False
```
**Symbols:**

```
ffffffff81b160d0-ffffffff81b16278: inhibited_store (STB_LOCAL)
ffffffff81eeefec-ffffffff81eef02b: inhibited_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t inhibited_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:1461
Inline: False
```
**Symbols:**

```
ffffffff81ca9c10-ffffffff81ca9e01: inhibited_store (STB_LOCAL)
ffffffff820a679d-ffffffff820a67f7: inhibited_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t inhibited_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:1464
Inline: False
```
**Symbols:**

```
ffffffff81d111e0-ffffffff81d113dc: inhibited_store (STB_LOCAL)
ffffffff82127baa-ffffffff82127c04: inhibited_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t inhibited_store(struct device *dev, struct device_attribute *attr, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/input.c (0)
Location: drivers/input/input.c:1464
Inline: False
```
**Symbols:**

```
ffffffff81dc6de0-ffffffff81dc6fdc: inhibited_store (STB_LOCAL)
ffffffff8220952b-ffffffff82209585: inhibited_store.cold (STB_LOCAL)
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
