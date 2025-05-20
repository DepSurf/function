# Function: <code>auxiliary_bus_probe</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int auxiliary_bus_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/auxiliary.c (0)
Location: drivers/base/auxiliary.c:63
Inline: False
```
**Symbols:**

```
ffffffff817d8a00-ffffffff817d8a76: auxiliary_bus_probe (STB_LOCAL)
ffffffff81c0e62f-ffffffff81c0e64b: auxiliary_bus_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int auxiliary_bus_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/auxiliary.c (0)
Location: drivers/base/auxiliary.c:63
Inline: False
```
**Symbols:**

```
ffffffff817bcb40-ffffffff817bcbb6: auxiliary_bus_probe (STB_LOCAL)
ffffffff81c00a42-ffffffff81c00a5e: auxiliary_bus_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int auxiliary_bus_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/auxiliary.c (0)
Location: drivers/base/auxiliary.c:63
Inline: False
```
**Symbols:**

```
ffffffff81846e90-ffffffff81846f06: auxiliary_bus_probe (STB_LOCAL)
ffffffff81d034cc-ffffffff81d034e8: auxiliary_bus_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int auxiliary_bus_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/auxiliary.c (0)
Location: drivers/base/auxiliary.c:204
Inline: False
```
**Symbols:**

```
ffffffff8198b890-ffffffff8198b91d: auxiliary_bus_probe (STB_LOCAL)
ffffffff81ecbc73-ffffffff81ecbc8f: auxiliary_bus_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int auxiliary_bus_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81afae70)
Location: drivers/base/auxiliary.c:204
Inline: False
```
**Symbols:**

```
ffffffff81afae70-ffffffff81afaf10: auxiliary_bus_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int auxiliary_bus_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81b49260)
Location: drivers/base/auxiliary.c:204
Inline: False
```
**Symbols:**

```
ffffffff81b49260-ffffffff81b49300: auxiliary_bus_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int auxiliary_bus_probe(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/auxiliary.c (ffffffff81ba1650)
Location: drivers/base/auxiliary.c:204
Inline: False
```
**Symbols:**

```
ffffffff81ba1650-ffffffff81ba16f0: auxiliary_bus_probe (STB_LOCAL)
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
