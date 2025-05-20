# Function: <code>hte_ts_get</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hte_ts_get(struct device *dev, struct hte_ts_desc *desc, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hte/hte.c (0)
Location: drivers/hte/hte.c:567
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:hte_edge_setup
```
**Symbols:**

```
ffffffff81f00da8-ffffffff81f00dce: hte_ts_get.cold (STB_LOCAL)
ffffffff81be45c0-ffffffff81be47f6: hte_ts_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hte_ts_get(struct device *dev, struct hte_ts_desc *desc, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hte/hte.c (ffffffff81d90630)
Location: drivers/hte/hte.c:567
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:hte_edge_setup
```
**Symbols:**

```
ffffffff81d90630-ffffffff81d90880: hte_ts_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hte_ts_get(struct device *dev, struct hte_ts_desc *desc, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hte/hte.c (ffffffff81dfe8e0)
Location: drivers/hte/hte.c:567
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:hte_edge_setup
```
**Symbols:**

```
ffffffff81dfe8e0-ffffffff81dfeb02: hte_ts_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hte_ts_get(struct device *dev, struct hte_ts_desc *desc, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hte/hte.c (ffffffff81eb5900)
Location: drivers/hte/hte.c:562
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:hte_edge_setup
```
**Symbols:**

```
ffffffff81eb5900-ffffffff81eb5b22: hte_ts_get (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
