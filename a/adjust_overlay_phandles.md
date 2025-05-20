# Function: <code>adjust_overlay_phandles</code>

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
void adjust_overlay_phandles(struct device_node *overlay, int phandle_delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/resolver.c (ffff800010b76810)
Location: drivers/of/resolver.c:40
Inline: False
Direct callers:
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:adjust_overlay_phandles
```
**Symbols:**

```
ffff800010b76810-ffff800010b7691c: adjust_overlay_phandles (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void adjust_overlay_phandles(struct device_node *overlay, int phandle_delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/resolver.c (c0c58b28)
Location: drivers/of/resolver.c:40
Inline: False
Direct callers:
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:adjust_overlay_phandles
```
**Symbols:**

```
c0c58b28-c0c58c20: adjust_overlay_phandles (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void adjust_overlay_phandles(struct device_node *overlay, int phandle_delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/resolver.c (c000000000c54840)
Location: drivers/of/resolver.c:40
Inline: False
Direct callers:
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:adjust_overlay_phandles
```
**Symbols:**

```
c000000000c54840-c000000000c54c34: adjust_overlay_phandles (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void adjust_overlay_phandles(struct device_node *overlay, int phandle_delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/resolver.c (ffffffe000729ba4)
Location: drivers/of/resolver.c:40
Inline: False
Direct callers:
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:adjust_overlay_phandles
```
**Symbols:**

```
ffffffe000729ba4-ffffffe000729cd2: adjust_overlay_phandles (STB_LOCAL)
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
