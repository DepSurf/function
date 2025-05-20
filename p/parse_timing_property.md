# Function: <code>parse_timing_property</code>

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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int parse_timing_property(const struct device_node *np, const char *name, struct timing_entry *result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/of_display_timing.c (ffff800010761ad8)
Location: drivers/video/of_display_timing.c:25
Inline: True
Direct callers:
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
```
**Symbols:**

```
ffff800010761ad8-ffff800010761be8: parse_timing_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int parse_timing_property(const struct device_node *np, const char *name, struct timing_entry *result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/of_display_timing.c (c08e421c)
Location: drivers/video/of_display_timing.c:25
Inline: True
Direct callers:
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
```
**Symbols:**

```
c08e421c-c08e4320: parse_timing_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int parse_timing_property(const struct device_node *np, const char *name, struct timing_entry *result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/of_display_timing.c (c0000000008c5670)
Location: drivers/video/of_display_timing.c:25
Inline: True
Direct callers:
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
```
**Symbols:**

```
c0000000008c5670-c0000000008c57c4: parse_timing_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int parse_timing_property(const struct device_node *np, const char *name, struct timing_entry *result);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/of_display_timing.c (ffffffe0005086f6)
Location: drivers/video/of_display_timing.c:25
Inline: True
Direct callers:
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
  - drivers/video/of_display_timing.c:of_parse_display_timing
```
**Symbols:**

```
ffffffe0005086f6-ffffffe0005087ce: parse_timing_property (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
