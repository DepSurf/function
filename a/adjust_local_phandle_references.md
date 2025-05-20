# Function: <code>adjust_local_phandle_references</code>

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
int adjust_local_phandle_references(struct device_node *local_fixups, struct device_node *overlay, int phandle_delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/resolver.c (ffff800010b76920)
Location: drivers/of/resolver.c:159
Inline: False
Direct callers:
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:adjust_local_phandle_references
```
**Symbols:**

```
ffff800010b76920-ffff800010b76b6c: adjust_local_phandle_references (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int adjust_local_phandle_references(struct device_node *local_fixups, struct device_node *overlay, int phandle_delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/resolver.c (c0c58c20)
Location: drivers/of/resolver.c:159
Inline: False
Direct callers:
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:adjust_local_phandle_references
```
**Symbols:**

```
c0c58c20-c0c58e6c: adjust_local_phandle_references (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int adjust_local_phandle_references(struct device_node *local_fixups, struct device_node *overlay, int phandle_delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/resolver.c (c000000000c54c40)
Location: drivers/of/resolver.c:159
Inline: False
Direct callers:
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:adjust_local_phandle_references
```
**Symbols:**

```
c000000000c54c40-c000000000c55480: adjust_local_phandle_references (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int adjust_local_phandle_references(struct device_node *local_fixups, struct device_node *overlay, int phandle_delta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/resolver.c (ffffffe000729cd2)
Location: drivers/of/resolver.c:159
Inline: False
Direct callers:
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:of_resolve_phandles
  - drivers/of/resolver.c:adjust_local_phandle_references
```
**Symbols:**

```
ffffffe000729cd2-ffffffe000729f1a: adjust_local_phandle_references (STB_LOCAL)
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
