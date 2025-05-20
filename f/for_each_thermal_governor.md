# Function: <code>for_each_thermal_governor</code>

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
int for_each_thermal_governor(int (*cb)(struct thermal_governor *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8195c820)
Location: drivers/thermal/thermal_core.c:621
Inline: False
```
**Symbols:**

```
ffffffff8195c820-ffffffff8195c899: for_each_thermal_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int for_each_thermal_governor(int (*cb)(struct thermal_governor *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8193ffa0)
Location: drivers/thermal/thermal_core.c:572
Inline: False
```
**Symbols:**

```
ffffffff8193ffa0-ffffffff81940019: for_each_thermal_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int for_each_thermal_governor(int (*cb)(struct thermal_governor *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819e48c0)
Location: drivers/thermal/thermal_core.c:519
Inline: False
```
**Symbols:**

```
ffffffff819e48c0-ffffffff819e4939: for_each_thermal_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int for_each_thermal_governor(int (*cb)(struct thermal_governor *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81b49ab0)
Location: drivers/thermal/thermal_core.c:521
Inline: False
```
**Symbols:**

```
ffffffff81b49ab0-ffffffff81b49b35: for_each_thermal_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int for_each_thermal_governor(int (*cb)(struct thermal_governor *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81ce1210)
Location: drivers/thermal/thermal_core.c:512
Inline: False
```
**Symbols:**

```
ffffffff81ce1210-ffffffff81ce1295: for_each_thermal_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int for_each_thermal_governor(int (*cb)(struct thermal_governor *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d49480)
Location: drivers/thermal/thermal_core.c:507
Inline: False
```
**Symbols:**

```
ffffffff81d49480-ffffffff81d49505: for_each_thermal_governor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int for_each_thermal_governor(int (*cb)(struct thermal_governor *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81e00290)
Location: drivers/thermal/thermal_core.c:548
Inline: False
```
**Symbols:**

```
ffffffff81e00290-ffffffff81e00315: for_each_thermal_governor (STB_GLOBAL)
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
