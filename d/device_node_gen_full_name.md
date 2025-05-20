# Function: <code>device_node_gen_full_name</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
char *device_node_gen_full_name(const struct device_node *np, char *buf, char *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d95630)
Location: lib/vsprintf.c:1884
Inline: False
Direct callers:
  - lib/vsprintf.c:device_node_string
```
**Symbols:**

```
ffff800010d95630-ffff800010d95768: device_node_gen_full_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *device_node_gen_full_name(const struct device_node *np, char *buf, char *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e91370)
Location: lib/vsprintf.c:1884
Inline: False
Direct callers:
  - lib/vsprintf.c:device_node_string
```
**Symbols:**

```
c0e91370-c0e914d4: device_node_gen_full_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *device_node_gen_full_name(const struct device_node *np, char *buf, char *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000eda6b0)
Location: lib/vsprintf.c:1884
Inline: False
Direct callers:
  - lib/vsprintf.c:device_node_string
```
**Symbols:**

```
c000000000eda6b0-c000000000eda900: device_node_gen_full_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *device_node_gen_full_name(const struct device_node *np, char *buf, char *end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008bf216)
Location: lib/vsprintf.c:1884
Inline: False
Direct callers:
  - lib/vsprintf.c:device_node_string
```
**Symbols:**

```
ffffffe0008bf216-ffffffe0008bf32a: device_node_gen_full_name (STB_LOCAL)
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
