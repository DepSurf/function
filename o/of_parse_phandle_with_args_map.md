# Function: <code>of_parse_phandle_with_args_map</code>

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
int of_parse_phandle_with_args_map(const struct device_node *np, const char *list_name, const char *stem_name, int index, struct of_phandle_args *out_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6b518)
Location: drivers/of/base.c:1578
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
```
**Symbols:**

```
ffff800010b6b518-ffff800010b6b95c: of_parse_phandle_with_args_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_parse_phandle_with_args_map(const struct device_node *np, const char *list_name, const char *stem_name, int index, struct of_phandle_args *out_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4e8ac)
Location: drivers/of/base.c:1578
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
```
**Symbols:**

```
c0c4e8ac-c0c4ed58: of_parse_phandle_with_args_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_parse_phandle_with_args_map(const struct device_node *np, const char *list_name, const char *stem_name, int index, struct of_phandle_args *out_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c45100)
Location: drivers/of/base.c:1578
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
```
**Symbols:**

```
c000000000c45100-c000000000c456bc: of_parse_phandle_with_args_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_parse_phandle_with_args_map(const struct device_node *np, const char *list_name, const char *stem_name, int index, struct of_phandle_args *out_args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe0007209d8)
Location: drivers/of/base.c:1578
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
```
**Symbols:**

```
ffffffe0007209d8-ffffffe000720e1e: of_parse_phandle_with_args_map (STB_GLOBAL)
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
